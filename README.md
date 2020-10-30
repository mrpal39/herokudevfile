# herokudevfile
heroku dev file template


echo "# heroku" >> README.md

git init


git add .
git commit -m "update"


git push -u origin main

git add README.md

git branch -M main



git remote add origin git@github.com:mrpal39/herokudevfile.git

git push -u origin main
                
pip install python-decouple


heroku run python3 manage.py migrate
heroku run python3 manage.py createsuperuser
heroku run python3 manage.py runserver
