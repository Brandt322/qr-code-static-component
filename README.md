# Frontend Mentor | QR code component

This project is a simple QR code component built with HTML and CSS. The component is responsive and adjusts its layout according to the device's screen size.

## Structure

The HTML structure of the component is as follows:

- A `div` with the class `card` serves as the main container.
- Inside the `card`, there is another `div` with the class `container` that holds the content of the card.
- The `container` has two main sections: `header` and `section`.
- The `header` contains an image of the QR code.
- The `section` contains a heading and a paragraph that instructs the user to scan the QR code.

## Styles

The CSS styles are defined in the `style` tag within the `head` of the HTML document. The styles include:

- Basic styles for the `html` and `body` elements.
- Styles for the `card` and `container` classes that center their content and give them a specific width and height.
- Styles for the `header` and `section` elements that arrange their children in a column and center them.
- Styles for the `img` element in the `header` that control its width and how it fits into its container.
- Styles for the `h1` and `p` elements in the `section` that control their font size, weight, alignment, and color.
- Media queries for larger devices (tablets and desktops) that adjust the width of the `card`.

## Responsive Design

The component is designed to be responsive. It was designed under the mobile First approach and has different styles for mobile devices, tablets, and desktops:

- On mobile devices, the `card` takes up the full width of the screen.
- On tablets and larger devices (screen width of 768px and above), the `card` takes up 65% of the screen width and is centered.
- On desktops and larger devices (screen width of 1024px and above), the `card` takes up 25% of the screen width.

## Author - 🤖

- Website - [Github](https://github.com/brandt33)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/brandt33)
