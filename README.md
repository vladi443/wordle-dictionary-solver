# wordle-dictionary

C++ algorithm that scores and attempts to guess the daily word for the popular web game _Wordle_.

## Installation

Refer to the compile code instructions found at https://ziggurat.systems/docs/compile-instructions/.

## Usage

Windows

1. Navigate to the folder where the compiled Dictionary file is located.
2. Once in the targeted folder, open CMD and type ```<preferred-name>.exe``` or double click the ```<preferred-name>.exe``` file from file explorer.
3. Dictionary will start either in the CMD window where the command was typed, or will open a new CMD window if opened through file explorer.
4. Dictionary will then begin loading data from the text files and prepare to start. If an error occurs while loading the data from the text files Dictionary will display an error message and exit the process. If this occurs go back to ```step 4-6``` from the installation instructions.
5. Once started, Dictionary will ask you wheter you want to boot the program in debug mode. Debug mode allows you to input a word that will be traced throughout the program's algorithm, allowing you to easily troubleshoot or identify problems you might encounter. Input ```Y/n``` to either boot in debug or normal mode.
6. Dictionary will then proceed to ask if it should compute optimal starting words before continuing. Dictionary does that by identifying the most used charachters and trying to make a word with them, increasing the chance that your word will have a match. You can select if you want to compute optimal starting words by typing ```Y/n```. (Note: even if you select for dictionary to compute optimal starting words, you do not have to use them as a starting word. Dictionary will let you choose which word you want to start with).
7. Once these settings have been made, Dictionary will boot up and display a small instructions window that can be used as a reference when using the program. It will ask the user for ```input``` which will be the word that the user chooses to begin with. Make sure you input the word with spaces between each charachter. (ex. b r e a d).
8. Once the input was collected, Dictionary will ask for the ```output``` of the selected word. The output is the result you get from typing the word you chose (the input) into the _Wordle_ website. The output will therefore be a 5-digit number, with each digit being 0 to represent no match of the correlating charachter, 1 to represent the correlating charachter is present in a different location, and 2 to present the correlating charachter is present in the same location. Make sure you input the number with spaces between each digit. (ex. 2 2 0 2 2).
9. Dictionary will then use the inputted information to re-score the words and display the top 20 best matching words together with a definition for some of the words.
10. Dictionary will then ask you to repeat ```steps 7-9```, inputting new words until you have guessed the daily word.
11. Once guessed, Dictionary will ask you wheter you want to restart the session or quit the program. You can choose that by typing ```(Y/n)```.

Linux / MacOS

1. Navigate to the folder where the compiled Primes file is located.
2. Once in the targeted folder, open terminal and type ```./<preferred-name>```.
3. 4. Dictionary will then begin loading data from the text files and prepare to start. If an error occurs while loading the data from the text files Dictionary will display an error message and exit the process. If this occurs go back to ```step 4-6``` from the installation instructions.
4. Dictionary will start in the same terminal window where the ```step 2``` command was executed.
5. 5. Once started, Dictionary will ask you wheter you want to boot the program in debug mode. Debug mode allows you to input a word that will be traced throughout the program's algorithm, allowing you to easily troubleshoot or identify problems you might encounter. Input ```Y/n``` to either boot in debug or normal mode.
6. Dictionary will then proceed to ask if it should compute optimal starting words before continuing. Dictionary does that by identifying the most used charachters and trying to make a word with them, increasing the chance that your word will have a match. You can select if you want to compute optimal starting words by typing ```Y/n```. (Note: even if you select for dictionary to compute optimal starting words, you do not have to use them as a starting word. Dictionary will let you choose which word you want to start with).
7. Once these settings have been made, Dictionary will boot up and display a small instructions window that can be used as a reference when using the program. It will ask the user for ```input``` which will be the word that the user chooses to begin with. Make sure you input the word with spaces between each charachter. (ex. b r e a d).
8. Once the input was collected, Dictionary will ask for the ```output``` of the selected word. The output is the result you get from typing the word you chose (the input) into the _Wordle_ website. The output will therefore be a 5-digit number, with each digit being 0 to represent no match of the correlating charachter, 1 to represent the correlating charachter is present in a different location, and 2 to present the correlating charachter is present in the same location. Make sure you input the number with spaces between each digit. (ex. 2 2 0 2 2).
9. Dictionary will then use the inputted information to re-score the words and display the top 20 best matching words together with a definition for some of the words.
10. Dictionary will then ask you to repeat ```steps 7-9```, inputting new words until you have guessed the daily word.
11. Once guessed, Dictionary will ask you wheter you want to restart the session or quit the program. You can choose that by typing ```(Y/n)```.

## Troubleshooting

If you encounter any problems during compiling or using Dictionary, please open an issue and describe the problem found. Sample data or screenshots will be extremely helpful troubleshooting the problem.

Make sure you have successfully followed the installation steps, especially ```steps 4-6```, as Dictionary requires to be able to read the two text files in order to work properly.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change or add to Dictionary

Please make sure to update tests as appropriate and document the changes made.

## Acknowledgements

Special thanks to [MakeaREADME](https://www.makeareadme.com) which template and information I used when developing this README.

Special thanks to [english-words github repository](https://github.com/dwyl/english-words), from which the ```words_dictionary.txt``` file was taken, and special thanks to [Custom Dictionary](https://raw.githubusercontent.com/sujithps/Dictionary/master/Oxford%20English%20Dictionary.txt), from which the ```words_definitions.txt``` file was taken. You can click on their names to look, use, or support their projects. Their work was crucial to the development of the Dictionary algorithm, so special thanks again for making their work available to the public.

Dictionary was inspired by the popular [Wordle](https://www.nytimes.com/games/wordle/index.html) Web Game, which you can play by clicking on its name.

## License
[GNU GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html)
