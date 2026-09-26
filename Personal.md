---
layout: default
title: "Personal"
---
<style>
/* Add pleasant margins and spacing */
.personal-container {
  max-width: 800px;
  margin: 0 auto;               /* Centers all content */
  padding: 20px 10px;
  line-height: 1.6;
  font-size: 18px;
}

/* Image layout */
.personal-images {
  display: flex;
  flex-wrap: wrap;
  gap: 15px;
  justify-content: center;
  margin-top: 20px;
}
.personal-images img {
  max-width: 30%;
  min-width: 200px;
  height: auto;
  border-radius: 8px;
  object-fit: cover;
}
</style>

<div class="personal-container">

<p>
On a personal note, I love travelling, history, and hiking.
</p>

  <div class="personal-images">
    <img src="{{ '/assets/img/history_travel.jpg' | relative_url }}" alt="History and Travel" />
    <img src="{{ '/assets/img/hiking_stream.jpg' | relative_url }}" alt="Hiking in Nature" />
    <img src="{{ '/assets/img/running_little_island.jpg' | relative_url }}" alt="Running in New York" />
  </div>
</div>



