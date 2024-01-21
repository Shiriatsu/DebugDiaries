# CS61a-No module named 'urllib3.packages.six.moves'

When encountering the ModuleNotFoundError: No module named 'urllib3.packages.six.moves' error while running python3 ok -q python-basics -u after completing CS61a lab00, the solution is to downgrade Python from version 3.12 to 3.11. Follow these steps:

## 1.Download Python 3.11 from the [official Python website](python.org).

## 2.Install virtualenv:
```pip install virtualenv```

## 3.Create a virtual environment:
Open the terminal in your project folder and execute the following command:
```virtualenv -p python3.11 venv```

This will create a virtual environment named venv in the current directory, using Python 3.11.

## 4.Activate the virtual environment:
On macOS/Linux:
```source venv/bin/activate```

Now, running ```python3 ok -q python-basics -u``` should not result in an error.

## 5.After running the command, deactivate the virtual environment:
```deactivate```

By following these steps, you can resolve the ModuleNotFoundError issue and successfully run the specified command in your virtual environment.
