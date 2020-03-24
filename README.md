# Battle Buddies

## Authors
Young Jun Choi (@WHYjun)

Soo Hyeok Lee (@soohyeok)

Byoungsul Lee (@leeb24)

Sangjoon Lee (@sj0726)

Jewoo Lee (@aisora1222)

## How to install dependencies and run server

```
npm install
node index.js
```

## Inspiration

Young Jun has served as a Korean soldier in US Army for two years, and one of his jobs was to help his fellow soldiers' transitions back into civilian life. Sadly, most of them were helpless during the transition, not because they didn't try, but because they didn't know how to. We hoped to create a platform that is easily accessible and helpful for the veterans.

## What it does

Those who see the veterans in need of help, or veterans themselves can send a simple text message to our system to get help for what they need to settle into the civilian life. Our system offers help with jobs, job trainings, consulting, and VA hospitals. Also, we made a web application to find the things I've just mentioned in a single page.

## How we built it

We used Twilio to handle SMS flow from veterans to our Nodejs backend server. We saved SMS data and users' demographic data into database and posted the helps offered in the frontend forum.

## Challenges we ran into

None of us had fullstack experience in JavaScript, so it was a challenge for us. We struggled a lot from it, but we also learned a lot as well.

## Accomplishments that we're proud of

Unlike other applications, we used Twilio and SMS only as the only interface of our application. 

## What's next for Battle Buddies

What we plan to do is getting the real data from veterans and NGOs to fill our forum with actual data. Also, we plan on applying similar methods to tutoring system for the general public. From this, we hope to relieve the overcrowded BU office hours. We desire to create a proper community where people could actively get involved, rather than just words of 'advice'.
