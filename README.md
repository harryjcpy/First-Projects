# Heart Trail Animation

A simple and fun front-end project that creates a heart trail animation effect as the user moves their mouse cursor across the screen. The project uses JavaScript to dynamically generate heart shapes of various sizes and colors that follow the cursor, creating a visually appealing animation.

## Features

- **Mouse Movement Listener:** Listens for mouse movements and creates a heart trail.
- **Dynamic Heart Shapes:** Generates hearts of varying sizes and positions based on the cursor movement.
- **Smooth Animations:** Hearts fade out and change color gradually, providing a pleasing animation effect.

## Technologies Used

- **HTML5** for structuring the webpage.
- **CSS3** for styling the elements and animations.
- **JavaScript** for adding dynamic behavior and interactivity.

## Getting Started

### Prerequisites

To run this project locally, you need a web browser (like Chrome, Firefox, etc.) and an internet connection to fetch the heart icon image.

### Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/harryjcpy/heart-trail-animation.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd heart-trail-animation
    ```
3. **Open `index.html` in your browser:**
    ```bash
    open index.html
    ```
   or simply double-click on the `index.html` file.

### How It Works

- The project listens for mouse movements on the `body` element.
- When the user moves their mouse, a new heart shape (`span` element) is created at the cursor's position.
- The size of the heart is randomized to add a dynamic visual effect.
- The hearts fade out and change color as they animate upward, disappearing after a few seconds.

## Customization

You can easily customize the appearance and behavior of the heart trail by editing the `style.css` and `index.js` files:

- **Change the Heart Icon:** Replace the URL in the `background` property of the `span` selector in `style.css` with any other image URL.
- **Adjust Heart Size:** Modify the `Math.random()` multiplier in `index.js` to control the maximum size of the hearts.
- **Change Animation Duration:** Adjust the duration value in the `animation` property of `span` in `style.css` to make the hearts fade out faster or slower.

## Contributing

If you have any ideas or suggestions to improve the project, feel free to fork the repository and submit a pull request. Any contributions are greatly appreciated!

## Acknowledgements

- This project was inspired by various front-end animation tutorials found on YouTube.
