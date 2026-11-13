# Practice 1: Configuring Windows PowerShell

## Tasks Covered:
1. **Start and Pin PowerShell Console:** 
   - Launched the 64-bit Windows PowerShell console as Administrator and pinned it to the taskbar[cite: 458].
2. **Configure Console Properties:** 
   - Adjusted buffer size, command history, quick-edit mode, and UTF-8 code page (65001)[cite: 460].
3. **Start a Shell Transcript:** 
   - Captured the session output using `Start-Transcript`:
     ```powershell
     Start-Transcript C:\DayOne.txt
     ```
   - Verified transcript logging and reviewed system details via `$PSVersionTable`, `$ShellId`, `$PSCulture`, and `Get-Module`[cite: 461, 463].
4. **PowerShell ISE Customization:** 
   - Launched the 64-bit Windows PowerShell ISE as Administrator[cite: 464, 465]. 
   - Customized the appearance (single-pane view, hiding the command pane, and adjusting the color theme between Dark/Light modes)[cite: 466, 470, 471, 472].
5. **Stop Transcript:**
   - Ended the logging session using:
     ```powershell
     Stop-Transcript
     ```
