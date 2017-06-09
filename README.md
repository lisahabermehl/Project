# This is the old version, the new one can be found over here: [Calendar](https://github.com/lisahabermehl/Calendar)
## Project proposal

### Goal
This app might be handy for people who have a hard time planning their schoolwork: what am I supposed to do, how much time do I have and what is the best way to spread this over the days while ik rekening houd met wat ik al op de planning heb staan. To help the user in all of these things the following tools are available in the app:
* The app will be connected to your own Google Calendar. It's not possible to edit activities in the Google Calendar whilst your in the app, the goal of the app is simply to give an overview of everything that is on the Todo list but still has to be fit into the existing calendar.
* An extra feature of this app is the Todo list. This list exists of the so called main items (course) and subitems (the different things that have to be done for this course - reading a chapter, reading articles, writing an essay). When adding all these subitems, the user has the option to give an estimation of time to spend on this subitem (or the user can enter how many pages he/she is has to read)
* In the settings the user can install how much time he/she spends on reading one page or how much time he/she wants to spend on writing an essay and how many days should be planned for this. 

### Visual sketch

![](docs/image.JPG)

### How does it work?
Firstly there will be a login screen where the user can log in with Firebase. The idea for using this is that the Todo list items can be stored in Firebase's database. But since it's not really necessary and since it's also possible to do this with the SQLite database, I'll probably skip this login option. After logging in (or not  ;)) the user will end up in the Calendar. 
##### My calendar
* An overview of Google Calendar AND the items from the Todo list
* The items from the Todo list will be added considering the following things: when the subitem has to be done, how time the user will probably spend doing it (looking at the amount of time spend on reading one page, how many pages have to be read), what activities are already on the calendar

##### To do
* Consists of two different lists: a main list (courses), a sublist (things that need to be done for a specific course)
* Main list, like: writing a thesis, a programming project
* Sublist, like: what articles need to be read

##### SOG
* Shows a random GIF.
* But there's also an option to look for a certain GIF (happy, party etc.) and a option to refresh the screen and see another random GIF.

### APIs and such
* [Google Calendar](https://developers.google.com/google-apps/calendar/quickstart/android)
* [Giphy](https://github.com/Giphy/GiphyAPI)

### Things to keep in mind
* I have to make sure that I won't make everything more difficult by using all of these different things. Because I'm planning on using two different API's, I'm not sure if this will make things more complicated, especially since I only have four weeks to make this app. In that case I would probably leave the SOG tab out and think about something simpler.
* Making a sublist might take a lot of time, if it takes too much time to make this I'll probably magically transform it in a one-list-thing.
* Thinking about a right algoritm that will plan the Todo things in a way that makes sense and is humanely possible might take a lot of time as well.
* And for everything else that seems to be taking more time than expected: think about if this is really necessary or can be replaced by something simpler.


### MVP and dreams
MVP is My Calendar, the Todo list and the Settings. Because this is what it's all about; based on these three things the algoritm can plan the Todo items in the existing Calendar while using all the user characteristics that have been set in the Settings. Things that might make the app more fun are: GIFs, a stopwatch that the user can use to determine how much time he/she is spending on reading one page, a progressbar - how much have I done, how much do I have to do when looking at the Todo list.

### Similar apps
There are a couple of apps that, in one way or another, try to do the same thing
#### [To-Do Calendar Planner](https://play.google.com/store/apps/details?id=com.timleg.egoTimerLight)
* Same as Google Calendar.
* Shows progression.
#### [Any.do: To-do list & Calendar](https://play.google.com/store/apps/details?id=com.anydo)
* But this isn't focused on studying, the user just adds things to the Todo list and this will be added to a calendar?
#### [Schedule Planner Classic](https://play.google.com/store/apps/details?id=com.intersog.android.schedule)
* Could use some ideas from this app when it comes to having an overview of everything (My Calendar) en displaying the Todo list.
#### Over all
I think that the visible part will be the same for most apps. But the thing that distinguishes my app from all the other Planning/Calendar/Todo apps is the fact that my app will calculate and add tasks to your calendar to make sure that you'll be done on time with reading articles or writing an essay. 
