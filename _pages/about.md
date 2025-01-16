---
permalink: /
title: "Academic Pages is a ready-to-fork GitHub Pages template for academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is the front page of a website that is powered by the [Academic Pages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. 


## My YouTube Video

{% raw %}
<div class="video-wrapper">
    <div class="video-left">
        <h4> LOW COST AI ASSISTED CERVICAL CANCER SCREENING FOR LBC IN DEVELOPING COUNTRIES</h4>
        <iframe width="560" height="315" 
                src="https://youtu.be/embed/pmVvwGuVn0w" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
        </iframe>
    </div>
    <div class="video-right">
        <h3>Assembly AI Winter Hackathon 2022</h3>
        <iframe width="560" height="315" 
              src="https://www.youtube.com/embed/tsm9s5sQJl8" 
              frameborder="0" 
              allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
              allowfullscreen>
        </iframe>
    </div>
</div>
{% endraw %}
<style>
.video-wrapper {
  display: flex; /* Flex container for side-by-side layout */
  justify-content: space-between; /* Creates space between videos */
  gap: 16px; /* Optional: Add space between videos */
}

.video-left,
.video-right {
  flex: 1; /* Allows videos to share equal width */
  max-width: 48%; /* Ensures they fit within the container */
}
</style>