### Inspiration

With so many fitness apps, we wanted to curate a way for our fitBuddies to find a fitness plan tailored to them. We wanted a fitness plan to be fully integrated into Messenger, so "Fit for Me" can provide encouragement and track progress directly from Messenger. 

### What it does it do

After being asked a series of questions like weight range, height, fitness goals, and previous activity, "Fit for Me" will pair you with one or two fitness plans from apps like Runkeeper, MindBody, a nearby Meetup group, or another popular app. Depending on how frequent our fitBuddies want to track progress, they can take a photo and share it on Facebook. Headbands and other accessories from brands can be added to photos using Spark AR. 

### How we built it

The chat bot was built using "facebook for developers" documentation written in javascript. We used Sketch to make the wireframes. To motivate and give fitBuddies the opportunity to share progress, Spark AR was used to capture photos and add accessories. 

### Challenges we ran into

Spark AR: We originally wanted to use Spark AR to do body segmentation and recognition. With the ability to identify a person's arms, legs, and torso, we planned to project their current body in gray and have their "goal" body overlaid on top. This proved to be tricky with current technologies since just changing the x-axis percentage wouldn't be enough. We're excited to see how that technology progresses. 

Messenger: We found the lack of a messenger boilerplate challenging for 8 hours. We planned to modify the "Original Coast Clothing" chatbot and soon realized that the control flow was too complex to modify. A tree-based software similar to Spark AR Studio would have made the process much faster since the classes couldn't be easily modified without diving deeply into the code. 

Deploying: We found having a package-lock.json and yarn.lock simulatenously crashed our heroku. It took us a long time to resolve this issue. 

### Accomplishments that we're proud of

We are proud of our wireframes and how much we learned in a short period time. 

### What we learned

For some of us, it was our first exposure to AR. Also, our first hackathon. :) 

### What's next for Fit for Me

We'll continue to build out our chat bot and bring all the components together. 

### Acknowledgements

** "Original Coast Clothing" chatbot
** Spark AR Studio


