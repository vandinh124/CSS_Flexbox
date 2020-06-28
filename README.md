# CSS_Flexbox
Terminology

Flex container (parent): 

Display : defines a flex container and mandatory to work with flexbox
    Flex: display left to right -> a block (there are some space left)
    Inline-flex: the container wrap around the item without space left
    
Flex-direction: defines the direction in which the flex items are placed in the container
    Row: left to right with item (1 to 9)
    Row-reverse: left to right with reversed item (9 to 1)
    Column: top to bottom with item (1 to 9)
    Column-reverse: top to bottom with reversed item(9 to 1)
    
Flex-wrap: is used to control the wrapping of items within a container
    Nowrap: when you change the size of the page, flex item wont be wrap by the container.
    Wrap: wrap by the container
    wrap-reverse : wrap by the container and items are reversed
    
Flex-flow: shorthand for combination of flex direction and flex wrap
    Flex-flow: <flex-direction><flex-wrap>

Justify-content: defines the alignment of items along the main axis
    Space-between
    Space-around
    space-evenly
    flex-start
    flex-end
    center
    
Align-items: defines how flex items are laid out along the cross
    Stretch (default value)
    Flex-start (all the items are pushed to the cross start)
    Flex-end (all the items are pushed to the cross end)
    Center
    Baseline: the text inside each item is aligned the item itself positioned based on where the text will sit

Align-content: align along the cross axis, only work when there are multiple rows of flex items ( mix of justified content and align items)
    Stretch (default value)
    Flex-start
    Flex-end
    Center
    Space-around
    space-between
    
    
Flex Item (children)
    Order: control the order of items in the flex container
    Integer value (ex: order 1;)
    
Flex-grow: amount of available space inside the flex’s container the item should take up
    Flex-grow: 0 (no change, it’s default)
    Flex-grow: 1 (takes up the space evenly)
    Flex-grow: 3 (that item take up the space 3 times compare to the other)
    
Flex-shrink: dictates the shrink factor of the flex items when the default size of flex items is larger than the flex container. Relative to the other items in the container
    Flex-shrink: 0 (no shrink)
    Flex-shrink: 1 (default value)
    Flex-shrink: 4 ( shrink 4 times as much)
    
Flex-basic: set initial size of the flex item before the actual space in the container is distributed. Pixels, percentages, or relative units
    Flex-basic: 0 (default value)
    
Flex: shorthand for flex grow, flex shrink and flex basic
    Flex: 2 5 200px;
    Flex: 0 1 auto (default)
    
Align-self: align the items individually, overrides the align-items value of the flex container
    Auto
    Flex-start
    Flex-end
    Center
    stretch

Flexbox axes

Main Axis (run left to right)  (main start to main end: main size)
Cros Axis (run top to bottom) (cross start to cross end: cross size)


