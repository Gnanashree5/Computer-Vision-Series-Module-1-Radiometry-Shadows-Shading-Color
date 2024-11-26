# Module 1: Introduction to Radiometry, Sources, Shadows, and Color in Computer Vision

Welcome to the first module of the **Computer Vision** series. In this module, we will delve into the fundamental concepts of **Radiometry**, **Light Sources**, **Shadows and Shading**, and **Color Science**, which form the backbone of understanding how computers "see" and interpret visual information. These concepts are critical for creating algorithms that analyze, enhance, and manipulate images. Whether you're a beginner or looking to refresh your knowledge, this notebook provides practical code implementations and clear explanations.

---

## Table of Contents
1. [Radiometry: Measuring Light](#radiometry-measuring-light)
2. [Sources, Shadows, and Shading](#sources-shadows-and-shading)
3. [Color Science](#color-science)

---

### Radiometry: Measuring Light

Understanding how light interacts with surfaces is the foundation of computer vision. In this section, we will explore **Radiometry**, which deals with the measurement of light energy. Key topics include:

- **Light in Space**: How light travels through space, from point sources to distributed sources.
- **Light Surfaces**: Understanding the reflection and transmission of light on surfaces.
- **Important Special Cases**: Special scenarios such as diffuse and specular reflections.

By the end of this section, you'll have a strong understanding of light intensity and its spatial distribution, which will help in many computer vision tasks such as object recognition and scene reconstruction.

**Python Code**: 
- Code to simulate light intensity distribution
- Visualization of light energy on surfaces

---

### Sources, Shadows, and Shading

Light doesn't just illuminate a scene; it interacts with objects, creating **shadows** and defining **shading**. This section introduces the concept of **Photometric Stereo** and how shadows and shading can be used to infer 3D shapes from 2D images.

Topics covered include:
- **Qualitative Radiometry**: Understanding how light interacts with objects qualitatively.
- **Sources and Their Effects**: Different types of light sources (e.g., point lights, directional lights) and how they affect shading.
- **Local Shading Models**: How local surface properties (e.g., reflection, texture) affect the visual appearance of objects.
- **Global Shading**: The role of interreflections in complex scenes.

**Python Code**:
- Code demonstrating how different light sources affect the shading of 3D objects.
- Example of shadow formation in images.

---

### Color Science

Color is one of the most important aspects of computer vision, helping us to distinguish and identify objects. This section introduces the **physics of color** and explains how color is perceived by humans and represented in images.

Key topics include:
- **The Physics of Color**: How light of different wavelengths corresponds to different colors.
- **Human Color Perception**: How the human visual system perceives and interprets color.
- **Representing Color in Computers**: How colors are represented in digital images (RGB, HSV, etc.).
- **Surface Color from Finite Dimensional Linear Models**: How colors are modeled using linear transformations, and how this can be applied in image processing.

**Python Code**:
- Code to convert between RGB and HSV color models.
- Demonstrations of how different color models represent the same image.

---

## Conclusion

In this module, we have laid the foundation for understanding how light, shading, and color are fundamental concepts in computer vision. These principles are widely used in various applications such as image segmentation, object recognition, and 3D scene reconstruction. The included Python code examples will help you get hands-on experience with these concepts and provide a deeper understanding of their practical applications.

By the end of this module, you will have learned:
- How light interacts with surfaces and how this interaction can be measured and modeled.
- The importance of shadows and shading in recognizing and analyzing objects.
- The physics behind color perception and how computers handle and manipulate colors in images.


## Next Steps

After completing this module, you'll be ready to dive deeper into more advanced topics in computer vision, such as **Edge Detection**, **Segmentation**, and **3D Vision**. Stay tuned for more modules in this series!

---

