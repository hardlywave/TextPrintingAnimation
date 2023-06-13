# Text Printing Animation

The Text Printing Animation script is a JavaScript function that creates a dynamic typing effect for text elements on a webpage. It allows you to animate the printing of text, giving it a unique and engaging appearance.

The script works by targeting specific HTML elements with the class name "print". It retrieves the text content from these elements and gradually displays it character by character, simulating the effect of typing. The animation includes a blinking cursor at the end of the printed text, enhancing the realistic typing experience.

You can customize various parameters of the animation using data attributes:

- `data-message`: The last printed message before finishing! (Type: String)
- `data-remove`: Removal speed (Type: Integer)
- `data-pouse`: Pre-removal pause (Type: Integer)
- `data-delay`: Printing speed (Type: Integer)
- `data-cursor`: Cursor's option (Type: String)

Adjusting these attributes allows you to control the speed of printing, the delay before removal starts, and the type of cursor used. By fine-tuning these settings, you can achieve different typing speeds and create the desired visual effect.

Additionally, the script provides a callback function that allows you to control the visibility of the printed text or trigger other actions when the printing animation is complete. This can be useful for synchronizing the animation with other elements or events on your webpage.

Overall, the Text Printing Animation script adds an interactive and attention-grabbing element to your website, making the text come alive and engaging your visitors with a unique typing effect.

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
  data-message="Completed!"
  data-remove="50"
  data-pouse="1300"
  data-delay="150"
  data-cursor="|"
  >
    Hello, World!
</span>

<!-- JavaScript -->
<script>
  TextPrintingAnimation();
</script>
