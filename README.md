#  Student Performance Analysis using NumPy

A programmatic data manipulation project that utilizes multi-dimensional NumPy matrices to analyze academic metrics, focusing on vectorized slicing, broadcasting, and universal boolean masking arrays.

## Dataset Architecture
The data contains 5 distinct student records in 2D matrix:
* **Column 0:** Age
* **Column 1:** Math Marks
* **Column 2:** Science Marks

##  Core Tasks Solved
1. **Dimensional Profiling:** Calculated matrix resolution using matrix shapes.
2. **Aggregations:** Computed statistical means and maximum records.
3. **Boolean Filtering:** Extracted granular rows meeting score boundaries ($>90$).
4. **Vectorized Broadcasting:** Updated target rows dynamically ($+5$ marks).
5. **Universal Masking Rules:** Filtered dual-pass matrices using `.all(axis=1)`.
6. **Defensive Modification:** Cloned arrays to safely mutate invalid records without data pollution.

##  Installation & Usage
Clone the project and install requirements via terminal:
```bash
git clone https://github.com
pip install -r requirements.txt
jupyter notebook
```
