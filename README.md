# Notes Management Application
This application was created using Next as framework in the frontend and other technologies such as:

- react
- styled-components
- react-icons
- hooks
- context
- react-hot-toast
- python
- django
- MySQL

To use this application, copy the repository to your computer and then proceed to install the packages so that you can run the application.

## Implementing database

### Database
Is necesary first create a dabatebase in MySQL with the name "notes_management_djang" this allow to do the migration and the conection

#### Recommended
Use XAMPP and PHPmyAdmin to easier handle

# Backend 
- Go to the folder named "Notes Management API"

        cd Notes_Management_API

- Run the python manage.py makemigrations command to detect possible changes to migrations. It doesn't matter if you don't find changes.

        python manage.py makemigrations
    
- Ahora procede a realizar la migracion a la base de datos con el siguiente comando "python manage.py migrate"

        python manage.py migrate

If you have an error is possibl that you forgot create the database or the name is wrong

- Now is time to run the server with the next command

        python manage.py runserver

- You will see the next message "Watching for file changes with StatReloader
"

# Frontend

If you are inside the "Notes Management API" folder, you need to go up one level in the direction with the following command

    cd ..

If you are not sure where you are use the following command depending on the console you are using

        git bash: ls
        cmd: dir

Now install all the dependencies using the following command

Using npm to install: 

    npm install

An finally to execute the application use the nex command
    
Run the application:

    npm run dev
