<h1 align="center">🏷️ Discord Bio</h1>
<p align="center">
  <b>I've been working on this site as a form of bio for a friend of mine, talking to him, we've come to an agreement that I'll put the template here on Github for public use! So I hope you enjoy it. 🥰</b></br>
  <sub>This is a fully static HTML/CSS site!<sub>
</p>

> It's a site just a little bit similar to the Discord profile... Don't tell them 😅
    
### ✨ What is included?

This site is not just a bunch of HTML code with a little CSS, it is also:

- ✅ A replica of the Discord profile!
  - A replica that is pretty hard to find here on Github.
- ✅ Real-time Discord profile data using [Lanyard API](https://github.com/Phineas/lanyard/). You need to join [Lanyard's Discord](https://discord.gg/z2xW3zxYdt) for your profile to work!
  - Automatically takes your username along with your Discord icon, using just your ID.
- ✅ Simple setup!
  - You only need to fill in a few things for your website to look like you!
  - In `index.html` and in `config.js`

### 🔧 Getting Started

If you are interested in using this site, you need to know a few things!

- Download the source as a ZIP folder or clone it via `git` using the `git clone` command.
- Fill in the required spaces in these files below:
  - Index: `index.html` - You need to use this example link below, via [Imgur](https://imgur.com/upload)
```html
<div id="banner" style="background-image: url(https://i.imgur.com/C3CMuIF.png);"></div> 
<div id="user-info">
```
  - Config: `config.js`
- The most important part is in `config.js`
  - **P.S.** You need to fill in everything right, especially your discord ID, for everything to work without any errors.
```js
const USER_ID = "YOUR DISCORD ID HERE";
const BACKGROUND_IMAGE = "assets/images/";
```

> For all of this to work, you need to be on the official Lanyard server, [click here](https://discord.gg/lanyard) to enter.

Remembering that you can use and abuse this site as you want, I'm posting it here especially for people who want a template like this, or people who don't know how to program and want to start somewhere. So, enjoy! 🥰

### 🙏 Thanks

[Lanyard API](https://github.com/Phineas/lanyard/), an amazing project with an excellent author that made me come up with the idea of making a website like this!
