# Ex04 Places Around Me
## Date: 

## AIM:
To develop a website to display details about the places around my house.

## DESIGN STEPS:
### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## PROGRAM:
### MAP.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: rgb(174, 214, 243);">
    <h1 style="color: rgb(0, 0, 255);"><b>MADIPAKKAM</b></h1>
    <img src="MAP.png" width="80%" height="60%" usemap="#MapNew" ><br>
    <MAP name="MapNew">
         <AREA shape="circle" coords="321,111,50" href="SivaVishnuTemple.html" Title="Siva Vishnu Temple"> </AREA>
         <AREA shape="circle" coords="334,485,69" href="Turf.html" Title="FC Meena Turf"> </AREA>
         <AREA shape="circle" coords="747,462,63" href="School.html" Title="Velammal New Gen School"> </AREA>
         <AREA shape="circle" coords="955,46,52" href="Game.html" Title="E3 Gaming Store"> </AREA>
         <AREA shape="circle" coords="1121,519,54" href="RE.html" Title="Royal Enfield Show Room"> </AREA>       
    </MAP>
    <h2 style="color: rgb(0,0,255);"> DHARSHINI K - 212223230047</h2>
</body>
</html>
~~~

### Game.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: rgb(207, 125, 123);">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: rgb(87, 16, 16);"><b>E3 GAMING STORE</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: rgb(87,16,16); ">(Madipakkam,Chennai-600091)</h2>
    <p style="font-style: italic;color: rgb(7, 3, 127);font-size: 25px;">
        E3 Sports near Madipakkam is a well-known sports academy dedicated to providing comprehensive training in various athletic disciplines. The academy offers professional coaching in sports like cricket, football, badminton, and basketball, with a focus on both skill development and fitness. The facilities at E3 Sports are designed to cater to athletes of all levels, from beginners to advanced players, with well-maintained grounds, courts, and equipment.

The coaching staff consists of experienced trainers who emphasize technique, physical fitness, and sportsmanship. They create a positive and motivating environment where individuals can hone their athletic skills and improve their performance. E3 Sports also conducts regular tournaments and practice sessions to help students gain competitive exposure.
        </p>
    <p style="font-style: italic;color: rgb(7,3,127);font-size: 25px;">Apart from sports training, the academy promotes the overall well-being of its participants, encouraging a healthy and active lifestyle. Whether one is training for professional sports or looking for recreational activity, E3 Sports provides a structured and engaging platform for growth. Its well-organized programs are designed to build confidence, teamwork, and leadership qualities in all participants. </p>
</body>
</html>
~~~

### RE.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: rgb(0, 0, 0);">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: rgb(255, 255, 0);"><b>ROYAL ENFIELD SHOW ROOM</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: rgb(255,255,0); ">(Velachery,Chennai-600042)</h2>
    <p style="font-style: italic;color: rgb(255, 255, 255);font-size: 25px;">
        The Royal Enfield showroom near Madipakkam is a popular destination for motorcycle enthusiasts, offering a range of iconic Royal Enfield models known for their classic design, powerful performance, and timeless appeal. The showroom provides a welcoming atmosphere for both potential buyers and motorcycle aficionados, with a display of models like the Bullet, Classic, Himalayan, and Meteor.

        The staff at the showroom are knowledgeable and attentive, helping customers choose the right bike based on their preferences and needs. They provide detailed information on specifications, features, and performance to ensure that buyers make informed decisions. In addition to new motorcycle sales, the showroom also offers services like test rides, financing options, and insurance assistance. </p>
    <p style="font-style: italic;color: rgb(255, 255, 255);font-size: 25px;">The service center associated with the showroom is equipped with modern tools and trained mechanics to ensure that motorcycles receive top-notch maintenance and repairs. Genuine Royal Enfield parts and accessories are also available, making it a one-stop destination for all Royal Enfield-related needs.
    </p>
</body>
</html>
~~~

