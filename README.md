# ezxt
A simpler, automatic way to extract files using Python 3.
Works on all Linux distributions.

## Installation
To install this simply download the file, and use the command:
```bash
sudo cp -va ezxt /usr/sbin/ && chmod +x /usr/sbin/ezxt
```
## Usage
Using this is very simple:
```bash
ezxt [FILE]
```
It will automatically detect the filetype and extract it for you. No fuss.

## Notes
So far, this will only extract the most common type of files. Use ```ezxt --help``` or ```ezxt -h``` to check which ones are supported (don't worry, though, as most are supported!).

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
