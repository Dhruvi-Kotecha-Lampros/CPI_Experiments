## Structure  
**Data/:** Contains experimental data files.

**Test_Delegation_Functionality/:** Holds test files for delegation functionality.

**Python_Files/:** Contains a Jupyter Notebook (.ipynb file) that demonstrates delegation experiments with varying OP token amounts and tracks the resulting changes in CPI.

**delegation/:** The virtual environment used for this project. Dependencies are listed in requirements.txt.

## Prerequisites  
To use this project, you need:  
Python 3.x installed  

## Setup Instructions  
**1. Clone the Repository** (if not already done):  
   `git clone https://github.com/Dhruvi-Kotecha-Lampros/CPI_Experiments.git`  
   `cd CPI_Experiments`  

**2. Set Up Virtual Environment:**  
   `python -m venv delegation`  

**3. Activate Virtual Environment:**  
  On **Windows**:  
    `delegation\Scripts\activate`  
    
  On **macOS/Linux**:  
    `source delegation/bin/activate`  

**4. Install Dependencies:**  
  `pip install -r requirements.txt`  

**5. Run Jupyter Notebook**  
   Navigate to the Python_Files/ directory and open the Jupyter Notebook to experiment with delegation.  

## Usage  
a. Open the Jupyter Notebook in Python_Files.  
b. Modify the delegation values to experiment with different amounts of OP tokens.  
c. Observe how these changes affect the Concentration of Power Index (CPI) and explore insights on delegation impact.  
