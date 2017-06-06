## project proposal

### What problem will be solved for the user?
Deze app kan handig zijn voor mensen die het lastig vinden om schoolwerk te plannen: wat moet ik allemaal doen, hoeveel tijd ben ik er ongeveer aan kwijt en hoe zou ik dit dan moeten verdelen over mijn dagen waarbij ik rekening houd met wat ik al op de planning heb staan. 

### What features will be available to solve the problem?
* De app wordt gekoppeld aan een Google Calendar. 
* Een extra feature van deze app is de To do list. Deze lijst bestaat uit hoofditems (vakken bijvoorbeeld) en daaronder subitems (de verschillende dingen die zouden moeten gebeuren - het lezen van een hoofdstuk, het lezen van een artikel, schrijven van een essay). 
* In het hoofdmenu kan de user instellen hoeveel tijd hij/zij kwijt is of kwijt wilt zijn aan het lezen van een artikel of het schrijven van een essay. Bij het invoeren van de subitems kan de user aangeven waar het om gaat (een artikel, een essay) of kan de user iets nieuws toevoegen.

### A visual sketch of what the application will look like for the user; if you envision the application to have multiple screens, sketch these all out separately.

![](doc/image.JPG)

### What data sets and data sources will you need, how you will get the data into the right form for your app?
Ik ga de GoogleCalendar API gebruiken, en als het niet teveel is ook de Giphy API. Hoe ik de data er goed in krijg, zal ik hier uit halen: 
* [Google Calendar](https://developers.google.com/google-apps/calendar/quickstart/android)
* [Giphy](https://github.com/Giphy/GiphyAPI)

### What separate parts of the application can be defined (decomposing the problem) and how these should work together.
Eerst dus de main screen, waar het volgende op staat:
##### My calendar
* Een overzicht van Google Calendar + items uit de list
* Door te kijken naar wat iemand al te doen heeft, wat diegene nog allemaal moet doen, wanneer dit af moet zijn en 
##### To do
* Dit bestaat uit twee verschillende lijsten
* Een main iets zoals bijvoorbeeld “schrijven van scriptie”
* En subitems: welke artikelen moeten worden gelezen, hoeveel tijd is daarvoor nodig
##### SOG
* Hier komt standaard een random GIF te staan
* Daarnaast rechtsbovenin een optie om een bepaald soort GIF op te zoeken (happy, party etc.) en hier ook een optie om te refreshen en een andere random GIF te zien.
  
### Which external components (online APIs, libraries etc.) you will need to make certain features possible (name and URL link).
Ik ben van plan om een Google Calendar API te gebruiken, maar moet nog even uitzoeken of dit wel zo makkelijk is: of mensen makkelijk kunnen inloggen in hun Google Calendar in de app. En een Giphy API.

### Technical problems or limitations that could arise during development and what possibilities you have to overcome these.
Waar ik op zou moeten letten is dat ik het mij niet te moeilijk maak met al deze verschillende dingen. Want het zijn wel twee verschillende API’s die ik ga gebruiken, ik weet nog niet zo goed of dit teveel kan zijn en kan leiden tot het crashen van de applicatie. In dat geval zou ik de SOG tab weglaten en hier iets anders voor moeten verzinnen. 
Verder denk ik niet dat er veel problemen kunnen zijn. Maar als er iets niet lijkt te werken of als er teveel tijd in gestoken moet worden, dan denk ik dat het handig is om er dan voor te kiezen om een stapje terug te gaan en een simpele vervanging te zoeken. 

### A review of similar mobile apps, in terms of features and technical aspects: what do they offer? how have they implemented it? can you do it in the same way?
Er zijn wel wat apps die hetzelfde doen.
#### [To-Do Calendar Planner](https://play.google.com/store/apps/details?id=com.timleg.egoTimerLight)
Zelfde als Google Calendar en daarbij is progression zichtbaar.
#### [Any.do: To-do list & Calendar](https://play.google.com/store/apps/details?id=com.anydo)
Maar deze zijn niet gericht op studenten en het studeren. 
#### [Schedule Planner Classic](https://play.google.com/store/apps/details?id=com.intersog.android.schedule)
Ik zou hier wel wat ideeën uit kunnen halen als het gaat om het totale overzicht (My Calendar) en het weergeven van de To do list. Ik denk dat het zichtbare gedeelte wel overeenkomt. Alleen dat de app zelf gaat berekenen wanneer dingen gedaan moeten worden om op tijd klaar te zijn met een opdracht of met het lezen van artikelen is wel iets wat mijn app anders maakt. 

### Which parts of the application define the minimum viable product (MVP) and which parts may be optional to implement.
MVP is wel het My Calendar, de To do list en de Settings. Want hier draait het allemaal om. Het toevoegen van de GIFs is iets extra’s. Andere dingen die ook grappig zijn om toe te voegen is een stopwatch die een user kan gebruiken om te bepalen hoelang hij/zij bezig is met het lezen van een artikel van n pagina’s. En een progressbar: hoeveel moet de user nog doen gezien de To do list en hoeveel heeft hij/zij al gedaan (kan voor motivatie zorgen).
