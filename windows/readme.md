# Windows configuration and customization

This file includes commands to customize Windows 10. 

## Localization

Run the following commands in Powershell terminal to customize OS:
  
    # Set Slovenian locale for non-Unicode programs (system locale)
    Set-WinSystemLocale -SystemLocale sl-SI

    # Set Slovenian regional format (date, time, currency, etc.)
    Set-WinHomeLocation -GeoId 212  # Slovenia's GeoID is 212
    Set-Culture -CultureInfo sl-SI

    # Set Slovenian date/time formats for current user
    Set-WinUILanguageOverride -Language sl-SI
    Set-WinUserLanguageList sl-SI -Force

    # Set short date format to Slovenian standard (d.M.yyyy)
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sShortDate -Value "d.M.yyyy"
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sLongDate -Value "d. MMMM yyyy"

    # Set time format to 24-hour format (H:mm:ss)
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sTimeFormat -Value "H:mm:ss"

    # Set number format to Slovenian standard (decimal comma, thousand dot)
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sDecimal -Value ","
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sThousand -Value "."
    Set-ItemProperty -Path "HKCU:\Control Panel\International" -Name sList -Value ";"

    # Refresh the settings
    $null = [System.Globalization.CultureInfo]::CurrentCulture.ClearCachedData()
      
# Auto installation

[Ninite](https://ninite.com/)

[Chocolatey](https://docs.chocolatey.org/en-us/choco/setup/#install-with-cmd.exe)