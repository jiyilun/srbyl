# srbyl
## Project Description

1. Search for restaurants nearby[SearchRestaurants], given lat, lon, return a list of restaurant object.
    * Package:api

    * className:SearchRestaurants
    
    * URL pattern:[/restaurants], http method:[Get]
    
2. Recommend restaurants for the user, given the user id, return a list of recommended restaurants objects.[RecommendRestaurants]


    * URL pattern:[/recommendation], http method:[Get]
    
1. Set/Unset favorite restaurants for the uses, given the user id and a list of favorite restaurants ids, return status[ok or error].

    * URL pattern:[/history], http method:[POST]
