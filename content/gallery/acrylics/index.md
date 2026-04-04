---
title: "Acrylics Gallery"
draft: false
---

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.11.1/baguetteBox.min.css">

<style>
.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
  margin-top: 2rem;
  max-width: 1000px;
  margin-left: auto;
  margin-right: auto;
}
.gallery figure {
  margin: 0;
  text-align: center;
  background-color: transparent;
}
.gallery a img {
  width: 100%;
  height: auto;
  border-radius: 10px;
  box-shadow: 0 4px 16px rgba(132, 107, 138, 0.2);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.gallery a img:hover {
  transform: scale(1.02);
  box-shadow: 0 6px 24px rgba(132, 107, 138, 0.35);
}
.gallery figcaption {
  margin-top: 0.6rem;
  font-size: 1rem;
  color: #846B8A;
  font-style: italic;
}
</style>

<div class="gallery">

<figure>
  <a href="/images/acrylic/danny.PNG"><img src="/images/acrylic/danny.PNG" alt="Danny" /></a>
  <figcaption>Danny</figcaption>
</figure>

<figure>
  <a href="/images/acrylic/lindsays-friend.PNG"><img src="/images/acrylic/lindsays-friend.PNG" alt="Lindsay's Friend" /></a>
  <figcaption>Lindsay's Friend</figcaption>
</figure>

<figure>
  <a href="/images/acrylic/man-number1.PNG"><img src="/images/acrylic/man-number1.PNG" alt="Man #1" /></a>
  <figcaption>Man #1</figcaption>
</figure>

<figure>
  <a href="/images/acrylic/man-number4.PNG"><img src="/images/acrylic/man-number4.PNG" alt="Man #4" /></a>
  <figcaption>Man #4</figcaption>
</figure>

<figure>
  <a href="/images/acrylic/mum.jpg"><img src="/images/acrylic/mum.jpg" alt="Mum" /></a>
  <figcaption>Mum</figcaption>
</figure>

</div>

<script src="https://cdnjs.cloudflare.com/ajax/libs/baguettebox.js/1.11.1/baguetteBox.min.js"></script>
<script>
  window.addEventListener('load', function() {
    baguetteBox.run('.gallery');
  });
</script>

<a href="/" class="back-link" style="display: inline-block; margin-top: 3rem; background-color: #846B8A; color: white; padding: 12px 24px; border-radius: 8px; text-decoration: none; font-weight: bold;">← Back to Home</a>