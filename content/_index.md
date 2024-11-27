---
type: info
custom_title: "letterstamp — home"
BookToc: true
---
<div style="position: relative; display: inline-block; overflow: visible;">
  <img src="/images/landscape.png" alt="Landscape" style="width: 100%; height: auto;">
  <div style="position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: #FF4433; font-family: 'Linea', sans-serif; font-size: 80px; font-weight: bold; white-space: nowrap;">
    welcome to letterstamp
  </div>
</div>


Thanks for stopping by. Take a look around if you'd like.

I use this website to jot down my thoughts and share my travels.

You can see what I am currently up to <a href="/posts" style="color: #FF7F50; text-decoration: none;">here.</a>

<br>
<span style="text-align: right; display: block;"><ins>As of 27/11/2024, I am in:</ins></span>

<div id="typewriter"></div>

<script>
    const sentence = "Melbourne, Australia.";
    let index = 0;

    function typeWriter() {
        if (index < sentence.length) {
            document.getElementById("typewriter").textContent += sentence.charAt(index);
            index++;
            setTimeout(typeWriter, 100); // Adjust the speed here (in milliseconds)
        }
    }

    // Start the typewriter effect after the page is loaded
    window.onload = typeWriter;
</script>

<style>
    #typewriter {
        font-family: 'Orbit-Regular', monospace; /* Typewriter-style font */
        font-size: 15px; /* Size of the text */
        text-align: right;
        white-space: nowrap; /* Prevent line breaks */
        overflow: hidden; /* Hide overflowing content */
        color: #c970db; /* Text color green */
    }
</style>