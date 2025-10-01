**Notes from scripts:**

## To set up and install dependencies from a requirements.txt file for your Python project, follow these steps:

#### Step 1: Create a Virtual Environment (Optional but Recommended)
It's a good practice to create a virtual environment for your project to isolate its dependencies from the system Python environment. You can create a virtual environment using the venv module that comes with Python:
bash
`python -m venv myenv`
Replace myenv with the name you want to give to your virtual environment.

#### Step 2: Activate the Virtual Environment
To activate the virtual environment, run:

- On Windows:
- `myenv\Scripts\activate`

On macOS/Linux:
- `source myenv/bin/activate`
You should now see the name of the virtual environment printed on your terminal, indicating that it's active.

#### Step 3: Install Dependencies from requirements.txt
Navigate to the directory containing your requirements.txt file and run:
- `pip install -r requirements.txt`
This command tells pip to install all the dependencies specified in the requirements.txt file.

That's it! Your project should now have all the necessary dependencies installed.
