# WinZedInstall

### HOW TO USE:

1. **Download the script** (`zedinstall.ps1`)
2. **Execute the script** in the parent directory where Zed should be.
3. **Run the script** using `.\zedinstall.ps1` in PowerShell:
   - If you encounter an error regarding "Execution policy", run:
     ```powershell
     Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope Process
     ```
4. **The script will now start!**

### REQUIRED DEPENDENCIES:

- Rust
- Git
- Windows 10/11 64-bit
- MSVC (Microsoft Visual C++) - VS YYYY C++ x64/x86 build tools (latest)

### INSTALLING DEPENDENCIES:

#### Using `installdependencies.ps1`:

- **Run** `installdependencies.ps1` to install dependencies **except** C++ build tools.
