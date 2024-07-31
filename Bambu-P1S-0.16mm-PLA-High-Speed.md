# Printer Profile: Bambu P1S 0.16mm for High Speed PLA

## Quality
### Layer Height
- Layer Height: 0.16 mm
- Initial Layer Height: 0.2 mm

### Line Width
- Default: 0.42 mm
- Initial Layer: 0.5 mm
- Outer Wall: 0.42 mm
- Inner Wall: 0.45 mm
- Top Surface: 0.42 mm
- Sparse Infill: 0.45 mm
- Internal Solid Infill: 0.42 mm
- Support: 0.42 mm

### Seam
- Seam position: Random
- Scarf joint seam: None

### Precision
- Slice gap closing radius: 0.049 mm
- Resolution: 0.012 mm
- Arc fitting: YES
- X-Y hole comparison: 0 mm
- X-Y contour comparison: 0 mm
- Elephant foot compensation: 0.15 mm
- Precise Z height: NO

### Ironing - NONE

### Wall generator: Classic

### Advanced
- Order of walls: inner/outer
- Print infill first: NO
- Bridge flow: 1
- Thick bridges: NO
- Only one wall on top surfaces: Top surfaces
- Only one wall on first layer: NO

## Strength
### Walls
- Wall loops: 6
- Detect thin wall: NO

### Top/bottom shells
- Top surface pattern: Monotonic line
- Top shell layers: 6
- Top shell thickness: 1 mm
- Bottom surface pattern: Monotonic
- Bottom shell layers: 4
- Bottom shell thickness: 0 mm
- Internal solid infill pattern: rectilinear

### Sparse infill
- Sparse infill density: 5%
- Sparse infill pattern: Gyroid
- Length of sparse infill anchor: 400%
- Maximum length of sparse infill anchor: 20

### Advanced
- Infill/wall overlap: 15%
- Infill direction: 45
- Bridge direction: 0
- Minimum sparse infill threshold: 15
- Infill combination: NO
- Detect narrow internal solid infill: YES
- Ensure vertical shell thickness: YES

## Speed
### Initial Layer Speed
- Initial layer: 50
- Initial layer infill: 105

### Other layers speed
- Outer wall: 200
- Inner wall: 300
- Small perimeters: 50%
- Small perimeter threshold: 0 mm
- Sparse infill: 330
- Internal solid infill: 300
- Top surface: 200
- Slow down for overhangs: YES
- Overhang speed:
  - 60 (10%,25%)
  - 30 (25%,50%)
  - 10 (50%,75%)
  - 10 (75%,100%)
- Bridge: 50
- Gap infill: 300
- Support: 150
- Support interface: 80

### Travel speed: 500

### Acceleration
- Normal printing: 10000
- Initial layer: 500
- Outer wall: 5000
- Inner wall: 0
- Top surface: 2000
- Sparse Infill: 100%

## Support
### Support
- Enable support: YES
- Type: Tree (Auto)
- Style: Tree Slim
- Threshold angle: 20
- On build plate only: NO
- Support critical regions only: YES
- Remove small overhangs: YES

### Raft
- Raft layers: 0

### Filament for Supports
- Support/raft base: Default
- Support/raft interface: Default

### Advanced
- Tree support branch distance: 5 mm
- Tree support branch diameter: 2 mm
- Tree support branch angle: 45
- Support wall loops: 0
- Tree support brim width: 0 mm
- Top Z distance: 0.25 mm
- Bottom Z distance: 0.2 mm
- Base pattern: Hollow
- Base pattern spacing: 2.5 mm
- Pattern angle: 0
- Top interface layers: 3
- Bottom interface layers: 2
- Interface pattern: default
- Top interface spacing: 0.7 mm
- Normal support expansion: 0 mm
- Support/object xy distance: 0.35 mm
- Support/object first layer gap: 0.2 mm
- Max bridge length: 10 mm
- Independent support layer height: YES

## Others
### Bed adhesion
- Skirt loops: 0
- Skirt height: 1
- Brim type: Auto
- Brim width: 5 mm
- Brim-object gap: 0.1 mm

### Prime tower
- Enable: YES
- Width: 35  mm
- Prime volume: 45
- Brim width: 3 mm

### Flush options
- Flush into objects' infill: NO
- Flush into objects' support: YES

### Special mode
- Slicing mode: Regular
- Print sequence: By layer
- Spiral Vase: NO
- Timelapse: Traditional
- Fuzzy skin: None

### Advanced
- Interlocking depth of a segmented region: 0 mm

### G-code output
- Reduce infill retraction: YES

### Post-processing scripts: NONE
