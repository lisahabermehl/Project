# Design Document
Hier wordt er specifiek ingegaan op hoe de technische delen van de app samenhangen. 

## MainActivity.java
Dit zal waarschijnlijk gewoon het inlogscherm zijn. Hier wordt FireBase voor gebruikt, kan dit voor een groot deel overnemen van [Problem set 6](https://github.com/lisahabermehl/lisahabermehl-pset6).

## MyCalendar.java
Hoe dit er precies uit komt te zien ben ik dus nog niet helemaal uit. 
Ik ga morgen weer verder met uitzoeken hoe de Google Calendar API hier gebruikt kan worden. 

### my_calendar.xml
Hier wordt de [CalendarView](http://abhiandroid.com/ui/calendarview) voor gebruikt, waarbij de user een popup met de TODO's van die dag te zien krijgt bij het klikken op de desbetreffende dag.

## ToDo.java
Zal voor een groot deel uit [Problem set 4](https://github.com/lisahabermehl/lisahabermehl-pset4) komen. 
* onCreate
* onCreateOptionsMenu
* onOptionsItemSelected
* updateUserInterface
* deleteToDo
## Helper.java
* SQLite shizzle

### activity_main.xml 
ListView

### to_do.xml
TextView die in de bovenstaande ListView komt te staan
