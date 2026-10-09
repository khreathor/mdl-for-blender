### **Question:** "I created solid color skin and after exporting and loading MDL in an engine, it appears to be black." ###

**Answer:** "One thing that can ruin your day with skins (especially placeholder skins) is the floor fill feature. Some engines attempt to replace the bright blue background some original Quake models had on their skins, because it looks ugly when seams show. They do this by flood-filling the skin with black, starting from the top left corner of the skin.

This can wipe out actual visible portions of the skin if they are painted with a continuous block of colour which extends to the top-left corner. A reasonable workaround is to paint just the top left pixel in a different colour to the adjacent pixels, so that the flood fill is contained." - *Preach*

*Source: [func_msgboard](http://celephais.net/board/view_thread.php?id=4&start=18927&end=18929)*
*Archived Backup: [archive.org](https://web.archive.org/web/0/https://celephais.net/board/view_thread.php?id=4&start=18927&end=18929)*
