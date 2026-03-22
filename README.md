# WORDLE 🔠
A replica of the original Wordle game on The New York Times made by Josh Wardle, made using the Python Tkinter library.

## INSTALLATION ⚙️
Clone the repository:

```bash
git clone https://github.com/CrypticT1tan/wordle.git
```

Use package manager pip to install the following:

```bash
pip install pyinstaller
```

To build the executable file, use the terminal to go into the same directory as the main.py file and run the command below:

```bash
pyinstaller main.py --hidden-import=tkinter --onefile --windowed --add-data "../assets:assets" --icon=../assets/wordle.icns --name "Wordle"
```

Open up the dist file to find an executable file with your desired name, and open it.

## USAGE 🔧
The rules work exactly the same as the Wordle game on The New York Times website.  
Input 5-letter word guesses into the entry box to figure out the mystery word within 6 guesses.  
Press the Enter key to get the results of your guess.  
Green 🟩 means the letter is in the right spot.  
Yellow 🟨 means the letter is in the mystery word but is also misplaced.  
White ⬜ means the letter isn't in the mystery word at all.  

## CONTACT 📞
For any questions, contact me at gavinkiosco@gmail.com via email or cryptict1tan on Discord.
