# PATIENTS DATA RECORD ANALYSIS

Generate 1000 by 6 columns data using NumPy random method. Generate the patient_id , height, weight, sex and age columns separately. Calculate their bmi = weight/height**2 . Using NumPy, stack all columns together. Transform your data into pandas DataFrame. Create a new column in your Dataframe and name it “interpretation”. Fill the column with underweight, normalweight, overweight, obese, clinically obese based on their bmi column. Using your dataset perform statistical analysis and answer the following;

1.Mean height, weight and age

2.All underweight and obese

3.How many underweight patient are 30 years but below 45

4.How many patient are normal and are females below 25 years

5.Number of males who are obese

6.number of male and females who are above the average age and are normal

## SETUP
Install the required packages to be able to run the evaluation locally.

You need to have Python 3 on your system (a Python version lower than 3.10). Then you can clone this repo and being at the repo's root :: repository_name> ... follow the steps below:

Windows (Python should be added to the Path variable of environment):

  python3 -m venv venv; venv\Scripts\activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt  

Linux & MacOs:

  python3 -m venv venv; source venv/bin/activate; python -m pip install --upgrade pip; python -m pip install -r requirements.txt

  The both long command-lines have a same structure, they pipe multiple commands using the symbol ; but you may manually execute them one after another.

1.Create the Python's virtual environment that isolates the required libraries of the project to avoid conflicts;

2.Activate the Python's virtual environment so that the Python kernel & libraries will be those of the isolated environment;

3.Upgrade Pip, the installed libraries/packages manager to have the up-to-date version that will work correctly;

4.Install the required libraries/packages listed in the requirements.txt file so that it will be allow to import them into the python's scripts and notebooks without any issue.

## EVALUATION
This evaluation will be automatically grade, so please follow the instructions carefully.

You can run this command bellow being at the root of the repository to be sure your solutions are the good ones before to push your solutions.

python -m pytest -v

If everything is okay, you will have such an output

================================================= test session starts =================================================
platform xxx -- Python 3.9.6, pytest-7.2.0, pluggy-1.0.0 -- /xxx/python3
cachedir: .pytest_cache
rootdir: xxx/Git-and-GitHub-final-assignment
collected 3 items                                                                                                     

tests/test_filled_table.py::test_not_empty_table PASSED                                                         [ 33%]
tests/test_filled_table.py::test_not_empty_rows PASSED                                                          [ 66%]
tests/test_readme_table.py::test_contains_table PASSED                                                          [100%]

