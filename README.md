# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:
## Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp.

## Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

## Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

## Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

## Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py.
## Code:
Include your HTML code here
## map.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>
            Image Map
        </title>
    </head>
    <body >
        <h1 align="center" >
            <font color="red" >
                    SAVEETHA UNIVERSITY
            </font>


            
        </h1>
        <h3 align="center">
        <font color="blue">
            BARATHRAJ B(212222230019)
        </font>
            
        </h3>
        <center>
            <img src="/static/image/map.png" usemap="#image-map">
            <map name="image-map">
            <area  alt="" title="Saveetha college of Architecture" href="SCAD" shape="rect" coords="378,52,428,102" style="outline:none;" target="_self"     />
            <area  alt="" title="Saveetha Engineering College" href="SEC" shape="rect" coords="570,358,620,408" style="outline:none;" target="_self"     />
            <area  alt="" title="Saveetha college of Nursing" href="http://www.image-maps.com/" shape="rect" coords="212,399,262,449" style="outline:none;" target="_self"     />
            <area  alt="" title="SIMATS" href="Simats" shape="rect" coords="709,338,759,388" style="outline:none;" target="_self"     />
            <area  alt="" title="Saveetha medical college" href="SMA" shape="rect" coords="762,646,812,696" style="outline:none;" target="_self"     />
            <area shape="rect" coords="1484,789,1486,791" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
            </map>




        </center>
        <p align="center">
            <font color="maroon"  face="Comic Sans MS" >
                This Image Map shows various locations around my home.<br>
                Click the location and get information about it.
            </font>
        </p>


    </body>
</html>
```
## sec.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>SEC</title>
    </head>
    <body bgcolor="yellow">
        <h1 align='center'>SAVEETHA ENGINEERING COLLEGE</h1>
        <center>
          <img src ="/static/image/sec.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
         Saveetha Engineering College (SEC) was established in 2001, by the Founder Chairman Dr. N. M. Veeraiyan, a committed and 
         dedicated Medical Professional.SEC has a total strength of 4349 students in 15 UG courses, 8 PG Courses including MBA, MS by 
         Research and Doctoral programs (PhD)  in five Departments.National Board of Accredition NBA has Accredited 5 UG courses.Ranked 
         96 by NIRF- National Institute Ranking Framework for the academic year 2017-18 among all IITs, Central, State and Private Institutions 
         in India. Awarded 'A' GRADE with a high score of 3.19 on a scale of 4 by the National Assessment and Accreditation Council (NAAC) for 
         5 Years.SEC awarded AUTONOMOUS status by the UGC from the academic year 2019-2020. SEC is recognized as a Scientific and Industrial 
         Research Organization (SIRO) by the Department of Scientific and Industrial Research (DSIR), Government of India.
</p>
    </body>

</html>
```
## sse.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>SSE</title>
    </head>
    <body bgcolor="green">
        <h1 align='center'>SAVEETHA SCHOOL OF ENGINEERING</h1>
        <center>
          <img src ="/static/image/sse.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
        Saveetha School of Engineering (SSE) Chennai, is a private institution, affiliated to AICTE, established in 2005, 
        located in the Chennai city of Tamil Nadu state. It is accredited NAAC ‘A’ Grade and got recognition by 43rd rank 
        in NIRF. SSE is one of the 80 universities around the globe which get the IET-UK Accreditation. The college promises 
        for being one of the best engineering colleges in India by keeping high standards of quality education in engineering 
        fields. Under Saveetha School of Engineering Admissions 2019, the college offers some full time Undergraduate, Postgraduate 
        and Doctoral programs in many departments. Each department is enriched with experienced, dedicated and knowledgeable faculty 
        members. With extra-ordinary infrastructure facilities and with innovative teaching methods like MILA, Flipped Classes, etc., 
        SSE provides the best platform for the students to excel in their academics. 
</p>
    </body>

