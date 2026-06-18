<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Untuk Kamu ❤️</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap');

body {
  margin: 0;
  font-family: 'Poppins', sans-serif;
  background: linear-gradient(135deg, #ff9a9e, #fad0c4);
  text-align: center;
  color: white;
  min-height: 100vh;
  overflow-x: hidden;
}

.card {
  margin: 30px auto;
  padding: 30px 20px;
  max-width: 400px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.2);
  backdrop-filter: blur(15px);
  -webkit-backdrop-filter: blur(15px);
  box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.3);
  transition: all 0.3s ease;
}

.hidden { display: none !important; }

button {
  padding: 12px 24px;
  border: none;
  border-radius: 25px;
  background: #ff4d6d;
  color: white;
  font-weight: 600;
  margin: 10px;
  cursor: pointer;
  box-shadow: 0 4px 15px rgba(255, 77, 109, 0.4);
  transition: transform 0.2s, background 0.2s;
}

button:hover {
  transform: scale(1.05);
  background: #ff758f;
}

input {
  padding: 10px 15px;
  border-radius: 20px;
  border: 1px solid rgba(255,255,255,0.5);
  background: rgba(255,255,255,0.9);
  color: #333;
  text-align: center;
  font-size: 16px;
  outline: none;
  margin-bottom: 10px;
  width: 80%;
  max-width: 250px;
}

/* Efek Hujan Hati */
.heart {
  position: fixed;
  top: -20px;
  font-size: 20px;
  user-select: none;
  pointer-events: none;
  animation: fall linear infinite;
}
@keyframes fall {
  to { transform: translateY(105vh); }
}

/* Memory game */
.grid {
  display: grid;
  grid-template-columns: repeat(4, 65px);
  gap: 10px;
  justify-content: center;
  margin-top: 20px;
}
.box {
  width: 65px;
  height: 65px;
  background: white;
  color: transparent;
  border-radius: 10px;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 24px;
  cursor: pointer;
  user-select: none;
  transition: background 0.3s, transform 0.2s;
}
.box.flipped {
  background: rgba(255, 255, 255, 0.9);
  color: initial;
}
.box.matched {
  background: #ffccd5;
  color: #ff4d6d;
  pointer-events: none;
}

/* Catch game */
#heartGame {
  position: relative;
  height: 250px;
  background: rgba(255,255,255,0.1);
  border-radius: 15px;
  overflow: hidden;
  margin-bottom: 15px;
}
.catch {
  position: absolute;
  font-size: 30px;
  cursor: pointer;
  user-select: none;
  animation: pop 0.3s ease;
}
@keyframes pop {
  0% { transform: scale(0); }
  100% { transform: scale(1); }
}

/* Suwit Game */
.rps-options {
  display: flex;
  justify-content: space-around;
  margin-top: 20px;
}
.rps-btn {
  font-size: 30px;
  background: white;
  border-radius: 50%;
  width: 60px;
  height: 60px;
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  box-shadow: 0 4px 10px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}
.rps-btn:hover {
  transform: scale(1.1);
}

#end p {
  line-height: 1.8;
  font-size: 15px;
  text-align: left;
  white-space: pre-line;
}
</style>
</head>

<body>

<audio autoplay loop>
<source src="https://www.bensound.com/bensound-music/bensound-romantic.mp3" type="audio/mp3">
</audio>

<h1 style="margin-top: 30px; text-shadow: 0 2px 5px rgba(0,0,0,0.1);">Untuk Kamu ❤️</h1>

<div id="story" class="card">
  <p id="text" style="font-size: 18px; font-weight: 300;"></p>
  <button onclick="next()">Lanjut</button>
</div>

<div id="game1" class="card hidden">
  <h2>Memory Game ❤️</h2>
  <p style="font-size: 13px;">Cocokkan dua emoji yang sama ya!</p>
  <div class="grid" id="grid"></div>
</div>

