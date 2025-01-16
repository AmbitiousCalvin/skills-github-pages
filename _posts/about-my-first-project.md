---
title:  "Reflecting on My First Big React Project: The Photo App"
date: 2025-16-01
---

# Reflecting on My First Big React Project: The Photo App

## Introduction
So, I built my first big React project—a photo app using the Pexels API. Honestly, I had no idea what I was doing most of the time. It was all trial and error, and when I got stuck, I’d ask ChatGPT for help. The solutions were pretty simple once I asked, but getting to that point was a bit of a mess.

Here’s what I learned from the whole process:

---

## 1. State Management Was a Mess
### What happened
I didn’t handle state well at first. Fetching data from the API was a struggle, and the UI behaved weirdly because I wasn’t managing loading states properly.

### What I learned
State management is EVERYTHING in React. Without it, nothing makes sense.

### What I did
I started using `useState` and `useEffect` properly, added loading/error states, and it made everything run way smoother.

---

## 2. DOM Updates Were Sluggish
### What happened
I was doing a lot of unnecessary re-renders, which made the app slow. I didn’t really think about performance until it became a problem.

### What I learned
React’s all about optimization. Don’t keep re-rendering stuff for no reason.

### What I did
I used `useMemo` and `React.memo` to keep things efficient. It made a huge difference.

---

## 3. Forgot to Add Default Values to Destructuring
### What happened
I kept forgetting to add default values when destructuring, which led to a ton of errors and wasted time.

### What I learned
Default values save you from a lot of unnecessary bugs.

### What I did
I added defaults when destructuring, and it cleared up a lot of issues.

---

## 4. React Strict Mode Tricked Me
### What happened
I didn’t know React Strict Mode runs everything twice, so I spent a lot of time trying to figure out why my pictures were being duplicated. Turns out, it’s just React doing its thing in development mode!

### What I learned
Don’t panic if things look weird in development mode. React Strict Mode is there to help catch errors, even if it means running things more than once.

### What I did
Once I figured it out, I stopped stressing and carried on with the project.

---

## 5. Project Management Was a Struggle
### What happened
I didn’t have a clear plan or timeline, and I got stuck trying to make everything perfect. I wasn’t sure what the final app would look like, and I spent way too much time tweaking small things.

### What I learned
Perfectionism slows you down. Having a plan is key.

### What I did
I started breaking the project into smaller tasks and focused on completing one thing at a time. It helped a lot.

---

## 6. Over-Tweaking Styles
### What happened
I was obsessing over every little style change, which killed my progress.

### What I learned
Styles can wait. Get the functionality down first.

### What I did
I kept styling minimal while I worked on functionality, then came back to design later.

---

## Conclusion
Building this app was a wild ride. I made a lot of mistakes, but each one taught me something. If you're working on a project like this, just remember to manage your state, avoid over-complicating things, and don’t get stuck on the small stuff.

In the end, it was all about learning and growing. I’m ready to take on my next project with all these lessons in mind.


Stay tuned for updates!
