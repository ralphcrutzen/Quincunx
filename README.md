# Quincunx
Design for a Galton board

I designed this using InkScape, then used TinkerCad to make an stl. The top pane was lasercut out of clear acrylic.

![Photo](photos/quincunx.jpg)

Things you need:
- 3D printer
- Laser cutter
- Clear acrylic
- 3 mm nuts & bolts (x4)
- Steel balls with (probably) a diameter of 2 mm.

I used steel balls with a diameter of 1 mm. Unfortunately, these were too small. Because of satic electricity, some of the balls get stuck half way. So I advice to use larger balls. Currently, I am awaiting an order of 2 mm balls.

File | Description
---- | -----------
[Quincunx bottom.svg](/Quincunx%20bottom.svg) | The back panel
[Quincunx.svg](/Quincunx.svg) | Middle panel with the hexagons and columns
[Quincunx top.svg](/Quincunx%20top.svg) | Top panel with Pascal's triangle and the normal distribution formula
[Quincunx.stl](/Quincunx.stl) | Top and middle panel grouped.

In the provided .stl file, the middle panel has a thickness of 1 mm, to be used with balls of the same diameter. If you want to use balls with a larger diameter (which I recommend), use the following workflow to create your own .stl file to be 3D printed.
- Import [Quincunx bottom.svg](/Quincunx%20bottom.svg) and [Quincunx.svg](/Quincunx.svg) into [TinkerCad](https://www.tinkercad.com/).
- Set the thickness of both panels. For the middle panel: use the diameter of the balls you are using.
- Align both panels, then group them.
- Export to an .stl file
- 3D print the .stl file
- Lasercut [Quincunx top.svg](/Quincunx%20top.svg). Black = cut. Red = engrave.

If you dont't want Pascal's triangle and the normal distribution formula on the top panel you can lasercut [Quincunx bottom.svg](/Quincunx%20bottom.svg).

If you like what I made, you can [!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://www.buymeacoffee.com/ralphcrutzen)

License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
