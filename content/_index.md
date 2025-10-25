---
type: info
custom_title: "letterstamp — home"
BookToc: true
---
<!-- <p class="responsive-text">for a brief moment, i am back in melbourne</p>
<img src="/images/tree.png" alt="Image" style="display: relative; margin: 0 auto; width: 80%;"> -->

<div style="position: relative; text-align: center;">
  <img src="/images/house.png" alt="Image"
       style="position: absolute; top: 0; left: 50%; transform: translateX(-50%);
              width: 50%; z-index: 0; opacity: 0.8;">
  <p class="responsive-text shimmer"
     style="position: relative; z-index: 1; margin: 0;">
    for a brief moment, i am back in melbourne
  </p>
  <div style="position: relative; z-index: 2; margin-top: calc(20% + 1em); text-align: center;">
    <p style="margin: 0;">i've returned home temporarily for some <br>ear issues that require medical attention.<br> i will be posting more after that's sorted.<br><br>in the meantime, checkout my previous<a href="/posts" style="text-decoration: none; color: #dc143c;"> journal entries.</a> <br><br>
  </div>
</div>


<style>
  /* Default styles for larger screens */
  .responsive-text {
    font-family: 'Manifont', sans-serif;
    font-size: 60px;
    margin-bottom: 40px;
    color: #dc143c;
    transform: rotate(-3deg);
    padding-left: 10px;
  }

  /* Shimmer effect */
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

  /* Mobile-specific styles */
  @media (max-width: 600px) {
    .responsive-text {
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