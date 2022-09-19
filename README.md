# LaunchPad-Challenge

## Frontend Web

You and your friends are developing a new start-up called DRUBER, a drone-based ride share application that carries you to your destination. 
The original specification was to develop a web page that works in 1920x1080 however your company has realized that it is missing an entire 
market of smartphone users. Describe how you can modify your code to work in smartphone resolutions e.g. 750x1334 (iPhone 8).
Please give specific examples where possible, but do not implement an entire DRUBER clone!

## Answer
What I would do is dependent on what our code looks like so far and the tech stack we are working with. For example, if our website is 
a react web app and we are using semantic-ui-react, simply adding:
```<meta name="viewport" content="width=device-width, initial-scale=1">' ``` to the CSS file 
might solve the problem. The same thing could work if we are working with bootstrap.

However, it is preferred that a website is either built from scratch to be mobile friendly or built to have a mobile design that is unique from the desktop one. If we have the time and developers, I would create a new mobile website that is inspired by the original and matches the colour theme. If we don’t have the time, @media queries are our best bet along with the line of code mentioned above. We might also choose a new look for the desktop website that is more mobile friendly and deploy that. 

