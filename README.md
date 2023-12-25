




## Configuration (MacBook, Linux &amp; Windows)
### Prerequisites

- Python version >= 3.9

### Steps
#### Common Step for All Platforms

- **Install Python (if not already installed)**
   - On **Linux**:
    ```sql
    sudo apt-get update
    sudo apt-get install python3
    ```
   - On **MacBook** (using Homebrew):
    ```css
    brew install python@3.9
    ```
   - On **Windows**:
      - Download and install Python from the
      Python website
      .
      - Make sure to check the option "Add Python 3.9 to PATH" during installation.
   - **Install Python 3 Virtual Environment**
   - This step is common for all platforms:
    ```css
    python3 -m pip install --user virtualenv
    ```

#### Platform-Specific Steps

- **Create a Virtual Environment**

```
python3 -m venv .venv
```
- **Activate the Virtual Environment**
   - On **Linux** and **MacBook**:
    ```bash
    source .venv/bin/activate
    ```
   - On **Windows**:
    ```
    .\.venv\Scripts\activate
    ```
- **Install Required Python Packages**

```
python3 -m pip install -r requirements.txt
```
- **Optional: Deactivate the Virtual Environment**
   - To exit the virtual environment when your work is done:
    ```
    deactivate
    ```

### Notes

- Ensure that you have Python 3.9 or higher installed on your system. You can check this by running `python3 --version`.
- On a MacBook, if you do not have Homebrew installed, you can install it from
brew.sh
, or alternatively, download Python directly from the
Python website
.
- On Windows, it is important to add Python to the PATH to ensure that the `python3` command is recognized in the Command Prompt.