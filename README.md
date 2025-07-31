# ComfyUI Prompt Selector

A structured prompt generator for video generation based on the Wan2.2 video generation prompt guide.

## Features

- Multiple scene type selections
- Dynamic control options including motion scenes and character emotions
- Cinematic aesthetic controls (lighting, camera, lens, etc.)
- Various visual styles and special effects
- Automatic structured prompt generation

## Usage

1. Add the "Prompt Selector" node in ComfyUI
2. Select various parameter options as needed
3. The node will automatically generate corresponding prompt text

## Parameters

- **Scene Type**: Natural scenes, urban scenes, fictional scenes
- **Motion Scene**: Various motion action options
- **Character Emotion**: Emotional expression options
- **Camera Movement**: Camera motion styles
- **Light Source/Type**: Cinematic lighting controls
- **Shot Type**: Different shot compositions
- **Focal Length**: Lens focal length selection
- **Color Tone**: Color style control
- **Visual Style**: Artistic style selection
- **Special Effects**: Special photography effects

All parameters support the "——" empty option. Only parameters with specific selections will be included in the final prompt.

## Installation

1. Clone or download this repository to your ComfyUI custom_nodes directory
2. Restart ComfyUI
3. The "Prompt Selector" node will be available in the "prompt/generator" category

## License

This project is open source and available under standard licensing terms.