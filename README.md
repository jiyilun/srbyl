# srbyl
## Project Description

1. Search for restaurants nearby[SearchRestaurants], given lat, lon, return a list of restaurant object.
    * Package:api

    * className:SearchRestaurants
    
    * URL pattern:[/restaurants], http method:[Get]
    
    <img width="1394" alt="screen shot 2017-08-16 at 11 16 51 pm" src="https://user-images.githubusercontent.com/10042885/29398565-2be94fdc-82da-11e7-8213-b6ee535b413d.png">
    
2. Recommend restaurants for the user, given the user id, return a list of recommended restaurants objects.[RecommendRestaurants]


    * URL pattern:[/recommendation], http method:[Get]
    
    <img width="1374" alt="screen shot 2017-08-16 at 11 23 07 pm" src="https://user-images.githubusercontent.com/10042885/29398508-f8e0c1ec-82d9-11e7-8a2c-679335eca0f3.png">
    
1. Set/Unset favorite restaurants for the uses, given the user id and a list of favorite restaurants ids, return status[ok or error].

    * URL pattern:[/history], http method:[POST]
    
   <img width="1395" alt="screen shot 2017-08-16 at 11 14 56 pm" src="https://user-images.githubusercontent.com/10042885/29398525-03f0b9b6-82da-11e7-97ab-86d010702d6d.png">


