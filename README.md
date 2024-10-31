# Welcome to My GitHub Profile!

<p align="center">
  <img src="https://img.shields.io/github/commit-activity/y/{YOUR_USERNAME}/{YOUR_REPOSITORY}" alt="Commit Activity">
</p>

<h2>👋 Hello, I'm {YOUR_NAME}!</h2>

<p>Current Date and Time:</p>
<p id="datetime"></p>

<script>
  // JavaScript to update the current date and time
  function updateDateTime() {
    var now = new Date();
    var options = { weekday: 'long', year: 'numeric', month: 'long', day: 'numeric', hour: '2-digit', minute: '2-digit', second: '2-digit' };
    document.getElementById('datetime').innerHTML = now.toLocaleDateString('en-US', options);
  }

  setInterval(updateDateTime, 1000);
</script>

### About Me
I’m a software developer with a passion for creating impactful software. I'm currently working on:
- **Project 1**
- **Project 2**

---

### GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username={YOUR_USERNAME}&show_icons=true&theme=radical" alt="GitHub Stats">
</p>

Feel free to explore my repositories and connect with me on [LinkedIn](https://www.linkedin.com/in/{YOUR_LINKEDIN_USERNAME}/)!

---

**Last Updated:** <span id="lastUpdated"></span>
<script>
  document.getElementById('lastUpdated').innerText = new Date().toLocaleDateString();
</script>
