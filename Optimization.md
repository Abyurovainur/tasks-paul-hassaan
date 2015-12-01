To speed up our original algorithm we needed to speed up our loops

We have a function called contains(). It iterates through an array checking to see if the given number is in the array. This gets called every time we process a "task", this happens A LOT.

To speed this up we decided to create a boolean array called contains. If the "task" has already been added to the answers array we set it to True, otherwise it's False. This way we don't have to iterate through an array every time but rather look up a bool at a known location. This greatly sped up algorithm from 3+ seconds to .06 seconds.