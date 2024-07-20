# Minecraft ID Map Generator

This is a simple tool I built to assist with making mods for older versions of Minecraft that don't have unique IDs or key names for item variants such as wood types, wool or other block colors, etc.

- A list of all the item IDs for a given Minecraft version should be pasted in (probably from a wiki list) that includes repeated IDs for item variants. (For example, for all wool colors in Minecraft 1.7.10, ID #35 will be repeated 16 times.
- Minecraft ID Map Generates a HashMap of all the IDs that are repeated, with the key being the items' ID and the value being the number of occurrences.