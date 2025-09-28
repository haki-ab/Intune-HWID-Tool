$OutputFile = "$PSScriptRoot\AutopilotHWID.csv"
try {
    Set-ExecutionPolicy -ExecutionPolicy Bypass -Scope Process -Force
    Install-Script -Name Get-WindowsAutoPilotInfo -Force -ErrorAction Stop | Out-Null
} catch {}
try {
    Get-WindowsAutoPilotInfo -OutputFile $OutputFile
} catch {
    Write-Host "Unable to retrieve hardware hash. Run as administrator and try again."
}
Read-Host "Press Enter to continue..."
