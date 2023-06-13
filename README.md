# Text Printing Animation

The Text Printing Animation script is a JavaScript function that creates a dynamic typing effect for text elements on a webpage. It allows you to animate the printing of text, giving it a unique and engaging appearance.

## Features

- Simulates the effect of typing by gradually displaying text character by character.
- Supports customization of animation parameters such as printing speed, character delay, and pause duration.
- Includes a blinking cursor at the end of the printed text for a realistic typing experience.
- Provides a callback function for controlling text visibility and triggering actions upon animation completion.

## Usage

1. Include the Text Printing Animation script in your web project.
2. Add the "print" class to the HTML elements that you want to animate.
3. Customize the animation parameters as needed.
4. Call the `TextPrintingAnimation()` function to start the animation.

## Example

```html
<!-- HTML -->
<span 
  class="print" 
  data-message="The last printed message before finishing!: String"
  data-remove="Removal speed: Integer"
  data-pouse="Pre-removal pause: Integer"
  data-delay="Printing speed: Integer"
  data-cursor="Cursor's option: String"
  >
    Hello, World!
</span>

<!-- JavaScript -->
<script>
  TextPrintingAnimation();
</script>
