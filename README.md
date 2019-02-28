# RestaurantFinder
This application can be used to know the top restaurants and cuisines available at any location user wants to know.
Note: As am using Zomato api to retrieve data,this app will be able to show only restaurants from places where zomato provides their services.😃

how to use:-
     once user entered the location he prefers and press search button app will retrieve data from zomato database and displays cuisines available at that location and a list of top restaurants from that place.if user clicks on cuisines he will be redirected to cuisinesearch activity and app will display restaurants based on the cuisine user prefers🍲🍕.
  if user clicks on a restaurant image then he will be redirected to detail activity where user can know address,avgcost for two,price range,rating and reviews of restaurant(as api provides only 5 reviews for restaurant only those will be displayed),user can also know the precise location of the restaurant by clicking on provides locate (fab icon),which will redirect him to map activity to mark the location of restaurant📍.
  
  user can mark restaurant favourite❤ and the details of restaurant will be stored in room database and retrieved using LiveData.
  the details of last visited restaurant will be shown in the homescreen widget.
  😊😊
