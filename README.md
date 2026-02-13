# Frontend Mentor - Profile Card Component

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

![Desktop screenshot](./screenshots/desktop-screenshot.png)

### Links

- Live Site URL: [https://fem-solutions.github.io/profile-card-component](https://fem-solutions.github.io/profile-card-component)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

## What I learned

#### Semantic HTML

- Used `<article>` because the profile card is a self-contained, independent component.
- The card is structured with two logical groups: profile and stats. While `<section>` could be used, it's not necessary since the `<article>` already provides semantic meaning.
- Used an unordered list `<ul>` for the stats, as they represent a list of related items (Followers, Likes, Photos).

#### Accessibility

- Added `aria-label` to the `<main>` element to describe its role when needed.
- Added `aria-label="years old"` to the age `<span>` to provide context for screen readers.
- Wrapped the name and age in a container (wrapper) to group them, with the name as an `<h1>` and age as a `<span>` inside.

## Author

- Frontend Mentor - [@amansgz](https://www.frontendmentor.io/profile/amansgz)
- Github - [@amansgz](https://github.com/amansgz)

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io/) challenges help you improve your coding skills by building realistic projects.
