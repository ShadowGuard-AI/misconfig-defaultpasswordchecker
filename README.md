![Banner](banner.png)

# misconfig-DefaultPasswordChecker
Scans configuration files and running processes for the presence of default passwords. Uses a predefined database of common default credentials and simple pattern matching via `psutil` and file system crawling. - Focused on Check for misconfigurations in configuration files or infrastructure definitions

The run exits 1 when the `--root-dir` value does not exist or is not a directory, before any completed scan line is printed and before any output file is written. Files that cannot be read during the walk are counted, the closing status states that the file scan was incomplete with the unread count, and the run exits 1.

## Install
`git clone https://github.com/ShadowStrikeHQ/misconfig-defaultpasswordchecker`

## Usage
`./misconfig-defaultpasswordchecker [params]`

## Parameters
- `-h`: Show help message and exit
- `--root-dir`: The root directory to start the file system scan. Defaults to 
- `--no-process-scan`: Disable scanning of running processes.
- `--output`: No description provided
- `--verbose`: No description provided

## License
Copyright (c) ShadowStrikeHQ
