# 🕒 CBTL Location Processor

This project processes and transforms Coffee Bean & Tea Leaf (CBTL) store data, specifically focusing on store location details. It takes raw data https://www.coffeebean.com.my/amlocator, performs formatting and cleanup, and outputs a the clean version of the data in a excel file.

---

## Getting Started

1. **Prepare the Environment**  
   Make sure you have Python 3.8+ and Jupyter installed. You can set up the environment with:

   ```bash
   pip install pandas
   pip install beautifulsoup4
   pip install openpyxl
   pip install requests
   ```

2. **Change the path**  
   On the last cell, change the path for excel output file.
   ```bash
    USER_PATH = "/Users/adibrafi/Desktop/" # Replace with your own path
    FILE_NAME = "cbtlLocation.xlsx" # Rename the output file if desired
    ```

3. **Run the Notebook**  
   Open the notebook and run all cells.

---

## Data Visualization
This project use Tableau Public. Screenshot will be given inside this repository

For full interactive: https://public.tableau.com/views/CBTLStoreLocator/Dashboard1?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
