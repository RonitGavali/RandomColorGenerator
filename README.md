# Random Color Generator

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Description
This is a simple web application that generates a random background color when the button is clicked. The generated color code is displayed on the screen and is automatically copied to the clipboard.

## Features
- Generates a random background color on page load and button click.
- Displays the generated color code in hexadecimal format.
- Automatically copies the generated color code to the clipboard.

## Technologies Used
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## How It Works
1. The webpage loads with a randomly generated background color.
2. Clicking the "Click Me" button generates a new random color.
3. The generated color code is displayed on the screen.
4. The color code is automatically copied to the clipboard.

## File Structure
```
- index.html  (Main HTML file)
- style.css   (CSS for styling)
- script.js   (JavaScript for functionality)
```

## Code Explanation
### `script.js`
1. The `getColor` function generates a random hexadecimal color code using `Math.random()` and `toString(16)`.
2. The background color of the webpage is updated with the generated color.
3. The color code is displayed inside the `<h1>` tag with id `color-code`.
4. The generated color code is copied to the clipboard using `navigator.clipboard.writeText()`.
5. The `getColor` function is called on page load and also triggered on button click.

## Installation and Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/random-color-generator.git
   ```
2. Navigate to the project directory:
   ```sh
   cd random-color-generator
   ```
3. Open `index.html` in a web browser.

## Demonstration
Below is a short video demonstrating the functionality of this project:

```html
<video width="600" controls>
  <source src="[video/demo.mp4](https://github.com/RonitGavali/RandomColorGenerator/blob/main/RandomColorGenerator.mp4)" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

## Contribution
Feel free to fork this repository and contribute by submitting pull requests.

## License
This project is open-source and available under the MIT License.

