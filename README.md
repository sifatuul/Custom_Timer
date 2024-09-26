
# Custom Timer

A simple web-based timer that takes user input (in minutes) and starts a countdown. The timer features a large, clear display and minimalistic design, perfect for timing tasks or activities.

## Features

- Input field to enter a time (in minutes)
- Starts countdown when the user presses "Enter"
- Automatically stops when time reaches zero
- Large, easy-to-read timer display
- Dynamic formatting: displays as `MM:SS` or `HH:MM:SS` based on input

## Demo



## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/custom-timer.git
   ```

2. Navigate to the project directory:

   ```bash
   cd custom-timer
   ```

3. Open `index.html` in your web browser to use the timer.

## Usage

1. Open the page in any modern browser.
2. Input the number of minutes you want to set for the timer.
3. Press **Enter** to start the countdown.

## Technologies Used

- HTML5
- CSS3 (Including Google Fonts for custom typography)
- JavaScript

## How It Works

- The user inputs a number in the text box.
- Upon pressing "Enter", the input is converted from minutes to seconds.
- The timer countdown is displayed on the screen with a large, easy-to-read font.
- If the input is greater than or equal to 60 minutes, the timer shows the `HH:MM:SS` format.
- Otherwise, the timer shows the `MM:SS` format.
- The timer stops automatically when it reaches zero.

## Contributing

Feel free to open issues or submit pull requests with improvements and bug fixes. Contributions are always welcome!

## License

This project is licensed under the MIT License.