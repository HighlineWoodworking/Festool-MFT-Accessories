# MFT Pucks

Pucks to support material on a [Festool MFT/3 Table](https://www.festoolusa.com/accessories/sawing/underframes-and-work-benches/work-benches/495315---mft3).

<img src="images/pucks.png" alt="MFT pucks." width="50%" />

## Tools and Materials

* CNC machine
* 3/4 inch MDF
* 1/4 inch end-mill, only required bit, good examples:
  * [Cadence Manufacturing "The Jenny"](https://www.cadencemfgdesign.com/product-page/the-jenny-bit-8675309)
  * [Woodpeckers US2100U](https://www.woodpeck.com/ultra-shear-2-flute-quarter-inch-solid-carbide-spiral-bits.html)
* 90 deg v-bit for edge chamfers, 1/4 inch cutting diameter to fit in channels made by outline:
  * [SpeTool W06007](https://spetools.com/products/spetool-w06007-v-groove-chamfer-router-bit-1-4-dia-1-4-shank-90-deg)
  
## Machining

Two-sided, side one has a hole and side two has a pin.  Pucks fit in the 20mm diameter MFT dog holes, and also to stack on one another.

Example machining procedure using alignment holes in the spoil board that are parallel to the x or y axis, and a straight edge on the material that is also dead perpendicular to the top and bottom sides.  Possible because the drawing is symmetrical in x and y.  Using an x-axis reference:

* align bottom edge of material to pins along the x-axis
* zero to lower-left corner with drawing origin also lower-left (x and y increase to right and up respectively)
* cut holes and chamfers
* flip material along x-axis, former lower-left top is now on the bottom of the upper-left corner
* align top edge of material to pins along the x-axis
* zero to upper left corner
* change origin in drawing to upper-left and generate g-code for pins, outline cutout and chamfers
* coordinates in g-code increase right and down (negative y coordinates)
* machine pins, outline cutout and chamfers

## Files

* 60mm_pucks_two.art = [Carveco Maker](https://carveco.com/carveco-software-range/carveco-maker/) source file

## Dimensions

TODO: Add images.






