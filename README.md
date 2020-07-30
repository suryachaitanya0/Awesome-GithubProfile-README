# Awesome-profile-README

Your beginner Profile-README Guide( A Guide to create a Awesome Profile-README).

Github recently released a feature which allows users to create a profile-level README to display on their GitHub profile page,
This is a great way to introduce yourself to the Github community as you highlight your skills and projects.

# Table of contents:

- [What's a Github Profile-README?](#What's-a-Github-Profile-README?)
- [How do I create a Profile-README?](#How-do-I-create-a-Profile-README?)
- [What to add to your README?](#What-to-add-to-your-README?)
- [References](#References)
- [Additional Resources](#Additional-Resources)
- [Contributions](#Contributions)

## What's a Github Profile-README?

Apparently `www.github.com/#your-username/#your-username` is a ✨special ✨ repository that you can use to add a `README.md` to your GitHub profile.

The GitHub Profile-level README feature allows more content than the profile bio, supports markdown which means you can play around with 
the content more visually and the `README.md` is significantally more visible as it is placed above pinned repositories
and takes up as much space above the fold of the webpage as you like.

## How do I create a Profile-README?

The Profile-README is created by creating a new repo that’s the same name as your `username`.

### This is how it works:

1. Create a repo with your github username (e.g. `https://github.com/#your-username/#your-username`)

For example, my GitHub username is `suryachaitanya0` so, I created a new repo with the name `suryachaitanya0`.(The letter-casing must match your GitHub username.)

_One thing to Note: If you already have a project in a repo-named `#username/#username` and are interested in setting up a Profile-level README, then I recommend re-naming 
that repository._

2. Create a `README.md` file inside the repo.

3. Add content( introduction text,banner, links, GIFs, images, emojis, etc).

4. Commit your new README!

  If you're on GitHub's web interface you can choose to commit directly to the repo's main branch (i.e., master or main) which will make it immediately 
  visible on your profile) or Push changes to GitHub if you made changes locally (i.e., on your computer).

That's it.

## What to add to your README?

1. A Greeting message.

2. Bio or Self-description(Try to keep it simple).

3. Make your page memorable by Adding Images, Icons and GIF to make the page look bit dynamic, instead of just filling it with text.

  You can also add a hero image( A large banner at the top of your page).
  This is the first thing that people will see when they visit, so make it exciting!

4. Include Stats

  If you are using Github for your projects or use it to contribute to open source, you probably have a lot of commits and Pull Requests.
  
  Anurag Hazra created amazing widget which compiles all those stats into one.
  It generates GitHub stats dynamically on your readmes!
  
  #### Link to repo: [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
  
  ### Adding GitHub Stats Card
   Copy paste this into your markdown content, and that's it. Simple!
   Change the `?username=` value to your GitHub's username.
   
   ```md
   [![github stats](https://github-readme-stats.vercel.app/api?username=#your-username)](https://github.com/anuraghazra/github-readme-stats)
   ```
   
   _Note: Ranks are calculated based on user's stats, see [src/calculateRank.js](./src/calculateRank.js)_
   
   ### Include Top Languages Card

   Top languages card shows github user's top langauges which has been mostly used.

   _NOTE: Top languages does not indicate my skill level or something like that, it's a github metric of which languages i have the most code on github, it's a new feature of       github-readme-stats_

   Copy-paste this code into your readme and Change the `?username=` value to your GitHub's username..

   Endpoint: `api/top-langs?username=anuraghazra`

   ```md
   [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=#your-username)](https://github.com/anuraghazra/github-readme-stats)
   ```
   
   #### For more Information on stats visit [github-readme-stats](https://github.com/anuraghazra/github-readme-stats)
   
6. You are not limited to Markdown when it comes to editing your README. Github's Flavored Markdown allows using some of the HTML tags.

	Here's some of the basic things you can do:
	* Center a section using `<center>`
	* Create a widget that opens and closes using `<details>`

7. Want to link to external sites? Add some icons which redirect to your social networks or projects.
  I recommend using the free and open source RemixIcon library and just changed the color to suit the color scheme.
  
  _One thing to note: Make sure your images are of great quality. We wouldn't want images to show up pixelated.
  If you are using vector images, upload them using SVG instead of JPG or PNG._

8. Add counter to GitHub profile

 [Anton komarev](https://github.com/antonkomarev) created amazing widget which counts the visitors.
 
 #### Link to repo: [github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter/)
 
 Copy-paste this code into your readme and Change the `?username=` value to your GitHub's username.

 ```markdown
 ![](https://komarev.com/ghpvc/?username=#your-username)
 ```
 
 #### For more Information about counter visit [github-profile-views-counter](https://github.com/antonkomarev/github-profile-views-counter/)
 
9. Highlighting, what all your working on right now.

10. automate your GitHub profile README
	
	* [Create a dynamic Markdown file with Go and GitHub Actions](https://victoria.dev/blog/go-automate-your-github-profile-readme/)
	* You can also display latest blogs posts dynamically using [Github Action](https://github.com/features/actions)

## Tired of editing Github Profile-README?

This tool provides an easy way to create github profile readme with latest addons like visitors count, github stats etc.
- https://github.com/rahuldkjain/github-profile-readme-generator

## References:

- https://github.com/coderjojo/creative-profile-readme
- https://github.com/kautukkundan/Awesome-Profile-README-templates

## Additional Resources:

- https://mytrashcode.com/github-profile-readme-examples
- https://dev.to/jayehernandez/3-ways-to-spice-up-your-github-profile-readme-1276
- https://dev.to/m0nica/how-to-create-a-github-profile-readme-1paj

## Contributions
To contibute visit [Contibutions.md](https://github.com/suryachaitanya0/Awesome-profile-README/Contributions.md)

### Contributions are welcomed! <3

#### Found this project useful ❤️,Support by clicking the ⭐ button on the upper right of this page.
