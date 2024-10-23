"# powershell_tool" 
# Shutdown Confirmation Script

A PowerShell script that provides a modern, graphical user interface for confirming system shutdown operations.

## Overview

This script creates a customized Windows Forms dialog box that prompts users to confirm shutdown operations. It provides a clean, modern interface with customizable colors, fonts, and interactive elements.

## Features

- Modern, flat design interface
- Customizable color scheme
- Draggable window
- Multiple confirmation types:
  - Simple confirmation
  - Question with Yes/No options
  - Information display
  - Warning messages
  - Error messages
- Checkbox confirmation for critical operations
- Radio button options for Yes/No choices
- Responsive layout that adjusts to content

## Requirements

- Windows PowerShell 5.1 or later
- Windows OS with .NET Framework
- Administrative privileges (for shutdown operations)

## Usage

1. Run the script directly in PowerShell:
```powershell
.\shutdown.ps1
```

2. The script can be called with parameters for different confirmation types:
```powershell
Get-Popup -Message "Your message here" -Type "Question"
```

### Available Types
- Question
- Confirmation
- Information
- Warning
- Error



