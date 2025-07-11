# 🚀 Cursor Trial Reset Tool

[![GitHub release](https://img.shields.io/github/release/Nom-nom-hub/cursor-trial-unlimited.svg)](https://github.com/Nom-nom-hub/cursor-trial-unlimited/releases)
[![GitHub stars](https://img.shields.io/github/stars/Nom-nom-hub/cursor-trial-unlimited.svg)](https://github.com/Nom-nom-hub/cursor-trial-unlimited/stargazers)
[![GitHub license](https://img.shields.io/github/license/Nom-nom-hub/cursor-trial-unlimited.svg)](https://github.com/Nom-nom-hub/cursor-trial-unlimited/blob/master/LICENSE)

The most reliable and safe tool for resetting your Cursor trial period. This tool is designed to work seamlessly on both Windows and macOS systems.

> Current Version: v17
> Next Release: v18

## ✨ Features

- 🔄 **Complete Reset**: Removes all trial-related data
- 💾 **Automatic Backup**: Creates backups before making any changes
- 📝 **Detailed Logging**: Comprehensive operation logs
- ✅ **Verification System**: Ensures all operations are successful
- 🛡️ **Safety First**: Built-in safety checks and validations
- 🌐 **Cross-Platform**: Supports both Windows and macOS

## 📋 Prerequisites

### Windows
- Windows 10 or later
- PowerShell 5.1 or later
- Administrator privileges

### macOS
- macOS 10.13 or later
- Terminal access
- Administrator privileges

## 🚀 Installation

### Windows
1. Download the `cursor_reset.ps1` script
2. Right-click the script and select "Run with PowerShell"
3. If prompted, allow the script to run

### macOS
1. Download the `cursor_reset_mac.sh` script
2. Open Terminal
3. Make the script executable:
   ```bash
   chmod +x cursor_reset_mac.sh
   ```

## 💻 Usage

### Windows
1. Close Cursor if it's running
2. Right-click `cursor_reset.ps1`
3. Select "Run as Administrator"
4. Follow the on-screen instructions
5. Restart Cursor

### macOS
1. Close Cursor if it's running
2. Open Terminal
3. Navigate to the script directory
4. Run the script with sudo:
   ```bash
   sudo ./cursor_reset_mac.sh
   ```
5. Follow the on-screen instructions
6. Restart Cursor

## 🔍 What This Tool Does

### Windows
- Removes registry entries:
  - `HKCU:\Software\Cursor`
  - `HKCU:\Software\Microsoft\Windows\CurrentVersion\Uninstall\Cursor`
- Deletes local app data:
  - `%LOCALAPPDATA%\Cursor`
- Clears Windows cache:
  - `%TEMP%\Cursor*`
  - `%TEMP%\cursor*`

### macOS
- Removes application data:
  - `~/Library/Application Support/Cursor`
  - `~/Library/Caches/Cursor`
  - `~/Library/Preferences/com.cursor.Cursor.plist`
- Cleans system caches:
  - `~/Library/Caches/com.cursor.Cursor`

## 🔒 Safety Features

1. **Automatic Backup**
   - Creates timestamped backups
   - Stores in a dedicated backup directory
   - Preserves all original data

2. **Verification System**
   - Validates all operations
   - Confirms successful removal
   - Provides detailed status reports

3. **Logging System**
   - Detailed operation logs
   - Timestamp for each action
   - Error tracking and reporting

## ⚠️ Important Notes

- Always close Cursor before running the script
- Keep the backup files until you confirm everything works
- Run the script with administrator privileges
- Do not modify the script unless you know what you're doing

## 🔧 Troubleshooting

### Common Issues

1. **Script won't run**
   - Ensure you have administrator privileges
   - Check if PowerShell execution policy allows scripts
   - Verify the script is not blocked by Windows

2. **Backup fails**
   - Check available disk space
   - Ensure you have write permissions
   - Verify the backup directory is accessible

3. **Reset doesn't work**
   - Make sure Cursor is completely closed
   - Check the log file for errors
   - Try running the script again

## 📝 Log Files

Logs are stored in the `logs` directory with the format:
```
cursor_reset_YYYYMMDD_HHMMSS.log
```

Each log contains:
- Timestamp for each operation
- Success/failure status
- Detailed error messages (if any)
- Backup information

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## ⭐ Support

If you find this tool helpful, please consider:
- Starring the repository
- Sharing with others
- Reporting any issues

## 🔗 Links

- [GitHub Repository](https://github.com/Nom-nom-hub/cursor-trial-unlimited)
- [Latest Release](https://github.com/Nom-nom-hub/cursor-trial-unlimited/releases)
- [Issue Tracker](https://github.com/Nom-nom-hub/cursor-trial-unlimited/issues)

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspired by the need for a reliable reset tool
- Built with safety and reliability in mind 