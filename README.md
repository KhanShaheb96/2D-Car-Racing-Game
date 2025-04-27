# 🏎️ 2D Car Racing Game | OpenGL & GLUT  
**Computer Graphics Course Project**  
*American International University-Bangladesh (AIUB)*  

---
A complete 2D racing game developed using OpenGL and GLUT for the Computer Graphics course at American International University-Bangladesh.

## Features
- Smooth player car controls
- Dynamic AI-controlled opponent cars
- Progressive difficulty system
- Real-time scoring
- Cross-platform compatibility
- Sound effects

## Technologies
- OpenGL
- GLUT
- C++11

## **Game Controls**  
| **Key**        | **Action**               |
|---------------|-------------------------|
| `SPACE`       | Start/Pause Game        |
| `ESC`         | Exit Game               |
| `←` `→`      | Move Car Left/Right     |
| `↑` `↓`      | Increase/Decrease Speed |

---
## **Team (AIUB)**  
| **Name**                   | **ID**       | **Contribution** |
|---------------------------|-------------|-----------------|
| Nasimul Arafin Rounok     | 21-45353-2  | 20%             |
| Fardin Abu Ubaid          | 21-44863-2  | 20%             |
| Muhtasib Ibtida Kousik    | 21-44864-2  | 20%             |
| Adil Ahmed Shamim         | 21-45190-2  | 20%             |
| Hasin Aabrar Khan         | 21-45297-2  | 20%             |

## 2D-Car-Racing
├── src/                # Source code
│   └── main.cpp        # Main game logic
├── assets/             # Resource files
│   ├── car.wav         # Engine sound
│   └── screenshot.png  # Game preview
├── README.md           # This file
└── LICENSE             # MIT License

**Installation**  

### **Windows**  
bash
g++ src/main.cpp -o game.exe -lfreeglut -lglu32 -lopengl32
game.exe
### **Linux**
sudo apt install freeglut3-dev
g++ src/main.cpp -o game -lglut -lGLU -lGL
./game

### 2. LICENSE

```text
MIT License

Copyright (c) 2023 AIUB Computer Graphics Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