<div id="game2" class="card hidden">
  <h2>Kode Rahasia 🔐</h2>
  <p>Hint: tanggal spesial kita (format: ddmmyy / mmd home / sesuai set)</p>
  <p style="font-size: 12px; opacity: 0.8;">Contoh default: 1110</p>
  <input id="kode" placeholder="Masukkan kode..."> <br>
  <button onclick="cekKode()">Cek</button>
  <p id="kodeHasil" style="font-weight: 600;"></p>
</div>

<div id="game3" class="card hidden">
  <h2>Tangkap Hatinya 💓</h2>
  <p style="font-size: 13px;">Ketuk hati yang muncul sampai skor 5!</p>
  <div id="heartGame"></div>
  <p style="font-size: 18px; font-weight: 600;">Score: <span id="score">0</span></p>
</div>

<div id="gameScramble" class="card hidden">
  <h2>Susun Kata ✨</h2>
  <p style="font-size: 14px;">Susun huruf acak ini menjadi kata yang romantis!</p>
  <h3 id="scrambledWord" style="font-size: 28px; letter-spacing: 3px; color: #ff4d6d; background: white; display: inline-block; padding: 5px 15px; border-radius: 10px;">KUA CATIN KUMA</h3>
  <br><br>
  <input id="scrambleInput" placeholder="Jawaban kamu..."> <br>
  <button onclick="cekScramble()">Kirim</button>
  <p id="scrambleHasil" style="font-weight: 600;"></p>
</div>

<div id="gameRPS" class="card hidden">
  <h2>Suwit Sweet ✌️✊✋</h2>
  <p style="font-size: 13px;">Kamu harus menang melawan aku 2 kali!</p>
  <div class="rps-options">
    <div class="rps-btn" onclick="playRPS('✌️')">✌️</div>
    <div class="rps-btn" onclick="playRPS('✊')">✊</div>
    <div class="rps-btn" onclick="playRPS('✋')">✋</div>
  </div>
  <p id="rpsDetail" style="margin-top: 15px; font-size: 14px; min-height: 40px;"></p>
  <p style="font-size: 16px; font-weight: 600;">Skor Kamu: <span id="rpsScore">0</span> / 2</p>
</div>

<div id="game4" class="card hidden">
  <h2>Kalau aku salah kamu...</h2>
  <button onclick="pilih('marah')">Marah 😢</button>
  <button onclick="pilih('maaf')">Maafin ❤️</button>
  <p id="pilihan" style="margin-top: 15px; font-weight: 600;"></p>
</div>

<div id="game5" class="card hidden">
  <h2>Susun Cerita Kita 🧩</h2>
  <p style="text-align: left; max-width: 200px; margin: 10px auto;">
    1. Ketemu<br>
    2. Sayang<br>
    3. Berantem<br>
    4. Baikan
  </p>
  <input id="urutan" placeholder="Contoh: 1234"> <br>
  <button onclick="cekUrutan()">Cek</button>
  <p id="hasilUrutan" style="font-weight: 600;"></p>
</div>

<div id="end" class="card hidden">
  <h2>💔 Dari Aku...</h2>
  <p>
  Selama 9 bulan ini...  
  aku sadar aku bukan pasangan yang sempurna.  

  Aku sering ga nurut...  
  sering keliatan kayak ga peduli...  
  bahkan kadang bikin kamu ngerasa ga dihargain sebagai pasangan aku.  

  Dan itu semua salah aku.  

  Aku minta maaf... bukan cuma sekadar kata,  
  tapi karena aku sadar aku udah nyakitin orang yang paling aku sayang.  

  Terima kasih.
  karena kamu masih bertahan sejauh ini udah sayang sama aku selalu .  

  Terima kasih karena kamu ga pergi walaupun aku sering bikin kamu sedih.  

  Jujur... aku takut kehilangan kamu.  

  Aku mungkin belum jadi yang terbaik,  
  tapi aku bener-bener pengen belajar jadi lebih baik buat kamu dan selalu ingin ngasih yang terbaik buat kamu .  

  Karena kamu itu penting banget buat aku... ❤️
