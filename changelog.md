# Changelog
### 5/2/2024
* All bugs has been fixed.
* Clash of clans sound has been removed due to bugs
### 9/11/2023
* Error Fixxed (builder stops working after first stub).
### 9/10/2023
* Added Battle.Net session stealer
### 11/08/2023
* Added Clash of clans sound on startup (idk why tbh i was boreed).
* Fixed Phantom (used just gave u an error when starting the builder).
### 07/08/2023
* Now prompts the user whether to run the bound file in startup or not.
* Renames entry point (may break unpackers).
* Fixed gcc flag for future PyInstaller update.
* Added browsers' autofills data stealer.
* Now recompiles PyInstaller's bootloader if `gcc` is found.
* Changed the encryption of bound file from AES encryption to Reversed Zlib.
* Fixed GoFile uploader.
* Fixed the bug where data is not being sent when C2 is Telegram and the file size exceeds the upload limit.
* Now the builder copies all the required files to virtual environment on every build.
* Now encrypts the bound executable.
* Now checks if defender blocked the file in case of UAC bypass.
* Readded the certificate and version file.
* Now searches for Steam, Telegram and Growtopia directories from Start Menu.
* Changed configuration file from 'config.ini' to 'config.json'.
* Removed certificate and version file to reduce detections.
* Added Growtopia session stealer.
* Removed tree file generated at the root of the archive.
* Added support for multi-word password of archive.
* Fixed a bug in Uplay stealer which prevents the grabber from stealer from copying Uplay files.
* Removed SSL certificate check in builder.
* Fixed 'AttributeError' in Discord injection.
* Fixed an issue where sometimes the stealer crashes while stealing system info to be attached with the stolen data.
* added a changelog.
