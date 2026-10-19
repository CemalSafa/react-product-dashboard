# React Product Dashboard

This is my assignment for the React part of the course. It's a simple
dashboard thing with a list of products, a button to show/hide them, and
a text input where you type your name and it shows up below. Everything
is just hardcoded data, nothing fancy, no fetching or anything.

## Files

- App.jsx - this is the main one, has the state stuff (show/hide and the
  name you type) and renders everything else
- components/ProductList.jsx - has the list of products in it (just made
  up some laptop/phone/tablet stuff) and loops through them with map
- components/Product.jsx - shows one product, just gets title and price
  as props, doesn't do anything else really
- components/Card.jsx - just a wrapper with a border around it basically,
  doesn't know or care what's inside

## Stuff I struggled with

While working on App.jsx I ran the dev server and only the heading
showed up, no button, no input, nothing. I was confused for a bit and
thought I broke something, turned out I just hadn't actually saved/
re-ran things properly after editing the file. Once I ran it again
everything showed up fine. Small thing but it threw me off for a minute.
