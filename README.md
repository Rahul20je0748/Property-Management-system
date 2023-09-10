# 🏚️ Property-Management

The **Property Management** website is designed to provide the facility to a user to buy or sell/rent his properties
such as apartments and rooms also to add and apply for projects.


 # For Registration Of Properties
   - ![preview](https://github.com/Rahul20je0748/Property-management-system/blob/main/preview1.gif)

-



# For Applying Properties

  -![preview](https://github.com/Rahul20je0748/Property-management-system/blob/main/preview2.gif)


 # Data in MySQL
 -![image](https://github.com/Rahul20je0748/Property-Management-system/blob/main/sql%201.jpg)
 -![image](https://github.com/Rahul20je0748/Property-Management-system/blob/main/sql%202.jpg)


## Instructions For Project Setup
- **Step 1.**
Create new folder and open git bash inside that folder write command-
```
git clone https://github.com/Rahul20je07478/Property-Management-System.git
```
- **Step 2.**
  - Install latest version of python and a code editor (Pycharm or Visual Studio Code).
  - Download & Install MYSQLCLIENT For Python : https://www.lfd.uci.edu/~gohlke/pythonlibs/#mysqlclient open this link and under MySQLclient select the wheel according to your python version and 32/64 bit windows system. 
  - After installing the wheel Open command prompt inside that folder. To open a command prompt window in any folder, simply hold down the Shift key and right-click on the desktop. In the context menu, you will see the option to Open command window here. Clicking on it will open a CMD window.
  
  ![image](https://user-images.githubusercontent.com/64724039/117949549-da2ab980-b32f-11eb-8a26-13178b05864e.png)

  - And write the below command in cmd.

  ![image](https://user-images.githubusercontent.com/64724039/117949687-03e3e080-b330-11eb-8269-d233634fd7c8.png)

- **Step 3.**
   Create a local host connection and click on Server Tab then select Data Import. You can see that there are two options import from self-contained file and import from dump project folder choose the option import from self-contained file and browse to the location where the **property_management.sql** file is present and click on start import which is on the bottom right of this window. Then go to the schemas tab and click on refresh to
   see the new database named **property_management** added. The database setup is completed.

   ![image](https://user-images.githubusercontent.com/64724039/117950541-ea8f6400-b330-11eb-8820-3c5e31ed1eae.png)

- **Step 4.**
   Open the project files in the code editor. Open `main.py` file and if your MySQL username and password are not **root** then you can replace the username and password written in `main.py` file with your MySQL username and password.

- **Step 5.**
  **Installing Packages**

  For Visual Studio Code do the following:
   - Open **New Terminal**

    ![image](https://user-images.githubusercontent.com/64724039/117951623-f7f91e00-b331-11eb-8c7a-2baba835b685.png)

   - And now run the following commands in the terminal:
    ```
    python -m venv env
    Set-ExecutionPolicy Unrestricted -Scope Process
    env\scripts\activate
    pip install flask
    $env:FLASK_APP = "main"
    pip install bcrypt
    pip install flask_mysqldb
    pip install flask_mail
    flask run
    ```
   - Or run `requirements.txt` file :
    ```
    pip install -r requirements.txt
    ```
  For Pycharm code editor do the following:
   - Open the terminal
    
    ![image](https://user-images.githubusercontent.com/64724039/117953503-b2d5eb80-b333-11eb-9a21-f9f08cda86bb.jpg)

   - And run the following commands:
    ```
    pip install flask
    pip install bcrypt
    pip install flask_mysqldb
    pip install flask_mail
    ```
   - Or run `requirements.txt` file :
    ```
    pip install -r requirements.txt
    ```
   - Now run the main.py file and click on the localhost link of the project or go to http://127.0.0.1:5000/ to see  the project.
