# IP_Kit
## Overview
IP_Kit is a custom Nuke Gizmo that provides a selection of commonly used Input Process (IP) presets. This tool is perfect for artists who frequently switch between different IP settings, saving valuable time and ensuring consistency across projects. 
![IP_KitExample.gif](https://github.com/Ssoklv/IP_Kit/blob/main/IP_KitExample.gif)
## Features
- Blur: Apply adjustable blur to your comp for evaluating luminosity/color distribution.
- Saturation: Apply saturation to your comp, with an option to do so through logarithmic space.
- Mirror
- High Pass: Extract a high-detail pass through Frequency Separtion technique. Useful for checking grain & textures.
- LUT: Apply a LUT through [OCIOFileTransform](https://learn.foundry.com/nuke/content/reference_guide/color_nodes/ociofiletransform.html) node
## Installation
1. **Download the Gizmo**: Clone or download the IP_Kit repository from GitHub.
2. **Add to .nuke**: Place the IP_Kit Gizmo file into your C:/user/.nuke directory.
3. **Configure Menu**: Add the IP_Kit to your Nuke menu for easy access. Modify your menu.py file as follows:
```python
import nuke
nuke.pluginAddPath('./path_to_your_gizmo_folder')
```
## Usage
Add IP_Kit, rename it to "VIEWER_INPUT" / change the "input process" in the Viewer's Settings to "IP_Kit"
