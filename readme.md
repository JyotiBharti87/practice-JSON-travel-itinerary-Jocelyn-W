Pair team Jocelyn W / Jyoti B

Answer the questions: 
○ Nesting: How did you organize the additional details in the traveler field, 
and how does it improve the organization of the data overall? 
We both created a nested object for the contact information.  It improves the organization
because it keeps all the information related to the traveler tied to that object.
If it wasn't nested it could be confused with the phone number of a location for example.

○ Arrays: For the destinations and activities, what data structure did you use? 
What impact did this decision have? 

Both of them are an array of objects.  It makes it logical and easy to maintain them.
It is easy at a glance to see what the data relates to.

○ Scalability: How could this JSON structure be expanded to include additional details, 
such as hotel information or transportation options? 

The current arrivalDate and departureDate could be used for hotel check in dates.  It would be easy
to add a hotel field in each location object of the destination array.  Transportation options
could be added to each destination object.  It would most likely be an array of objects.

○ Real-World Application: How would this data be useful in a travel app or API?

It could be helpful for travel agents or individuals trying to plan a trip. It 
gives all the package information without requiring additonal research.