### School.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: darkslateblue;">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: rgb(255, 253, 105);"><b>VELAMMAL NEW GEN SCHOOL</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: rgb(255,253,105); ">(Madipakkam,Chennai-600091)</h2>
    <p style="font-style: italic;color: rgb(0, 255, 251);font-size: 25px;">
        Velammal New Gen School in Pallikaranai is a part of the renowned Velammal group of educational institutions, known for its commitment to academic excellence and holistic development. The school offers a dynamic learning environment that focuses on both intellectual growth and character building. It follows a modern curriculum that emphasizes experiential learning, innovation, and technology integration, ensuring students are well-prepared for future challenges.
        
        The campus is equipped with state-of-the-art facilities, including well-furnished classrooms, science and computer labs, a well-stocked library, and spaces for extracurricular activities like sports, music, and art. Teachers at Velammal New Gen School are highly qualified and dedicated to fostering a nurturing atmosphere where students are encouraged to excel academically and personally.
        
        </p>
    <p style="font-style: italic;color: rgb(0,255,251);font-size: 25px;">In addition to academics, the school places great importance on values such as discipline, respect, and teamwork, creating an environment conducive to holistic growth. The school organizes various programs, competitions, and events to nurture leadership qualities and enhance student potential.
    </p>
</body>
</html>
~~~

### SivaVishnuTemple.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body style="text-align: center;background-color: darkslateblue;color: wheat;">
    <h1 style="font-family: 'Times New Roman', Times, serif;"><b>SIVA VISHNU TEMPLE</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;">(Madipakkam,Chennai-600091)</h2>
    <p style="font-style: italic;font-size: 25px;">
        The Siva Vishnu Temple in Madipakkam, Chennai, is a renowned place of worship dedicated to both Lord Shiva and Lord Vishnu. This unique combination of deities in one temple makes it a popular destination for devotees of both sects in Hinduism. 
        The temple is beautifully structured, reflecting traditional South Indian architecture with intricate carvings and vibrant gopurams (towering gateways).

The main sanctum houses idols of Lord Shiva and Lord Vishnu, along with other deities like Lord Ganesha, Goddess Parvati, and Lord Hanuman. The temple holds daily poojas and special rituals during festivals like Maha Shivaratri, Vaikunta Ekadasi, and Navaratri, attracting large crowds. 

Its serene environment and spiritual ambiance offer devotees a peaceful space for prayer and meditation. Located conveniently in the residential area of Madipakkam, the temple also engages in community activities and supports cultural and religious events, contributing to the social and spiritual fabric of the neighborhood.
    </p>
</body>
</html>
~~~

### Turf.html
~~~
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body style="text-align: center; background-color: blanchedalmond;">
    <h1 style="font-family: 'Times New Roman', Times, serif; color: darkgoldenrod;"><b>FC MEENA TRUF</b></h1>
    <h2 style="font-family: 'Times New Roman', Times, serif;color: darkgoldenrod; ">(Madipakkam,Chennai-600091)</h2>
    <p style="font-style: italic;color: darkgreen;font-size: 25px;">
        FC Meena Turf in Madipakkam, Chennai, is a popular sports facility known for its well-maintained artificial turf, designed for football enthusiasts. The turf provides a perfect venue for both casual players and serious athletes to engage in the sport, offering a high-quality playing surface that mimics natural grass.
        
        The facility is equipped with floodlights, making it ideal for evening and nighttime matches. FC Meena Turf regularly hosts local football tournaments, corporate events, and training sessions for players of all ages. It is also available for hourly bookings, allowing individuals and groups to reserve the space for friendly games or practice.</p>
    <p style="font-style: italic;color: darkgreen;font-size: 25px;">Conveniently located in the Madipakkam area, the turf has become a hub for the local football community, fostering a healthy and active lifestyle. The facility ensures safety and comfort, with ample parking space and basic amenities like restrooms and seating areas for spectators. Its focus on promoting football and fitness has made FC Meena Turf a go-to spot for sports lovers in and around Madipakkam.</p>
</body>
</html>
~~~

## OUTPUT:
### MAP
![image](https://github.com/user-attachments/assets/9cc8cdab-8cde-4e2a-9603-3fe3b3578145)

### Game
![image](https://github.com/user-attachments/assets/abd84698-3508-4a9a-a3bc-ae9c3fd244c7)

### RE
![image](https://github.com/user-attachments/assets/86e9603c-a3a2-49ce-8203-e1b2287eaea2)

### School
![image](https://github.com/user-attachments/assets/3bc63ecd-186b-465b-a30e-bab8ab19ff59)

### SivaVishnuTemple
![image](https://github.com/user-attachments/assets/a9e9cb9b-15e5-4160-a8cc-f49deab13bfa)

### Turf
![image](https://github.com/user-attachments/assets/77f17146-3d92-4f65-a4cd-7b5358f7cda5)

## RESULT:
The program for implementing image maps using HTML is executed successfully.
