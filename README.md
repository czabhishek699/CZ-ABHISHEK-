<body style="background-color: lightblue;">
 

<!-- wp:spacer -->
<div style="height:100px" aria-hidden="true" class="wp-block-spacer"></div>
<!-- /wp:spacer -->
<!-- wp:spacer -->
<div style="height:100px" aria-hidden="true" class="wp-block-spacer"></div>
<!-- /wp:spacer -->

<!-- wp:image {"align":"center","id":21,"sizeSlug":"large","linkDestination":"none","className":"is-style-rounded"} -->
<figure class="wp-block-image aligncenter size-large is-style-rounded"><img src="https://ojhaavicode.files.wordpress.com/2023/07/picsart_23-07-08_15-16-26-741-modified.png?w=720" alt="" class="wp-image-21"/></figure>
<!-- /wp:image -->

<!-- wp:heading {"textAlign":"center","level":1,"className":"margin-bottom-half"} -->

<!-- wp:heading {"textAlign":"center","level":1,"className":"margin-bottom-half"} -->
<h1 class="wp-block-heading has-text-align-center margin-bottom-half">Avishek Ojha</h1>
<!-- /wp:heading -->

<!-- wp:paragraph {"align":"center","style":{"typography":{"fontSize":18}}} -->
<p class="has-text-align-center" style="font-size:18px">Hey,There🤠| My Name is Avishek Ojha currently living in Jhapa,Nepal. Let's connect!</p>
<!-- /wp:paragraph -->

<!-- wp:social-links {"align":"center"} -->
<ul class="wp-block-social-links aligncenter">




<html>
<head>
  
</head>
<body>
    <a href="https://www.facebook.com/rbabhishek10?mibextid=b06tZ0" target="_blank">Facebook</a>
    <head>[

<a href="https://www.appcreator24.com/app2757290-xomk9w" target="_blank">DOWNLOAD OUR APP</a></head>
  

]
<a href="mailto:avishekojha66@gmail.com" class="contact-link">Contact Me Via Mail</a>
</body>
<html>
<head>
  <title>Flying Bird Animation</title>
  <style>
    #bird {
      position: absolute;
      top: 100px;
      left: 0;
    }
  </style>
</head>
<body>
  <div id="bird">🐦</div>

  <script>
    function flyBird() {
      const bird = document.getElementById("bird");
      const screenWidth = window.innerWidth;
      let birdLeft = 0;

      function moveBird() {
        birdLeft += 5; // Change this value to adjust the bird's speed
        bird.style.left = birdLeft + "px";

        if (birdLeft > screenWidth) {
          birdLeft = -100; // Reset the bird's position to the left side of the screen
        }

        requestAnimationFrame(moveBird);
      }

      moveBird();
    }

    flyBird();
  </script>
</body>
</html>
<footer>
<p>&copy; 2023 Avishek Ojha. All rights reserved.</p>
</footer>
