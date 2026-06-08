<p align="center">
  <img src="Scanumbra.png" alt="Scanumbra Logo" width="900">
</p>



# Scanumbra

Scanumbra is a lightweight, interactive shell utility designed for steganography, metadata analysis, and file privacy. It centralizes robust tools like ExifTool, Steghide, ImageMagick, and OpenSSL into a single, cohesive command-line interface.

## Features

* **Metadata Inspection**: View hidden file details and EXIF tags using ExifTool.
* **Steganography**: Securely hide or extract data inside image containers using Steghide.
* **Image Conversion**: Transition assets from JPEG to PNG natively via ImageMagick.
* **Symmetric Encryption**: Encrypt and decrypt sensitive files using OpenSSL with AES-256-CBC and PBKDF2 key derivation.
* **Smart Dependency Management**: Automatically detects missing system packages, handles installation on Debian-based systems via `apt`, or guides users on other distributions.

## Prerequisites

Scanumbra relies on the following standard tools:
* ExifTool
* Steghide
* ImageMagick
* OpenSSL

Upon its first execution, Scanumbra will automatically check for these dependencies. If you are on a Debian-based distribution, it will offer to install them for you. On other distributions, it will list the missing packages so you can install them via your package manager.

## Installation and Execution

1. Clone or download the repository containing the script:
   ```bash
   git clone [https://github.com/evdk25-wq/Scanumbra.git](https://github.com/evdk25-wq/Scanumbra.git)
   cd Scanumbra
   chmod +x Scanumbra.sh
   ./Scanumbra.sh
