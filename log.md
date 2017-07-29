# 100 Days Of Code - Log

### Day 1: June 24, 2017 (Saturday)

**Today's Progress**: Getting started with SVG.

**Thoughts**: I've been thinking about this for a long time. Just learning and practising the basics. I'm hoping to make some really awesome art using SVG in future. Perhaps coding CSS images is too mainstream for me now. :P

**Link(s) to work**
1. [SVG Tutorial Reference | Jenkov](http://tutorials.jenkov.com/svg/index.html)
2. [SVG Tutorial Reference | W3C Schools](https://www.w3schools.com/graphics/svg_intro.asp)

### Day 2: June 25, 2017 (Sunday)

**Today's Progress**:
1. Learned SVG elements are their attributes.
2. Created an image of "Peacock" in SVG at Codepen.

**Thoughts**: Tutorials by Jenkov are more comprehensive and really helpful for intermediate level coders. I had fun while coding in SVG, though it was challenging at the start. But coding CSS images really helped me out here as I always have the approach of figuring out common patterns before jumping to code. And besides, it took me almost 2 hours to get those curves right. :P

**Link(s) to work**
1. [Peacock SVG | Codepen](https://codepen.io/AshBardhan/details/bRogLR)

### Day 3: June 26, 2017 (Monday)

**Today's Progress**:
1. Learned SVG animation.
2. Added animations on the previously made "Peacock" SVG at Codepen.

**Thoughts**: I always love to make animations in CSS. So I gave it a shot in SVG as well. It is interesting and bit challenging. But too many elements and attributes have to be put inside the code to make it work, especially on reusable elements with minor tweaks. I feel CSS animation is better and it's great in SCSS. I'll try to do that way tomorrow. Anyways, Eid Mubarak everybody! :)

**Link(s) to work**
1. [Peacock SVG - Animated | Codepen](https://codepen.io/AshBardhan/details/owGVXJ/)

### Day 4: June 27, 2017 (Tuesday)

**Today's Progress**:
1. Separated the animation logic from the previously made "Peacock" SVG and added it in CSS.
2. Applied [BEM appraoch](https://css-tricks.com/bem-101/) while naming CSS classes.

**Thoughts**: The code seems neat now (especially the SVG), but the Line of code (LoC) has increased overall. However, you do have a separate control while animating (especially on common elements like - green feathers of the peacock). Another thing I've noticed that the green feathers get repainted in pure SVG code while toggling tabs, but not in CSS animations. Still gotta make my source code shorter by using SCSS later on.

**Link(s) to work**
1. [Peacock SVG + CSS - Animated | Codepen](https://codepen.io/AshBardhan/details/rwYEPK/)

### Day 5: June 28, 2017 (Wednesday)

**Today's Progress**:
1. Optimized my CSS animations in "Peacock" SVG, using SCSS preprocessor.
2. Discovered the problem behind [repainting of SVG animated peacock feathers](https://twitter.com/CreativeBakchod/status/879911856793567232). Had to [initialize position on every component](https://twitter.com/CreativeBakchod/status/880284920467279872) to avoid repainting. That's a bummer! :P

**Thoughts**: Well coding in SCSS is really fun. You can do a lot programming using SCSS, especially loops, nesting, string concatenation and arithmetic operations. It is helpful when you've some components having common design pattern (sometimes minor tweaks in position or animations though). And for BEM lovers, this is best thing you can ever have. Just check my code mentioned in the links below and you'll know why. ;)

Also, my LoC has been reduced from 81 to 48. That's better, cleaner and prettier. So satisfying!
![Ahh! I love it](http://i1.kym-cdn.com/photos/images/newsfeed/000/591/928/94f.png)

**Link(s) to work**
1. [Peacock SVG + SCSS - Animated | Codepen](https://codepen.io/AshBardhan/details/xrpyor/)
2. [Peacock SVG - Animated (no more repainting) | Codepen](https://codepen.io/AshBardhan/details/owGVXJ/)

### Day 6: July 3, 2017 (Monday)

**Today's Progress**:
1. Purchased a new domain and hosting for making my sister's new fashion blog.
2. Completed Wordpress setup on new hosting and migrated blog data from her previous blog. 

**Thoughts**: I was busy for few days on the tasks mentioned above. This is first time I've purchased any hosting or domain, and getting my hands dirty on their platforms. For making a blog, I prefer Github pages or free Wordpress. But my sister needed more bandwidth and disk space for her blog, which a hosting service can provide. Based on her requirements, we bought domain from [GoDaddy](https://in.godaddy.com/) and hosting from [Bluehost](https://www.bluehost.in/). I purchased Linux-based hosting with a capacity of handling 3 domains (first domain already had a setup for her blog, while saving other two for future).

PS: I'm planning the same for my blog and portfolio site. But I will manually code and integrate with Github pages. Will get into it as soon as I'm finished with her blog setup. So Chill!

![Just Chill](http://s2.quickmeme.com/img/1c/1c5d8711c98ed915385ff723dd1d5d4931105e59dc3b33776c1058062e4249fe.jpg)

**Link(s) to work**
1. [Web Hosting Guide](https://www.webhostingsecretrevealed.net/web-hosting-beginner-guide/)

### Day 7: July 4, 2017 (Tuesday)

**Today's Progress**: Getting started with HTML5 Canvas.

**Thoughts**: Just like SVG, I've also thought of learning and practising the basics of HTML5 Canvas. Discovered some similar concepts (rectangle, fill, stroke and methods of making a line, curve etc). Just minor changes in the syntax. But unlike SVG, the canvas is painted in raster-form which will break the sharpness of an element being made. Not so cool! :P

**Link(s) to work**
1. [HTML5 Canvas Tutorial Reference | Jenkov](http://tutorials.jenkov.com/html5-canvas/index.html)
2. [HTML5 Canvas Tutorial Reference | W3C Schools](https://www.w3schools.com/graphics/canvas_intro.asp)

### Day 8: July 6, 2017 (Thursday)

**Today's Progress**:
1. Learned some more concepts on HTML5 Canvas.
2. Created the same image of "Peacock" in HTML5 Canvas at Codepen.

**Thoughts**: Like I mentioned in my previous post about raster painting and blurriness of HTML5 canvas. Well it really showed after making that [same peacock](https://codepen.io/AshBardhan/details/bRogLR). Applied the modular and iterative logic for components, which I've used previously in my [animated SVG + CSS peacock](https://codepen.io/AshBardhan/details/rwYEPK/). So therefore, no problem in setting coordinates for the every component. But I had a bit struggle which applying transformation on any component as it is dependent on the previous component's position. So I had to reset the transformation in the end of making of new component. Yeah! The hard paid off and I was able to make it. But still, the curves aren't looking nice bruh! :P

**Link(s) to work**
1. [Peacock HTML5 Canvas | Codepen](https://codepen.io/AshBardhan/details/pwZBbM/)

### Day 9: July 8, 2017 (Saturday)

**Today's Progress**: Wrote some additional CSS to fix position of some external plugins inside my sister's fashion blog.

**Thoughts**: Wordpress provides a lot free themes to for your blog. And since I've already purchased a hosting service and installed Wordpress in it, most of their paid themes have been unlocked. Plus, it also gives you the power to customize CSS both internally and externally.

Currently, I've experimented with some themes which provides a lot of CSS rules for page layout and basic components required for the blog. But sometimes, the CSS for some of the external plugins are not provided by such themes. So this is where I've to add some CSS on my own. Applying this, I was able to apply the custom CSS rules on required plugins, overriding the default ones.

PS: The blog is still under-construction and confidential. I'll share the link as soon as I complete this project and go live. :) 

**Link(s) to work**
1. [Wordpress CSS Reference](https://codex.wordpress.org/CSS)
2. [Customize CSS Reference](https://en.support.wordpress.com/custom-design/editing-css/)

### Day 10: July 9, 2017 (Sunday)

**Today's Progress**:
1. Created a temporary maintenance page on my sister's blog.
2. Edited `.htaccess` config file, which will redirect to maintenance page when someone else is accessing the home page.

**Thoughts**: Since this blog is under-construction and confidential, I have to make sure it is only accessible by me and my sister's system during development. So I added some code into the `.htaccess` file, allowing our IP addresses only to access the whole website while others will be redirected to our maintenance page. 

**Link(s) to work**
1. [htaccess | Wordpress Reference](https://codex.wordpress.org/htaccess)
2. [htaccess | bluehost Reference](https://my.bluehost.com/cgi/help/htaccess)

### Day 11: July 10, 2017 (Monday)

**Today's Progress**:
1. Minor UI fixes on my sister's blog, after selecting a theme.
2. Learned about SSH access and generated SSH keys in my cPanel account.
3. Connected to a Shared Server of my sister's blog via SSH remotely from my laptop. 

**Thoughts**: Digging deeper into backend fo a while. Using SSH, I'm now easily able to access files of my sister's blog (which is present inside `public_html` folder). Don't need change file(s) on the cPanel File Manager interface anymore. However, I'm planning to create a private repo at Bitbucket storing only files inside `public_html` blog folder and syncing with corresponding cPanel files via SSH keys.  

**Link(s) to work**
1. [SSH Command Reference](https://www.ssh.com/ssh/command/)
2. [SSH Access | bluehost Reference](https://my.bluehost.com/cgi/help/180)
3. [Connecting to a Shared Server SSH with a Mac](http://www.inmotionhosting.com/support/website/ssh/shared-server-ssh-mac)

### Day 12: July 11, 2017 (Tuesday)

**Today's Progress**: Made a special art at Codepen using Pug (formerly Jade) and SCSS, dedicated to my 26th Birthday. 

**Thoughts**: Gave myself a Birthday Treat. :P  

**Link(s) to work**
1. [BardhanMania 26 - 7 Segment LED | Codepen](https://codepen.io/AshBardhan/details/RgqXBp/)

### Day 13: July 13, 2017 (Thursday)

**Today's Progress**: 
1. Made a private repository at Bitbucket of `public_html` folder (consisting my sister's blog contents).
2. Connected this repo with my laptop and remote shared server via SSH keys.  

**Thoughts**: It's bit hectic to change any file inside the code editor of cPanel File Manager. Their interface is not that great, especially manipulating content in multiple files. Plus, I required some version control of `public_html` folder.

So therefore, I made a private repo at Bitbucket of this folder (excluding all media and gallery files). I've also forked this repo on my laptop via SSH, so that I'll be able to code locally and comfortably in [PHPStorm](https://www.jetbrains.com/phpstorm/). :)   

**Link(s) to work**
1. [Hosting cPanel files to Git Repository](http://monkeylogic.com/using-cpanel-to-host-your-git-repository-and-deploy-automatically/)
2. [SSH Access to Bitbucket | Atlassian Reference](https://confluence.atlassian.com/bitbucket/use-the-ssh-protocol-with-bitbucket-cloud-221449711.html)
3. [SSH Access to Bitbucket | StackOverflow Reference](https://stackoverflow.com/questions/16074832/cannot-push-to-git-repository-on-bitbucket)
4. [Configuring Multiple SSH Keys](https://confluence.atlassian.com/bitbucket/configure-multiple-ssh-identities-for-gitbash-mac-osx-linux-271943168.html)

### Day 14: July 14, 2017 (Friday)

**Today's Progress**:
1. Learned HTML5 Canvas animation.
2. Added animations on the previously made "Peacock" at Codepen.
3. Experimented animation speed by [altering frame rate](https://twitter.com/CreativeBakchod/status/886124359730855937).

**Thoughts**: There's a some things you've to take care of while doing this, like - clearing the canvas and running animation timing logic before every frame you're "painting" pixels inside. Unlike CSS and SVG animation, you've to write your own timing function (`linear` is easy). However, I was able make my animation slower by increasing the number of frames. It worked by slow-motion camera. That's interesting! ;)

**Link(s) to work**
1. [Peacock HTML 5 Canvas - Animated | Codepen](https://codepen.io/AshBardhan/pen/ZyPBxN)
2. [Peacock - One Picture, Different Styles| Codepen](https://codepen.io/collection/nVmEeV/)

### Day 15: July 15, 2017 (Saturday)

**Today's Progress**:
1. Learned about Wordpress file and directory structure.
2. Ignored and removed core Wordpress folders and files from my private repository.

**Thoughts**: Understanding the complete architecture of Wordpress file system should be better, before starting into code. Previously, I've included in whole `public_html` Wordpress folder from `cPanel` to my private `Bitbucket` repository. I noticed that Wordpress core folders (`wp-admin` and `wp-includes`) and files (`wp-login` , `wp-signup` etc.), which are not supposed to edited are present in my repo. It simply means that I don't need backup for such files.

So therefore, I ignored and removed them from my repo, making sure they're still present on my `cPanel` file system. Now, I only have folders and files, which are supposed to be customized and must be considered as backup.

**Link(s) to work**
1. [Wordpress File and Directory Structure](http://www.wpbeginner.com/beginners-guide/beginners-guide-to-wordpress-file-and-directory-structure/)
2. [Wordpress Site Architecture](https://codex.wordpress.org/Site_Architecture_1.5#Core_Structure)
2. [Wordress Files Backup Idea](http://www.wpbeginner.com/beginners-guide/which-wordpress-files-should-you-backup-and-the-right-way-to-do-it/)

### Day 16: July 16, 2017 (Sunday)

**Today's Progress**:
1. Learned about making child theme at Wordpress.
2. Created a new child theme and made some tweaks in styling and layout on it.

**Thoughts**: Now I'm coding at Wordpress! :P

![That's right bitches](http://akns-images.eonline.com/eol_images/Entire_Site/2015315/rs_300x300-150415091312-600.Success-Kid-Sammy-Griner.jl.041515.jpg)

**Link(s) to work**
1. [Wordpress Theme Development](https://codex.wordpress.org/Theme_Development)
2. [Making Child Theme at Wordpress Tutorial](http://www.wpbeginner.com/wp-themes/how-to-create-a-wordpress-child-theme-video/)

### Day 17: July 18, 2017 (Tuesday)

**Today's Progress**: Still working on Sister's fashion blog
1. Brought back `wp-includes` core Wordpress files from the source code, to understand some default component generating functions.
2. Customized some of those functions inside `functions.php` file of my current theme folder.

**Thoughts**: Coding at Wordpress is fun! :P

**Link(s) to work** Working on a private project. Will share link once I launch the website.

### Day 18: July 19, 2017 (Wednesday)

**Today's Progress**: Still working on Sister's fashion blog
1. Installed and activated `Instagram` plugin inside the blog, making some layout and styling changes on it.

**Thoughts**: Coding at Wordpress is fun! :P

**Link(s) to work** Working on a private project. Will share link once I launch the website.

### Day 19: July 20, 2017 (Thursday)

**Today's Progress**: Still working on Sister's fashion blog
1. Tweaked styling and layout of multiple components like - sidebar, footer, blog-content, anchor-tags etc.

**Thoughts**: Rebuild, Redesign and Rework! Too Much Fun! :P

**Link(s) to work** Working on a private project. Will share link once I launch the website.

### Day 20: July 21, 2017 (Friday)

**Today's Progress**:
1. Tweaked some more styling and layout of multiple components.
2. Added responsiveness in the website using `media-queries`. 
3. Removed all maintenance page redirect from `.htaccess` file and launched the website.

**Thoughts**: Finally, the day has come. It was really a tough assignment to do. I've launched a website for the first time. Started from purchasing a domain/hosting to understanding and coding in `PHP` till I made it live. I'm so happy and proud of myself. :)

However, I'll be doing some refactoring and UI tweaks for a while. I've also shared my work with my fellow developers and designers. All eyes and open for honest feedbacks.

![I finally did it](http://m.memegen.com/a42ebx.jpg)

**Link(s) to work** 
1. [My Sister's Fashion Blog](http://realgirltalks.com/)

### Day 21: July 24, 2017 (Monday)

**Today's Progress**:
1. Revised the basics of HTML, CSS, JS and jQuery, with the help of `freeCodeCamp`.
2. Completed their 23 hrs of lessons within 3 hrs so far.

**Thoughts**: Just a quick revision of basic frontend skills. I've joined `freeCodeCamp` months ago. But started taking their course since yesterday. 

It's really a good place to code real-time, especially for those who are just starting it. Although you must refer other sources (perhaps a book) to get deeper into the concepts they're explaining.

Looking forward to complete their advanced courses and work on their non-profit projects with fellow developers soon. ;)

**Link(s) to work** 
1. [freeCodeCamp | Tutorial](https://www.freecodecamp.org)
2. [freeCodeCamp | My Account Progress](https://www.freecodecamp.org/ashbardhan)

### Day 22: July 25, 2017 (Tuesday)

**Today's Progress**:  Updated minor UI tweaks in some components like - Blog content tags and Slider caption box, of my Sister's fashion blog.

**Thoughts**: Few changes were recommended by friends and colleagues after the website's launch.

**Link(s) to work** 
1. [My Sister's Fashion Blog](http://realgirltalks.com/)

### Day 23: July 28, 2017 (Friday)

**Today's Progress**: Attended the first day of [JS Channel 2017](http://2017.jschannel.com/) Conference at Bangalore, India. Learned from the following talks:
1. Keynote by Preethi Kasireddy
2. State maintenance with Redux in a multi layered JavaScript Application by Varsha Saha
3. Service Worker and The Role they Play in Modern-day Web Apps by Mukul Jain
4. Building Cross Platform Desktop Applications Using Electron by Rahul Rout
5. Building applications for the next billion users by Siddharth Kshetrapal
6. Workshop on styled-components by Max Stoiber
7. Demand Driven Applications with GraphQL by Vinci Rufus
8. Animation in VueJS by Sarah Drasner

**Thoughts**: This is my first conference and first trip to Bangalore. I did minor coding during workshop session, but learned quite a lot from the speakers. I got inspired from many of them especially a 10 year old coder, who has made 3 Minecraft Mods so far. Impressive!

Being an UI developer (as I mostly work on `HTML` and `CSS`), it was quite challenging for me to understand advanced concepts and new frameworks of JavaScript. But I was familiar with ReactJS and Electron, as I've done some minor projects using them in the past. Quite a lot of things have changed now in React. Will catch up on it sooner. :) 

**Link(s) to work** 
1. [Simone Parekh - 10 year old coder | YouTube](https://www.youtube.com/channel/UCPGKU_tzBZ-xU7p8hUuZQqA)
2. [Simone Parekh - 10 year old coder | Website](https://sites.google.com/view/xlargehamster/)

### Day 24: July 29, 2017 (Saturday)

**Today's Progress**: Attended the second day of [JS Channel 2017](http://2017.jschannel.com/) Conference at Bangalore, India. Learned from the following talks:
1. JavaScript V8 engine by Franziska Hinkelmann
2. Dealing with Data Offline in Web Apps by Jai Santosh
3. Building beautiful interfaces in React Native by Sanket Sahu
4. Super-charged Developer Tools for React Native by Parashuram N
5. Workshop on U `&` I with React by Farhad Ghayour
6. Keynote on ReactJS by Andrew Clark

**Thoughts**: Overall this was more of a `ReactJS` Conference, as most of the speakers talked about `React`, `Redux` and its associated tools. They've given the use cases of the B2C websites of today, which require high performance in page rendering speed.

Although there is no separation of concerns as everything `HTML` and `CSS` wrapped in `JS` now. It requires some level of skills to understand that. Will be practising on it sonner. ;)
 
**Link(s) to work**: No links added