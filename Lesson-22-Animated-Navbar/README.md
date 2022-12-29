## transform : translate

- `translateX(50%)` : User percentage basis on the size of the element, positive number move to left and negative number move to right.
- `translateY()` : use moving up and down.
- `translate()` : use moving both x axis and y axis.

## transform : rotate

- `rotateX('angle')` : use moving y axis means it flips with y axis or flips with up and down.
- `rotateY('angle')` : use moving x axis means it flips with x axis or flips with left or right side.
- `rotateZ('angle')` : use moving z axis i.e. it flips with clock wise or anti clock wise direction.
- `rotateZ()` is equavalent to `rotate()`

## transform : scale

- `scale(value)` : use inc/dec size on x axis.
- `scale(value)` : use inc/dec size on x axis..
- `scale(value,value)` : use inc/dec size on x axis or y axis.

## transition

- transition-property : which property(s) are affected on transition. properties are separated with comma.
- transition-duration : how long it take time to complete transition
- transition-timing-function : need to study
- transition-delay : time delay to start transition
- transition : \<transition-property> \<transition-duration> \<transition-timing-function> \<transition-delay>.
- example: `transition : all 2s ease .5s`

## animation

- animation: <name> <duration> <timing-function> <delay> <iteration-count> <direction> <fill-mode>;
