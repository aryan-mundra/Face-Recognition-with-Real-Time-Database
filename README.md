# Face-Recognition-with-Real-Time-Database
![new](https://github.com/aryan-mundra/Face-Recognition-with-Real-Time-Database/assets/144268029/6e3222a7-bf8a-4ef9-969c-d14aafac050e)





# Once the face is recognized and attendance is marked, this screen appears

![122](https://github.com/aryan-mundra/Face-Recognition-with-Real-Time-Database/assets/144268029/9b4cc322-483b-4e08-afe1-25ab56aa55cd)

# Steps to run this code
1) Create and virtual environment
   ```python -m venv env```

2) Activate the virtual environment 
```source env/Scripts/activate```

3) Install required packages to run the project 
```pip install -r requirements.txt ```

4) Make and account on Firebase console
5) Go to Project settings -- > Service accounts --> Generate new Private key(Python)
6) Put the private key file in the main directory by the name "serviceAccountKey.json"
7) Your directory should look like this
   
9) Firebase console --> Realtime database ---> Create new database in test mode
10) Firebase console --> Storage ---> Create new storage bucket in test mode
11) Substitute the values of Database Url and Storage bucket in all the files (main.py , EncodeGenerator.py , AddDatatoDatabase.py)
   
   ```firebase_admin.initialize_app(cred, {
    'databaseURL': "PUT URL HERE",
    'storageBucket': "PUT URL HERE"})

11) Run EncodeGenerator.py
12) Run  AddDatatoDatabase.py
13) Run main.py

![111](https://github.com/aryan-mundra/Face-Recognition-with-Real-Time-Database/assets/144268029/af118cb2-f0a5-4e7d-bb30-22ee3ea83e0b)


