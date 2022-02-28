# Star_Social
Social Star is an application in which users can create groups for different topics. They can create posts in those groups and join other groups.The main technologies for development are Python, Django, HTML, CSS, JavaScript.

## Dependencies
Dependencies for the project are handled using Pipenv. Use `pip install --user --upgrade pipenv pip` to update your **pip** and **pipenv** packages. 
Afterwards use `pipenv install --dev --deploy --ignore-pipfile` to create the Python virtual environment with all the project's dependencies.
You can use `pipenv shell` to start a shell in the new venv, or use `pipenv run <command>` for running commands inside the venv.

## Style formatting
This project contains several tools used to adapt styling to PEP8 conventions, organize imports and check for poor code design.

For code formatting use `isort polls` and `autopep8 --in-place --recursive polls`.
For running static checks use `isort -c polls`, `flake8 polls` and `pylint polls`.
If additional dependencies are required during development, use `pipenv install <package>` (for packages required in production) or 
`pipenv install --dev <package>` (for development tasks) to install the package, include it in the Pipfile and update the Pipfile.lock.

## The following images represent the functionality of the application
<img width="1440" alt="Screenshot 2022-02-28 at 14 05 18" src="https://user-images.githubusercontent.com/75396991/155982307-4390845f-c80a-4bea-bd47-27e28d0dac02.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 05 32" src="https://user-images.githubusercontent.com/75396991/155982321-2bccad0f-7911-4494-bc4a-d723264facb8.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 05 42" src="https://user-images.githubusercontent.com/75396991/155982335-0579ead7-ff0a-47c8-be28-61916a539bd5.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 06 04" src="https://user-images.githubusercontent.com/75396991/155982344-f0c11ee2-c890-40f4-b40a-ed93496cdc38.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 07 18" src="https://user-images.githubusercontent.com/75396991/155982350-e9dd06d6-4888-4921-9cbf-7af7aa82193e.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 07 27" src="https://user-images.githubusercontent.com/75396991/155982355-eafaab6d-c908-41b1-a964-d5d53309a4e2.png">
<img width="1440" alt="Screenshot 2022-02-28 at 14 20 11" src="https://user-images.githubusercontent.com/75396991/155982611-1c1ba171-4f43-48ba-a6fb-cb90d7995869.png">
