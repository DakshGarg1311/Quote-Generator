# Fierce Quote Generator Landing Page

This project is a simple, visually striking landing page that displays inspirational quotes. It features a fiery background gradient and animated flame elements to create a dynamic and intense aesthetic. Clicking the "GET QUOTES" button will cycle through a predefined set of Naruto quotes.

## Features

* **Dynamic Background:** A smooth, animated gradient of dark reds and blacks creates a fierce and engaging backdrop.
* **Animated Flames:** Floating, blurred flame elements with a subtle flicker animation enhance the visual intensity.
* **Bold Call to Action:** A prominent "GET QUOTES" button with a glowing hover effect encourages user interaction.
* **Quote Display:** A stylishly formatted quote is displayed prominently on the page, with a subtle pulsing text shadow.
* **Responsive Design (Basic):** The layout adapts to smaller screens with adjustments to the quote text size.
* **Naruto Quotes:** Currently configured to display a collection of inspirational quotes from the anime series Naruto.

## How to Use

1.  **Clone the Repository:** If you have this code in a GitHub repository, clone it to your local machine:
    ```bash
    git clone <repository_url>
    ```
2.  **Open in Browser:** Navigate to the directory where you saved the `index.html` file and open it with your web browser (e.g., Chrome, Firefox, Safari).
3.  **Get Quotes:** Click the "GET QUOTES" button to display a random quote from the Naruto series. Click again to see another quote.

## Code Structure

* **`index.html`:** Contains the main HTML structure, including the button, the quote display area (`<p class="quote">`), and the embedded CSS and JavaScript.
* **`<style>` tag:** Includes all the CSS rules for styling the background, container, button, quote text, and flame animations.
* **`<script>` tag:** Contains the JavaScript code that:
    * Defines an array (`narutoQuotes`) of quote objects, each containing a `quote`, `character`, and `imageUrl` (currently not displayed).
    * Implements a `quote()` function that randomly selects a quote from the `narutoQuotes` array and updates the content of the `<p class="quote">` element.

## Customization

* **Quotes:** To change the quotes, modify the `narutoQuotes` array in the `<script>` section. You can add more quotes or replace the existing ones.
* **Styling:** Adjust the CSS rules within the `<style>` tag to change the colors, fonts, animations, and overall appearance of the landing page.
* **Images (Future Enhancement):** The `imageUrl` property in the `narutoQuotes` array is currently not used. You could extend the JavaScript to also display an image associated with each quote.

## Potential Enhancements

* **Display Character Name:** Show the character who said the quote.
* **Image Display:** Utilize the `imageUrl` to display relevant images.
* **More Quotes:** Expand the `narutoQuotes` array with a larger variety of quotes.
* **User Interface Improvements:** Add more sophisticated animations or transitions.
* **Responsiveness:** Implement a more comprehensive responsive design for various screen sizes.
* **Quote Source:** Allow users to select quotes from different categories or sources.

## Author

[DakshGarg1311]
