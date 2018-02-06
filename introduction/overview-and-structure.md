# Overview & Structure

This course consists of a bunch of modules, including:

 - Firebase Console
 - Firebase Authentication
 - Firestore
 - Realtime Database
 - Cloud Functions for Firebase
 - Firebase Storage
 - Cloud Messaging
 - Firebase Hosting

## Modules

Some of these modules are **much** larger than others.

For instance, we'll breeze through Authentication, Storage, Hosting and Messaging. These topics are isolated and straightforward. They don't require much decision-making. We need to get comfortable with how these services fit into a production-worthy Firebase architecture, and then we can move on. 

However, Cloud Firestore, the Realtime Database, Security Rules and Cloud Functions are an entirely different story.

These modules are multi-purpose tools that can be used in all sorts of creative ways. We'll go much deeper into these Firebase features. We'll cover common use cases and potential pitfalls. And we'll try to inspire you with advanced architectures that will make your apps both performant and easier to write.

| Module          | Intensity      | Reasoning                                                                            |
| --------------- | -------------- | ------------------------------------------------------------------------------------ |
| Console         | 🌶             | A quick walk-through |
| Authentication  | 🌶             | Auth is the easiest Firebase feature to implement. |
| Firestore       | 🌶🌶🌶🌶🌶      | Firestore is the meat of Firebase's offering. |
| Realtime DB     | 🌶🌶🌶🌶        | The Realtime DB (RTDB) has some "gotchas" |
| Functions       | 🌶🌶🌶🌶🌶      | Functions is the back end of your app. It's tricky to develop on, but crazy powerful |
| Storage         | 🌶🌶           | Small API with some complexity |
| Messaging       | 🌶🌶           | The Firebase SDK hides most complexity |
| Hosting         | 🌶🌶           | Static file hosting has some detail, but it's mostly just static files. |

## Module Structure

Each module will start of with an introduction. Introductions answer questions like "why do you need Firebase Authentication?" or "how does Cloud Functions work with Firestore?"

Next, we'll walk through how the feature is used in a live application. This is a public-facing web app whose code you can inspect and interact with yourself. You can also pull down the code and deploy it to your own Firebase project for a deeper dive into its features.

Once we've seen the Firebase service in action, we'll spin up our own Firebase project and implement a feature step by step. 

Finally, we'll summarize what we've learned, provide you with some notes--kind of a cheatsheet for the feature--and refer you to additional learning resources and next steps.

## Example Module

Let's use Firebase Authentication as an example.

First, we'll explain why Firebase Authentication is critical to your application. Why you need it, and how your app will be better because you took the time to implement it.

Next, we'll show how Firebase Authentication works in our production app.

Then we'll break out our code editors and implement a basic authentication. We won't go any deeper than we need to, but you'll have coded a working implementation that you can take with you.

And finally we'll wrap up with a summary of how we've implemented Firebase Authentication, downloadable notes with descriptions of the functions that you should know, and suggestions for next steps in implementing Firebase Authentication in a more sophisticated way.
