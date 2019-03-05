# Debloat-window-10
Destroy your window 10 to just run game faster
## Let's Blaze it

- [Download [zip]](https://github.com/W4RH4WK/Debloat-Windows-10/archive/master.zip)

## Execution

Enable execution of PowerShell scripts:

    PS> Set-ExecutionPolicy Unrestricted

Unblock PowerShell scripts and modules within this directory:

    PS > ls -Recurse *.ps1 | Unblock-File
    PS > ls -Recurse *.psm1 | Unblock-File

## Usage

1. Install all available updates for your system.
2. Edit the scripts to fit your need.
3. Run the scripts from a PowerShell with administrator priviledges (Explorer
   `Files > Open Windows PowerShell > Open Windows PowerShell as
   administrator`)
4. `PS > Restart-Computer`
5. Run `disable-windows-defender.ps1` one more time.
6. `PS > Restart-Computer`
