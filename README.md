# Hi there 👋, I'm Katsumi Kobayashi (小林 活水)

System Architect and Application Architect, and an independent iOS app developer based in Tokyo, Japan.

[LinkedIn](https://www.linkedin.com/in/katsumikobayashi0515/) | [X](https://x.com/Katsumi1972)

## 🚀 About Me
- 📍 Based in: Tokyo, Japan
- 💻 Current role: System Architect, Application Architect, and private iOS app developer
- 🌱 Learning: whatever I need

## 🏆 Awards
- **1st place, Super Hackathon 2013 in Summer** (August 2013), Team Hustler, "AED SOS". Lead developer on a team of five. [Announcement](http://super-hackathon.net/news/)

## 🛠️ Tech Stack
- **Languages:** TypeScript, JavaScript, C, Objective-C, Swift
- **Frontend:** React, Next.js, Tailwind CSS
- **Backend:** Node.js, API Gateway, Lambda, AppSync
- **Infrastructure:** AWS

## 📦 Featured Projects
Source code for Nagi and AED SOS is private. The source of the Niconico Douga player can no longer be found.

### Nagi (凪)
An iOS app that sends a message you set up in advance when you arrive at or leave a place. It uses iOS region monitoring and CloudKit's shared database, with no server of our own, so even the developer can't see your data. Unlike Life360, it never shares your location, only your message and a timestamp.

### AED SOS (Super Hackathon 2013 in Summer, 1st place)
When someone requests help in the app, people nearby are shown where the nearest AED is and where the person in need is. Built with Parse.com (GeoSearch). Later extended with Twilio so the responders and the requester can join one group conversation.

### BzCalendar (iPhone calendar app, formerly on the App Store)
A calendar with a fast monthly view. On the iPhones of that time, drawing a month was slow, so the app caches the data of the previous and next months. Written in Objective-C before ARC, with manual memory management; Swift was added later. The app is no longer on the App Store, so I published the source for reference: [Katsumi0515/bzcalendar](https://github.com/Katsumi0515/bzcalendar)

### Niconico Douga player (third-party app, formerly on the App Store)
A third-party iPhone player for Niconico Douga, not made by the service itself. I built it with Apple's SpriteKit (text nodes and video nodes), expecting that adjusting timing and speed would be enough to make a Niconico-style player. It also had a playful mode where tapping a comment blows it up.
The hardest part was Niconico's APIs: several different APIs had to be combined, and showing rankings was also difficult. When I updated the app, Apple's review asked for a way for users to report objectionable content. Because it was not an official player, I could not provide that, so I stopped publishing it and closed the app. The source code is no longer available.
