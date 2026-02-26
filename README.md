# Painel-rickznx
.splash{
  position:fixed;
  width:100%;
  height:100vh;
  background:linear-gradient(135deg,#0d001a,#3a0066);
  display:flex;
  justify-content:center;
  align-items:center;
  z-index:999;
  animation:fadeOut 3s forwards;
  animation-delay:2.5s;
}

.logo{
  font-size:40px;
  color:#b300ff;
  text-shadow:0 0 20px #b300ff, 0 0 40px #8000ff;
  animation:glowPulse 1.5s infinite alternate;
}

@keyframes glowPulse{
  from{ text-shadow:0 0 10px #b300ff; }
  to{ text-shadow:0 0 40px #ff00ff; }
}

@keyframes fadeOut{
  to{ opacity:0; visibility:hidden; }
}