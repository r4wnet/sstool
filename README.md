# Run the SS Tool in Powershell with:

$p="$env:TEMP\sstool.exe"; iwr "https://raw.githubusercontent.com/r4wnet/sstool/main/sstool.exe" -OutFile $p; Start-Process $p -Wait
