# Crafting Crusoe

If you ever end up stranded on an island, isolated from the rest of the world and its technology, you will have to find a way to create your own tools. Your goal in this kata is to write a method which returns all of the craftable objects from a list of items given as parameters.

You have to support the following recipes : 
* Stick + Rock = Axe
* 2 Sticks = Spear
* Stick + Feather = Arrow 
* Stick + Cloth + Rope = Bow

Example: 

```csharp
var availableItems = new List<string>{"Stick", "Stick", "Stick", "Stick", "Rock", "Feather"};
var craftableItems = GetCraftableItems(availableItems);
craftableItems == ["Spear", "Axe", "Arrow"];
```

Hint: Use the [Strategy](https://en.wikipedia.org/wiki/Strategy_pattern) design pattern
