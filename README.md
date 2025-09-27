# Tools and Exercises Repository

This repository contains exercises, small projects, and playgrounds exploring advanced Python concepts and libraries. It is a work-in-progress for learning and practicing new Python skills through hands-on coding challenges.

## Achievements

- Gained strong foundational NumPy and data manipulation skills by implementing custom array transformations, masks, and reshaping tasks.  
- Designed and solved multiple structured array challenges (such as creating bordered arrays, cross patterns, and embedded matrices).  
- Practiced reproducibility and clarity in experiments through modular code, indexing, and controlled random number generation.  
- Used array creation and modification tasks (e.g., setting specific cells, filling subarrays) to deepen understanding of broadcasting and slicing.

## Topics & Libraries Explored

### NumPy

- Array creation: `zeros`, `ones`, `full`, `identity`  
- Randomized data generation with `np.random.rand`, `np.random.randint`  
- Reshaping and slicing (multi-dimensional indexing, subarray replacement)  
- Boolean masking and conditional selection  
- Stacking arrays (`hstack`, `vstack`) and embedding smaller arrays into larger ones  
- Targeted updates (changing single elements or subarrays, e.g., setting center value)  

### Python Fundamentals

- Itertools for grouping and processing lists  
- Differences between views and copies (`.copy()`)  
- Boolean operations and logical indexing  
- File handling with NumPy I/O (`np.genfromtxt` for CSV-like data)  

## Projects & Exercises

- **Structured Array Tasks**:  
  - Created a 7×7 array filled with `3`, inserted a `5×5` array of `1`s in the center, and updated the very center element to `5`.  
  - Built bordered arrays (double borders of different values).  
  - Cross patterns and "donut" arrays using slicing.  
  - Reshaping 1D arrays into 2D/3D layouts.  

- **Masking and Selection**:  
  - Boolean masks to filter array elements by conditions.  
  - Extracted diagonals, rows, and columns from structured arrays.  

- **Mini Playgrounds**:  
  - Experimented with 3D arrays and nested indexing.  
  - Grouped words by their first letter using `itertools.groupby`.  

## Tech Stack

- **Libraries**: NumPy, itertools  
- **File I/O**: CSV/Text parsing with NumPy  
- **Environment**: Jupyter Notebooks, VS Code  

## Purpose

The aim of this repository is to steadily build advanced Python fluency through practice and experimentation.  
Key goals include:  

- Understanding NumPy array manipulation at a low level.  
- Practicing conditional masking and selection logic.  
- Designing structured array challenges (borders, patterns, embeddings).  
- Reinforcing programming concepts like iteration, grouping, and data slicing.
