# Mosqueton-Goku

Inspired by [Capslock by Vonng](https://github.com/Vonng/Capslock), [Goku by yqrashawn](https://github.com/yqrashawn/GokuRakuJoudo), [TaranVH 2nd Keyboard scripts](https://github.com/TaranVH/2nd-keyboard) and [Karabiner God Mode by Nikita Voloboev](https://medium.com/@nikitavoloboev/karabiner-god-mode-7407a5ddc8f6); `Mosqueton-Goku` is my own Karabine+Goku configuration which aims to provide very useful (at least for me) keyboard shortcuts to improve my productivity on my **Mac**. `Mosqueton-Goku` is also a very bad half spanish translation of `Karabiner-Goku`, sorry I was not inspired at the time. Nothing fancy, if you find it useful feel free copy and modify it.

## Pre-requisites

- [karabiner-elements](https://karabiner-elements.pqrs.org/)
- [goku](https://github.com/yqrashawn/GokuRakuJoudo)
- [watchexec](https://github.com/watchexec/watchexec)
- [joker](https://github.com/candid82/joker)

## Install (mac)

1. Clone this repo
2. Create a softlink

   ```bash
   ln -s mosqueton-goku/karabiner.edn ~/.config/karabiner.edn
   ```

3. Install Goku

   ```bash
   brew install yqrashawn/goku/goku
   ```

4. Start Goku service

   ```bash
   brew services start goku
   ```

5. Open Karabiner and confirm you can see rules enabled

## Usage

### Chrome

| Origin | Maps to                          | Comment            |
| ------ | -------------------------------- | ------------------ |
| `F1`   | <kbd>^</kbd>+<kbd>PageUp</kbd>   | Go to previous tab |
| `F2`   | <kbd>^</kbd>+<kbd>PageDown</kbd> | Go to next tab     |
| `F3`   | <kbd>⌘</kbd>+<kbd>W</kbd>        | Close tab          |

### VSCode

| Origin | Maps to                                             | Comment               |
| ------ | --------------------------------------------------- | --------------------- |
| `F1`   | <kbd>^</kbd>+<kbd>⎇</kbd>+<kbd>⌘</kbd>+<kbd>´</kbd> | Go to previous editor |
| `F2`   | <kbd>^</kbd>+<kbd>⎇</kbd>+<kbd>⌘</kbd>+<kbd>ç</kbd> | Go to next tab        |
| `F3`   | <kbd>⌘</kbd>+<kbd>W</kbd>                           | Close tab             |

### Finder

| Origin | Maps to                                           | Comment   |
| ------ | ------------------------------------------------- | --------- |
| `F1`   | <kbd>⌘</kbd>+<kbd>]</kbd>                         | Go back   |
| `F2`   | <kbd>⌘</kbd>+<kbd>`</kbd> | Cycle through windows |
| `F3`   | <kbd>⌘</kbd>+<kbd>W</kbd>                         | Close tab |

## **WIP**
