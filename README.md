# kumpuldimana
python web app. with flask and mysql

backend : python

database : postgresql

      command line :
      - /q %quit
      in app command :
      CREATE TABLE <name_table> ( <name_col> <DATA_TYPE> )
      

framework : django (single web app page)

      - command line : django-admin startproject <nama>
      - python3 manage.py runserver
      - python3 manage.py startapp <name>
      - python3 manage.py migrate %add data to database
      - python3 manage.py makemigrations <name_of_app> %make model in /app/migrations
      - python3 manage.py sqlmigrate <app_name> 0001
      - python3 manage.py check %this checks for any problems in your project without making migrations or touching the database.
      - python3 manage.py createsuperuser
      
      
Making Model change: 
1. Change your models (in models.py).
2. Run python manage.py makemigrations to create migrations for those changes
3. Run python manage.py migrate to apply those changes to the database.

frontend template : react

html/css : bootstrap
template : bootswatch

date : https://www.reddit.com/r/reactjs/comments/4yhk9a/airbnb_open_source_react_date_picker/

Tutorial : 
1. HTML/CSS : https://www.youtube.com/watch?v=5GcQtLDGXy8

https://realpython.com/blog/python/flask-by-example-part-1-project-setup/
https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world
https://www.reddit.com/r/learnpython/comments/2lk6lj/how_to_implement_a_web_calendar/

https://www.youtube.com/watch?v=zYHv6U86X0Y

HTML cheat sheet : http://www.simplehtmlguide.com/cheatsheet.php


features :
- doodle like webapp

- poling berdasarkan :



      1. Kota
      2. Waktu https://github.com/Serhioromano/bootstrap-calendar https://fullcalendar.io/
      3. Nama Voter
      4. jenis : resto, cafe, other(cinema dll.)
      
- Setelah vote akan ada uniq reshareable link buat partisipan lain.
- Setelah semua partisipan vote. dan hasil ditentuin. 5 pilihan terbaik muncul.

- LINE API, FB messenger API : setelah ditentuin. user option notifikasi lewat line atau facebook messenger dari API sebelum hari h. dll. https://developers.line.me/messaging-api/overview
  https://developers.facebook.com/docs/messenger-platform
- data restoran diambil dari Zomato API https://developers.zomato.com/documentation#/

# function flow:
1. input nama
2. select Map (daerah) https://www.wired.com/2014/07/a-drag-and-drop-toolkit-that-lets-anyone-create-interactive-maps/
3. select range waktu.
..... %TODO


test1234121213134124sdfsfs
