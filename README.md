# Animated Div Elements

This project dynamically generates div elements inside two parent containers (`.c1` and `.c2`) and animates them using Anime.js.

## Features
- Creates a specified number of child divs inside `.c1` and `.c2`
- Uses Anime.js to apply a scaling animation to all child divs
- Animation includes staggered delays for a visually appealing effect

## Technologies Used
- **HTML**: Structure of the elements
- **CSS**: Basic styling (not included in this snippet but can be added)
- **JavaScript**: DOM manipulation and element creation
- **Anime.js**: Animation handling

## Installation
1. Clone this repository:
   ```sh
   git clone <repository-url>
   ```
2. Open the `index.html` file in your browser.

## Usage
Modify the `num1` and `num2` variables to adjust the number of child elements generated inside `.c1` and `.c2`.

```javascript
let num1 = 250;
let num2 = 300;
```

Customize the animation properties inside the `anime()` function to achieve different effects.

## Dependencies
- [Anime.js](https://animejs.com/)

## License
This project is open-source and available under the [MIT License](LICENSE).

