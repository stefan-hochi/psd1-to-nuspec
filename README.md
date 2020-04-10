# fork from  tyconsulting/psd1-to-nuspec.ps1
Generate NuGet specification .nuspec file based on PowerShell module manifest .psd1

Import-Module .\psd1-to-nuspec.psm1
New-NuSpecFile -ManifestPath Test.psd1