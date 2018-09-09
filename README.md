# Basic ESP8266 WeMos Matrix Shield for Digital Morphing Clock

This shield is used to get simplify ESP8266 connectivity with a [WeMos][22] ESP8266 and nice matric RGB led. This idea came from excellent project called [Morphing Digital Clock][3] done by [HariFun][1] Instructable

See it in action, nice isn't it?

<img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/Morphing-Clock.gif">

This breakout has just few minimal features. **The V1.0 was missing B1 on 6 pin out connector, so you should grab it elsewhare, but it's now fixec on V1.1**

*New in V1.1*

- Power, added big connector 3.5mm spaced to put the supplied power cable
- Changed 3.5mm Phoenix connector by a 5mm one allowing the stronger power cabmle to fit info
- Moved output connector to the right you can use the supplied flat band connector
- Output connector can go straight to output connector of Matrix, allowing to use a 6 PIN ISP Arduino Like ribbon cable.
- Increased PCB traces width for 5V power
- Added some wiring info on bottom silk


*Still in V1.0+*

- DC Barrel power connector 
- Zero Press Fit power connector
- All necessary headers to connect the Matric Shield

WeMos provide 3 D1, [D1 Mini Lite][20], [D1 Mini][21] or [D1 Mini Pro][22].

**Boards are untested yet, order from [PCBs.io][4]**

# Detailed Description

Look at the schematics for more informations.

# Schematic  

<img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/WeMos-Matrix-Shield-sch.png">

# Boards  

<img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/WeMos-Matrix-Shield-top.jpg" alt="Top" width="40%" height="40%">&nbsp;
<img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/WeMos-Matrix-Shield-bot.jpg" alt="Bottom" width="40%" height="40%">

You can order the PCB of this board at [PCBs.io][4]. PCBs.io give me some reward when you order my designed boards from their site. This is pretty good, because I can use these rewards to create and design new boards and order them for free, so if you don't care about PCB manufacturer please use PCBs.io.

# Assembled boards

TBD

# BOM

Nothing fancy, just some headers and 2 differents power conector (choose the one you prefer) :

 - Ebay search for "DC Power Jack Barrel PCB Mount"
 <img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/DC-Power-Barrel.jpg">
 - Phoenix contact PCB terminal block - SPTAF ref 1864286 (V1.0) or 1864435 (V1.1+) can be found anywhere
 <img src="https://github.com/hallard/WeMos-Matrix-Shield/raw/master/pictures/SPTAF-1864286.jpg">

# License

<img alt="Creative Commons Attribution-NonCommercial 4.0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png">   

This work is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/)    

# Misc

See news and other projects on my [blog][2] 

Thanks to [HariFun][1] for this awesome stuff, please review and see how to build on [Instructable][3]
 
[1]: https://www.instructables.com/member/HariFun/
[2]: https://hallard.me
[3]: https://www.instructables.com/id/Morphing-Digital-Clock/
[4]: https://PCBs.io/share/zMPKb

[20]: https://wiki.wemos.cc/products:d1:d1_mini_lite
[21]: https://wiki.wemos.cc/products:d1:d1_mini
[22]: https://wiki.wemos.cc/products:d1:d1_mini_pro