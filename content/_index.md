---
type: info
custom_title: "letterstamp — home"
BookToc: true
---
<!-- <p class="responsive-text">for a brief moment, i am back in melbourne</p>
<img src="/images/tree.png" alt="Image" style="display: relative; margin: 0 auto; width: 80%;"> -->

<div style="position: relative; text-align: center;">
  <div style="position: relative; width: 30%; margin: 0 auto;">
    <img src="/images/a_dithered.gif" alt="Image"
         style="width: 100%; height: auto; opacity: 0.8; display: block;">
  </div>
  <p class="responsive-text-2"
     style="position: absolute; top: 0; left: 0; right: 0; z-index: 1; margin: 0;">
    <span style="color: #dc143c ;">I AM BACK IN MELBOURNE</span>
  </p>
    <p class="responsive-text shimmer"
     style="position: absolute; top: 0; left: 0; right: 0; z-index: 0; margin: 15;">
    <span style="color: #0c1c1dff ;"><br><br>*temporarily</span>
  </p>
  <div style="position: relative; z-index: 2; margin-top: 1em; text-align: center;">
    <p style="margin: 0;">i've returned home temporarily for some <br>ear issues that require medical attention.<br> i will be posting more after that's sorted.<br><br>in the meantime, checkout my previous<a href="/posts" style="text-decoration: none; color: #dc143c;"> journal entries.</a>
  </div>
</div>


<style>
  .responsive-text {
    font-family: 'Der75', sans-serif;
    font-size: 50px;
    margin-bottom: 40px;
    color: #dc143c;
    transform: rotate(4deg);
    padding-left: 300px;
  }

  .responsive-text-2 {
    font-family: 'Der75', sans-serif;
    font-size: 60px;
    margin-bottom: 40px;
    color: #000000ff;
    transform: rotate(-3deg);
    padding-left: 10px;
  }

  .shimmer {
    background: linear-gradient(
      to right,
      #dc143c 0%,
      #ff758c 20%,
      #dc143c 40%,
      #dc143c 100%
    );
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    background-size: 200% auto;
    animation: shimmer 10s linear infinite;
  }

  @keyframes shimmer {
    0% {
      background-position: 200% center;
    }
    100% {
      background-position: -200% center;
    }
  }

  @media (max-width: 600px) {
    .responsive-text {
      padding-left: 20px;
      font-size: 35px;
    }
    .responsive-text-2 {
      padding-left: 20px;
      font-size: 35px;
    }
  }
</style>


<!-- 
Thanks for stopping by. Take a look around if you'd like. 

I use this website to jot down my thoughts <br>and share my travels.

<br>
<span style="text-align: left; display: block;"><ins>As of 10/07/2025, I am in:</ins></span>

<div id="typewriter"></div>

<script>
    const sentence = "Hanoi, Vietnam.";
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
        text-align: left;
        white-space: nowrap; /* Prevent line breaks */
        overflow: hidden; /* Hide overflowing content */
        color: #c970db; /* Text color green */
    }
</style> 
-->