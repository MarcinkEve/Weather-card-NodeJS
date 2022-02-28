# Atkurti dizainą dinaminiu būdu:

## Sukurkite objektą "weather" su šiais indeksais:

status,
degrees,
feeling,
humidity
 
Status gali turėti šias reikšmes:
"Broken Clouds", "Mostly Sunny"
Atsitiktinai parinkite vieną iš jų.
Degrees reikšmei generuokite atsitiktinį skaičių nuo 10 iki 25.
Feeling reikšmei skaičių nuo 13 iki 27.
Humidity reikšmei skaičių nuo 50 iki 90.
Visas reikšmes perduokite į frontend sekciją iš backend naudojantis fetch() funkcija.
Priklausomai nuo statuso parinkite atitinkamą paveiksliuką.
 
 ![](frontend/img/MicrosoftTeams-image.png)

 # Install

 ### FRONTEND

Run file:

- in current directory open new terminal and write in console
 
 <!-- > npm i -D dead-server -->
 > npm i

 > npm run dev

This will start live server at port 3000 where browser renders weather forecast website.


 ### BACKEND

It runs on it's own server at `http://localhost:3001`

 Run file:

- in current directory open new terminal and write in console

 <!-- > npm i express

 > npm i --save-dev nodemon

 > npm i cors -->
 > npm i

 > npm run start
