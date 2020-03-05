# Read: 14a Summary
## CSS Transforms, Transitions, and Animations


***The `transform` property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.***
> Elements may be distorted, or transformed, on both a two-dimensional plane or a three-dimensional plane. 

* Using the `scale` value within the `transform` property allows you to change the appeared size of an element. 
* The `translate` value works a bit like that of relative positioning, pushing and pulling an element in different directions without interrupting the normal flow of the document.
* The last `transform` value in the group, `skew`, is used to distort elements on the horizontal axis, vertical axis, or both
* With CSS3 `transitions` you have the potential to alter the appearance and behavior of an element whenever a state change occurs, such as when it is hovered over, focused on, active, or targeted.
***Animations within CSS3 allow the appearance and behavior of an element to be altered in multiple keyframes***
> when more control is required, transitions need to have multiple states. In return, this is where animations pick up where transitions leave off.

*` Fade` in effects are coded in two steps: first, you set the initial state; next, you set the change, for example on `hover:`
* Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them
* To grow an element, you used to have to use its `width` and `height`, or its `padding`. But now we can use CSS3’s `transform` to enlarge.
* CSS `transforms` have a number of different uses, and one of the best is transforming the rotation of an element. Give your `div`the class `rotate`
* transitioning a square element into a round one, and vice versa. With CSS, it’s a simple effect to achieve, we just transition the `border-radius` property.
* We can also create highly complex animations using `@keyframes, animation and animation-iteration.`
* ghost button; a button with no background and a heavy border

