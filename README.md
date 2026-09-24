## Run the SS Tool in PowerShell with:

```powershell
$P="$env:TEMP\sstool.exe"; iwr "https://raw.githubusercontent.com/r4wnet/sstool/main/sstool.exe" -OutFile $P; Start-Process $P -Wait
```
