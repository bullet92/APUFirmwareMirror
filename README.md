# APUFirmware Mirror
PC Engines APU firmware mirror of the official [download site](https://pcengines.github.io) for archive purpose.

Updated until firmware v4.19.0.1 2023-02-02

 * [How to verify the firmware files](https://asciinema.org/a/227035)
 * The rom files that are compressed on the original site with gz have checksum over the archive instead of the rom file.
   These checksums where automatically corrected when downloading with the help of [`APUFirmware`](https://github.com/Monkeycat-nl/APUFirmware) `apufirmware bulk` downloader.
 * These files seem to have an invalid checksum on the original site: apu2_v4.0.23.rom apu3_v4.0.23.rom apu4_v4.0.23.rom apu5_v4.0.23.rom apu1_v4.9.0.1.rom apu2_v4.9.0.1.rom apu3_v4.9.0.1.rom apu4_v4.9.0.1.rom apu5_v4.9.0.1.rom
 * The file apu3_v4.0.11.rom.tar.gz contains apu2_v4.0.11.rom and is removed

## See also

* [`APUFirmware`](https://github.com/Monkeycat-nl/APUFirmware) PC Engines APU firmware auto downloader and updater.
* [`APUWifi`](https://github.com/Monkeycat-nl/APUWifi) Automatic debian atheros wifi driver patch.
