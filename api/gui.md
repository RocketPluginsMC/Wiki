# GUI

## How to create a GUI

Create a class that extends to **Menu**

```java
public class ExampleMenu extends Menu {
}

```

### Create the constructor

```java
public class ExampleMenu extends Menu {

    public ExampleMenu(MenuUtility menuUtility) {
        super(menuUtility);
    }
    
}

```

### Implement all methods

```java
public class ExampleMenu extends Menu {

    public ExampleMenu(MenuUtility menuUtility) {
        super(menuUtility);
    }

    @Override
    public String getMenuName() {
        return "§e§lExample Menu";
    }

    @Override
    public int getSlots() {
        return 9;
    }

    @Override
    public void handleMenu(InventoryClickEvent inventoryClickEvent) {
    }

    @Override
    public void setMenuItems() {
    }
    
}

```

### Create an item, add it in the GUI:

```java
public ItemStack example = makeItem(Material.COAL, "§7Example COAL", "§7This is an example coal");

@Override
public void setMenuItems() {
    this.getInventory().setItem(1, example);
}

```

### Create a Click Event

```java
public ItemStack example = makeItem(Material.COAL, "§7Example COAL", "§7This is an example coal");

@Override
public void handleMenu(InventoryClickEvent event) {
    if (event.getCurrentItem().equals(example)) {
        event.setCancelled(true);
        event.getWhoClicked().closeInventory();
        event.getWhoClicked().sendMessage("Yay, it works!");
    }
}
```



{% file src="../.gitbook/assets/examplemenu.java" caption="Download the file" %}



