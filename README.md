# FreeBSD Linux Game Launcher

This project provides a simple game launcher for FreeBSD, 
using a Debian-based Linux environment and `zenity` for a graphical user interface. 
The launcher allows users to select and launch games with an icon, 
following FreeBSD Desktop Guidelines.

## Features

- Easy setup of a Linux environment using `debootstrap`.
- Graphical interface for selecting and launching games using `zenity`.
- Option to display a game icon after successful installation.
- Self-expanding window for game installation and launch progress.
- Desktop entry creation for easy game launching.

## Requirements

- FreeBSD
- `debootstrap`
- `zenity`

## Installation

1. Make the setup script executable:
    ```sh
    chmod +x game_launcher_setup.sh
    ```

2. Run the setup script as root:
    ```sh
    sudo ./game_launcher_setup.sh
    ```

3. Follow the prompts to select the installation directory and Debian release.

4. Use the game launcher to select and launch games:
    ```sh
    game-launcher
    ```

## Usage

- To enter the Linux environment:
    ```sh
    sudo enter-linux
    ```

- To launch a game:
    ```sh
    game-launcher
    ```

## License

This project is licensed under the MIT License.
