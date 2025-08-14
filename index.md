---
layout: page
title: "About Me"
---

<style>
/* Scoped styles so we don't affect the rest of the site */
.about {
  display: grid;
  grid-template-columns: 1fr 220px;   /* text | photo */
  gap: 1.25rem 2rem;
  align-items: start;
}
.about .photo {
  justify-self: end;
}
.about .photo img {
  width: 220px;        /* adjust as you like */
  max-width: 100%;
  border-radius: 10px; /* optional rounding */
  display: block;
}
@media (max-width: 800px) {
  .about {
    grid-template-columns: 1fr;       /* stack on small screens */
  }
  .about .photo {
    justify-self: center;
  }
  .about .photo img {
    width: 60%;
    max-width: 260px;
  }
}
</style>

<div class="about">
  <div class="copy">
    I’m a Ph.D. student in the
    <a href="https://ecs.syracuse.edu/academics/electrical-engineering-and-computer-science">
      Department of Electrical Engineering and Computer Science
    </a>
    at Syracuse University, advised by
    <a href="https://sites.google.com/view/gvenkata/home">Venkata (GV) Gandikota</a>.
    My research interests include coding theory, lattices, information theory, and quantum information theory.

    <p>Here are some quantum information theory notes you might find interesting:</p>
  </div>

  <figure class="photo">
    <img src="{{ '/IMG_6983.jpg' | relative_url }}" alt="Personal photo" loading="lazy" decoding="async">
  </figure>
</div>
