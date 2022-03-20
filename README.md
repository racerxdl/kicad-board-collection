# Kicad Board Collection

Kicad Board Collection for use in 3D Projects

Sometimes I re-create the PCBs that I buy from Aliexpress and other sellers in Kicad so I can use the Freecad KicadStepUp plugin to generate a STEP file so I can use for drawing my 3D Printed models. Since
I thought it might be usefull for some other people, I decided to just collect them inside a github repository.

## Current Collection

* [AS5600 12-bit Absolute Encoder](AS5600/README.md)
* [CJMCU MPU-925x IMU](CJMCU-925x/README.md)
* [MPU6050 IMU](MPU6050/README.md)

## Warnings and Limitations

These are done to have an _almost_ perfect match with the boards I got. But the goal is to have a close enough board so I can use in my 3D Assemblies inside Freecad. Feel free to make a pull request to improve the accuracy with the real board.

You're free to use to anything you want (even producing those boards here and selling it) just keep in mind that:

* I haven't tested any of those designs
* They're made for generating STEP files and not GERBER files
* You will not blame me if something doesn't work as expected


## Contributing

Feel free to fork and add boards to this project and then make a pull request. I just expect that:

1. Board is made in Kicad
2. It has the PCB traces (basically it should represent a working board)
3. Should have a README.md inside the board folder with a picture of the 3D Model
4. The board size, holes and component positions should match the real board. The PCB traces doesnt need to match (you can route by yourself differently than the real board since it does not affect the 3D Model)
5. Preferably with the generated STEP file using Freecad
6. If you did the kicad drawing and the STEP file, an affiliate link for where to buy the board is allowed in the README as a reference where to buy.