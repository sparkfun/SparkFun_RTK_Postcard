3d_model directory
====================
This folder should contain the 3D model of the product

## File Converter - `*.wrl` to `*.glb` *(old method)*
https://imagetostl.com/convert/file/wrl/to/glb#convert

## Model Editor
https://modelviewer.dev/editor/

## File Optimizer
https://www.loci-labs.com/optimizer

## Solder Mask - Color Correction
Open `*.glb` file and locate the `baseColorFactor` parameter with the following values:
```
          0.7027450799942017,
          0.1537254899740219,
          0.0909803956747055,
          0.8313725590705872
```
Replace those values with the following values: `[,,,1]`
```
          0.7418950796127319,
          0.0302486829459667,
          0.0122311776503920,
          1
```
