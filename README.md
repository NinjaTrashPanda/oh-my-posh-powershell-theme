# oh-my-posh-powershell-theme

My first attempt at a theme for Oh My Posh. Designed specifically for Powershell and Python.

The names of the colours used in the palette section are taken from the names given to the colours by the site coolors.co

To use place file in the folder specified in the POSH_THEEMS_PATH environment variable (to find this type `echo env:POSH_THEMES_PATH` in Powershell)

To run Oh-My-Posh when opening Powershell, create/edit the file Microsoft.PowerShell_profile.ps1 and add the following:

```
oh-my-posh init pwsh --config "$env:POSH_THEMES_PATH/ninjaraccoon.omp.json" | Invoke-Expression
```

More details and info at (https://ohmyposh.dev/docs/installation/windows)[https://ohmyposh.dev/docs/installation/windows]
