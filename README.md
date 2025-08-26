# Klipper Note

If you're running Klipper, it's recommended to add the following configuration to your `printer.cfg` file.

```gcode
# Enable object exclusion
[exclude_object]

# Enable arcs support
[gcode_arcs]
resolution: 0.1
```

## Some background

AtenSlic3r is forked from Orcaslicer.

OrcaSlicer was originally forked from Bambu Studio, it was previously known as BambuStudio-SoftFever.
[Bambu Studio](https://github.com/bambulab/BambuStudio) is forked from [PrusaSlicer](https://github.com/prusa3d/PrusaSlicer) by Prusa Research, which is from [Slic3r](https://github.com/Slic3r/Slic3r) by Alessandro Ranellucci and the RepRap community.
OrcaSlicer incorporates a lot of features from [SuperSlicer](https://github.com/supermerill/SuperSlicer) by @supermerill
OrcaSlicer's logo is designed by community member Justin Levine (@freejstnalxndr).

# License
- **AtenSlic3r** is licensed under the GNU Affero General Public License, version3. AtenSlic3r is based on OrcaSlicer by SoftFever.
- **OrcaSlicer** is licensed under the GNU Affero General Public License, version 3. OrcaSlicer is based on Bambu Studio by BambuLab.
- **Bambu Studio** is licensed under the GNU Affero General Public License, version 3. Bambu Studio is based on PrusaSlicer by PrusaResearch.
- **PrusaSlicer** is licensed under the GNU Affero General Public License, version 3. PrusaSlicer is owned by Prusa Research. PrusaSlicer is originally based on Slic3r by Alessandro Ranellucci.
- **Slic3r** is licensed under the GNU Affero General Public License, version 3. Slic3r was created by Alessandro Ranellucci with the help of many other contributors.
- The **GNU Affero General Public License**, version 3 ensures that if you use any part of this software in any way (even behind a web server), your software must be released under the same license.
- OrcaSlicer includes a **pressure advance calibration pattern test** adapted from Andrew Ellis' generator, which is licensed under GNU General Public License, version 3. Ellis' generator is itself adapted from a generator developed by Sineos for Marlin, which is licensed under GNU General Public License, version 3.
- The **Bambu networking plugin** is based on non-free libraries from BambuLab. It is optional to the OrcaSlicer and provides extended functionalities for Bambulab printer users.
