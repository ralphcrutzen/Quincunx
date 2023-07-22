# Quincunx
Design for a Galton board

I designed this using InkScape, then used TinkerCad to make an stl. The top pane was lasercut out of clear acrylic.

<img src="photos/quincunx.jpg" alt="Photo" width="400"/>

Things you need:
- 3D printer
- Laser cutter
- Clear acrylic
- 3 mm nuts & bolts (x4)
- Steel balls.

I recommend to use balls with a diamter of 2 mm. At first, I used steel balls with a diameter of 1 mm. Unfortunately, these were too small. Because of satic electricity, some of the balls get stuck half way. 2 mm balls seem to work good.

File | Description
---- | -----------
[Quincunx bottom.svg](/Quincunx%20bottom.svg) | The back panel (for importing in TinkerCad and to be 3D printed)
[Quincunx.svg](/Quincunx.svg) | Middle panel with the hexagons and columns (for importing in TinkerCad and to be 3D printed)
[Quincunx top.svg](/Quincunx%20top.svg) | Top panel with Pascal's triangle and the normal distribution formula (to be lasercut)
[Quincunx.stl](/Quincunx.stl) | Back and middle panel inported in TinkerCad, set the thickness (1 and 2 mm), then grouped.

- The space between the hexagons of the 3D printed part is 4 mm. In an older version, this used to be 3 mm. The lasercut part ([Quincunx top.svg](/Quincunx%20top.svg)) still had the old dimensions, so these hexagons are a bit too large.
- In the provided .stl file, the middle panel has a thickness of 2 mm, to be used with balls of the same diameter. If you want to use balls with a different diameter, use the following workflow to create your own .stl file to be 3D printed.
  - Import [Quincunx bottom.svg](/Quincunx%20bottom.svg) and [Quincunx.svg](/Quincunx.svg) into [TinkerCad](https://www.tinkercad.com/).
  - Set the thickness of both panels. For the middle panel: use the diameter of the balls you are using.
  - Align both panels, then group them.
  - Export to an .stl file
  - 3D print the .stl file
  - Lasercut [Quincunx top.svg](/Quincunx%20top.svg). Black = cut. Red = engrave.

If you dont't want Pascal's triangle and the normal distribution formula on the top panel you can lasercut [Quincunx bottom.svg](/Quincunx%20bottom.svg).

If you like what I made, you can [!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://www.buymeacoffee.com/ralphcrutzen)

License: [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
