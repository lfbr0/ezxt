# ezxt
A simpler, automatic way to extract files using Bash.
Works on all Linux distributions.

## Installation
To install this simply download the file, and use the command:
```bash
sudo cp -va ezxt /usr/sbin/ && chmod +x /usr/sbin/ezxt
```
Or you can do it all at once with:
```bash
sudo wget https://raw.githubusercontent.com/lribr0/ezxt/master/ezxt && sudo cp -va ezxt /usr/sbin/ && chmod +x /usr/sbin/ezxt
```
## Usage
Using this is very simple:
```bash
ezxt [FILE] [PATH_TO_EXTRACT_FILE_TO]
```
Specifying a path is optional, however. You can just use ```ezxt [FILE]``` , and it will extract to $PWD - the Working Directory.
It will automatically detect the filetype and extract it for you. No fuss.

## Notes
So far, this will only extract the most common type of files. Use ```ezxt --help``` or ```ezxt -h``` for help.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
