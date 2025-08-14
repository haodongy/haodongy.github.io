---
layout: page
title: "About Me"
---

<style>
/* Float the photo to the top-right; stack nicely on small screens */
.profile-photo {
  float: right;
  margin: 0 0 1rem 1rem;
  width: 180px;           /* tweak as you like */
  border-radius: 10px;    /* optional */
}
@media (max-width: 700px) {
  .profile-photo {
    float: none;
    display: block;
    margin: 0 auto 1rem;
    width: 55%;
    max-width: 260px;
  }
}
</style>

<img class="profile-photo"
     src="{{ '/IMG_6983.jpg' | relative_url }}"
     alt="Personal photo"
     loading="lazy"
     decoding="async">


I’m a Ph.D. student in the [Department of Electrical Engineering and Computer Science](https://ecs.syracuse.edu/academics/electrical-engineering-and-computer-science) at Syracuse University, advised by [Venkata (GV) Gandikota](https://sites.google.com/view/gvenkata/home).
My research interests include coding theory, lattices, information theory, and quantum information theory.

Here are some quantum information theory notes you might find interesting:
