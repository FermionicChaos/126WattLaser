# High Power 445nm Laser Rifle

This project is my private weekend project which aims to create a high power portable laser rifle.
I'm not the first dipshit to come up with the idea of a Laser Rifle, Styro Pyro has been doing this
much longer than I have, but I figured I would give a shot at doing it better. :3

The goals of this project are to implement an auto focusing system using LIDAR Range Finding.

![Alt Text](https://github.com/FermionicChaos/126WattLaserRifle/blob/master/images/Screenshot_2024-05-29_173527.png)

That's correct, the original idea was for it to be a wrist gauntlet, but considering that I want to add an auto focusing
lens with LIDAR range finding, it was more appropriate to make this into a rifle instead. This project would be way to bulky
for a wrist laser.

![Alt Text](https://github.com/FermionicChaos/126WattLaserRifle/blob/master/images/IMG_20240531_123011_627.jpg)


# Device Operation

As of right now, the 126 Watt Laser Rifle is successfully operating at full power, which means that
the device is outputting a fair amount of heat. The system draws a total of about 300 Watts of power, and it
is being powered by a 144Wh 40V Ryobi battery. At first the battery seemed like over kill for the project when 
I was trying to build a custom 18650 battery array, but it turned out to be perfect for it. These 40V Ryobi batteries
are 18650 arrays to begin with

![Alt Text](https://github.com/FermionicChaos/126WattLaserRifle/blob/master/images/IMG_20240601_151150_968.jpg)
![Alt Text](https://github.com/FermionicChaos/126WattLaserRifle/blob/master/images/IMG_20240601_150853_114.jpg)

The device is easily able to cut through cardboard, wood, and even metal when focused into a central point.

![Alt Text](https://github.com/FermionicChaos/126WattLaserRifle/blob/master/images/IMG_20240601_150749_808.jpg)


# Device Parts

The three most expensive parts for this project currently are the Ryobi battery, which is around $150 currently.
The NUBM37 Laser Diode Array, which was purchased off of EBay for $250 used. Lastly, the LIDAR auto focusing system 
which has yet to be implemented, which is $220 on Amazon.

The [NUBM37-125W Laser Diode Array](https://www.ebay.com/itm/313906557893?itmmeta=01HZAQKGK5XB1ZK7XANT0GYJ5P&hash=item491649f3c5:g:9tIAAOSweqplgbHu&itmprp=enc%3AAQAJAAAAwM7NU6Jin9ycd%2F6uL1RTjB0hEzZlC4t63KgvhyaAii%2FTHIM1JRSIYwNxzprOl%2FocTJ%2BZYT1zVmMFw92pioZEAxJdKykexYyinboVfrtF5OGXamT3mc%2FzPvNw8xumHy2TWj8k%2BD7ibYk4hXeAm5CPPipLS9yEhunuwYBYXglsvjnfL3axr58T0ijNTrJp2eSt8F0N2ivkec6eJWTO2r9MOfsaiplf%2BpgxwMDrNNHlt7dEbUKcCAIjmqD9BxtErmd9pA%3D%3D%7Ctkp%3ABk9SR9SJztf6Yw) of course the central piece to this 

The[Thermalright Assassin X120 Refined SE CPU Air Cooler](https://www.amazon.com/dp/B09LHBFPJ6?psc=1&ref=ppx_yo2ov_dt_b_product_details) is used for cooling
the laser diode array as it generates a tremendous amount of heat, and it must be dissipated or the heat will damage the diode array. At full power, this 
cooler does get quite warm, but it does its job keeping the laser cool, especially at full power.

Two [Aideepen 1200W 20A DC Boost Converters](https://www.amazon.com/dp/B01MSYVMAL?psc=1&ref=ppx_yo2ov_dt_b_product_details) are used to boost the battery voltage up to 
power both arrays in parallel. These boost converters are quite cheap, but they do the job quite well.

The [Ryobi 40V 144Wh Lithium-Ion Battery OP4040 ](https://www.amazon.com/Ryobi-40V-Lithium-Ion-Battery-OP4040/dp/B07QYH36TC/ref=sr_1_7_mod_primary_new?crid=KWWWOS7T3T20&dib=eyJ2IjoiMSJ9.icpE7Kfs1c6Q8fHu0Ly0VF_T8DaL4xGqs3ct3EVcHVoiX5cnV-f5XqDk9xUt5PsqINLoLb8t3_fC8c3r91KvAtsDjrjE-FFLhlm6oo9cHb3xUyu9nMXdI-dg1-5io5b-R6VDA6bW5KWxspqEQ1cOkQpASOkOOCWYraw4NorEtfGNRFNnyIUkvBN3qfYs4_bAVaoJNdu65vxZ4AM4A-n_bC2eecEVpKYQWCXjjyFxGg6Apwfx3BYHePHBjOSLe8kzeBJScatTxXX0WJ5Jm3_fPcGIrrmKVIYBubfoRBIIQKw.nV42e-cAk3YFAAU-PTJZatXyEiPZGQUOqK5jSdAS0Io&dib_tag=se&keywords=ryobi+40v+battery&qid=1717273831&sbo=RZvfv%2F%2FHxDF%2BO5021pAnSA%3D%3D&sprefix=ryobi+40v+4ah+batterybatter%2Caps%2C213&sr=8-7) is used in this project
to power the laser device. Since the laser diode array easily uses 300 Watts of power, this battery will last a runtime of just shy of half an hour. I do no reccomend running the laser that long continously to avoid heat damage and reducing
the lifetime of the laser. 

# Cost of Production

The total cost of production is as follows for the device.

| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 |
| Row 2 Col 1 | Row 2 Col 2 | Row 2 Col 3 |
| Row 3 Col 1 | Row 3 Col 2 | Row 3 Col 3 |
