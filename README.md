# YouTube Clone - Frontend Project

A fully responsive replica of the YouTube homepage built with pure HTML and CSS.

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

---

## Overview



### Links

- Live Site URL: [https://ed-wilson10.github.io/youtube-clone/](https://ed-wilson10.github.io/youtube-clone/)

---

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Responsive Web Design
- Mobile-first workflow

### What I learned

This project was a great exercise in recreating a real-world, production-level UI from scratch. I deepened my understanding of CSS Grid for the video thumbnail layout and Flexbox for the header and sidebar navigation. Managing multiple sections of a complex page taught me how to organise CSS files effectively and keep styles modular.

```html
<div class="video-grid">
  <div class="video-preview">
    <div class="thumbnail">
      <img src="thumbnails/video1.jpg" alt="Video thumbnail" />
    </div>
    <div class="video-info">
      <img src="channel-picture/author.jpg" class="profile-pic" alt="Channel" />
      <div class="video-details">
        <p class="video-title">Video Title Here</p>
        <p class="author-name">Channel Name</p>
        <p class="stats">1M views · 2 days ago</p>
      </div>
    </div>
  </div>
</div>
```

```css
.video-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
  gap: 16px;
  padding: 16px;
}
```

### Continued development

Areas I want to keep improving in future projects:

- Adding JavaScript interactivity (search bar, sidebar toggle, dark mode)
- Converting the layout into a React component-based structure
- Improving accessibility with proper ARIA roles and keyboard navigation
- Exploring CSS animations for smoother UI transitions
- Eventually integrating a real API (e.g. YouTube Data API) to fetch live content

---

## Author

- GitHub - [@Ed-wilson10](https://github.com/Ed-wilson10)
- Frontend Mentor - [@Ed-wilson10](https://www.frontendmentor.io/profile/Ed-wilson10)
- X / Twitter - [@edsey_jr](https://www.twitter.com/edsey_jr)
