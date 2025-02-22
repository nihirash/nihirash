### My name is Aleksandr Sharikhin

I'm doing software engineering for living(currently using Rust mostly) but this GitHub profile contains mostly my hobby projects for retrocomputers.

Here will be some guide for some my repos. 

#### Development

- [BSimple](https://github.com/nihirash/bsimple-ez80-compiler) compiler. B-like programming language and compiler that fits into 24K binary on eZ80. Targetting to eZ80(mostly for Agon Light/Console8 but can be used for any eZ80 CPU in ADL mode). Working on desktop computers(mac, linux; windows should work too but untested cause I have no access to Windows) as well as on Agon Light2 directly. Compiles to assembly and can be mixed with almost any assembly code

#### CP/M related stuff

 - [ZINC is Not CP/M](https://github.com/nihirash/zinc) - CP/M compat layer for Agon's MOS
 - CP/M 2.2 port for [Agon Light](https://www.thebyteattic.com/p/agon.html) computer is located [here](https://github.com/nihirash/Agon-CPM2.2)
 - For ZXUno and Spectrum +3 with divMMC and +3e firmware is [here](https://github.com/nihirash/cpm-uno). Initially, it was only for ZXUno but now it have possiblity to be built with classic ZX Spectrum screen driver
 - For [Karabas Pro](http://github.com/andykarpov/karabas-pro) ZX Spectrum compatible computer located is [here](https://github.com/nihirash/karabas-pro-cpm). Most funny fact about it - it have CI on Github Actions for creating public releases.
  - Very quick and dirty made [file manager for CP/M](https://github.com/nihirash/cpm-fm). It should be compiled with BDS C and can work on almost any CP/M machine(uses only 8080 mnemonics)

#### Network stuff for vintage computers

For long time I was mostly known as developer of network tools for ZX Spectrum compatible computers. 

And main entry point for this code was my [zx-net-tools](https://github.com/nihirash/zx-net-tools) repository. Work on code located in this repository mostly freezed but I did some replacements:
 
 - New [WiFi networks manager](https://github.com/nihirash/netman-zx) that replaces old netman
 - [Moon Rabbit](https://github.com/nihirash/moon-rabbit-zx) Gopher browser for ZX Spectrum compatbile computers
 - And version of [Moon Rabbit for MSX2](https://github.com/nihirash/moon-rabbit) compatible computers(working using UNAPI TCP/IP)
 - [Internet NEXTplorer](https://github.com/nihirash/internet-nextplorer) for ZX Spectrum Next
 
I did tool for remote loading code to ZX Spectrum compatible computers - [Lain](https://github.com/nihirash/Lain). You can use it for real hardware checks when you making cross-platform development. 

For Agon Light I did [Snail Gopher browser](https://github.com/nihirash/agon-snail). It's still experimental software but you can use it, explore internals and develop some new stuff using it

Also I did some experiments for creating new firmware for ESP8266 for using it as offload tcp/ip stack. [This version](https://github.com/nihirash/esp-binary-firmware) was used in MSX's BadCat Wifi cart.

#### Kinda Games 
 
 - [Rokky](https://github.com/nihirash/Agon-rokky) simple Rock's'Diamonds game for Agon Light. I'm using it like test site for Agon Development. 
 - Daddy of prev. game - [Rocks And Ghosts](https://github.com/nihirash/rocksnghosts) for Jupiter Ace(with 16k ram pack). Once I've let that every platform should have Boulder Dash like game. So I did it for Jupiter Ace
 - [Lost Donation Box Incident](https://github.com/nihirash/touhou-zero) pseudo-Bullet Hell game for ZX-Evolution with TSConf firmware. Game can be downloaded [here](https://nihirash.itch.io/lost-donation-box-incident)(also here's video with game play). There's version with emulator for Windows. Emulator works fine under Wine.
- [Sinty Snoki](https://github.com/nihirash/Ssssnaaakkeee) is proof-of-concept game. It's a snake game that uses MIDI out of ZX Spectrum 128 for playing background music. For screenshots and downloadable version check [itch.io page of game](https://nihirash.itch.io/zx-spectrum-sinty-snoke)

#### Other still usable retrocomputer's stuff

 - [W65C02S Basic](http://github.com/nihirash/cerberus-w65c02s-basic) for Cerberus 2100 and Cerberus 2080 computers. It's custom port of Microsoft's Basic for 6502 processors. My first ever experience with 6502 assembly.
 - [Agon Music Track Compiler](https://github.com/nihirash/agon-music-track-compiler) - very strange way for creating music for Agon Light. You should write text file that will contains notes and compile it into song, using simple compiler. 


#### Supporting me

You can support me with two ways now:
 
 - Using [Ko-Fi service](http://ko-fi.com/nihirash) - easy for you and me way(also there's some dev.log)

 - Using Etherium crypto: `0x13105803B79CF6541867d137fDbdf942d0bDA863`