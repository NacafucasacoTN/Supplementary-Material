# Supplementary-Material
Repository dedicated to archiving supplementary materials, including mathematical formulas and primarily Python code, used in the scientific productions of Enya Tiemi de Almeida Nacafucasaco. 
For more information, refer to the Lattes curriculum: http://lattes.cnpq.br/3328020991326761.

# Step-by-Step Guide: Running the Variance Test Script in Python

This guide provides detailed instructions on how to set up your environment and run the variance test script on a conventional computer. Follow these steps carefully to ensure a smooth experience.

## 1. Install Python

To run the script, you need Python installed on your computer. Follow these steps to install it:

1. **Download Python:**
   - Go to the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)
   - Download the latest stable version for your operating system (Windows, macOS, or Linux).
   
2. **Install Python:**
   - Run the downloaded installer.
   - Ensure you check the option **"Add Python to PATH"** before clicking "Install Now".
   - Wait for the installation to complete.
   
3. **Verify Installation:**
   - Open a terminal or command prompt and type:
     ```sh
     python --version
     ```
   - If installed correctly, it should display the installed Python version.


## 2. Install a Free IDE (Optional but Recommended)

For better usability, it is recommended to use an Integrated Development Environment (IDE). A good free option is **VS Code**:

1. **Download and Install VS Code:**
   - Visit: [https://code.visualstudio.com/](https://code.visualstudio.com/)
   - Download and install it following the on-screen instructions.

2. **Install the Python Extension in VS Code:**
   - Open VS Code.
   - Go to **Extensions** (Ctrl + Shift + X).
   - Search for **Python** and click **Install**.


## 3. Install Required Libraries

Before running the script, install all required Python packages. Open a command prompt or terminal and run the following command:

```sh
pip install scipy numpy matplotlib
```

This command will install:
- **scipy** (for statistical tests)
- **numpy** (for numerical computations)
- **matplotlib** (for generating graphs)

If you are using Jupyter Notebook, you may also need:
```sh
pip install jupyter
```


## 4. Run the Script

Once Python and the required libraries are installed, follow these steps to execute the script:

1. **Create a new Python file:**
   - Open VS Code (or any text editor of your choice).
   - Create a new file and save it as `variance_test.py`.
   
2. **Copy and Paste the Script:**
   - Copy the full script provided in the article.
   - Paste it into the `variance_test.py` file.
   
3. **Run the Script:**
   - Open a terminal in VS Code (or use the command prompt).
   - Navigate to the folder where the script is saved using `cd`:
     ```sh
     cd path/to/your/script
     ```
   - Run the script with:
     ```sh
     python variance_test.py
     ```
   
4. **Enter Your Data:**
   - The script will ask you to enter the data for two groups.
   - Type the values separated by commas (e.g., `1.2, 2.3, 3.1, 4.5`).
   - Press **Enter** to proceed.

5. **View Results:**
   - The script will generate a graph comparing the two distributions.
   - The test result (Levene’s test p-value) will be shown in the legend.
   - The figures will be saved as PNG and TIFF files in the script’s folder.


## 5. Troubleshooting

If you encounter errors, consider the following solutions:
- **ModuleNotFoundError:** Ensure all required libraries are installed (`pip install scipy numpy matplotlib`).
- **Python Not Recognized:** Check if Python is added to the system PATH.
- **Graph Not Displaying:** Ensure you have `matplotlib` installed and try running the script again.


## 6. Conclusion

By following this guide, you should be able to run the variance test script successfully. If you need further assistance, refer to the official documentation of Python and the required libraries.

Happy coding!

