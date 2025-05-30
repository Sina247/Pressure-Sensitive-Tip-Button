# Pressure-Sensitive Tip Button [Webflow × GSAP]

A micro-interaction demo recreating Webflow’s “hold to flip coin” tipping button, powered by GSAP Physics2D and Tweakpane. Users press “Leave Tip” and feel responsive, physics-based feedback as the coin flips, tumbles, and lands with configurable bounce, spin, and velocity.

---

## 🚀 Features  
- **Pressure-sensitive animation**: Button rotation on press influences flip distance, spin count, and bounce.  
- **Physics-based coin throw**: Uses GSAP’s Physics2DPlugin for realistic trajectory, gravity, and collision effects.  
- **Dynamic configuration**: Tweakpane GUI lets you live-adjust timeScale, bounce, velocity, distance, spins, theme, and muted state.  
- **Mobile & desktop**: Touch-friendly “press and hold” behavior with fallback to click.  
- **Pure HTML/CSS/JS**: No build tools required—ES modules via Skypack CDN.  

---

## 🔨 Tech Stack  
- **GSAP** v3.13.0 + Physics2DPlugin  
- **Tweakpane** v4.0.4 for runtime controls  
- **Normalize.css** & **Google Fonts** (Inter, Gloria Hallelujah)  
- Vanilla ES modules (no bundler)  

---

## 💻 Usage  

1. **Install** (optional clone)  
   ```bash
   git clone https://github.com/your-username/pressure-tip-button.git
   cd pressure-tip-button
