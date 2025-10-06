---
layout: default
title: "About"
nav_order: 1
---

<!-- Dynamic Inspirational Quote Section -->
<div id="quote-section" style="font-style: italic; color: #555; margin: 20px 0; font-size: 1.2rem;">
  <!-- This will be replaced by JavaScript -->
</div>

<!-- JavaScript to display a random quote -->
<script>
  const quotes = [
    "Success is not final, failure is not fatal: It is the courage to continue that counts. – Winston Churchill",
    "The only way to do great work is to love what you do. – Steve Jobs",
    "It does not matter how slowly you go as long as you do not stop. – Confucius",
    "You have to learn the rules of the game. And then you have to play better than anyone else. – Albert Einstein",
    "The future belongs to those who believe in the beauty of their dreams. – Eleanor Roosevelt",
    "Do not wait to strike till the iron is hot, but make it hot by striking. – William Butler Yeats",
    "The difference between a successful person and others is not a lack of strength, not a lack of knowledge, but rather a lack in will. – Vince Lombardi",
    "If you are not willing to risk the usual, you will have to settle for the ordinary. – Jim Rohn"
  ];

  // Function to display a random quote
  function getRandomQuote() {
    const randomIndex = Math.floor(Math.random() * quotes.length);
    document.getElementById("quote-section").innerText = quotes[randomIndex];
  }

  // Call the function when the page loads
  window.onload = getRandomQuote;
</script>


<div class="headshot-container" style="display: flex; align-items: center; flex-wrap: wrap;">
  <img 
    src="/assets/img/headshot.jpg" 
    alt="Hossein Mahani" 
    style="width: 4cm; height: 4cm; border-radius: 25%; object-fit: cover; margin-right: 15px;">
  <div class="name-container">
    <h1 id="hossein-name">Hossein Mahani</h1>
    <p>*Mechanical Engineer & Researcher*</p>
  </div>
</div>

<h2 id="about-me">About Me</h2>
<p style="text-align: justify; text-justify: inter-word; line-height: 1.6;">
  I hold a Master's degree in Mechanical Engineering and have specialized in additive manufacturing and material processing. My research includes two journal publications, and one ongoing publication related to metal 3D printing, in addition to holding two national patents in material processing and mechanical design. With over two years as a research assistant, I have honed my skills in data analysis, simulations, and proposing innovative methods for solving complex engineering challenges. I am also proficient in CAD and FEA tools, which support my work in 3D printing and material development. I have an IELTS score of 7 and GRE score of 315, which reflect my strong academic communication. As a passionate problem solver and researcher, I have learned that every problem is an opportunity for new discovery. I have led multiple academic projects and continue to push the boundaries of additive manufacturing, aiming to expand its application in engineering and biomedical fields.
</p>


## Research Interests
- Additive manufacturing (metal & polymer 3D printing)  
- Nanocomposites  
- Powder Processing  
- Materials characterization  
- Finite Element Analysis (FEA)
  
   


> See  **[CV](/cv)** , **[Publications](/publications)** , and **[Contact](/contact)** for details.
