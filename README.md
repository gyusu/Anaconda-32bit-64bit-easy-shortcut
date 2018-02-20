# Anaconda-32bit-64bit-easy-shortcut
For anyone who uses both Anaconda 32-bit and 64-bit with **Windows 10**.

## Install
#### *After Effect*
1. generate cmd(administrator) shortcut
2. generate Anaconda Prompt 32bit(administrator) shortcut
3. generate Anaconda Prompt 64bit(administrator) shortcut

and makes them universally accessible for USER (by adding path)

### Step 1. Clone or Download ZIP
```shell
$ git clone https://github.com/gyusu/Anaconda-32bit-64bit-easy-shortcut C:/Anaconda-32bit-64bit-easy-shortcut
```

### Step 2. set Environment Variables for Anaconda directory
open cmd.exe with Administrator Right, and set Environment Variables as below
```shell
setx ANACONDA_32BIT "YOUR ANACONDA 32bit DIRECTORY PATH"
setx ANACONDA_64BIT "YOUR ANACONDA 64bit DIRECTORY PATH"
```
(example)
```shell
setx ANACONDA_32BIT "C:\Users\gyusu\Anaconda3_32"
setx ANACONDA_64BIT "C:\Users\gyusu\Anaconda3_64"
```

### Step 3. Add repository's directory to PATH
```shell
setx path "%path%;C:\Anaconda-32bit-64bit-easy-shortcut"
```

## Usage

- <kbd>Windows</kbd> + <kbd>R</kbd> -> ***sudocmd*** <kbd>Enter</kbd>
- <kbd>Windows</kbd> + <kbd>R</kbd> -> ***conda32*** <kbd>Enter</kbd>
- <kbd>Windows</kbd> + <kbd>R</kbd> -> ***conda64*** <kbd>Enter</kbd>  

in File Explorer..
- <kbd>Ctrl</kbd> + <kbd>L</kbd> -> ***sudocmd*** <kbd>Enter</kbd>
- <kbd>Ctrl</kbd> + <kbd>L</kbd> -> ***conda32*** <kbd>Enter</kbd>
- <kbd>Ctrl</kbd> + <kbd>L</kbd> -> ***conda64*** <kbd>Enter</kbd>

