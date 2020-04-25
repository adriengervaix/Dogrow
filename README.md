# Dogrow — 

![intropic](https://adriengervaix.com/projects/dogrow/assets/bigpicture.jpg)

Grow your instagram pupup

This Chrome extension scales up every popup on instagram.
We simply tweak the style of the page to have a bigger popup & modal on every instagram page

# Features

- Scaling up profile & explore page popup
- Scaling up following & followers list popup

# How

We simple add a style to these element

> div[role="dialog"] div[role="dialog"] div[role="dialog"]{
>    max-width: 70% !important; 
> }


> div[role="presentation"] div[role="dialog"]{
>    max-height: 80% !important; 
> }

