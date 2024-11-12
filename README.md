# ark-ini-loader
Ark INI Loader

Ark INI Loader is a goofy Windows application designed to quickly load and replace your InI files for the game ARK: Survival Evolved. This tool allows you to easily import, preview, and apply custom INI configurations to streamline your gameplay settings.
Features

    Load Base Config File: Select the primary BaseDeviceProfiles.ini (formerly known as ConsoleVariables) configuration file.
    Import INI Files: Import individual ini files or batch-load multiple ini files from a selected folder.
    Preview and Apply: Preview the contents of each imported INI file and apply it to the base config with a single click.
    Backup Creation: Creates a backup of your base file before any changes are applied.
    Custom INI List Management: Easily clear the INI list or select specific configurations.

Installation

    Download the latest release from the Releases page.
    Extract the .zip file contents to a directory of your choice.
    Run the Ark INI Loader.exe file to start the application.

    Note: This application is built with Python and PyInstaller, so no Python installation is required for the executable.

Usage

    Set Base File Path: Click "Browse" to select the BaseDeviceProfiles.ini file you wish to modify.
    Import INI Files:
        Load Folder: Load all .ini files from a selected folder.
        Load Single File: Import a single .ini file from anywhere on your system.
    Select and Preview: Choose an imported INI file from the dropdown to preview its contents.
    Apply Configuration: Click "Apply" to replace the base file with the selected INI file.
    Clear INI List: Remove all loaded INI files from the dropdown with the "Clear INI List" button.

Requirements

    Windows OS: This tool is designed for Windows.

Troubleshooting

    Windows Defender Flag: This executable may be flagged by Windows Defender as a false positive due to the PyInstaller bundling process. To resolve this:
        Add an exception in Windows Defender.

Contributing

If you'd like to contribute to the Ark INI Loader project, please submit a pull request or open an issue on GitHub. Contributions for additional features, bug fixes, and documentation improvements are welcome!
License

This project is licensed under the MIT License - see the LICENSE file for details.
Author

GoofyAhhDev
Made with ❤️ and frustration to streamline ARK INI management.