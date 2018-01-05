## Description

This is a simple google cloud function made with firebase that returns "Hello World!" to the browser. It is created for the task

["Set up a Google Cloud Function that returns "Hello World" to the browser"](https://codein.withgoogle.com/dashboard/task-instances/6377955666165760/)  in GCI.

----

## Usage

You can access the cloud function [here](https://us-central1-hello-world-3457a.cloudfunctions.net/helloWorld).

----

## Editing and Deploying

Before editing anything you need to make sure you have [Node.js](https://nodejs.org/en/), and [firebase](https://firebase.google.com/) installed on your computer.

To edit the cloud function go inside the "functions" folder, open "index.js", and do your editing.

When you are done, open the console and type ```firebase deploy``` *(this may take several seconds)*.

When it's done it should look somthing like this: ![firebase deploy screenshot](https://user-images.githubusercontent.com/7314229/34612354-13202c06-f232-11e7-90b8-2595693fb2fd.png)

You need to look at the "Function URL": ![screenshot from 2018-01-05 16-07-16](https://user-images.githubusercontent.com/7314229/34612456-96c62d9e-f232-11e7-9675-0009dcc4c8e7.png)

Copy the URL, paste it in your browser, and you should see your changes. That's it :+1:
