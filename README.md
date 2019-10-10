# Financial analysis of budget data
Python script that analyzes profit/loss over a period of time

## Setup & Go
Requirements
  * Git @ https://git-scm.com
    - Download the latest version from the home page
    - If there is an option to add 'git' to the PATH, then choose to do so
  * Python 3.7 or higher @ https://www.python.org/downloads/
    - Download the latest version from the home page
    - Windows: Make sure to choose the option to add Python to the PATH on the first Setup Wizard screen.
  * pip - Python package installer (comes with Python >=3.4) 

These instructions will assume execution from an OS terminal console
window. The type of operating system should not matter, except that
you will need to [Google how to open a terminal window](http://lmgtfy.com/?q=how+do+I+open+a+terminal+window) 
if you are not already familiar.  

1. Create a project workspace for your development projects
    ```
    mkdir my-workspace
    cd workspace
    ```
     
2. Clone this project to your local workstation
   ```
   git clone https://github.com/setholindaman/financial_analysis.git
   cd financial_analysis
   ```

3. Install dependent Python packages used by this application
    ```
    pip install PyYAML 
    ```

4. Run the program to enter into the main menu
    ```
    python main.py  
    ```