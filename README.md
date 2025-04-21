# Embergency
HackDavis 2025 Project :)

Inspiration:
After hearing about the California GovOps challenge, our minds instantly went to addressing the invisible threat of compromised communications during wildfires. For example, during California’s Camp Fire of 2018, 17 cell towers were downed, greatly interfering with the ability for citizens to stay updated during the dangerous situation. This remains an issue to this day, as in 2021, “56% of the 4,272 emergency alert calls in the first hours of the Paradise fire failed,” leading to the death of 85 Californian citizens. To address this, we wanted to make an application that could make it easy for those to know whether or not their communications lines are in danger of being compromised by a raging fire.

What it does:
Given a user's input city, our application can be used to locate nearby fires and return communications towers that are in danger of being compromised, allowing users to better prepare for fire response. This can be applied to firefighters who need to quickly determine where they should go next, along with citizens who want to stay updated on their surroundings.

How we built it:
The first course of action was planning out what web APIs we were going to use to access data, and it was instantly apparent that we were going to need a way for users to input their desired city, see if there was a fire nearby, and if so, which communications tower had a chance of being damaged by said fire. Taking in the user’s input city, we would use a real-time database to locate any nearby fires, and then extract the latitude and longitude of the fire. From there, we would use those coordinates to locate the cell tower that was closest to the fire and return said cell tower’s location. If the user recognized the cell tower’s location/their proximity to it, they could better prepare and be wary about any potential communications outages. Working through the project, we implemented each API one by one, parsing through each API’s returned JSON data and extracting the relevant information we needed to display or use to fetch more information from another API. Then, after getting the fundamental functionalities completed, we spent the rest of the time on styling and making sure that it was easy for users to interact with.

Challenges we ran into:
Regarding the challenges we faced, since we were totally new to hacking, we spent a lot of time setting up the project one way and then scrapping it, realizing that there was a more efficient way to progress. However, after we were able to settle on a stable project structure, we had a lot of fun working on it. This is also the first time we worked with APIs, so there was a lot of documentation that we had to learn about and research, which was unexpected.

Accomplishments that we're proud of:
Honestly, we are proud of the entire project, as this was the first time we ever did anything like this. We had no idea how to really approach something like this, and a lot of things were learned along the way. Overall, we've become better developers than before starting this project

What we learned:
A lot of us used Git and GitHub for the first time, which is an invaluable skill for both industry and personal use. We also learned a lot about using APIs in web and app development, and as a whole, learned a lot more about hands-on development than we ever had before.

What's next for Embergency:
In the future, we want to implement Google Maps integration, along with other features that make it easier for the users to visualize their query's results. We also want to make sure that users can understand the severity of the fire's threat, which can be implemented through the integration of more real-time data APIs.

