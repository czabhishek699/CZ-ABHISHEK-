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
<p class="has-text-align-center" style="font-size:18px">Hey,There🤠| My Name is<p style="color:red;">
 Avishek Ojha</p>. I'm currently living in Jhapa,Nepal. Let's connect!</p>
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
  
  
</head>
<body>
 
</body>
</html>

<body>
    <h1>Feedback Form</h1>
    <form action="submit_feedback.php" method="post">
        <label for="feedback">Your Feedback:</label><br>
        <textarea id="feedback" name="feedback" rows="4" cols="50" required></textarea><br>
        <input type="submit" value="Submit">
    </form>
</body>
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
<!DOCTYPE html>
<html>
<head>
    <title>Public Comment System</title>
</head>
<body>
    <h1>Comments</h1>
    <ul id="commentsList">
        <!-- Existing comments will be displayed here -->
    </ul>

    <h2>Add a Comment</h2>
    <form onsubmit="submitComment(event)">
        <label for="comment">Your Comment:</label><br>
        <textarea id="comment" name="comment" rows="4" cols="50" required></textarea><br>
        <input type="submit" value="Submit">
    </form>

    <script src="script.js"></script>
</body>
</html>
function submitComment(event) {
  event.preventDefault();
  const commentInput = document.getElementById("comment");
  const commentText = commentInput.value;

  // Create a new list item to display the comment
  const newCommentItem = document.createElement("li");
  newCommentItem.textContent = commentText;

  // Add the new comment to the comments list
  const commentsList = document.getElementById("commentsList");
  commentsList.appendChild(newCommentItem);

  // Clear the input field
  commentInput.value = "";

  // Send the comment to the server using an API call (Not implemented in this example)
  // You'll need a server-side script (e.g., PHP) to handle storing the comments in a database
}
?php
if ($_SERVER["REQUEST_METHOD"] === "POST" && isset($_POST["comment"])) {
    // Get the comment from the POST data
    $comment = $_POST["comment"];

    // Store the comment in a database or any other desired action

<footer>
<p>&copy; 2023 Avishek Ojha. All rights reserved.</p>
</footer>
