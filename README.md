Wordle Game Clone
A fully-functional, browser-based implementation of the popular Wordle game with a clean, modern UI.
Features

🎮 Complete Wordle gameplay experience
🎭 Dark and light theme toggle
📊 Statistics tracking (stored in local storage)
📱 Fully responsive design for desktop and mobile
⌨️ Physical and on-screen keyboard support
🔄 Animated tile flips and UI feedback
❓ Built-in how-to-play guide
🎲 Word selection from a curated list

Technologies Used

HTML5
CSS3 (with animations and responsive design)
Vanilla JavaScript
LocalStorage API for game statistics

How to Play

Guess the WORDLE in 6 tries
Each guess must be a valid 5-letter word
After each guess, the color of the tiles will change:

🟩 Green: Letter is in the correct position
🟨 Yellow: Letter is in the word but in the wrong position
⬜ Gray: Letter is not in the word



Installation and Setup
No dependencies required! This game runs entirely in the browser with vanilla JavaScript.
Option 1: Direct download

Clone this repository: git clone https://github.com/your-username/wordle-clone.git
Open index.html in your browser

Option 2: GitHub Pages
Visit the live demo here
Project Structure
wordle-clone/
├── index.html      # Main HTML file with embedded CSS and JavaScript
├── README.md       # Project documentation
└── LICENSE         # License information
Customization
You can customize the game by modifying the following:

WORDS array: Add or remove words from the word list
CSS variables: Change the color scheme in the :root section
Word length and number of guesses: Requires more extensive code changes

Future Enhancements

 Daily challenges
 Word definitions after completion
 Additional languages
 Hard mode
 Custom word length option
 Share results functionality

Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

Fork the repository
Create your feature branch (git checkout -b feature/amazing-feature)
Commit your changes (git commit -m 'Add some amazing feature')
Push to the branch (git push origin feature/amazing-feature)
Open a Pull Request

License
This project is licensed under the MIT License - see the LICENSE file for details.
Acknowledgments

Inspired by the original Wordle game
Word list curated from common 5-letter English words
