WIP

```java title="ExamplePlugin.java"
package com.example;

import org.bukkit.plugin.java.JavaPlugin;
import io.phanisment.itemcaster.api.ApiHelper;
import io.phanisment.itemcaster.util.CasterLogger;

public class ExamplePlugin extends JavaPlugn {
  @Override
  public void onEnable() {
    ApiHelper.registerExternalItem(new ExampleIExternalItem());
    
  }
}
```

``` java title="ExampleIExternalItem.java"
package com.example;

import org.bukkit.Material;
import org.bukkit.inventory.ItemStack;
import org.bukkit.inventory.meta.ItemMeta;
import io.lumine.mythic.api.config.MythicConfig;
import io.lumine.mythic.core.items.MythicItem;
import io.phanisment.itemcaster.api.IExternalItem;
import java.util.Optional;

public class ExampleIExternalItem implements IExternalItem {
  @Override
  public String getPlugin() {
    return "example";
  }
  
  @Override
  public Optional<ItemStack> resolve(String[] parts, MythicItem item, MythicConfig config) {
    ItemStack item = new ItemStack(Material.STICK);
    ItemMeta meta = item.getItemMeta();
    
    meta.setCustomModelData(1000);
    
    item.setItemMeta(meta);
    
    return Optional.of(item);
  }
}
```