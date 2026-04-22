# Manim Animation Templates 🎬📐

![Manim Logo](https://raw.githubusercontent.com/ManimCommunity/manim/main/logo/cropped.png)

## Overview
This repository contains a collection of Python-based educational animation scripts created during my internship at **Skillbanc**. These scripts leverage **Manim** (Mathematical Animation Engine) — the engine created by 3Blue1Brown — to programmatically generate high-quality math, logic, and educational videos.

*(Note: These scripts were originally contributed to the [Skillbanc/manim-templates](https://github.com/Skillbanc/manim-templates) organization repository.)*

---

## 🎯 Key Features & Topics Covered
The `Source` directory contains over 150 unique animation scripts covering various educational topics, ranging from basic elementary math to advanced geometry, algebra, and statistics. 

Topics included but not limited to:
- **Foundational Math:** Fractions, Decimals, Number Lines, Integers.
- **Algebra:** Linear Equations, Algebraic Expressions, Exponents.
- **Geometry:** Practical Geometry, Triangles & Properties, Symmetry, Shapes.
- **Advanced Topics:** Set Operations, Statistics, Divisibility Rules.
- **Custom Graphics:** AWS Services architecture animations (EC2, S3, RDS, IAM).

## 🛠️ Technology Stack
- **Language:** Python 3.x
- **Animation Framework:** [Manim Community Edition](https://www.manim.community/)
- **Media Output:** Generates MP4 videos and SVG graphics programmatically.

## 🚀 How to Run

### Prerequisites
You need to install Python and Manim on your system.
For detailed installation instructions, check the [Official Manim Installation Guide](https://docs.manim.community/en/stable/installation.html).

### Execution
To render an animation from a script, navigate to the `Source` directory and run:

```bash
manim -pql <filename>.py <ClassName>
```
- `-p` : Previews the animation immediately after rendering.
- `-ql` : Renders at low quality (faster for testing). Use `-qh` for high quality (1080p60).
- `<ClassName>` : The name of the Python class inside the script that inherits from `Scene`.

Example:
```bash
manim -pql AdditionFractions.py AdditionFractionsScene
```

## ✨ Contributions
All python files in the `Source` folder were authored and continuously iterated upon to deliver production-ready educational assets during my core development phase at Skillbanc.

## 📱 Other Technical Works & Portfolio
In addition to these educational animations, my portfolio includes:
- **Flutter & Android Studio Mobile Apps**: Developed natively compiled applications (such as targeted quiz apps) using the Flutter UI toolkit and Android Studio.

