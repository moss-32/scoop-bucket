# Moss Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [Moss-32](https://moss32.com) fantasy console CLI.

## Installation

1. Install Scoop

Open **PowerShell** and run:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Add Moss Bucket URL (only needed first time)

Run the following command to add this repository to your Scoop installation:

```powershell
scoop bucket add moss https://github.com/moss-32/scoop-bucket
```

3. Install Moss

```powershell
scoop install moss
```

## Updating

To update moss console:

```powershell
scoop update moss
```