aku boleh minta sesuatu? jangan terlalu kasar ya sama aku terkadang aku juga sedih dan sakit tapi aku udah maafin kok rasa sayang aku lebih besar dari pada luka aku 

  Perjalanan kita panjang, jangan nyerah, kita harus saling sayang saling peduli jangan nyakitin satu sama lain.

  Aku mau kita lewatin terus masalah apapun situasinya jangan sampai kita malah jadi saling tidak peduli dengan kondisi masing masing banyak hal yang harus kita lakuin dan banyak hal yang harus kita pelajari bareng bareng, jangan selalu ngerasa sendiri apapun yang kamu rasain kamu boleh cerita ke aku disini aku selalu mau bantu kamu support kamu kita bakal hadapin semuanya ber2 .  

  Aku sayang kamu selalu FATHUR RAHMAN AL GHOZI. 💕
  </p>
</div>

<script>
/* 1. LOGIKA TEKS PEMBUKAAN */
let teks = [
  "Hai kamu...",
  "Aku tau aku banyak salah...",
  "Aku mau kamu ngerasain sesuatu dulu lewat game ini...",
  "Main ya ❤️"
];
let i = 0;
document.getElementById("text").innerText = teks[0];

function next() {
  i++;
  if(i < teks.length) {
    document.getElementById("text").innerText = teks[i];
  } else {
    document.getElementById("story").classList.add("hidden");
    startMemory();
  }
}

/* 2. LOGIKA MEMORY GAME (PENCERMINAN KARTU) */
let cards = ["❤️","😢","❤️","😢","💕","💔","💕","💔"];
cards.sort(() => 0.5 - Math.random());
let flippedCards = [];
let matchedCount = 0;

function startMemory() {
  document.getElementById("game1").classList.remove("hidden");
  let grid = document.getElementById("grid");

  cards.forEach((emoji, index) => {
    let div = document.createElement("div");
    div.className = "box";
    div.dataset.value = emoji;
    div.dataset.index = index;
    
    div.onclick = function() {
      if (flippedCards.length < 2 && !this.classList.contains('flipped') && !this.classList.contains('matched')) {
        this.classList.add('flipped');
        this.innerText = emoji;
        flippedCards.push(this);

        if (flippedCards.length === 2) {
          setTimeout(checkMatch, 700);
        }
      }
    };
    grid.appendChild(div);
  });
}

function checkMatch() {
  let [card1, card2] = flippedCards;
  if (card1.dataset.value === card2.dataset.value) {
    card1.classList.add('matched');
    card2.classList.add('matched');
    matchedCount += 2;
    if (matchedCount === cards.length) {
      setTimeout(() => {
        document.getElementById("game1").classList.add("hidden");
        document.getElementById("game2").classList.remove("hidden");
      }, 1000);
    }
  } else {
    card1.classList.remove('flipped');
    card2.classList.remove('flipped');
    card1.innerText = "";
    card2.innerText = "";
  }
  flippedCards = [];
}

/* 3. LOGIKA KODE RAHASIA */
function cekKode() {
  let k = document.getElementById("kode").value;
  // Kamu bisa mengganti "0901" dengan tanggal jadian / tanggal spesial kalian di bawah ini
  if(k === "1110") {
    document.getElementById("game2").classList.add("hidden");
    startCatch();
  } else {
    document.getElementById("kodeHasil").innerText = "Salah 😢 Coba ingat lagi tanggal berharga kita.";
  }
}

/* 4. LOGIKA CATCH GAME (TANGKAP HATI) */
let score = 0;
let catchInterval;

