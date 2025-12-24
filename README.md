<!-- =============================== -->
<!-- About Me | Short Intro + Journey -->
<!-- Author: VishalMakwana08         -->
<!-- =============================== -->
<html>
  <head>

    <style>
/* ===== Enhanced CSS ===== */
.title {
  font-size: 2.4rem;
  font-weight: 700;
  color: #58a6ff;
  animation: fadeInDown 1.2s ease-in-out;
}

.subtitle {
  font-size: 1.2rem;
  color: #c9d1d9;
  margin-bottom: 25px;
  animation: fadeIn 1.5s ease-in-out;
}

.card {
  max-width: 800px;
  margin: auto;
  padding: 25px;
  border-radius: 14px;
  background: linear-gradient(145deg, #0d1117, #161b22);
  box-shadow: 0 0 25px rgba(88, 166, 255, 0.15);
  animation: slideUp 1.2s ease-in-out;
}

.card p {
  font-size: 1.05rem;
  line-height: 1.8;
  color: #e6edf3;
  text-align: justify;
}

.highlight {
  color: #58a6ff;
  font-weight: 600;
}

/* ===== Animations ===== */
@keyframes fadeInDown {
  from {
    opacity: 0;
    transform: translateY(-30px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

@keyframes fadeIn {
  from {
    opacity: 0;
  }
  to {
    opacity: 1;
  }
}

@keyframes slideUp {
  from {
    opacity: 0;
    transform: translateY(40px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}
</style>
<script>
/* ===== Lightweight JS (Type Effect) ===== */
const text = `
I am a BCA student who began my journey in programming with my first C program.
That single program sparked my curiosity and pushed me deeper into the world of technology.

Over time, I developed a strong interest in web development and Python programming.
I enjoy learning how software works behind the scenes and continuously improve my skills.

I am enthusiastic about building a career in tech roles such as Software Developer,
Android Developer, and other technology-driven positions.
`;

let i = 0;
const speed = 20;

function typeEffect() {
  if (i < text.length) {
    document.getElementById("journey").innerHTML += text.charAt(i);
    i++;
    setTimeout(typeEffect, speed);
  }
}

typeEffect();
</script>
  </head>
  <body>
<div align="center">

  <h1 class="title">👋 Hi, I'm Vishal Makwana</h1>

  <p class="subtitle">
    BCA Student | Programmer | Web & Python Enthusiast
  </p>

</div>


<div class="card">

  <p id="journey"></p>

</div>

</body></html>
