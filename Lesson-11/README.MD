1. When we use float : left/right, there is an issue with floating items. We use a legacy way to fix this issue and that is declare a class with rule {clear:both}.
2. Still there is an issue when the floating items wrapped within a section. To solve this, we can use a modern way and that is using a rule with wrapped item {display: flow-root}
