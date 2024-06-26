# Ex04 Places Around Me
## Date: 30-03-2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

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

## CODE
## mao.html
```
<html>
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font color="black"><b>UTHANGARAI</b></font>
        </h1>
        <h3 align="center">
            <font color="black"><b>THIRUMALAI (212223040229)</b></font>
        </h3>
        <center>
            <img src="map.png" usemap="#image-map">
            <map name="image-map">
                <area target="" alt="SANKAR CAFE" title="SANKAR CAFE" href="cafe.html" coords="494,99,646,155" shape="rect">
                <area target="" alt="POORVIKA MOBILES" title="POORVIKA MOBILES" href="poorvika.html" coords="378,17,568,77" shape="rect">
                <area target="" alt="SRI VADIVELAN MAHAL" title="SRI VADIVELAN MAHAL" href="mahal.html" coords="227,347,77" shape="circle">
                <area target="" alt="SRIRAM ELECTRICALS" title="SRIRAM ELECTRICALS" href="electricals.html" coords="1208,211,1449,277" shape="rect">
                <area target="" alt="SIVASAKTHI FITNESS" title="SIVASAKTHI FITNESS" href="fitness.html" coords="327,499,517,548" shape="rect">
            </map>
        </center>
    </body>
</html>
```
## cafe.html
```
<html>
    <head>
        <title>CAFE</title>
    </head>
    <body bgcolor="darkblue">
        <h1 align="center">
            <font color="lavender"><b>UTHANGARAI</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>SANKAR CAFE</b></font>
        </h2>
        <hr size="3" color=="red">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Sankar Cafe is one of the most famous hotels at Uthagarai, mainly known for their high quality vegetarian meals that usally be served for lunch. It is a pure vegetarian hotel, which is located at the most crowdiest place of Uthangarai, near Bangalore Highway. The menu at Sankar Cafe boasts a diverse selection of vegetarian dishes, ranging from traditional South Indian specialties like dosas, idlis, and vadas to innovative fusion creations that tantalize the taste buds.The attentive staff ensures that guests feel welcomed and cared for throughout their dining experience, making Sankar Cafe a beloved culinary destination in Uthangarai for locals and visitors alike.
            </font>
        </p>
    </body>
</html>
```
## poorvika.html
```
<html>
    <head>
        <title>MOBILES</title>
    </head>
    <body bgcolor="skyblue">
        <h1 align="center">
            <font color="black"><b>UTHANGARAI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>POORVIKA MOBILES</b></font>
        </h2>
        <hr size="3" color=="cyan">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Poorvika Mobiles is a leading mobile shop nestled in the heart of Uthangarai, offering an extensive range of mobile phones, accessories, and related services. Renowned for its exceptional customer service and wide selection of products, Poorvika Mobiles caters to the diverse needs and preferences of tech enthusiasts and smartphone users in the area. Whether you're looking to upgrade your current device, purchase a gift for a loved one, or explore the latest mobile trends, Poorvika Mobiles is your go-to destination in Uthangarai for all things mobile-related.
            </font>
        </p>
    </body>
</html>
```
## mahal.html
```
<html>
    <head>
        <title>MAHAL</title>
    </head>
    <body bgcolor="orange">
        <h1 align="center">
            <font color="blue"><b>UTHANGARAI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>SRI VADIVELAN MAHAL</b></font>
        </h2>
        <hr size="3" color=="blue">
        <p align="justify">
            <font face="Times New Roman" size="6" color="black">
                Sri Vadivelan Mahal stands as a distinguished venue in the heart of Uthangarai, offering a picturesque setting for a variety of special occasions and events. Nestled amidst serene surroundings, this mahal exudes elegance and charm, providing an ideal backdrop for weddings, receptions, parties, and other gatherings. The mahal boasts spacious and well-appointed halls that can accommodate gatherings of various sizes, from intimate ceremonies to grand celebrations. Moreover, Sri Vadivelan Mahal's convenient location in Uthangarai makes it easily accessible for guests, while its serene ambiance provides a tranquil escape from the hustle and bustle of city life.
            </font>
        </p>
    </body>
</html>
```
## electricals.html
```
<html>
    <head>
        <title>ELECTRICALS</title>
    </head>
    <body bgcolor="pink">
        <h1 align="center">
            <font color="blue"><b>UTHANGARAI</b></font>
        </h1>
        <h2 align="center">
            <font color="green"><b>SRIRAM ELECTRICALS</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="red">
                Sriram Electricals stands as a cornerstone in Uthangarai, providing a comprehensive range of electrical products and services to both residential and commercial customers. With a reputation for reliability and quality, Sriram Electricals is the go-to destination for all electrical needs in the area. At Sriram Electricals, customers can discover an extensive inventory of electrical components, fixtures, and appliances sourced from trusted manufacturers. Moreover, Sriram Electricals also offers installation services, repairs, and maintenance, further enhancing its value proposition for customers.
            </font>
        </p>
    </body>
</html>
```
## fitness.html
```
<html>
    <head>
        <title>FITNESS</title>
    </head>
    <body bgcolor="green">
        <h1 align="center">
            <font color="yellow"><b>UTHANGARAI</b></font>
        </h1>
        <h2 align="center">
            <font color="plum"><b>SIVASAKTHI FITNESS</b></font>
        </h2>
        <hr size="3" color=="plum">
        <p align="justify">
            <font face="Times New Roman" size="6" color="white">
                Sivasakthi Fitness is a gym located in Uthangarai, Tamil Nadu, India. Sivasakthi Fitness is a premier fitness center,dedicated to empowering individuals on their journey towards health and wellness. At Sivasakthi Fitness, members have access to cutting-edge gym equipment, including cardio machines, weightlifting stations, and functional training areas, providing everything needed for a dynamic and effective workout session. The center's spacious and well-ventilated environment creates an inspiring atmosphere conducive to achieving fitness milestones.Beyond its exceptional facilities and personalized training programs, Sivasakthi Fitness fosters a supportive community of like-minded individuals who share a passion for health and fitness.
            </font>
        </p>
    </body>
</html>
```

## OUTPUT

![Screenshot 2024-04-01 142341](https://github.com/Thirumalai23013035/NearMe/assets/153185249/254116f9-01d4-47c0-9682-c6745057cd8e)

![317250116-31c15237-d384-4bbe-b8b4-44838328b794](https://github.com/Thirumalai23013035/NearMe/assets/153185249/66888e00-65af-441e-b26a-961cdb230c96)
![317250386-97407a7b-982b-4432-a8ca-d85d2539b6af](https://github.com/Thirumalai23013035/NearMe/assets/153185249/a94b2c0c-d3ea-4f16-95fc-ac4c2e0e9eb4)
![317250487-8d3e92d0-acf8-46db-8e6f-088a994873a4](https://github.com/Thirumalai23013035/NearMe/assets/153185249/84fed739-74a8-48a9-9ac3-d65ed7f50cba)
![317251086-71c88446-5129-438b-86a0-fd2f1437bd53](https://github.com/Thirumalai23013035/NearMe/assets/153185249/4e876c84-6eec-494e-badc-2019611ef8d7)

![317250251-06830ef9-e101-4f0a-b93c-d631b3cba95e](https://github.com/Thirumalai23013035/NearMe/assets/153185249/20b6c430-09e2-476e-947b-5560822d9212)




## RESULT
The program for implementing image maps using HTML is executed successfully.
