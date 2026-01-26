# 🐼 A Day in the Life of a Panda: Interactive 2D Animation System

A charming OpenGL-based 2D animation project showcasing a day in the life of a panda through four beautifully animated scenes. This project demonstrates fundamental computer graphics concepts including geometric modeling, animations, transformations, and user interaction.

## 📖 Project Description

This interactive animation project presents four distinct scenes depicting various activities in a panda's daily routine. Each scene features smooth animations, dynamic elements, and carefully crafted visual details to create an engaging viewing experience.

### Featured Scenes:

1. **🎋 Eating Bamboo** - Watch the panda enjoy its favorite meal in a sunny bamboo forest
  <img width="779" height="607" alt="image" src="https://github.com/user-attachments/assets/9b328991-8320-42d5-a129-8db2a460ec59" />
 
2. **🌊 By the River** - See the panda relaxing by a peaceful riverside
   <img width="776" height="593" alt="image" src="https://github.com/user-attachments/assets/07f90840-4fc0-4834-9b60-b69fc98605c1" />

3. **🌙 Sleeping in Cave** - Experience a serene night scene with the panda resting
   <img width="772" height="594" alt="image" src="https://github.com/user-attachments/assets/02521ffc-01f6-4090-9d32-b1548a9b45be" />

4. **⚡ Playing/Rolling** - Interactive scene where the panda playfully rolls across hills
   <img width="777" height="600" alt="image" src="https://github.com/user-attachments/assets/f7391a73-1856-40e6-9e8c-b3fad589b56a" />


## ✨ Features

- **4 Unique Animated Scenes** with distinct environments and moods
- **Smooth Animations** including hand movements, head tilting, breathing, rolling, and more
- **Dynamic Elements**:
  - Moving clouds across all daytime scenes
  - Twinkling stars in the night scene
  - Animated fireflies with glowing effects
  - Butterflies with flapping wings
  - Water reflections and flowing effects
- **Interactive Controls** for scene switching and panda movement
- **Reset Functionality** with clickable button and keyboard shortcut
- **Custom Graphics** - All elements drawn using OpenGL primitives (no external images)

## 🎮 Controls

| Key | Action |
| `1` | Switch to Scene 1 (Eating Bamboo) |
| `2` | Switch to Scene 2 (By the River) |
| `3` | Switch to Scene 3 (Sleeping in Cave) |
| `4` | Switch to Scene 4 (Playing/Rolling) |
| `SPACE` | Start/Pause panda rolling (Scene 4 only) |
| `R` | Reset panda position (Scene 4 only) |
| `ESC` | Exit the program |
| `Mouse Click` | Click RESET button in Scene 4 to reset panda |

## 🛠️ Technologies Used

- **Language**: C++
- **Graphics API**: OpenGL
- **Utility Library**: GLUT (OpenGL Utility Toolkit)
- **IDE**: Code::Blocks (recommended)
- **Compiler**: MinGW GCC

### For Windows Users:

1. Download and install [Code::Blocks with MinGW](http://www.codeblocks.org/downloads)
2. Download [freeglut](https://www.transmissionzero.co.uk/software/freeglut-devel/)
3. Set up OpenGL and GLUT in your IDE

## 🚀 Installation & Setup

### Step 1: Clone the Repository
```bash
git clone https://github.com/yourusername/2d-panda-lifestyle.git
cd 2d-panda-lifestyle
```

### Step 2: Configure Code::Blocks

1. Open Code::Blocks
2. Create a new GLUT project or open the provided `.cbp` file
3. Add the source file to your project

### Step 3: Link Libraries

Go to **Project → Build Options → Linker Settings** and add:
- `opengl32`
- `glu32`
- `freeglut`

### Step 4: Compile and Run

1. Build the project (F9)
2. Run the executable
3. Enjoy the panda animations!

## 🎨 Scene Details

### Scene 1: Eating Bamboo 🎋
- **Environment**: Bright sunny day with blue sky
- **Features**: Animated hand movement, bamboo forest background
- **Animation**: Panda's hand moves up and down while eating
- **Colors**: Vibrant greens and blues for a cheerful atmosphere

### Scene 2: By the River 🌊
- **Environment**: Peaceful riverside with flowing water
- **Features**: Animated head movement, bamboo forest, clean river
- **Animation**: Panda's head turns left and right while sitting
- **Colors**: Cool blues and greens for a calm setting

### Scene 3: Sleeping in Cave 🌙
- **Environment**: Nighttime with stars and moon
- **Features**: Breathing animation, twinkling stars, glowing fireflies, cave shelter
- **Animation**: Gentle breathing motion, firefly movement
- **Colors**: Dark blues and purples with glowing accents

### Scene 4: Playing/Rolling ⚡
- **Environment**: Hilly landscape with bamboo forest
- **Features**: Interactive rolling animation, butterflies, reset button
- **Animation**: Full 360° rolling motion across hills
- **Interaction**: Click RESET or press 'R' to restart

## 🔮 Future Enhancements

Based on our project analysis, potential improvements for future versions include:

### Advanced Interaction Features
- [ ] Add mouse-based panda movement control
- [ ] Implement drag-and-drop bamboo feeding
- [ ] Create interactive background elements

### Sound and Audio Integration
- [ ] Add ambient nature sounds for each scene
- [ ] Implement eating sounds in Scene 1
- [ ] Add water flowing sounds in Scene 2
- [ ] Include night cricket sounds in Scene 3
- [ ] Add rolling sound effects in Scene 4

### AI Behavior
- [ ] Implement autonomous panda decision-making
- [ ] Add random activity patterns
- [ ] Create hunger and sleep mechanics

### More Scenes and Story Expansion
- [ ] Add day-night cycle transitions
- [ ] Create additional seasonal scenes (rain, snow)
- [ ] Implement weather effects
- [ ] Add more panda activities (climbing, playing)

### Transition to 3D Graphics
- [ ] Upgrade to OpenGL 3D rendering
- [ ] Add depth and perspective
- [ ] Implement camera controls
- [ ] Create 3D panda model

### Performance and Visual Enhancements
- [ ] Implement particle systems for effects
- [ ] Add texture mapping
- [ ] Improve lighting and shadows
- [ ] Optimize rendering performance

### Educational Applications
- [ ] Add informative panda facts
- [ ] Create educational mode about panda behavior
- [ ] Implement interactive learning features

### Cross-Platform Support
- [ ] Port to modern OpenGL (3.3+)
- [ ] Add WebGL version for browser compatibility
- [ ] Create mobile app version

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request
