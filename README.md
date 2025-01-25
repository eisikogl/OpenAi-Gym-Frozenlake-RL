# gymnasium frozenlake RL 
OpenAI gym frozenlake AI RL project

This Project is using Python 3.10.11

How to Install:
1. Clone Project
2. Create Virtual Environment  ```python3.10 -m venv myenvname```
3. Activate Env windows: ``` myenvname\Scripts\activate ```
4. Install requirements:  ```pip install -r requirements.txt```
5. Change main run(```How many times to train```,```False to stop Updating Q-table```, ```True to show Simulation```)-> run(15000, is_training=True, render=False)
6. run: ```python validate.py```

# Python Commands for Virtual Environment Setup and Reinstallation


1. **Activating a Virtual Environment:**
   - **Windows (Command Prompt):**
     ```bash
     myenv\Scripts\activate
     ```
   - **Windows (PowerShell):**
     ```bash
     .\myenv\Scripts\Activate.ps1
     ```
   - **macOS/Linux:**
     ```bash
     source myenv/bin/activate
     ```
   **Explanation:** Activates the virtual environment so that any Python packages you install or use are isolated within that environment.

2. **Generate `requirements.txt` (If you don’t have it yet):**
   ```bash
   pip freeze > requirements.txt
   ```

3. **Reinstall Packages from `requirements.txt`:**
   ```bash
   pip install -r requirements.txt
   ```
   **Explanation:** Installs all the packages listed in the `requirements.txt` file into the current environment. This is typically used to set up a project with all the necessary dependencies.

4. **Force Reinstall All Packages:**
   ```bash
   pip install --force-reinstall -r requirements.txt
   ```
   **Explanation:** Reinstalls all packages listed in `requirements.txt`, even if they are already installed. This is useful for ensuring that you have the correct versions or to resolve issues with corrupted installations.

5. **Clear Pip Cache (Optional):**
   ```bash
   pip cache purge
   ```
   **Explanation:** Clears the `pip` cache, which can be helpful if you’re having issues with packages or corrupted installations.

6. **Create a Virtual Environment with a Specific Python Version:**
   ```bash
   python3.10 -m venv myenv
   ```
   **Explanation:** Creates a new virtual environment using Python 3.10. Replace `python3.10` with the path to the desired Python version if needed.

7. **Deactivate the Virtual Environment:**
   ```bash
   deactivate
   ```
   **Explanation:** Deactivates the currently active virtual environment and returns to the system's global Python environment.

8. **Install Packages from `requirements.txt` in a New Environment:**
   ```bash
   pip install -r requirements.txt
   ```
   **Explanation:** Installs all dependencies listed in `requirements.txt` into the virtual environment.

9. **Check the Installed Python Version in Virtual Environment:**
   ```bash
   python --version
   ```
   **Explanation:** Displays the current version of Python in the active virtual environment.

10. **Uninstall a Package:**
    ```bash
    pip uninstall <package_name>
    ```
    **Explanation:** Uninstalls a specified package from the active virtual environment.

11. **Update a Package:**
    ```bash
    pip install --upgrade <package_name>
    ```
    **Explanation:** Upgrades an already installed package to the latest version.
