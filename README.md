# Functional CMS
An open source highly extensible content management system built with a cluster of micro-service based components

## Why another CMS

There are lots of CMS available, like Wordpress and Octpress. These CMS are easy to set up and use. But it become a nightmare when you try to customize them. They are complex monolithic software, you have to read the lengthy doc and follow their rules. You stuck on their technology stack.

As a full stack (beginner level) software engineer, I always want to adapt and try new libraries, new programming languages and new technologies in my own blog. I want to drop in and replace the component in my blog easily. I want to have an CMS would not lock the engineer in any specific stack.

## What do 'functional' of Functional CMS means?

To make a software extensible and maintainable, you need to set up standard, so everyone can understand your code and build on top of it. In this project, I will pick approach other than API - data structure. I borrow the idea from functional programming, components without side effect, for the same input, always having the same output. After knowing the input and output data structure, engineers can replace any components with any technology. The components of the CMS is similar to an Lego block, you can reassemble them to customize you own CMS. Lengthy documentation on CMS is no longer needed, you know how to add new components after checking the in/out of depending components

## First step

I have a blog built with Hexo static site generator, I will create a Hexo post migrate tool first.
- Parse post data to JSONs
- Reduce the JSONs into APIs
- Build front-end with react
