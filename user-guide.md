# User Guide

## Overview

The FiveM Tool by Dogma Studio provides powerful features for optimizing your FiveM content creation workflow in Blender.

## Interface

### Main Panel Location

The tool is located in the 3D View sidebar:
1. Press `N` to open the sidebar (if not visible)
2. Look for the **"FiveM Tool by Dogma Studio"** tab
3. Click to expand the panel

### Panel Sections

The tool is organized into collapsible sections:

- **License**: License status and management
- **Vertex Color**: Tools for vertex color attributes
- **Bone Tools**: Bone renaming and conversion
- **Utility**: General utility tools

## License Management

### Checking License Status

The license section shows:
- Current license status (Active/Expired/None)
- Remaining days and hours
- License expiry information

### Activating License

1. Click **"Activate License"**
2. Enter your Tebex Transaction ID (format: tbx-xxxxx)
3. Click **"Verify License"**

### Testing Connection

If you have connection issues:
1. Click **"Test Server Connection"**
2. Check the result message

## Vertex Color Tools

### Smart Vertex Color

Creates optimized vertex color attributes for FiveM:

#### Preset Options
- **Rock**: For rocky materials and stones
- **Dirt**: For terrain and earthy materials  
- **Mountain**: For mountainous surfaces
- **Wall**: For walls and architectural surfaces

#### Usage
1. Select your object
2. Choose the appropriate preset
3. Click the preset button

### Specialized Attributes

For specific FiveM use cases:

- **External**: red vertex color for exterior mesh
- **Internal**: default green vertex color for interior mesh
- **Clothes**: Fabric and clothing materials
- **Emissive**: Luminous materials and neon effects

### Multiple Object Management

- **Create for Multiple**: Apply attributes to multiple selected objects
- **Delete for Multiple**: Remove attributes from multiple objects

## Bone Tools

### Bone Renaming

Converts Mixamo bone names to GTA format:

#### Configuration
1. Set **Mixamo Armature** name (default: "Armature")
2. Set **GTA Armature** name (default: "head_000_r")
3. Click **"Rename Bones"**

#### Usage
1. Select your character model
2. Configure armature names
3. Click **"Rename Bones"**

## Utility Tools

### UV Map Management

- **Rename UVMap Multiple**: Rename UV maps across multiple objects

### Object Management

- **Rename Objects**: Rename selected objects automatically

## Workflow Examples

### Example 1: Vehicle Setup

1. Import your vehicle model
2. Select exterior parts
3. Use **External** vertex color
4. Apply **Emissive** to lights/neon

### Example 2: Character Setup

1. Import character with Mixamo rig
2. Configure bone names
3. Use **"Rename Bones"**
4. Apply **Clothes** vertex color to clothing

### Example 3: Environment Setup

1. Import terrain/objects
2. Select appropriate preset (Rock, Dirt, Mountain, Wall)
3. Apply vertex colors
4. Use utility tools for organization

## Tips and Best Practices

### Before Starting
- Always backup your files
- Ensure you have a valid license
- Test on a copy of your model first

### Performance
- Apply vertex colors before final export
- Use multiple objects for complex models
- Organize UV maps properly

### Troubleshooting
- Check license status if features don't work
- Verify object selection before applying tools
- Test connection if license issues occur

## Next Steps

- Check [Troubleshooting](troubleshooting.md) for common issues
- [Report Issues](../../issues) if you encounter problems
- Contact support for advanced help 