# Amateur Radio Communication Over Light

This repository has information about my optical communications projects.

The primary receiver I've been using is based on a PD49pi sensor, an  Opa350
Transimpedance amplifier, and a TDA2050 audio amplifier. 

## Opa350
I bought a board with an Opa350 on ebay, and reverse engineered it
to make the [original schmatic](Opa350/schematic.pdf).
I've made modifications to the board, as suggested by Fred K1FMS, and added
the optical sensor [sensor schematic](OpticalRXpd49pi/schematic.pdf)

## TDA2050

The TDA2050 is an audio amplifier.  I got an amplifier board that uses this
part on Amazon.  After modifications for increased gain, also suggested by
K1FMS, I have this 
[TDA2050 Audio Amplifier](<TDA2050/Amazon TDA2050.png>)
Tom, W1EX, has made 
[further modifications](<TDA2050/TDA2050 Modified.png>)
which I haven't applied to my board yet.


## References

A similar system built by
[Rus, K2UA](https://github.com/rusk2ua/optical-receive-chain)

[TDA2050 module - Amazon](<https://www.amazon.com/dp/B0CDWTL57H?ref=ppx_yo2ov_dt_b_fed_asin_title>)

[PD49pi - ebay](https://www.ebay.com/itm/274341608439)
[data sheet](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/2997/PD49PI%2C%20PD481PI.pdf)

[Opa350 board - ebay](https://www.ebay.com/itm/387565439452)
[data sheet](https://www.ti.com/product/OPA350?keyMatch=OPA350&tisearch=universal_search&usecase=GPN-ALT)

[940nm IR Filter - ebay](https://www.ebay.com/itm/275733102696?var=577212356057)
[search](https://www.ebay.com/sch/i.html?_nkw=940nm+IR+Infrared+Narrow+Bandpass+Filter&_sacat=0&_from=R40&_trksid=p2332490.m570.l1313)

[TX flood light - Amazon](<https://www.amazon.com/dp/B0DNDVMY13?ref=ppx_yo2ov_dt_b_fed_asin_title>)


