
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For My Love ❤️</title>
<style>
/* --- Basic Styles --- */
body {
    margin: 0;
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg, #ff758c, #ff7eb3);
    color: rgb(252, 249, 249);
    text-align: center;
    overflow-x: hidden;
}
.container {
    padding: 20px 15px;
    max-width: 900px;
    margin: auto;
    animation: fadeIn 2s ease-in-out;
}

/* --- Header Glow --- */
.glow-name {
    font-size: 40px;
    font-weight: bold;
    animation: glow 2s infinite alternate;
    margin-bottom: 20px;
}
@keyframes glow {
    from { text-shadow: 0 0 10px white, 0 0 20px pink; }
    to { text-shadow: 0 0 20px white, 0 0 40px red; }
}

/* --- Profile Photo --- */
.photo-circle {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    overflow: hidden;
    margin: 20px auto;
    box-shadow: 0 0 25px #ff69b4;
}
.photo-circle img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

/* --- Paragraphs --- */
p, .section p {
    max-width: 95%;
    margin: 15px auto;
    text-align: center;
    line-height: 1.6;
}

/* --- Gallery --- */
.gallery {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 5px;
    margin: 10px 0;
}
.gallery img {
    width: 45%;
    max-width: 150px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    transition: transform 0.5s;
}
.gallery img:hover { transform: scale(1.1); }

/* --- Videos --- */
video {
    width: 90%;
    max-width: 300px;
    margin: 10px auto;
    display: block;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
}

/* --- Buttons --- */
button {
    margin-top: 20px;
    padding: 12px 25px;
    font-size: 16px;
    border: none;
    border-radius: 8px;
    background-color: white;
    color: #ff4b7d;
    cursor: pointer;
    transition: 0.3s;
    display: block;
    margin-left: auto;
    margin-right: auto;
}
button:hover {
    background-color: #ff4b7d;
    color: white;
    transform: scale(1.05);
}

/* --- Sliders --- */
.slider {
    margin-top: 20px;
    min-height: 100px;
    position: relative;
}
.slide {
    position: absolute;
    width: 100%;
    opacity: 0;
    transition: opacity 1s ease-in-out;
    font-size: 18px;
    line-height: 1.6;
    padding: 0 10px;
}
.slide.active { opacity: 1; position: relative; }

/* --- Popups --- */
.popup {
    position: fixed;
    top: 0; left: 0;
    width: 100%; height: 100%;
    background: rgba(0,0,0,0.6);
    display: none;
    justify-content: center;
    align-items: center;
    z-index: 10;
}
.popup-content {
    background: white;
    padding: 25px;
    border-radius: 15px;
    max-width: 400px;
    color: #333;
    text-align: center;
}

/* --- Response Message --- */
#response {
    margin-top: 15px;
    font-size: 20px;
    color: #ff2e88;
    font-weight: bold;
}

/* --- Heartbeat Animation --- */
.heartbeat { animation: heartbeat 1s infinite; }
@keyframes heartbeat {
    0%,50%,100% { transform: scale(1); }
    25%,75% { transform: scale(1.1); }
}

/* --- Countdown Timer --- */
#countdown { margin-top: 15px; font-size: 20px; font-weight: bold; }

/* --- Floating Hearts --- */
.heart {
    position: fixed;
    bottom: -20px;
    font-size: 18px;
    animation: float 6s linear infinite;
}
@keyframes float {
    0% { transform: translateY(0) scale(1); opacity: 1; }
    100% { transform: translateY(-700px) scale(1.3); opacity: 0; }
}

/* --- Fade In Animation --- */
@keyframes fadeIn { from {opacity: 0;} to {opacity: 1;} }

/* --- Responsive for Mobile --- */
@media (max-width: 600px) {
    .glow-name { font-size: 35px; }
    .photo-circle { width: 120px; height: 120px; }
    .gallery img { width: 80%; max-width: 150px; }
    video { max-width: 90%; }
    button { font-size: 14px; padding: 10px 20px; }
    p { text-align: center; }
}
</style>
</head>
<body>

