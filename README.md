<h1 align= center>Awesome-GithubProfile-README:octocat:</h1><br>
<p align = center>
Your beginner GithubProfile-README Guide( A Guide to create Awesome Profile-README). :smiley:
Github recently released a feature which allows users to create a profile-level README to display on their GitHub profile page,
This is a great way to introduce yourself to the Github community as you highlight your skills and projects.
</p>
<br><br>

# Table of contents::book: 

- [What's a Github Profile-README?](#What's-a-Github-Profile-README?)
- [How do I create a Profile-README?](#How-do-I-create-a-Profile-README?)
- [What to add to your README?](#What-to-add-to-your-README?)
- [Tired of editing Github Profile-README?](#Tired-of-editing-Github-Profile-README?)
- [Additional References](#Additional-References)
- [Additional Resources](#Additional-Resources)
- [Contributions](#Contributions)

## What's a Github Profile-README?

Apparently `www.github.com/#your-username/#your-username` is a ✨special ✨ repository that you can use to add a `README.md` to your GitHub profile.

The GitHub Profile-level README feature allows more content than the profile bio, supports markdown which means you can play around with 
the content more visually and the `README.md` is significantally more visible as it is placed above pinned repositories
and takes up as much space above the fold of the webpage as you like.
<br>
## How do I create a Profile-README?

The Github-Profile-README is created by creating a new repo that’s the same name as your `username`.

### This is how it works:

**1. Create a repo with your github username (e.g. `https://github.com/#your-username/#your-username`)**

For example, my GitHub username is `suryachaitanya0` so, I created a new repo with the name `suryachaitanya0`.(The letter-casing must match your GitHub username.)
<br><br>
![GitHub Repo Creation](https://github.com/suryachaitanya0/Awesome-GithubProfile-README/blob/master/images/createrepo.png?raw=true)

<br>

_Note: If you already have a project in a repo-named `#username/#username` and are interested in setting up a Profile-level README, then I recommend re-naming 
that repository._
  

**2. Create a `README.md` file inside the repo.**

**3. Add content( Introduction Text, Banner, Links, GIFs, Images, Emojis etc).**

**4. Commit your new README!**

  If you're on GitHub's web interface you can choose to commit directly to the repo's main branch (i.e., master or main) which will make it immediately 
  visible on your profile) or Push changes to GitHub if you made changes locally.( i.e., on your computer)

**That's it.:clap:**
<br>

## What to add to your README?

### 1. A Greeting message.

### 2. Bio or Self-description(Try to keep it simple).

### 3. Make your page memorable by Adding Images, Icons and GIF to make the page look bit dynamic, instead of just filling it with text.

  You can also add a hero image( A large banner at the top of your page).
  
  This is the first thing that people will see when they visit, so make it exciting!
  
  _Example: [Jayehernandez](https://github.com/jayehernandez)_
  <br><br>
  ![jaye](https://github.com/suryachaitanya0/Awesome-GithubProfile-README/blob/master/images/jaye.png?raw=true)
  <br>
### 4. Include Stats.

  If you are using Github for your projects or use it to contribute to open source, you probably have a lot of commits and Pull Requests.
  
  [Anurag Hazra](https://github.com/anuraghazra) created amazing Repo which compiles all those stats into one.
  It generates GitHub stats dynamically on your readmes!
  
  #### Link to repo: [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
  
  **1. Adding GitHub Stats Card.**
  
   Copy paste this into your markdown content, and that's it. Simple!
   
   Change the `?username=` value to your GitHub's username.
   
   ```md
   [![github stats](https://github-readme-stats.vercel.app/api?username=#your-username)](https://github.com/anuraghazra/github-readme-stats)
   ```
   
   _Note: Ranks are calculated based on user's stats, see [src/calculateRank.js](./src/calculateRank.js)_
   
   _Example:_
   
   ![Anurag's github stats](https://github-readme-stats.vercel.app/api?username=anuraghazra&count_private=true))
   
   
   **2. Include Top Languages Card.**

   Top languages card shows github user's top langauges which has been mostly used.

   _NOTE: Top languages does not indicate my skill level or something like that, it's a github metric of which languages i have the most code on github, it's a new feature of       github-readme-stats_

   Copy-paste this code into your readme and Change the `?username=` value to your GitHub's username..

   Endpoint: `api/top-langs?username=anuraghazra`

   ```md
   [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=#your-username)](https://github.com/anuraghazra/github-readme-stats)
   ```
   
   _Example:_
   
   [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra)](https://github.com/anuraghazra/github-readme-stats)
   
   #### For more Information on stats visit [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
   
### 6. You are not limited to Markdown when it comes to editing your README. Github's Flavored Markdown allows using some of the HTML tags.

  Here's some of the basic things you can do:
  
* Center a section using `<center>`
* Create a widget that opens and closes using `<details>`

### 7. Want to link to external sites? Add some icons which redirect to your social networks or projects.

  I recommend using the free and open source [RemixIcon library](https://remixicon.com/) and just changed the color to suit the color scheme.
  
  _Note: Make sure your images are of great quality. We wouldn't want images to show up pixelated._
  
  _If you are using vector images, upload them using SVG instead of JPG or PNG._

### 8. Add View-counter to GitHub profile.

 [Anton komarev](https://github.com/antonkomarev) created amazing Repo which counts the visitors.
 
 #### Link to the Repo: [github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter/)
 
 Copy-paste this code into your readme and Change the `?username=` value to your GitHub's username.

 ```markdown
 ![](https://komarev.com/ghpvc/?username=#your-username)
 ```
  _Example:_
 
 ![](https://komarev.com/ghpvc/?username=your-username)
 
 #### For more Information about counter visit [github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter/)
 
 _I recommend to create your own view-counter (or fork existing repo) and host on your own server._
 * Here is a article about creating view counter,[Click here](https://dev.to/tod/github-profile-view-counter-igj)
 
 _Alternatives:_
 [visitor-badge](https://visitor-badge.glitch.me/) By [Jwenjian](https://github.com/jwenjian/)
 
### 9. Highlighting, what all your working on right now.

### 10. Show your latest blog posts from any sources or StackOverflow activity

[Gautamkrishnar](https://github.com/gautamkrishnar) created amazing repo which Shows your latest blog posts from any sources or StackOverflow activity on your GitHub profile/project readme automatically using the RSS feed

Follow the repo Readme to add to your profile.
#### Link to the Repo : [blog-post-workflow](https://github.com/gautamkrishnar/blog-post-workflow)
_Example:_
<br><br>
![blogpost](https://github.com/suryachaitanya0/Awesome-GithubProfile-README/blob/master/images/blogposts.png?raw=true)
<br>

### 11. Add Wakatime Weekly Metrics.

[Athul](https://github.com/athul), [Anmol1098](https://github.com/anmol098) created amazing Repos which Shows your Dev Metrics in Readme.

Follow the repo Readme to add to your profile.
#### Link to the Repo : [waka-readme](https://github.com/athul/waka-readme) By [Athul](https://github.com/athul)
#### Link to the Repo : [waka-readme-stats](https://github.com/anmol098/waka-readme-stats) By [Anmol1098](https://github.com/anmol098)
_Example:_
<br><br>
![waka](https://github.com/suryachaitanya0/Awesome-GithubProfile-README/blob/master/images/waka.png?raw=true)
<br>

### 12. Add Colored Badges,Shields etc.

Add badges to your Profile. Here are some Repos, you can use to add Badges or Shields.
- [Markdown-badges](https://github.com/Ileriayo/markdown-badges) By [Ileriayo](https://github.com/Ileriayo)
- [Shields](https://shields.io/) By Shields.io
- [ColoredBadges](https://github.com/MikeCodesDotNET/ColoredBadges) By [MikeCodesDotNET](https://github.com/MikeCodesDotNET)

### 13. Automate your GitHub profile README:
	
   * Create a dynamic Markdown file with Go and GitHub Actions,[Click here](https://victoria.dev/blog/go-automate-your-github-profile-readme/)
   * Create Your Github readme with automated news data,[Click here](https://dev.to/mridul037/create-your-github-readme-with-automated-news-data-3a7n)
   * You can also display latest blogs posts dynamically using [Github Action](https://github.com/features/actions)
   * Create a self-updating Github Profile,[Click here](https://dev.to/ragebill/how-to-create-a-self-updating-github-profile-2m22)
   
### 14. Include other website stats, Extras.

   * Add linkedin profile stats: [Github-readme-linkedin](https://github.com/soroushchehresa/github-readme-linkedin) By [Soroushchehresa](https://github.com/soroushchehresa)
   
   * Add Stackoverflow stats: [Github-readme-stackoverflow](https://github.com/omidnikrah/github-readme-stackoverflow) By [Omidnikrah](https://github.com/omidnikrah/)
   
   
   * Add Medium article stats: [Github-readme-medium](https://github.com/omidnikrah/github-readme-medium) By [Omidnikrah](https://github.com/omidnikrah/)
   
   * Add spotify now playing card: [Spotify-github-profile](https://github.com/kittinan/spotify-github-profile) By [Kittinan](https://github.com/kittinan)
   
   * Add Programming jokes: [readme-jokes](https://github.com/ABSphreak/readme-jokes) By [ABSphreak](https://github.com/ABSphreak)
   
## Tired of editing Github Profile-README?

Try These tools,They provides an easy way to create github profile readme with latest addons like visitors count, github stats etc.
- [github-profile-readme-generator](https://github.com/rahuldkjain/github-profile-readme-generator) By [Rahuldkjain](https://github.com/rahuldkjain/)
- [github-profilinator](https://github.com/rishavanand/github-profilinator) By [rishavanand](https://github.com/rishavanand/)
- [github-profile-readme-generator](https://github.com/arturssmirnovs/github-profile-readme-generator) By [Arturssmirnovs](https://github.com/arturssmirnovs)

## Additional References:

- https://github.com/coderjojo/creative-profile-readme
- https://github.com/kautukkundan/Awesome-Profile-README-templates
- https://github.com/elangosundar/awesome-README-templates
- https://github.com/abhisheknaiidu/awesome-github-profile-readme

## Additional Resources:

- https://mytrashcode.com/github-profile-readme-examples
- https://dev.to/jayehernandez/3-ways-to-spice-up-your-github-profile-readme-1276
- https://dev.to/m0nica/how-to-create-a-github-profile-readme-1paj
- https://dev.to/satvikchachra/how-to-add-an-awesome-readme-to-your-github-profile-361n
- https://simonwillison.net/2020/Jul/10/self-updating-profile-readme/

## Contributions

To contibute visit [Contibutions.md](Contributions.md)

### Contributions are welcomed! <3

#### Found this project useful ❤️,Support by clicking the ⭐ button on the upper right of this page.
