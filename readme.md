# Key Codes Project

The **Key Codes Project** is a simple web application that displays the details of the key pressed by the user in a stylish and interactive UI. It shows the following information in real-time:

- The **key** that was pressed.
- The **code** associated with the key.
- The **key code** (numeric code of the key).

The application features a dynamic background with smooth gradient animations and interactive key display containers with hover effects.

## Features

- **Interactive UI:** Shows key details in real-time as you press keys on the keyboard.
- **Smooth Gradient Animation:** The background features a colorful gradient that shifts over time.
- **Key Display:** Each key pressed is displayed with its corresponding information.
- **Hover Effects:** Key containers have a dynamic hover effect that changes the background and elevates the container.

## Demo

![Key Codes Project Demo](image.png)

*Above is a demo of how the application works. Press any key to see its details in the containers.*

## How It Works

- When a key is pressed on the keyboard, the `keydown` event is captured using JavaScript.
- The event details are displayed in the UI, including:
  - `key`: The character of the pressed key.
  - `code`: The code of the key pressed (such as 'KeyA', 'Enter', etc.).
  - `keyCode`: The numeric keycode for the key pressed.

### Example:

When the "A" key is pressed:
- **Key:** A
- **Code:** KeyA
- **Key Code:** 65

## Customization

You can customize the background gradient, key colors, or animation effects by modifying the `style.css` file.

## Contributing

Feel free to contribute to the project by submitting pull requests. Here are some ways you can contribute:
- Add new features.
- Improve the UI/UX.
- Fix bugs or issues.

-----
