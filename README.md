# Person Page

A simple one-page personal site with your Twitter and Instagram, from a spreadsheet using [IFTTT](http://www.ifttt.com).

> In progress documentation

## Fork-n-Go (then some other things)

### First, fork this repository.

Now you have a copy of this repository which is just webfiles and one branch named `gh-pages` (which means GitHub will host it for free at username.github.io/person-page)

### Rename your fork

Once you've forked it, click on Settings and rename your fork, because probably `person-page` is not what you want in your URL. Maybe `me` or `hello`. You can also use a custom domain, but I won't explain that here.

### Set up Twitter and Instagram with IFTTT

1. Go to www.ifttt.com and create an account, use these recipes for creating a row on a spreadsheet every time you Instagram or Tweet.
 - Twitter [recipe](https://ifttt.com/recipes/178972-all-your-tweets-in-a-google-spreadsheet)
 - Instagram [recipe](https://ifttt.com/recipes/178973-copy-any-instagram-picture-i-take-to-google-drive)
2. Instagram or Tweet so that a spreadsheet is created. _It may take 10-15 mins for it to appear._
3. Go to those spreadsheets and add a header row.
 - For the Twitter one: **date, twitter, tweet, tweetURL**
 - For the Instagram one: **instadate, instacaption, instaurl, instasource**
4. Make each spreadsheet's data accessible:
 - File -> Publish to the Web -> Start Publishing
 - Share -> Anyone with link can view
5. Get each spreadsheet's URL, it's at the top of your browser!
6. Replace the URL's (`URL` and `URL2`) with the appropriate spreadsheet URL (or spreadsheet key, make sure you get the entire key, including hyphens and underscores if you're using just the key.) You can do this through GitHub.com and the Edit button when you click on the filename, or in your favorite text editor.
7. Commit those changes and push them to GitHub (the `gh-pages` branch in your fork).

### Style

There are basic styles included in `style.css` but go wild and make it your own, try other things!
