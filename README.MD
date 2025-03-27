 ## Máv utastájékoztató

 
 Ez a projekt egy egyszerű webes felületet biztosít a MÁV vonatindulások és érkezések megjelenítésére. A weboldal HTML és CSS segítségével készült, és egy táblázatos formátumban jeleníti meg az aktuális menetrendet.
![alt text](github_logo.png)

## Funkciók
🚉 Induló és érkező vonatok listázása táblázatban 
<br>⏰ Állomás, indulási és érkezési idők megjelenítése</br>
🎨 Felhasználóbarát, letisztult dizájn
## Használat
Egyszerűen nyisd meg a https://github.com/BulyakiBence/2025_01_30_MAV_utastajekoztato weboldalt a böngészőben, és a rendszer betölti az aktuális adatokat.

## Élő demó
A projekt élőben megtekinthető az alábbi linken:
https://bulyakibence.github.io/2025_01_30_MAV_utastajekoztato/ 
🏗️ Alap HTML szerkezet
<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MÁV Utastájékoztató</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h1>MÁV Utastájékoztató</h1>
    <table>
        <tr>
            <th>Vonat</th>
            <th>Indulás</th>
            <th>Érkezés</th>
            <th>Állomás</th>
        </tr>
        <tr>
            <td>1234</td>
            <td>12:30</td>
            <td>14:00</td>
            <td>Budapest</td>
        </tr>
    </table>
</body>
</html>
🎨 CSS Stílusok
body {
    
    background-color:rgb(25, 163, 25);
    text-align: center;
}

table {
    width: 80%;
   
    border-collapse: collapse;
}
🔧 Fejlesztési lehetőségek
 🔄 Dinamikus adatbetöltés API-n keresztül
 🔍 Keresési és szűrési lehetőségek
 📱 Reszponzív megjelenítés mobileszközökre