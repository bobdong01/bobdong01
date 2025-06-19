# Hey there :wave:

<img src="https://raw.githubusercontent.com/sagar-viradiya/sagar-viradiya/master/resources/banner.png" alt="Hello world">

<!-- Random Quote -->
<div id="random-quote" align="center" style="font-style: italic; margin: 1em 0;"></div>

<p align="center"> 
  Visitor count<br>
  <img src="https://profile-counter.glitch.me/bobdong01/count.svg" />
</p>

<!-- Fetch and insert a random quote -->
<script>
  fetch('https://api.quotable.io/random')
    .then(res => res.json())
    .then(({ content, author }) => {
      document.getElementById('random-quote').innerText = `“${content}” — ${author}`;
    })
    .catch(() => {
      document.getElementById('random-quote').innerText = "“Stay curious, stay learning.” — Unknown";
    });
</script>


## About me

I am a student at Johns Hopkins majoring in Computer Science and Applied Math. Currently I am working on some machine learning projects. Feel free to reach out to me! I am happy to chat!

## Get in touch :coffee:
- [LinkedIn](https://www.linkedin.com/in/bob-dong-990236227/)
