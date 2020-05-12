# Mosqueton-Goku

Inspired by [Capslock by Vonng](https://github.com/Vonng/Capslock) and [Goku](https://github.com/yqrashawn/GokuRakuJoudo), `Mosqueton-Goku` is a half spanish translation of `Karabiner-Goku`. It contains keyboard shortcuts and Hyper key implementation (remapping of Capslock key)

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

## **WIP**