# Bookmark Website

Bookmark website from my Tailwind course (Tailwind CSS From Scratch | Learn By Building Projects ) and from Frontend Mentor Challenge

fontFamily: ["Barlow", "sans-serif"],

colors: {
nude: " hsl(38, 90%, 81%)",
nude1: "#EED180",
gray1: "hsl(218, 11%, 65%)",
},

This is a bookmark website

We have our Navbar, positioned using flex, but on small screens we have our hamburger icon, and the menus pop out on an overlay that covers the screen with a little transparency

Hero Section: This section contains an image and content that is place side by side on large screens but are stacked on small and medium screens, it also has outlined buttons

Features section: section with a big heading and paragraph

Features Tabs: Here we've got separate tags that are hidden but with javascript we were able to make them show when you tap on their respective headings (N/B: it can only display a tab at a time)

Download Heading: section with a big heading and paragraph

Download Boxes: The download boxes, styled in form of a card, the different cards were positioned using flex, and the content of these cards were also positioned to stack on each other, with each card containing a browser icon, text and button

FAQ Heading: section with a big heading and paragraph

ACCORDION: Here each accordion has their specific titles, then the arrow svg that rotates (-180deg) on focus or click, lastly the accordion content that has a height of 0, but on focus gets the max height of screen

Newsletter Section: This has description, input and button

Footer:

## Usage

Install dependencies

```
npm Install
```

Run Tailwind CLI

```
npm run watch
```

![Alt text](images/bookmark.png)
