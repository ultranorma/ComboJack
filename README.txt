Hackintosh combojack support for alc256/alc255.
Confirmed to work on dell xps 13 9350/9360(alc256) and Xiaomi Air(i5-7200U, alc255)
1. Delete CodecCommander.kext，put ComboJack_Installer/VerbStub.kext in Clover/kexts/Other
2. Run ComboJack_Installer/install.sh in terminal and reboot
3. Done. When you attach a headphone there will be a popup asking about headphone type.

I know CleanMyMac reports this as mining malware, but I don't think CleanMyMac is a serious anti-malware. If you really believe these false alarms then compile by yourself (don't ask how).
