# Data Analysis

## JupyterLab

> JupyterLab is a next-generation web-based user interface for Project Jupyter.

> JupyterLab enables you to work with documents and activities such as Jupyter notebooks, text editors, terminals, and custom components in a flexible, integrated, and extensible manner

#### Code Consoles

> provide transient scratchpads for running code interactively, with full support for rich output

#### Kernel-backed documents

> enable code in any text file (Markdown, Python, R, LaTeX, etc.) to be run interactively in any Jupyter kernel.

> JupyterLab also offers a unified model for viewing and handling data formats. JupyterLab understands many file formats (images, CSV, JSON, Markdown, PDF, Vega, Vega-Lite, etc.

# NumPy

- a Python package used for data analysis
-

### Numpy 2-Dimensional Arrays / matrix

- rows are the first axis
- columns are the second axis
- the array function is used to convert th list of lists into an array

- Code Example(reading a csv file and converting the output list into an array)
  > import csv
  > with open("winequality-red.csv", 'r') as f:
        wines = list(csv.reader(f, delimiter=";"))
  import numpy as np
  wines = np.array(wines[1:], dtype=np.float)

### Alternative NumPy Array Creation Methods

- Using _np.zeros_ where are all elements are zeroes.

  > import numpy as np
  > empty_array = np.zeros((3,4))

- Using _numpy.random.rand._ where each element is a random number
  > np.random.rand(3,4)

### Reading files using NumPy

- using _numpy.genfromtxt_ function.
  > wines = np.genfromtxt("winequality-red.csv", delimiter=";", skip_header=1)

### Indexing NumPy Arrays

- > NumPy is zero-indexed, meaning that the index of the first row is 0, and the index of the first column is 0
- Exampele: "wines[2,3]" ===> element positioned in the third row and the fourth column

### Slicing NumPy Arrays

- using colon, selects elements up until the last index, without it being included.

  > wines[0:3,3]

- We can extract an entire column _wines[:,3]_ or an entire row _wines[3,:]_
- We can choose the whole array using _wines[:,:]_

### Assigning Values To NumPy Arrays

> wines[1,5] = 10

#### Arrays can either be single dimensional, two dimensional or multi dimensional

### NumPy Data Types

- using _array-name.dtype_
- Data type can be any of the following:
  > **float** — numeric floating point data.
  > **int** — integer data.
  > **string** — character data.
  > **object** — Python objects.

### Data Type Conversions

> _array-name.astype(int)_

### NumPy Array Operations

##### Single Array Math

> basic mathematical operations (/, \*, -, +, ^) with an array and a value, it will apply the operation to each of the elements in the array.

##### Multiple Array Math

- applying mathematical operations (/, \*, -, +, ^) between arrays

##### NumPy has many Array Methods, such as "sum()"

##### Subsetting can be done by choosing certain elemnts from the array, on which a certain condition applies to. In other words, we get to filter arrays based on a certain criteria.

> high_quality_and_alcohol = (wines[:,10] > 10) & (wines[:,11] > 7)
