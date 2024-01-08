/** Swiggy API Issue**/

E6.1 P1 - TOPICS

There could be different APIs as it is a production API - Swiggy API
Fetch/XHR -> will give us all the API calls
All -> Provides all the URLS including photos, APIs etc.

Under Header if you check we can see the APIs
https://www.swiggy.com/dapi/restaurants/list/v5?lat=13.0632293&lng=77.58211849999999&is-seo-homepage-enabled=true&page_type=DESKTOP_WEB_LISTING

How do we get the data out of it?

> card is a array object list
> All the best offers are coming from the first object
> We have to stay updated with the APIs
> This is how we break it down further:

json.data.cards[5].card.card.gridElements.infoWithStyle.resturants

earlier the key name was resturant.data.id but now it is changed to resturant.info.id
