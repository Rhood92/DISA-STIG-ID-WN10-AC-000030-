# STIG ID: WN10-AC-000030 - The minimum password age must be configured to at least 1 day.

## Synopsis
This PowerShell script ensures that the The minimum password age must be configured to at least 1 day.

## Notes
- **Author**: Richard Hood
- **LinkedIn**: [Richard Hood Jr.](https://www.linkedin.com/in/richard-hood-jr/)
- **GitHub**: [Rhood92](https://github.com/Rhood92)
- **Date Created**: 2025-04-1
- **Last Modified**: 2025-04-1
- **Version**: 1.0
- **CVEs**: N/A
- **Plugin IDs**: N/A
- **STIG-ID**: WN10-AC-000030

## Tested On
- **Date(s) Tested**: 
- **Tested By**: 
- **Systems Tested**: 
- **PowerShell Ver.**: 

## Usage
Put any usage instructions here.

Example syntax:
```powershell
 
try {
    # Run the command to set minimum password age to 1 day
    net accounts /minpwage:1
    Write-Host "Minimum Password Age has been successfully set to 1 day." -ForegroundColor Green
}
catch {
    Write-Error "Failed to apply minimum password age policy: $_"
} 