<div class="container">

    <div class="glow-name">BANDANA(Panda/Fucchi) ❤️<br>My Love❤️😗</div>

    <div class="photo-circle">
        <img src="photo her.jpeg" alt="Her Photo">
    </div>

    <h2>I Miss You So Much 🤍</h2>

    <!-- Main Slider -->
    <div class="slider" id="mainSlider">
        <div class="slide active">Every day without you feels incomplete. I miss your voice, your smile, and the comfort you bring into my life.</div>
        <div class="slide">I keep thinking about our memories, replaying them in my mind, wishing I could pause those beautiful moments forever.</div>
        <div class="slide">I know this week might feel uncomfortable for you. I truly wish I could be beside you, just to gently hold you.</div>
        <div class="slide">I miss hugging you so badly. I just want to wrap my arms around you and let you rest peacefully.</div>
        <div class="slide">Every single day without you feels a little incomplete. I miss the way you smile, the way your voice makes everything feel calm, and the way even simple moments become special when you are around.</div>
    </div>

    <!-- Surprise Section -->
    <div class="section">
        <h2>You Are My Safe Place</h2>
        <p>
            I know this week might feel uncomfortable for you. If you feel okay, can we meet this week? I don’t want anything except to gently hold you, let you rest peacefully in my arms, and make you feel safe and cared for 🤍<br>
            I'm always with you mero baccha ❤️😗<br>
            Don’t worry about anything. I’m right here if you need me 🤍 My arms will always be open to give you a warm hug that makes you feel safe and cared🫂❤️<br>
            That's my real love language for you ❤️
        </p>

        <button id="surpriseBtn">Click For Hidden Messages 💌💕</button>
        <div id="surprise" style="display:none; margin: 15px auto; max-width: 600px; font-size: 18px; line-height: 1.6; background: rgba(255,255,255,0.2); padding: 15px; border-radius: 10px;">
            You are safe with me 🤍<br>
            You don’t have to be strong all the time 🌸<br>
            Let me protect your peace 🌙<br>
            Your comfort matters to me most ❤️
        </div>
    </div>

    <h2>📖 Our Story</h2>
    <p>
        From the very first moment we connected, something felt truly special.
        You became my comfort, my peace, and my happiness in ways I never imagined.
        Every memory with you is precious—every laugh, every quiet moment, every silly conversation we shared.
        Even the simplest things, like talking about our day or just being near each other, make my heart feel full.
        You are not just part of my life — you are the most beautiful part of it.
        Being with you makes the world brighter, and even when we are apart, your presence stays with me, gently guiding me through every day.
        I cherish every moment we’ve shared, and I look forward to creating countless more memories together.
    </p>

    <h3>📸 Our Memories</h3>
    <div class="gallery">
        <img src="photo1.jpeg">
        <img src="photo2.jpeg">
        <img src="photo3.jpeg">
        <img src="photo4.jpeg">
        <img src="photo5.jpeg">
        <img src="photo6.jpeg">
    </div>

    <h3>🎥 Our Moments</h3>
    <video controls src="video1.mp4"></video>
    <video controls src="video2.mp4"></video>
    <video controls src="video3.mp4"></video>

    <button onclick="showPopup()">Click For A Message 💌</button>
    <div id="response"></div>

    <div id="countdown">
        Waiting to hug you... ⏳
        <div id="timer"></div>
    </div>

</div>

<!-- Popup -->
<div class="popup" id="popup">
  <div class="popup-content heartbeat">
    <h3>Can We Meet This Week? 🤍</h3>
    <p>
      I want to tell you something from my heart. Can we meet this week? Even for a short while? I just want to gently hold you and let you rest peacefully. Only if you feel comfortable. Your comfort matters most to me. 🤍
    </p>
    <button id="yesBtn">Yes ❤️</button>
    <button id="noBtn">No ❌</button>
  </div>
</div>

<script>
// --- Sliders ---
const mainSlides = document.querySelectorAll("#mainSlider .slide");
let mainIndex = 0;
setInterval(() => {
    mainSlides[mainIndex].classList.remove("active");
    mainIndex = (mainIndex + 1) % mainSlides.length;
    mainSlides[mainIndex].classList.add("active");
}, 4000);

// --- Surprise button ---
const surpriseBtn = document.getElementById("surpriseBtn");
const surpriseDiv = document.getElementById("surprise");
surpriseBtn.addEventListener("click", () => {
    surpriseDiv.style.display = "block";
    surpriseDiv.classList.add("heartbeat");
    surpriseDiv.scrollIntoView({ behavior: "smooth", block: "center" });
});

// --- Popup ---
const popup = document.getElementById("popup");
const yesBtn = document.getElementById("yesBtn");
const noBtn = document.getElementById("noBtn");
const response = document.getElementById("response");

function showPopup() { popup.style.display = "flex"; }
function closePopup() { popup.style.display = "none"; }

yesBtn.addEventListener("click", () => {
    closePopup();
    response.innerHTML = "Yayyy ❤️ I can't wait to see you and gently hug you! I love you Baccha ❤️";
});
noBtn.addEventListener("click", () => {
    popup.querySelector(".popup-content").innerHTML = `
        <h3>It's Okay 🤍</h3>
        <p>
        I completely understand. I just want you to feel safe and happy. 
        Whenever you're ready, even for a little while, I’ll be here with open arms. 
        I love you and your comfort matters most to me 💖
        </p>
        <button onclick="closePopup()">Close 🤍</button>
    `;
});

// --- Countdown ---
const targetDate = new Date();
targetDate.setDate(targetDate.getDate() + 3);
function updateCountdown() {
    const now = new Date().getTime();
    const distance = targetDate - now;
    const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance / (1000 * 60 * 60)) % 24);
    const minutes = Math.floor((distance / 1000 / 60) % 60);
    const seconds = Math.floor((distance / 1000) % 60);
    document.getElementById("timer").innerHTML =
        days + "d " + hours + "h " + minutes + "m " + seconds + "s ";
    if (distance < 0) {
        document.getElementById("timer").innerHTML = "I’m ready to hug you now ❤️";
    }
}
setInterval(updateCountdown, 1000);

// --- Floating Hearts ---
function createHeart() {
    const heart = document.createElement("div");
    heart.classList.add("heart");
    heart.innerHTML = "❤️";
    heart.style.left = Math.random() * 100 + "vw";
    heart.style.animationDuration = (Math.random() * 3 + 3) + "s";
    document.body.appendChild(heart);
    setTimeout(() => heart.remove(), 6000);
}
setInterval(createHeart, 500);
</script>

</body>
</html>

