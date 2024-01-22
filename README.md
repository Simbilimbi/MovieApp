---
difficulty: 3
training: true
chapter: "Chapter 4: Vue.js Ecosystem"
tags: vue
---

# Dedicated Movie Pages

# Challenge Description

> ⚠️ Do not use `PNPM` as it is giving issues with some of the code challenges.

In this challenge, let's use Vue Router to display the current app on the homepage but also allow linking to info about an individual movie. 

> 💡 HINT: We've already installed Vue Router in the boilerplate code

## Requirements

- Setup Vue Router in `main.js` with routes for:
  -  the homepage (`/`)
  -  and an individual movie (`/:id`)

> 💡 HINT: We've provided boilerplate code for each page in the `/src/pages` directory

- Modify App.vue so that it displays the proper component from the pages directory based on the current route
- Add a link on each movie item on the home page to go to the movie's detail page
- Display the info for the proper movie on the movie's detail page based on the id from the URL


## Other Considerations

- If you see the `data-test` attribute anywhere in the boilerplate don't remove it.
- TailwindCSS is preinstalled with the default config. It might be helpful for you, if you want to have some styles. (Not obligatory)

## Example of Finished App

This is an example of what the functionality should look like for the completed exercise. If you’d like to mimic this style, feel free to do so, but it is not required.

![Finished app in this challenge](https://i.imgur.com/yQMhBYn.gif)
