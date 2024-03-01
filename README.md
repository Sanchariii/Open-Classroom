<div align="center">




 
<h1> Open-Classroom </h2>

This is an attempt to clone the best features of google classroom and educative.io using django.


<img width="860" alt="landing page" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/7b6f4bb9-6ff9-4e25-97ce-5c8cfe0a998c">

<hr>
</div>

## Screenshots

<img width="960" alt="landing page" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/5fb2d2dc-af49-4b52-ba28-9de699eedadd">
<img width="960" alt="login page" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/0ac5f8e3-9ba5-411b-a9ca-45e56ba2d2d7">
<img width="960" alt="classroom" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/0d009e67-0857-4873-8e5e-5dec0cd1bf6a">
<img width="960" alt="DSA" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/bca00f40-a91a-4608-98de-ecdc7d693ea2">
<img width="960" alt="student view" src="https://github.com/Sanchariii/Open-Classroom/assets/88083502/9269765d-5ce3-431e-8b75-b775a187827c">

## Features Included 
- Custom Admin dashboard
- Create Classroom
- Join Classroom
- Add Posts 
- Create Assignments 
- Grade Assignments 
- Add Resources 
- Responsive, mobile-friendly design
- Forgot password 
- User registration









 
<br>
Clone the repository using the following command

```bash
git clone https://github.com/Sanchariii/Open-Classroom.git
# After cloning, move into the directory having the project files using the change directory command
cd Open-Classroom
```
Create a virtual environment where all the required python packages will be installed

```bash
# Use this on Windows
python -m venv env
# Use this on Linux and Mac
python3 -m venv env
```
Activate the virtual environment

```bash
# Windows
.\env\Scripts\activate
# Linux and Mac
source env/bin/activate
```
Install all the project Requirements
```bash
pip install -r requirements.txt
```
-Apply migrations and create your superuser (follow the prompts)
```bash
# apply migrations and create your database
python manage.py migrate

# Create a user with manage.py
python manage.py createsuperuser
```

Run the development server

```bash
# run django development server
python manage.py runserver
```
