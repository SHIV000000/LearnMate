# LearnMate


### Cloning the repository

--> Clone the repository using the command below :
```bash
git clone https://github.com/SHIV000000/LearnMate.git

```

--> Move into the directory where we have the project files : 
```bash
cd LearnMate
```

## Create a Virtual Environment

On macOS/Linux:
```bash
python3 -m venv venv
```

On Windows:
```bash
python -m venv venv
```

## Activate the Virtual Environment:

On Windows:
```bash
.\venv\Scripts\activate
```
On macOS/Linux:
```bash
source venv/bin/activate
 ```


Install Dependencies:

```bash
pip install -r requirements.txt
```

Apply Migrations:

```bash
python manage.py makemigrations
```

```bash
python manage.py migrate
```
**Create Superuser (Optional)**

 ```bash
python manage.py createsuperuser
```

**Run the Development Server**

```bash
python manage.py runserver
```

Visit http://127.0.0.1:8000/ in your browser.
