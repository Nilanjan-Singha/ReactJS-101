# ReactJS-101
ReactJS 101 is the ultimate tutorial to learn React. This is more of my React Notes but I have structured them properly so anybody viewing it will not face any issues. So, happy learing.
<hr>

## WHAT IS REACTJS?
ReactJS is a widely used frontend framework to build websites and WebApplications. Developed by Facebook in 2013, it has changed the way websites are made and is still predominant in the codemarket.

<details>
<summary>Q. What is Frontend?</summary>
Ans: Try opening a website. What you see is the frontend part of a website. The frontend is what people see and interact with—such as websites, visual elements, or user interfaces (UI). In more depth, frontend is the client-side of a website. To create frontend, you will nedd to learn programming languages like HTML(i know it is not), CSS, Javascript, React/Angular/Vue or Django/Flask in the Python world.
</details>

<details>
<summary>Q. What is Backend?</summary>
Ans: Think of a social media platform. You already know that there is too much data being sent and received each second on the website, but this process is not visible to us, right. Therfore, backend involves the processing, communication and storing of data. It is called the server-side of a website or webapp.
</details>

<details>
  <summary>Q. What is a Framework?</summary>
  Ans: A framework is a pre-defined structure to write a software. Think of it as a blueprint to building something along with the materials that are required. Frameworks help in better code management, time saving, resource saving, error debugging, etc.
</details>

### REACTJS COMPONENTS
So, itching to write ReactJS code already? No worries! Once you master the basics, React will feel like a piece of cake.
ReactJS is built around the idea of reusable components. But what does that mean exactly? Let’s first see where traditional Vanilla JavaScript (plain JavaScript without any libraries) can get tricky.
When you build pages with Vanilla JS, every time you click a link or navigate, the browser reloads the entire page - you see the loading icon, and the browser reconnects to the server for each new page. This can make your app feel slow and clunky.
Now imagine if you could load your website just once, connect to the server only once, and then navigate between different parts of the site without reloading the whole page. That would make your app much faster and smoother. This is exactly what ReactJS does by enabling single-page applications (SPAs).
Also, remember how in Vanilla JS you often have to manually find elements using querySelector or similar methods? Your code can get messy and hard to maintain. React solves this by automatically keeping track of the UI elements through its Virtual DOM - a lightweight copy of the real DOM - and only updates what actually changes. This means less manual work and cleaner code.

In summary: React helps you write less code, build more powerful and interactive apps, debug errors more easily, and make your websites faster and more efficient.
<hr>

OK, lets now dive into components. Let's say, you are making a movie website. In Vaniilajs, for each movie, you will need to create a card component. But what if I make a card once and then just in the movie details like title, image, etc and all the movies get displayed. Yeah, less code baby. How about make a navbar component once and using it in every pages of the website without typing for each page? So, think of components as Lego blocks, each block has its proper structure and meaning like the card component above and now we use nest the lego block with whatever other piece we find fit to create something else.

