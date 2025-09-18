# 👋 Hi — I'm Agba Valentine Cheluchi (Krixx / KrixxValle)

<p align="center">
  <!-- Inline animated SVG: humanoid robot working at a desk -->
  <svg width="520" height="220" viewBox="0 0 520 220" xmlns="http://www.w3.org/2000/svg">
    <!-- background desk -->
    <rect x="0" y="180" width="520" height="40" rx="4" fill="#1f2937" />
    <!-- monitor -->
    <rect x="310" y="40" width="160" height="100" rx="8" fill="#0f172a" stroke="#334155" />
    <rect x="326" y="56" width="128" height="72" rx="4" fill="#010617" />
    <!-- screen text (cycling simulated) -->
    <text x="392" y="96" font-family="monospace" font-size="12" fill="#7dd3fc" text-anchor="middle">
      <tspan id="screenText">Initializing...</tspan>
    </text>
    <!-- laptop/keyboard -->
    <rect x="140" y="140" width="240" height="8" rx="2" fill="#0b1220" />
    <rect x="170" y="120" width="180" height="20" rx="4" fill="#0b1220" />
    <!-- humanoid robot body -->
    <!-- head -->
    <g id="robot" transform="translate(90,30)">
      <circle cx="60" cy="30" r="24" fill="#cbd5e1" stroke="#94a3b8"/>
      <!-- eyes -->
      <circle cx="50" cy="26" r="3" fill="#0f172a"/>
      <circle cx="70" cy="26" r="3" fill="#0f172a"/>
      <!-- mouth (blinking) -->
      <rect x="48" y="36" width="24" height="3" rx="1.5" fill="#0f172a">
        <animate attributeName="height" dur="2.5s" values="3;1;3" repeatCount="indefinite"/>
      </rect>

      <!-- neck -->
      <rect x="56" y="52" width="8" height="10" fill="#94a3b8"/>
      <!-- body -->
      <rect x="36" y="64" width="48" height="56" rx="6" fill="#cbd5e1" stroke="#94a3b8"/>
      <!-- left arm (typing) -->
      <g id="leftArm" transform="translate(36,76)">
        <rect x="-34" y="6" width="34" height="10" rx="4" fill="#cbd5e1" stroke="#94a3b8">
          <animateTransform attributeName="transform" attributeType="XML" type="rotate"
            values="-8  -2 11; 6 -2 11; -8 -2 11" dur="1.0s" repeatCount="indefinite" />
        </rect>
        <rect x="-48" y="14" width="32" height="6" rx="3" fill="#7c8798"/>
      </g>

      <!-- right arm (rests) -->
      <g id="rightArm" transform="translate(84,76)">
        <rect x="0" y="6" width="34" height="10" rx="4" fill="#cbd5e1" stroke="#94a3b8"/>
        <rect x="28" y="14" width="32" height="6" rx="3" fill="#7c8798" />
      </g>

      <!-- legs -->
      <rect x="46" y="120" width="12" height="18" rx="3" fill="#94a3b8"/>
      <rect x="62" y="120" width="12" height="18" rx="3" fill="#94a3b8"/>
    </g>

    <!-- small CPU light pulsing -->
    <circle cx="460" cy="184" r="4" fill="#10b981">
      <animate attributeName="r" dur="1.6s" values="3;5;3" repeatCount="indefinite"/>
      <animate attributeName="opacity" dur="1.6s" values="0.6;1;0.6" repeatCount="indefinite"/>
    </circle>

    <!-- subtle floating bits -->
    <g fill="#60a5fa" opacity="0.25">
      <circle cx="30" cy="30" r="2">
        <animate attributeName="cy" dur="6s" values="10;30;10" repeatCount="indefinite"/>
      </circle>
      <circle cx="500" cy="50" r="2">
        <animate attributeName="cx" dur="8s" values="490;500;490" repeatCount="indefinite"/>
      </circle>
    </g>

    <!-- keyboard key press indicator -->
    <rect x="194" y="138" width="8" height="4" rx="1" fill="#94a3b8">
      <animate attributeName="y" dur="1.0s" values="138;132;138" repeatCount="indefinite"/>
    </rect>
  </svg>
</p>

<p align="center">
  <em>Humanoid assistant, busy building AI systems, typing out solutions...</em>
</p>

---

## 🧭 About — TL;DR
- 🔭 I build **AI chatbots**, backend services (Django / FastAPI), and AI tooling.  
- 🧑‍💻 "Excellent vibe coder" — I prefer practical, well-documented solutions.  
- 🌍 Based in Owerri, Imo, Nigeria — I work with global clients.

---

## 🛠️ Tech & Tools
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,django,fastapi,git,github,linux,postgres,flutter" alt="skills"/>
</p>

---

## ✨ Highlights
- Built **CELIA** AI fitness lead-gen (2,995 leads in 2 months)  
- Reduced support tickets by **79.6%** at Dog-Daily with an AI assistant  
- Created production chatbots integrated with CRMs & scheduling systems

---

## 📈 GitHub
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=krixx646&show_icons=true&theme=tokyonight" alt="GitHub stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=krixx646&theme=tokyonight" alt="streak" />
</p>

---

## 📫 Connect
<p align="center">
  <a href="https://linkedin.com/in/valentine-cheluchi">LinkedIn</a> ·
  <a href="mailto:krixxvalle@gmail.com">Email</a> ·
  <a href="https://krixx.pythonanywhere.com">AI Services (demo)</a>
</p>

---

## 🧩 Want a higher-fidelity animation (GIF / Lottie / custom SVG)?
If you want a crisp GIF or Lottie animation (for a smoother arm movement, better shading, or several frames like the robot switching tasks), I can:
- generate a **custom GIF** (ideal for simple embedding), or
- produce a **Lottie JSON** you can host and render elsewhere, or
- create a **more detailed SVG** and export it as an optimized GIF.

Tell me which format you prefer and I’ll create the asset and update the README with it.
