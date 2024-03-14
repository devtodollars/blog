---
layout:
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: false
---

# 🚧 My AI Tech Stack of a YC Backed Founder ($3.1k MRR)



Hey guys! I'm Matt. I'm a YC backed founder that built an AI app. I started building apps as an indiehacker before joining a YC backed company but I'm here to show you the ai tech stack I used to get myself up and running. I'm really excited to share this with you guys, because I've spent countless hours researching different frameworks best suited for building startups including: frontend, backend, analytics, payments, email, error monitoring, release processes, and more.&#x20;

In this post, I'm going to dive deep into the framework, why I choose a particular framework and some alternatives I considered and why I ultimately decided to go with the particular framework.

## My AI Tech Stack Needs

Before I dive deep into the specific framework I used, I'd like to dive deep into some of the requirements and needs. Everyone has different requirements and needs and depending on what sort of requirements / needs you have you'll use a different library or framework. Here were some of mine

* Development speed is **very important** to me.&#x20;
* Looking to start off with a web app for MVP with the potential for a mobile app.
* I expect growth to be super fast. Meaning I can't be paying exorbatant prices for having (\~100k users)
* I want the entire operation to be profitable
* It's important for me not to rewrite code
* I like everything integrated together working nicely and seamlessly

Ultimately at the end of the day whichever framework help me accomplished my needs the fastest was the best one for me. Building a startup is all about speed and I had to made decisions that allowed me to move quickly.

## Tech Stack Summary

## AI Tech Stack Details

### Frontend (Flutter Web)

#### **How Flutter made me faster**

* I built an app in the past using Flutter, so instead of starting from scratch I copied a bunch of code and got myself up and running extremely fast. TODO: plug my own DevToDollars template here
* That being said, I decided to stick with web only because deploying mobile apps to the play store and app store required an approval process and it was tedious. If I kept it on web only, I have control of this workflow and it's much faster. Especially early on speed is the biggest advantage.
* Another interesting choice is that I decided to keep the app mobile size. Meaning if they used the app on the desktop, there would be a bunch of padding on the side and they'd only work with a tiny portion of the screen. The reason for this choice was because it would reduce the amount of design that needed to be done and when I did port over to mobile it would be really easy to do so. It's typically easier to go from mobile first -> desktop vs the other way around.
* Another interesting decision was I used the default Material Design 3. The reasoning behind this was because it was faster and all the components were already prebuilt for me. Also, transitioning from Material 3 to another design would just be a matter of updating the theme.



{% hint style="info" %}
My other decisions from here on out also depend also depended on how well it integrates with Flutter
{% endhint %}

#### Comparison:

<table><thead><tr><th width="173">Framework</th><th>Pros</th><th>Cons</th></tr></thead><tbody><tr><td><strong>Flutter</strong></td><td><ul><li>Worked with Flutter in the past</li><li>Flutter supports all platforms</li><li>Amazing developer experience</li><li>Fast growing</li><li>Type errors caught at compile time</li></ul></td><td><ul><li>Flutter web is slow to load</li><li>Interfacing with Web JS is kind of finicky</li><li>Knowing what to do with state management is tricky</li></ul></td></tr><tr><td>React Native</td><td><ul><li>Lots of libraries + community support</li><li>Uses React which is a language I'm familiar with</li></ul></td><td><ul><li>It wasn't that easy to port React Native code into React. I t still required me to rewrite some parts.</li><li>Performance seemed to be an issue for me</li><li>Typescript is not strict</li></ul></td></tr><tr><td>Ionic</td><td><ul><li>Worked with React in the past</li><li>Lots of libraries + community support</li></ul></td><td><ul><li>A web app packaged in a native app</li></ul></td></tr></tbody></table>



### Backend (Supabase)

#### How Supabase made me faster

One thing I loved about Supabase was how they made the made the development experience so simple. They had great documentation, guides and tutorials and exactly what I needed, they have a great philosophy on not reinventing the wheel and they have a fantastic team running the whole thing. I can go on and on about how good Supabase is but let me list out how it helped&#x20;

* The Flutter SDK was a breeze to use saving me a bunch of time
* No need to setup a backend server, just used Deno functions to facilitate this process (e.g. making calls to OpenAI)
* Lots of flexibility with whatever I need because everything is just Postgres.
* Lots of guides and tutorials on everything I need especially with new OpenAI tutorials.
* All my other backend needs were met: Database, Authentication, Storage, Realtime, etc.

#### Comparison Chart

<table><thead><tr><th width="162">Framework</th><th>Pros</th><th>Cons</th></tr></thead><tbody><tr><td>Supabase</td><td><ul><li>Easy-to-use SDK</li><li>Very good documentation</li><li>Responsive team</li><li>Flexible framework</li><li>Powerful UI Dashboard</li></ul></td><td><ul><li>Deno might not have libraries I want and  the 1 minute timeout on the functions</li><li>Deno functions sometimes don't support the same libraries node does.</li></ul></td></tr><tr><td>Firebase</td><td><ul><li>Has notifications built in with Flutter</li></ul></td><td><ul><li>Expensive when you scale</li><li><a href="https://github.com/cachapa/firedart">Lack of full native Dart support</a></li><li><a href="https://github.com/firebase/flutterfire/issues/349">Slow build times</a></li><li><a href="https://groups.google.com/g/firebase-talk/c/gDAMWGVH88k?pli=1">No desktop support</a></li></ul></td></tr></tbody></table>

### Analytics (Posthog)

* All-in-one analytics the goal is to build fast
* A Flutter SDK that supported web
* Easy to build analytics for all my needs
* Includes



### Landing Page (Framer)

You might

#### How Framer Made me Faster

