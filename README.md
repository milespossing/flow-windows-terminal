This repository lovingly follows the [nord-windows-terminal](https://github.com/thismat/nord-windows-terminal) repository. Thank you @thismat for your hard work on that.

![screenshot](./screenshot.png)

# Getting Started

This is an _unofficial_ port of [Flow](https://github.com/0xstepit/flow.nvim) to Windows Terminal. Visit [Flow](https://github.com/0xstepit/flow.nvim) for more information about the theme. 

> Flow is an Nvim color scheme designed for transparent or dark backgrounds. It features carefully designed colors to help focusing during coding plus fluorescent details to provide a vibrant environment. Why fluo? Because it is cool!.

## Install

### Easy Install

Run the `install.ps1` PowerShell script to install the colorscheme via [Windows Terminal JSON Fragments](https://docs.microsoft.com/en-us/windows/terminal/json-fragment-extensions#where-to-place-the-json-fragment-files)

> **Note**  
> To allow the execution of the installation script without having to relax the [Execution Policy][ps-execpolicy] of the entire system, you can unblock the `install.ps1` file using the [Unblock-File][ps-unblockfile] PowerShell cmdlet.
>
> ```powershell
> Unblock-File .\install.ps1
> ```

[ps-execpolicy]: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.security/set-executionpolicy?view=powershell-7.2
[ps-unblockfile]: https://docs.microsoft.com/en-us/powershell/module/microsoft.powershell.utility/unblock-file?view=powershell-7.2

### Manual

TODO

Simply copy the JSON from [`flow.json`](https://raw.githubusercontent.com/milespossing/flow-windows-terminal/main/flow.json) or from this page, into the `schemes` section of Windows Terminal `profile.json`.
