# FTP Bruteforce Tool

A simple FTP brute force tool written in Python for educational purposes.

## Description

This tool performs dictionary-based FTP brute force attacks against remote servers. It reads potential passwords from a wordlist file and attempts to authenticate using each password until successful.

## Educational Purpose Only

⚠️ **Important:** This tool is intended for educational purposes only. It should only be used for:
- Testing your own systems
- Testing systems you have explicit permission to test
- Learning about network security concepts

## Requirements

- Python 3.x
- `ftplib` module (included in standard library)
- Wordlist file (default: `senhas.txt`)

## Usage

1. Edit `pw.txt` to include your target passwords (Create pw.txt and add passwords)
2. Run the script: `python ftp_bruteforce.py`
3. Enter the target IP when prompted

## Features

- IP address validation
- Error handling for common issues
- Clear status messages during operation

## Security Considerations

- Use responsibly and only on authorized systems
- Implement rate limiting to avoid account lockouts
- Add timeout support for unstable connections

## License

This project is for educational purposes only and comes with no warranty.
