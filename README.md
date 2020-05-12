# Mosqueton-Goku

Inspired by [Capslock by Vonng](https://github.com/Vonng/Capslock), [Goku by yqrashawn](https://github.com/yqrashawn/GokuRakuJoudo), and [Karabiner God Mode by Nikita Voloboev](https://medium.com/@nikitavoloboev/karabiner-god-mode-7407a5ddc8f6) `Mosqueton-Goku` is my own Karabine - Implementation which aims to provide very useful (at least for me) keyboard shortcuts to improve my productivity on my **Mac**. `Mosqueton-Goku` is also a very bad half spanish translation of `Karabiner-Goku`, sorry I was not inspired. Nothing fancy, if you find useful feel free copy and modify it.

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

### Chrome, VSCode

| Origin | Maps to          | Comment |
| ------ | ---------------- | ------- |
| `F1`   | `^PageUp`           |         |
| `F2`   | `^PageDown` |         |
| `F3`   | `Close tab`      |         |

### Finder

| Origin | Maps to              | Comment |
| ------ | -------------------- | ------- |
| `F1`   | `Go to previous tab` |         |
| `F2`   | `Go to next tab`     |         |
| `F3`   | `Close tab`          |         |

## **WIP**
