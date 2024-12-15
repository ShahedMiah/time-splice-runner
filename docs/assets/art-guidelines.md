# Art Guidelines for Time Splice Runner

## Overall Style
The game features three distinct visual styles corresponding to each timeline, while maintaining a cohesive overall look that ties everything together.

## Timeline-Specific Art Guidelines

### Past Era (Prehistoric)
- Color Palette:
  - Primary: Earth tones (browns, greens)
  - Secondary: Volcanic reds and greys
  - Accent: Bright nature colors
- Texture Style:
  - Natural, rough textures
  - Organic shapes
  - Weathered surfaces
- Key Elements:
  - Dinosaurs (various species)
  - Ancient plants
  - Natural obstacles (rocks, trees, tar pits)
  - Volcanic elements

### Present Era (Modern)
- Color Palette:
  - Primary: Urban greys and blues
  - Secondary: Street/safety yellows and reds
  - Accent: Neon sign colors
- Texture Style:
  - Modern materials (concrete, metal, glass)
  - Clean geometric shapes
  - Contemporary surfaces
- Key Elements:
  - City buildings
  - Vehicles
  - Construction sites
  - Street furniture

### Future Era (Cyberpunk)
- Color Palette:
  - Primary: Deep blues and purples
  - Secondary: Neon accents (cyan, pink)
  - Accent: Holographic effects
- Texture Style:
  - High-tech materials
  - Sleek, angular shapes
  - Glowing/luminescent surfaces
- Key Elements:
  - Hover vehicles
  - Security drones
  - Laser barriers
  - Holographic billboards

## Character Design

### Base Scientist Character
- Modern lab coat (adapts to each era)
- Time travel device visibly worn
- Clear silhouette for gameplay visibility
- Expressive animations

### Era-Specific Variations
- Past: Rugged/survival gear additions
- Present: Standard scientific equipment
- Future: High-tech augmentations

## UI Elements

### HUD Design
- Minimal, clean design
- Clear hierarchy
- Era-appropriate styling
- High contrast for readability

### Menu Design
- Timeline-themed backgrounds
- Consistent button styles
- Clear navigation elements
- Animated transitions

## Visual Effects

### Timeline Transitions
- Time distortion ripples
- Color palette shifts
- Particle effects
- Environment morphing

### Power-up Effects
- Distinct visual language
- Clear activation states
- Duration indicators
- Area of effect visualization

## Technical Specifications

### Texture Requirements
- Maximum Size: 2048x2048
- Format: PNG/JPEG
- Compression: Optimized for mobile
- Mipmaps: Enabled

### Model Requirements
- Polygon Budget: 
  - Characters: 3000-5000 triangles
  - Obstacles: 1000-2000 triangles
  - Props: 500-1000 triangles
- UV Mapping: Single UV set
- Rigging: Maximum 20 bones per character

### Animation Guidelines
- Frame Rate: 30 FPS
- Key Actions:
  - Jump: 8-10 frames
  - Slide: 10-12 frames
  - Run cycle: 16 frames
- Smooth transitions between states

## Asset Delivery Format

### 2D Assets
- Source Files: PSD/AI format
- Export Format: PNG with transparency
- Resolution: @2x and @3x for iOS
- Clear layer organization

### 3D Assets
- Source Files: FBX/Unity format
- Textures: PSD/PNG format
- Materials: Unity standard shader
- Clear hierarchy structure

## Optimization Guidelines

### Performance Targets
- Draw calls: Maximum 100 per frame
- Texture memory: Maximum 100MB
- Poly count: Maximum 50k on screen
- Particle effects: Maximum 1000 particles

### Memory Management
- Asset bundling strategy
- LOD implementation
- Texture atlasing requirements
- Asset streaming guidelines

## Style References
- Temple Run (core gameplay clarity)
- Subway Surfers (character design)
- Sonic Generations (timeline transitions)
- Spider-Man: Across the Spider-Verse (art style transitions)
