---
title: Home
layout: layout.njk
heroImage: true
---

# Welcome to my blog!

<p>This page is using a general layout. </p>


<div class="banner">
    <img src="/assets/banner.jpg" alt="banner">
</div>

<style>
h1 {
    text-align: center;
}
p{
    text-align:center
}
.banner {
    width: 100%;
    max-width: 500px; /* Makes it smaller - adjust this number */
    margin: 0 auto; /* Centers it */
    padding: 1rem 0;
}

.banner img {
    width: 100%;
    height: auto;
    aspect-ratio: 16 / 9; /* Rectangle ratio */
    object-fit: cover;
    border-radius: 8px;
}
</style>
