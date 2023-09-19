# Responsive Button

This HTML and CSS code snippet demonstrates the creation of a responsive button with a vibrant background color. The button is designed to adapt to various screen sizes and orientations, making it suitable for use in web applications and mobile-friendly designs.

## Features

- **Responsive Design**: The button is designed to be responsive, ensuring it looks great on both desktop and mobile devices.

- **Vibrant Color**: The button features a vibrant `mediumturquoise` background color, making it visually appealing.

- **Clickable**: The button is clickable and can be used to trigger actions or functions in your web application.

## Usage

1. Copy the HTML and CSS code provided in the snippet.

2. Paste the code into your HTML file within the appropriate section of your webpage.

3. Customize the button's appearance by modifying the CSS styles as needed. You can change the `background-color`, `border-color`, and other properties to match your design preferences.

4. Use JavaScript to add functionality to the button, such as handling click events and executing actions.

5. Test the responsive button on different devices and screen sizes to ensure it adapts correctly.

## Example

```html
<!DOCTYPE html>
<html>
  <style>
    .Absolute-Center {
      height: 10%;
      width: 7%;
      overflow: auto;
      margin: auto;
      position: absolute;
      top: 0;
      left: 0;
      bottom: 0;
      right: 0;
      background-color: mediumturquoise;
      border-color: mediumturquoise;
      cursor: pointer;
      position: fixed;
      z-index: 999;
    }

    .Center-Container {
      position: relative;
    }
  </style>
  <body>
    <div class="Center-Container">
      <button class="Absolute-Center"></button>
    </div>
  </body>
</html>
```

Feel free to integrate this responsive button into your web projects and tailor it to your specific design and functionality requirements.

![Recording 2022-10-19 at 17 46 58](https://user-images.githubusercontent.com/40829087/196724638-baa0c07b-a4b3-4377-ba47-3aaa45083d53.gif)
