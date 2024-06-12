# TO do list using Django for backend and React for frontend

## How to run the project
# backend:
- First verify you have Python install
  ```bash
  python --version
  ```
- To check if the Node module is installed
  ```bash
  node --version
  ```
## Clone the git repo: 
```bash
git remote add origin https://github.com/chetandeshpande1/Todo-List-using-Django-and-React.git
```

- Move into the directory using the below command:
```bash
cd django-react-project
```
- Now create a virtual environment using the below command:
```bash
python -m venv dar
```
- Activate the virtual environment that we just created using the below command:
```bash
dar\Scripts\activate.bat
```
  I have named my virtual environment “myenv”. This is necessary as we don’t have to install packages and dependencies globally. It is also a good programming practice.

- Now Install Django
  ```bash
  pip install django
  ```
- Now use the below command to migrate the project:
```bash
python manage.py migrate
```

- Now run the server
  ```bash
  python manage.py runserver
  ```

## frontend:
- redirect to frontend folder
  ```bash
  npm start
  ```
