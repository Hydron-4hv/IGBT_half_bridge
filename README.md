# IGBT_half_bridge
PCB for general use of TO-247 IGBTs in half bridge configuration. Variants for parallel IGBTs and horizontal mounting

Design notes:
- Have included a lot of different holes for various mounting requirements, so looks a bit swiss-cheesed
- Should be able to trim off part of the board and still access Vbus+/- and bridge output nodes
- Electrolytic cap footprints should be able to accommodate up to 35mm dia. caps, though with a little bit hanging over the edge of the PCB
- Various Fischer Elektronik SK 481 heatsinks can be used (with clips to hold IGBTs), either 2 separate heatsinks (suggest 37.5mm length) to avoid isolation requirements, or larger 50-84mm with isolation pads behind IGBTs. In all cases use an insulated washer for heatsink mounting screw, and consider adding kapton tape or similar to top layer to add isolation between heatsink and top layer tracks.
- Other heatsinks with IGBTs either vertical or horizontal (under PCB mount, screws accessed via supplied holes) can be used as desired 

Output notes:
- 3 different "PCB Variants" have been defined and output files generated:
  - Single IGBT in each of upper and lower half bridge position, SMD gate resistor, 2x 37.5mm SK481 heatsinks, no electrolytic caps
  - Dual IGBTs in each of upper and lower half bridge position, THD gate resistor, 2x 37.5mm SK481 heatsinks, electrolytic caps fitted
  - Dual IGBTs in each of upper and lower half bridge position (horizontally mounted), THD gate resistor, no heatsink, electrolytic caps fitted
- The "schematic" PDFs include a 3D model for viewing in compatible software (Adobe reader works, Foxit does not, unsure about others)
