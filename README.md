# data_analytics-


# Setup Instructions

Follow these steps to set up the project environment and install the required dependencies.

## 1. Create a Virtual Environment

Create a Python virtual environment using bash:

```bash
python -m venv .venv
```
Or, you can use this if you're comfy with VSCode:

1. Open the project folder in VS Code.
2. Press Ctrl + Shift + P to open the Command Palette.
3. Search for and select Python: Create Environment.
4. Choose Venv as the environment type.
5. Select your preferred Python interpreter/version.
6. Choose the project folder as the location for the virtual environment (or accept the default .venv location).
7. Wait for VS Code to finish creating and configuring the virtual environment.

If VS Code prompts you to install recommended dependencies after creating the environment, you may choose to proceed or skip this step.
> If your IDE prompts you to install dependencies automatically, you may choose to proceed or skip this step.

## 2. Activate the Virtual Environment

### Windows

```bash
.venv\Scripts\activate
```

### macOS/Linux

```bash
source .venv/bin/activate
```

## 3. Install `pip-tools`

Once the virtual environment is activated, install `pip-tools`:

```bash
pip install pip-tools
```

## 4. Navigate to the Project Root Directory

Ensure you are in the root directory of the project (the folder containing the assignment notebook and dependency files).

Example:

```bash
cd path/to/project-folder
```

## 5. Sync Dependencies

Install all required project dependencies using `pip-sync`:

```bash
pip-sync
```

This will install the exact package versions specified in the project's dependency files and remove any packages that are not required.

## 6. Launch the Assignment Notebook

After dependency synchronization is complete, start Jupyter Notebook or open the assignment notebook in your preferred IDE.

```bash
jupyter notebook
```

or

```bash
jupyter lab
```

