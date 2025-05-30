# Annimated-Tennis
# CSS Animated Tennis Balls

This project showcases three animated tennis balls bouncing and rotating with dynamic shadow

## Features

* **Three Animated Balls:** Displays three tennis balls, each with a distinct color.
* **Dynamic Shadows:** Each ball has a corresponding shadow that scales dynamically during the bounce animation.
* **CSS Animations:**
    * Balls bounce up and down while rotating.
    * Shadows shrink when the ball is at the peak of its bounce and return to normal size as the ball descends.
* **Tennis Ball Seam Effect:** The iconic white curved lines on the tennis balls are created using `::before` and `::after` pseudo-elements with borders.
* **Pure CSS:** All styling and animations are achieved without JavaScript.
* **Specific Positioning:** Balls are positioned in the center, left-of-center, and right-of-center of the viewport.

## File Structure
.
├── index.html       # The main HTML file structuring the content
└── style.css        # The CSS file for styling and animation

## How to View

1.  Ensure you have both `index.html` and `style.css` in the same directory.
2.  Open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Safari, Edge).

Customization
Colors: Change the background property for .ball, .ball2, .ball3, and body.
Animation Speed/Timing: Modify the duration (1.5s) or timing function (linear) in the animation properties. Adjust @keyframes percentages or transform values to alter the animation behavior.
Ball Size/Shadow Size: Change width and height properties for ball and shadow classes. Remember to adjust seam pseudo-element positioning if ball size changes significantly.
Number of Balls: Add or remove the div blocks (e.g., <div class="centerN"><div class="ballN"></div><div class="shadowN"></div></div>) in index.html and create corresponding CSS rules with unique positioning and potentially different animations or colors.
Positioning: Adjust top, left, and right properties for .center, .center2, and .center3 to change where the balls are displayed.
