# Soilcoin-Windows-mining
**Soil Windows Mining Guide**

Download the mining pakage and extract it. Download ethminer and extract the files to soil-mining-windows/ethminer
https://github.com/Genoil/cpp-ethereum/blob/master/releases/ethminer-0.9.41-genoil-1.1.7.zip

If you don't have already a soil address - generate one
gsoil/gsoil-new-account.bat

**Solo mining**
soil-mining-windows/gsoil-solomine.bat
+
For nvidia gpus
ethminer/solo-mining-cuda.bat
For amd gpus
ethminer/solo-mining-ocl.bat

**Pool mining**
ethminer/miners-zone-cuda.bat
ethminer/miners-zone-ocl.bat
ethminer/pool.sexy-cuda.bat
ethminer/pool.sexy-ocl.bat

Choose cuda for nvidia gpus and ocl for amd gpus and the pool of your choice.
Open the bat file with an edior and enter your [color=green]address [/color]and [color=brown]miner name[/color].
http://pool:port/[color=green]0x663682fd2d96064fdb2f152a56bab75d921065c0[/color]/[color=brown]martymcfly201[/color]

Happy mining!

