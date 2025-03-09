#  Data Mining Lab-1

Oleksii Frankov, MMAI-1

## Setup instructions

1. Create a Virtual Environment
    ```bash
    python -m venv lab1
    ```
   
2. Activate the Virtual Environment

   (Windows)

    ```bash
   lab1\Scripts\Activate
    ```
   
    (macOS/Linux)
    ```bash
    source lab1/bin/activate
    ```

3. Install the required dependencies:

   ```bash  
   pip install -r "requirements.txt"  
   ```
   
4. Install jupyter notebook if needed: 

   ```bash  
   pip install jupyter
   ```

## Usage

To run notebook, execute the following:

```bash  
python -m ipykernel install --user --name=lab1 --display-name "Python (lab1)"
jupyter notebook "lab1/maim.ipynb"
```
