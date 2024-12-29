# BMsmileys LaTeX Package

**Version**: 1.0  
**Release Date**: 2024-12-26  

## Overview

The `BMsmileys` package provides a collection of macros to include emoji icons in LaTeX documents. 
It is designed for users who want to enhance their documents with scalable and customizable emojis. 

The icons (svg) are sourced from [UXWing](https://uxwing.com/).

## Features

- A wide variety of emoji icons, including happy, sad, surprised, and more.
- Scalable icons with an optional size parameter.
- Easy-to-use macros for quick integration into LaTeX documents.

## Installation

1. Download the package files:
   - `BMsmileys.sty`
   - `png/` (folder with icon images)
   - `svg/` (folder with svg files, optional for developers)
   - `BMsmileys.dtx` and `BMsmileys.ins` (optional for developers)
   
2. Place `BMsmileys.sty` and the `png/` folder in the same directory as your LaTeX project or in your local `texmf` tree.

3. Include the package in your LaTeX document:
   ```latex
   \usepackage{BMsmileys}
