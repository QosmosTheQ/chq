# chq Command Usage Guide

The `chq` command is a custom script that allows you to change permissions on a file and execute it. This guide explains how to set up and use the `chq` command. (its simply chmod +x "filename" && ./filename)

## Prerequisites

- You should have a bash (sh) shell available on your system.

## Installation

1. Clone or download the repository to your local machine.

2. Navigate to the directory containing the `chq` script using the terminal:

    ```bash
    cd /path/to/chq/script
    ```

3. Make the script executable:

    ```bash
    chmod +x chq
    ```

4. Create a symbolic link to make the `chq` command available globally (optional):

    ```bash
    sudo cp mychq /usr/local/bin/
    ```

Now, you can use the `chq` command globally in your terminal.

## Usage

To use the `chq` command, follow these steps:

1. Open a terminal.

2. Type `chq` followed by the name of the file you want to change permissions on and execute. For example:

    ```bash
    chq
    ```


3. The script will prompt you to enter the file name. Type the name of the file you want to modify, and press Enter.

4. The script will change the file permissions to make it executable and then execute the file.

## Troubleshooting

If you encounter any issues, double-check the file path and permissions.
Ensure that you have the necessary privileges to execute files in the chosen directory.

## License
This project is licensed under the MIT License.