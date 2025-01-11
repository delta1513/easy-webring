# Easy Webring

A simple, lightweight webring system that runs entirely on GitHub Pages. Fork this repository to create your own webring!

## What is a Webring?

A webring is a collection of websites linked together in a circular structure. Each site in the webring has navigation links to the previous and next sites in the ring, making it easy for visitors to discover related websites.

## How to Create Your Own Webring

1. Fork this repository
2. Go to Settings > Pages and enable GitHub Pages on the main branch
3. Update `links.txt` with your initial list of websites

## How to Join This Webring

Want to join this webring? Simply create a Pull Request that adds your website's URL to `links.txt`. Make sure to:
- Add your URL on a new line
- Include the full URL (with `https://`)

## How to Add the Webring to Your Website

Add this HTML snippet to your website, replacing `YOUR-WEBSITE-URL` with your actual website's URL as it is in the text file you changed above (I know, this is ugly! I'll fix it later!!!):

```html
<div class="webring">
    <a href="https://my-webring.github.io/?referrer=YOUR-WEBSITE-URL&direction=prev">← Previous</a>
    <a href="https://my-webring.github.io/?referrer=YOUR-WEBSITE-URL&direction=random">Random</a>
    <a href="https://my-webring.github.io/?referrer=YOUR-WEBSITE-URL&direction=next">Next →</a>
</div>
```