</html>
```
## scad.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>SCA</title>
    </head>
    <body bgcolor="red">
        <h1 align='center'>SAVEETHA COLLEGE OF ARCHITECTURE</h1>
        <center>
          <img src ="/static/image/scad.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
            Saveetha College of Architecture and Design (SCAD), SIMATS is one of the premier Architecture institutes
            located in Chennai, Tamil Nadu. The Collegeis a constituent unit of Saveetha College of Medical and Technical 
            Sciences (SIMATS). SCAD was set up with a vision to improve standards in Architecture education, promote high-quality 
            research in the field and play a key role in constructing sustainable buildings. The Collegeoffers BArch as its only
            academic programme. With emphasis on practical experience, SCAD Chennai helps its students with innovative expression, 
            research, critical thinking, and creative exploration. It has collaborations with popular international universities and
            has signed MoUs (Memorandums of Understanding) with Penn State University, Gachon University and several other international
            universities. SCAD provides opportunities to take credit courses and involve in trans-disciplinary projects from Medical, 
            Dental and Engineering streams.
        </p>

    </body>

</html>
```
## simats.html
```
<!DOCTYPE html>
<html>
    <head>
        <title>SIMATS</title>
    </head>
    <body bgcolor="lightblue">
        <h1 align='center'>SAVEETHA INSTITUTE OF MEDICAL AND TECHNICAL SCIENCE </h1>
        <center>
          <img src ="/static/image/simats.png"  height="300" width="600" align="center" >
        </center>
        <p style="font-size: 24px">
        Saveetha Institute of Medical And Technical Sciences Chennai also known as SIMATS CHENNAI, is a Deemed to be University 
        situated in Chennai, Tamil Nadu. SIMATS CHENNAI was established in the year 2005. Its campus is spread over 150 Acres of 
        land. SIMATS CHENNAI is accredited by NAAC A. SIMATS CHENNAI offers admission in various courses like BA LLB (HONS.), 
        BBA + LLB (H), BDS, BE, BOT, B.P.Ed, BPT, BSc, B.Tech, DIP DENT, DIP DH, DIP DM, FFESS,  LL.D., LLM + Ph.D, MBA , MBBS, 
        M.CH, ME, M.Phil. (SCI), MPT, MS, PGDM, PhD Arts, Ph.D DENT, Ph.D. ENG, Ph.D MED, Ph.D (MGMT), Ph.D. (SCI). Various 
        Facilities provided by SIMATS CHENNAI are Medical Support Systems, Gym, Sports Complex, Library & Information Center, 
        Practical Lab, IT Centers, Auditorium, Canteen, Girls Hostel, Boys Hostel and etc. SIMATS CHENNAI is run by Saveetha Medical 
        and Educational Trust
        </p>
    </body>

</html>
```
## Output:
## server output
![WhatsApp Image 2023-06-07 at 9 12 17 PM](https://github.com/bharathraj1905/places-around-me/assets/121490575/c9d69aa4-f656-4eb9-ad73-8fb286ebcceb)



## client output
![WhatsApp Image 2023-06-07 at 8 54 46 PM (5)](https://github.com/bharathraj1905/places-around-me/assets/121490575/b7f7b427-a403-43fa-bdf4-01d962919d8c)
![WhatsApp Image 2023-06-07 at 8 54 46 PM (4)](https://github.com/bharathraj1905/places-around-me/assets/121490575/5714dfd3-677b-4e91-8c48-314573a2dbac)
![WhatsApp Image 2023-06-07 at 8 54 46 PM (3)](https://github.com/bharathraj1905/places-around-me/assets/121490575/6839676b-341c-4d51-a825-59efb9f471cc)
![WhatsApp Image 2023-06-07 at 8 54 46 PM (1)](https://github.com/bharathraj1905/places-around-me/assets/121490575/6358fae2-8cff-4bf0-87b0-f4276d32b79e)
![WhatsApp Image 2023-06-07 at 8 54 46 PM (2)](https://github.com/bharathraj1905/places-around-me/assets/121490575/2d171088-3882-449b-9488-f5e675f75be3)

## html validator
![WhatsApp Image 2023-06-07 at 8 58 08 PM](https://github.com/bharathraj1905/places-around-me/assets/121490575/e0c53480-795b-40b0-908b-f8b77fb503d4)


## Result:
Thus the code has been executed successfully.
