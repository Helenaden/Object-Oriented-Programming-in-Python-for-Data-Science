# Object-Oriented-Programming-in-Python-for-Data-Science

## Project Overview  
This project takes a hands-on approach to **Object-Oriented Programming (OOP) in Python**, applying it to a real-world data science challenge: handling image datasets annotated in the **Labelme polygon format**.  

The project shows how to **design reusable, modular code** that makes working with annotated images easier and more scalable. Along the way, you’ll see how to:  
- Download and organize example Labelme data.  
- Load and explore both image files and their JSON annotations.  
- Visualize polygon annotations over images with **Matplotlib**.  
- Refactor everything into a reusable Python class, `ImageData`, that keeps the workflow clean and efficient.  

## What This Project Covers  
1. **Setting Up the Project**  
   - Downloading the Labelme example dataset.  
   - Creating a simple folder structure for images and JSON files.  

2. **Exploring the Data**  
   - Loading an image alongside its JSON annotation.  
   - Inspecting shapes, labels, and polygon points from the annotation file.  

3. **Visualizing Annotations**  
   - Overlaying polygon labels on top of images to see the data in action.  

4. **Refactoring with OOP**  
   - Building the `ImageData` class that:  
     - Loads images and annotations together.  
     - Provides methods to inspect data.  
     - Visualizes annotations seamlessly.  

5. **Testing the Class**  
   - Instantiating `ImageData` and verifying that it correctly loads data, retrieves labels, and visualizes annotations.

## What You’ll Learn  
- Applying **OOP principles** to real data workflows.  
- Handling **image datasets with annotations** in Python.  
- Visualizing annotations in a clear, interpretable way.  
- Writing code that’s not only functional but **reusable and scalable**.  

## Why It Matters  
In data science, especially in computer vision, datasets often come with annotations that need to be parsed, inspected, and visualized. Doing this with scripts can quickly become messy.  

By wrapping the workflow into a **dedicated class**, this project shows how OOP can make your work more **organized, modular, and efficient**, skills that are directly transferable to larger machine learning and data engineering projects.  
