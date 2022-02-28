# Minidox Case Remix

# Development

I use Shapr3d for all my CAD-ish work and the source for the DXFs lives there. `dxf/Core.dxf` is an export of that file. 

# Use

`dxf/All Parts.dxf` contains all the indivdual parts. When I cut my cases, I drag the `All Parts.dxf` file into the Glowforge site and pick out the pieces I need. 

The thickness of the parts is really dealer's choice. I print the top and bottom plates in 3mm, with two 6mm spacers. If using the key switch plate, that pretty much has to be in 1.5mm acrylic. (My Minidox builds use Elite-C controllers and low-profile headers. If you used Pro Micro and standard sized headers, you will probably need a least an additional 6mm spacer.)

This is designed for round standoffs. Hex standoffs will not fit.

## Switch Plate

For the switch plate, there are two choices, size wise.

If you're soldering on your switches, I recommend using 3mm whatever. Wood works really well here but it doesn't matter. The keys are very stable in this configuration.

If you're hotswapping, you probably want 1.5mm acrylic (aka 1/16"). Switches are built for 1.6mm FR4, typically, and they click right in and are stable. 1.5mm acrylic is fragile though and care must be taken when swapping switches to not put too much strain on the plate. (Maybe cut a couple extras just in case)

You can also use 3mm whatever and it will work just fine. Problem is that the keys have nothing to click into so you will always pull the switch out if you try and change the key cap. If that's cool with you, 3mm is very stable and doesn't have any concerns about breaking as you swap things around.

# Original

Remixed from https://github.com/dotdash32/Cases

## What Did I Change?

Two major high notes:

* I removed the tenting options as that's not my jam
  
* This remix does not require tapping the top layer. It's designed for round standoffs with screws on the top and bottom. This required moving the screw holes around to make things less fragile with the larger bore holes.

Otherwise, I changed a whole lot of little things. Simplified a lot of the design to ensure that walls are the same size, remove double cuts caused by extra lines. Widened the USB port a bit. The switch holes are 14mm square now, with no little notches at the edges. 

This won't become a changelog but these sorts of cleanups are why the remix got started.

# Copyright / License

Copyright dotdash32 ( https://github.com/dotdash32 ): 2017-2020

Copyright sungo: 2022 - present

Licensed under GPL v1 (Original license is unversioned GPL which let me pick a version for this repo)
See included LICENSE.md file for details