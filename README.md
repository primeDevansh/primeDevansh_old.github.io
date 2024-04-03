# My Portfolio & Blog

Welcome to my portfolio and blog! Below, you'll find information about me and my work.

## About Me

I'm a passionate developer who loves creating beautiful and functional websites and applications.

## Portfolio

### Projects

- Project 1: [Project Name 1](#)
- Project 2: [Project Name 2](#)
- Project 3: [Project Name 3](#)

<details id="more-projects">
  <summary>View More Projects</summary>

  - Project 4: [Project Name 4](#)
  - Project 5: [Project Name 5](#)
</details>

## Blog

### Latest Posts

- [Post Title 1](#)
- [Post Title 2](#)
- [Post Title 3](#)

<details id="more-posts">
  <summary>View More Posts</summary>

  - [Post Title 4](#)
  - [Post Title 5](#)
</details>

<script>
  // JavaScript for animations and cool drop-downs
  
  // Function to toggle visibility of the "More Projects" section
  function toggleProjects() {
    var moreProjects = document.getElementById("more-projects");
    moreProjects.classList.toggle("show");
  }

  // Function to toggle visibility of the "More Posts" section
  function togglePosts() {
    var morePosts = document.getElementById("more-posts");
    morePosts.classList.toggle("show");
  }
</script>

<style>
  /* Style for drop-down sections */
  details {
    margin-bottom: 10px;
  }

  /* Style for drop-down summary */
  summary {
    cursor: pointer;
    font-weight: bold;
  }

  /* Style for drop-down content */
  details > div {
    display: none;
    padding-left: 20px;
  }

  /* Show drop-down content when summary is clicked */
  details[open] > div {
    display: block;
  }
</style>
