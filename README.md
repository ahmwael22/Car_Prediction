<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Point Descriptions</title>
<style>
  /* Add some basic styling */
  .point-list {
    list-style-type: none;
    padding: 0;
  }
  .point-list li {
    margin-bottom: 10px;
  }
</style>
</head>
<body>

<h1>Point Descriptions</h1>

<!-- Create a list of points -->
<ul class="point-list">
  <li><a href="#point1">Point 1</a></li>
  <li><a href="#point2">Point 2</a></li>
  <li><a href="#point3">Point 3</a></li>
</ul>

<!-- Descriptions for each point -->
<div id="point1">
  <h2>Point 1 Description</h2>
  <p>This is the description for Point 1.</p>
</div>

<div id="point2">
  <h2>Point 2 Description</h2>
  <p>This is the description for Point 2.</p>
</div>

<div id="point3">
  <h2>Point 3 Description</h2>
  <p>This is the description for Point 3.</p>
</div>

<script>
  // Add smooth scrolling effect when clicking on point links
  document.querySelectorAll('.point-list a').forEach(anchor => {
    anchor.addEventListener('click', function(e) {
      e.preventDefault();
      
      const targetId = this.getAttribute('href').substring(1);
      const targetElement = document.getElementById(targetId);
      
      if (targetElement) {
        targetElement.scrollIntoView({
          behavior: 'smooth'
        });
      }
    });
  });
</script>

</body>
</html>