function startCatch() {
  document.getElementById("game3").classList.remove("hidden");
  let area = document.getElementById("heartGame");

  catchInterval = setInterval(() => {
    let h = document.createElement("div");
    h.className = "catch";
    h.innerText = "❤️";
    
    h.style.left = Math.random() * (area.clientWidth - 30) + "px";
    h.style.top = Math.random() * (area.clientHeight - 40) + "px";

    h.onclick = () => {
      score++;
      document.getElementById("score").innerText = score;
      h.remove();

      if(score >= 5) {
        clearInterval(catchInterval);
        setTimeout(() => {
          document.getElementById("game3").classList.add("hidden");
          document.getElementById("gameScramble").classList.remove("hidden");
        }, 500);
      }
    };

    area.appendChild(h);
    setTimeout(() => { if(h.parentNode) h.remove(); }, 1500);
  }, 700);
}

/* 5. LOGIKA GAME BARU - SUSUN KATA */
function cekScramble() {
  let jawaban = document.getElementById("scrambleInput").value.trim().toLowerCase();
  if (jawaban === "AKU CINTA KAMU") {
    document.getElementById("scrambleHasil").innerText = "Bener! Hebat banget 🥰";
    setTimeout(() => {
      document.getElementById("gameScramble").classList.add("hidden");
      document.getElementById("gameRPS").classList.remove("hidden");
    }, 1500);
  } else {
    document.getElementById("scrambleHasil").innerText = "Salah 🥺 Clue-nya: Perasaan aku ke kamu.";
  }
}

/* 6. LOGIKA GAME BARU - SUWIT SWEET */
let rpsWinCount = 0;
function playRPS(pilihanUser) {
  let choices = ['✌️', '✊', '✋'];
  let pilihanBot = choices[Math.floor(Math.random() * 3)];
  let detail = `Kamu pilih ${pilihanUser} vs Aku pilih ${pilihanBot}<br>`;
  
  if (pilihanUser === pilihanBot) {
    detail += "Seri! Yuk coba lagi 🤝";
  } else if (
    (pilihanUser === '✌️' && pilihanBot === '✋') ||
    (pilihanUser === '✊' && pilihanBot === '✌️') ||
    (pilihanUser === '✋' && pilihanBot === '✊')
  ) {
    detail += "Kamu menang! Horeee 🎉";
    rpsWinCount++;
  } else {
    detail += "Aku menang 😜 Jangan menyerah!";
  }
  
  document.getElementById("rpsDetail").innerHTML = detail;
  document.getElementById("rpsScore").innerText = rpsWinCount;
  
  if (rpsWinCount >= 2) {
    setTimeout(() => {
      document.getElementById("gameRPS").classList.add("hidden");
      document.getElementById("game4").classList.remove("hidden");
    }, 2000);
  }
}

/* 7. LOGIKA PILIHAN RESPONS USER */
function pilih(pilihanUser) {
  if(pilihanUser === 'marah') {
    document.getElementById("pilihan").innerText = "Boleh kok kalau mau marah... Tapi dengerin penjelasanku setelah ini ya? 🥺";
  } else {
    document.getElementById("pilihan").innerText = "Makasih banyak ya udah berlapang dada... ❤️";
  }
  
  setTimeout(() => {
    document.getElementById("game4").classList.add("hidden");
    document.getElementById("game5").classList.remove("hidden");
  }, 2500);
}

/* 8. LOGIKA PUZZLE URUTAN JADILAH CERITA */
function cekUrutan() {
  let u = document.getElementById("urutan").value;
  if(u === "3412") {
    document.getElementById("game5").classList.add("hidden");
    document.getElementById("end").classList.remove("hidden");
  } else {
    document.getElementById("hasilUrutan").innerText = "Urutannya belum pas, coba lagi yuk! ❤️";
  }
}

/* EFEK LATAR BELAKANG HUJAN HATI */
setInterval(() => {
  let h = document.createElement("div");
  h.className = "heart";
  h.innerText = "❤️";
  h.style.left = Math.random() * 100 + "vw";
  h.style.animationDuration = (Math.random() * 3 + 2) + "s";
  h.style.opacity = Math.random() * 0.7 + 0.3;
  document.body.appendChild(h);
  setTimeout(() => h.remove(), 5000);
}, 400);
</script>

</body>
</html>
