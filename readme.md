**PNG Tweening Tool for Animators**

A powerful browser-based tool for creating smooth animations by generating in-between frames from two PNG images. This tool helps animators easily create fluid motion between keyframes without the need for specialized software.

✨ **Features**
- Easy-to-use interface for uploading starting and ending PNG frames
- Generate up to 100 in-between frames with a single click
- Seven different tweening methods to suit various animation needs
- Real-time animation preview with playback controls
- Customizable animation parameters including speed and easing functions
- Advanced visualization options for color transformations
- One-click download of all generated frames
- No installation required - works entirely in your browser

🚀 **Getting Started**
- Online Version
- The easiest way to use this tool is through the online version at: https://pngtweening.example.com
- Local Installation

**To run this tool locally:**
- Clone this repository:
- Copygit clone https://github.com/harp37/PNG-Tweening-Tool-For-Animators.git
- Navigate to the project folder:
- Copycd PNG-Tweening-Tool-For-Animators
- Open PNG-Tweening-Tool-For-Animators.html in your web browser.

No additional dependencies or build steps are required! The tool runs entirely in your browser using HTML, CSS, and JavaScript.

📖 **How to Use**
Basic Workflow
- Upload your PNG images:
- Click "Upload Starting PNG" to select your first frame
- Click "Upload Ending PNG" to select your last frame

**Configure your tweening settings:**
- Select the number of in-between frames (1-100)
- Choose a tweening method (see below for details)
- Adjust method-specific options if available
- Select an easing function to control the timing of the transition

**Generate frames:**
- Click the "Generate In-Between Frames" button
- Preview the results in the frame preview section

**Preview your animation:**
- Use the animation preview section to view your animation
- Adjust the FPS (frames per second) to control playback speed
- Toggle loop mode on/off

**Download your frames:**
- Click "Download All Frames" to get a zip file with all frames
- Frames are named in sequence for easy import into animation software

🎨 **Tweening Methods**
- Crossfade - Simple opacity blending between frames. Good for smooth transitions between similar images or for creating dissolve effects.
- Pixel Motion - Simulates movement of pixels between frames. Good for objects that change position but maintain similar structure. Creates a more dynamic transition than simple crossfade.
- Morphological - Advanced shape-based transformation that morphs objects from one form to another. Best for transforming shapes or characters between different poses or expressions.

**Options:**
- Edge Detection: Controls how strongly the algorithm detects and transforms edges
- Morph Strength: Determines the intensity of the morphing effect
- Process Quality: Balance between quality and processing speed

**Color Harmonize**
Transforms color palettes between images while maintaining structure. Great for style transitions or mood changes in scenes.
_Options:_
- Color Shift: Controls the intensity of color transformation
- Saturation: Adjusts the vibrancy of colors during transition
- Preserve Luma: Maintains original brightness levels to prevent washing out
- Palette Method: Choose between different color transformation algorithms

**Dissolve**
- Film-like dissolve transition with noise patterns. Creates a disintegration effect reminiscent of classic film transitions.

**Directional Wipe**
- Classic wipe transition revealing the second image gradually from one side. Creates a clean, professional transition effect.

**Zoom Blend**
- Combines zooming and fading effects for a dynamic transition with depth. Good for creating dramatic scene changes or focus shifts.

⚙️ **Advanced Options**
- Animation Speed - Control the playback speed of your animation by adjusting the frames per second (FPS) value. Higher values create faster animations, while lower values allow for more detailed examination of the tweening process.
- **Easing Functions** - Easing functions control how the transition progresses over time:
  - **Linear:** Constant speed throughout the transition
  - **Ease In:** Starts slow and accelerates toward the end
  - **Ease Out:** Starts fast and decelerates toward the end
  - **Ease In/Out:** Starts slow, accelerates in the middle, then decelerates at the end
  - **Bounce:** Creates a bouncing effect at the end of the transition
  - **Elastic:** Creates an elastic, springy effect at the end of the transition

The easing visualization shows a preview of how the selected function affects the transition timing.

🔧 **Technical Details**
The PNG Tweening Tool is built using pure HTML, CSS, and JavaScript with no external dependencies. It leverages modern Web APIs including:
- Canvas API for image processing
- File API for handling file uploads and downloads
- Web Workers for performance optimization during complex calculations
- All image processing happens locally in your browser - no images are uploaded to any server, ensuring your work remains private and secure.

**Browser Compatibility**
This tool works best in modern browsers:
- Chrome 60+
- Firefox 55+
- Safari 11+
- Edge 79+

📊 **Performance Considerations**
- Processing large images or generating many frames can be resource-intensive. For optimal performance:
- Keep image dimensions under 2000×2000 pixels
- When working with complex tweening methods like Morphological or Color Harmonize, start with fewer frames and increase gradually
- Choose "Fast" quality settings for initial tests, then switch to "High" for final output

📜 **License**
This project is licensed under the MIT License - see the LICENSE file for details.

👥 **Contributing**
Contributions are welcome! If you'd like to improve the PNG Tweening Tool:
- Fork the repository
- Create your feature branch (git checkout -b feature/amazing-feature)
- Commit your changes (git commit -m 'Add some amazing feature')
- Push to the branch (git push origin feature/amazing-feature)
- Open a Pull Request
- Please make sure to update tests as appropriate and adhere to the existing coding style.

📝 **Roadmap**
Future features planned for development:
- Support for transparent PNG backgrounds
- Batch processing of multiple frame pairs
- Additional tweening algorithms for specialized animation effects
- Export to GIF and video formats
- Layer masking for targeted tweening

🙌 **Acknowledgments**
Inspired by classic animation techniques and modern digital tweening algorithms
Special thanks to all the animators who provided feedback during development

Created with ❤️ for the animation community.
