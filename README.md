<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Random Slide Show</title>
<style>
  body { font-family: Arial, sans-serif; display: flex; justify-content: center; align-items: center; height: 100vh; margin: 0; }
  .slideshow-container { width: 60%; padding: 20px; background-color: #f3f3f3; border-radius: 10px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); }
  .slide { display: none; }
</style>
</head>
<body>

<div class="slideshow-container">
  <div class="slide">
    <h2>Slide 1 Title</h2>
    <p>This is the first piece of information.</p>
  </div>
  <div class="slide">
    <h2>Slide 2 Title</h2>
    <p>This is the second piece of information.</p>
  </div>
  <div class="slide">
    <h2>Slide 3 Title</h2>
    <p>This is the third piece of information.</p>
  </div>
</div>

<script>
window.onload = function showRandomSlide() {
  let slides = document.getElementsByClassName("slide");
  let slideIndex = Math.floor(Math.random() * slides.length);
  slides[slideIndex].style.display = "block";
}
</script>

</body>
</html>