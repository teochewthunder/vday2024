# Valentine's Day Animation
The animation consists of 10 AI-generated images. Each image will display and fade out, then fade in with a different image.

1. There is a container with several squares.
- Each square has a div that contains a fragment of the entire image.
- The fragment's background image is actually the entire image, offset according to the square's relative position.
2. When the animation starts, it animates either the `opacity` or `width` or `width` and `height` attributes, according to a randomly selected animation type.
- The animation will cause the element to become invisible (either through setting to full transparency or shrinking to 0)
- Then the image of the element will change.
- Then the animation will cause the element to become "visible" again.
3. The delay used by the `animate()` method will be determined by a randomly-selected sequence type.
- This may cause some squares to "disappear" or "appear" first depending on their relative position in the grid.
- There is a great number of special effects that can be accomplished by manipulating this.
4. Varying both the animation type and the sequence type will yield an interesting combination of effects.
