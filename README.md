# Developer Portfolio 2 🔥 


## A clean, modern and responsive dev portfolio using HHML CSS & Java Script

## BUILT BY MR JUICE ![maxresdefault](https://github.com/mrjuice01/web2/assets/100421286/0a5edeed-801a-48cb-b60a-0a6cf4f69461)



#### <p align="center">**Best WebTemplete**
</p>
<p align="center">
<a href="https://github.com/mrjuice01"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-%E2%99%A5-red" ></a>
 <a href="https://paypal.me/mrjuiceofc"><img title="Donate" src="https://img.shields.io/badge/Donate-PayPal-blue" ></a>
 <a href="https://github.com/mrjuice01/web2"><img title="GitHub version" src="https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=2.5.1.beta&x2=0"></a>
<a href="https://github.com/mrjuiceo1"><img title="GitHub version" src="https://img.shields.io/github/license/mrjuice/T-Remix?color=Brightgree" ></a>
 <a href="https://www.youtube.com/@mrjuiceofc"><img alt="Youtube" src="https://img.shields.io/badge/Youtube-Bhavik Tutorials-green"/></a>
 <a href="https://instagram.com/mr_juice7"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-mr_juice7-ff69b4"/></a>
 <a href="https://github.com/mrjuice01"><img title="Stars" src="https://img.shields.io/github/stars/mrjuice01/web2?style=social" ></a>
</p>

###### <p align="center">*This is official repository maintained by Mr Juice*
###### <p align="center"> *[**INSTAGRAM**](https://www.instagram.com/mr_juice7/) ❤️*
###### <p align="center"> *SUBSCRIBE [YOUTUBE](https://www.youtube.com/channel/@mrjuiceofc)❤️*
---



### Just Simple and well design portfolio to showcase works and skills
 - Useful for the freelancing journey 🚀. You can showcase your skills and the works you have done.   
 - Highly customizable portfolio. You can easily customize it as you want.     

## Live Demo 🚀
[don't click here](https://portfolioweb-taupe.vercel.app/)

## Technologies Used 🖥️

- [Java Script](https://javascript.org/)
- [Html](https://html.com/)
- [CSS](https://html.com/)
- [Email JS](https://www.emailjs.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [Iconify](https://iconify.design/)



## Getting Started

```bash
# Clone this repository
git clone https://github.com/mrjuice01/web2.git

# Go into the repository
cd web2
# Setup default environment variables

# For Linux
cp env.example .env.local
# For Windows
copy env.example .env.local

# Install dependencies
npm install

# Start a local dev server
npm start
```

## Setup 

- Create ENV File 

```bash
- dev-portfolio
  - node_modules
  - public
  - src
  - .env         <-- create it here
  - env.example  <-- this is the base file
  - .gitignore
  - package-lock.json
  - package.json
```

```env
// .env
EMAIL_SERVICE_ID= "YOUR SERVICE ID"
EMAIL_TEMPLATE_ID= "YOUR TEMPLATE ID"
PUBLIC_KEY= "YOUR PUBLIC KEY"
```
- Email JS - [Sign Up](https://dashboard.emailjs.com/sign-up)


## Customize according to your need.

#### Personalize page content in `src/mock/profile.js` & modify it as per your need.

```javascript
export const SOCIAL_LINKS = [
  {
    link: 'https://instagram.com/mr_juice7',         // <--- Social handle Link
    icon: 'akar-icons:instagram-fill',          // <--- Iconify Icon name
  },
  {
    link: 'https://github.com/mrjuice01',
    icon: 'akar-icons:github-fill',
  },
  {
    link: 'https://youtube.com/in/mrjuiceofc',
    icon: 'akar-icons:youtube-fill',
  },
];

export const HERO_TITLES = ['Mr Juice', 'Full-stack Developer', 'Javascript Enthusiast'];

export const aboutParagraph =
  'Highly motivated and enthusiastic Full Stack Developer with experience in designing, developing and maintaining web applications using technologies such as JavaScript, React, Node.js. ';

export const contactEmail = 'mrjuice017|@gmail.com';

export const documentTitle = 'Hello I am Mr Juice | Full Stack Developer | Software dev'


```

#### Customize Project Section

 `/src/mock/projects.js`
 
 - change projects with yours.

#### Customize Skill Section

 `/src/mock/tech-skills.js`
  
  - change skills with yours.
  - You can easily add new skill, new icon by providing iconify icon name.
  - example as below: 
```javascript
  {
    label: 'Your Skill',
    proficiency: '90%',
    icon: 'icon',  // <-- find icon from iconnify
    iconClasses: 'text-3xl', // <-- add classes
  }
```

## Add more Lottie
- checkout this directory `src/mock/lottie`
- You can add more lottie in `.json` format and use it. 



## For the Future
If you want to add more, Please don't hesitate to open a [pull request](https://github.com/mrjuice01/portfolioweb/pulls).


***
## Support <img src="https://user-images.githubusercontent.com/64035221/113476039-61b21c80-9496-11eb-93d1-97a97f6acaa6.png" width="30" height="30">

<table align="center" style="border:1px solid black;margin-left:auto;margin-right:auto;">
  <tr>
    <th><img src="https://user-images.githubusercontent.com/100421286/272568945-0cb5c1cb-b544-4287-962b-cf5ebab61d3d.jpg" width="100%" height="100%"></th>
  </tr>
  <tr>
    <td><a href="https://github.com/mrjuice01/"><p align='center'><b>Mr Juice</b></td>
  </tr>
  <tr>
    <td><p align='center'><b>Author</b></td>
  </tr>
</table>

<p align="center"><a href="https://github.com/mrjuice01"><img src="https://user-images.githubusercontent.com/64035221/96459220-834c7e00-123f-11eb-8417-534058a7ba62.png" alt="GitHub" width="80" height="80">
<a href="https://www.youtube.com/@mrjuiceofc"><img src="https://user-images.githubusercontent.com/64035221/96456596-4f238e00-123c-11eb-821e-85e9aaa3faec.png" alt="YouTube" width="80" height="80">
<a href="https://t.me/DeveloperJuice"><img src="https://user-images.githubusercontent.com/64035221/113977119-b91e0700-985f-11eb-9418-eab91ff1540e.png" alt="Telegram" width="80" height="">
<a href="https://www.instagram.com/mr_juice7/"><img src="https://user-images.githubusercontent.com/64035221/113977904-e61ee980-9860-11eb-82d1-9ebd795c8138.png" alt="Instagram" width="80" height="">
