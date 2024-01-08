/** CORS Issue**/

E6.2 P1 - TOPICS

Without the CORS issue the application doesnt work

How do we make tha app work without the CORS plugin?

Website - https://corsproxy.io/
Browser doesnt allow if the domains dont match

How do we use the corsproxy.io?
we copy this "https://corsproxy.io/?" and paste it before our URL

Now we are not directly connecting to the Swiggy website, we are calling the corsproxy which is making an api call internally
and getting us the data

corsproxy is handling the CORS issue
corsproxy.io has a limit - after 50-60 requests in a minute it will give an error
If we are building a scalable app then there is a issue
