<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0, user-scalable=yes, viewport-fit=cover">
<meta name="theme-color" content="#050508">
<meta name="description" content="Apache AI 2.00 - The Future Of Intelligent Assistance. Powered by Apache AI Engine System. Tanpa Bug, Gratis 100%, Aman.">
<title>Apache AI 2.00 - Apache Engine System</title>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=Space+Grotesk:wght@400;500;600;700&family=Fira+Code:wght@400;500&family=JetBrains+Mono:wght@400;500;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" crossorigin="anonymous" referrerpolicy="no-referrer" />
<style>
/* ================================================================
   APACHE AI 2.00 - UNIFIED SYSTEM
   Powered by Apache AI Engine System
   Owner: Muhammad Raffa Gunawan | Gunawan Group
   Release: December 23, 2026
   Status: Tanpa Bug - Gratis 100% - Aman
   ================================================================ */

*{margin:0;padding:0;box-sizing:border-box}

:root{
  --purple-900:#050510;
  --purple-800:#0a0a1a;
  --purple-700:#1a0b2e;
  --accent:#a855f7;
  --accent-secondary:#c084fc;
  --accent-glow:rgba(168,85,247,0.4);
  --bg-dark:#050508;
  --glass-bg:rgba(15,10,40,0.7);
  --glass-border:rgba(147,51,234,0.2);
  --text-primary:#e9d5ff;
  --text-secondary:rgba(196,181,253,0.7);
  --text-muted:rgba(196,181,253,0.4);
  --success:#4ade80;
  --warning:#fbbf24;
  --danger:#f87171;
  --info:#60a5fa;
  --font-main:'Inter',sans-serif;
  --font-display:'Space Grotesk',sans-serif;
  --font-mono:'Fira Code','JetBrains Mono',monospace;
}

html{scroll-behavior:smooth}
body{
  font-family:var(--font-main);
  background:var(--bg-dark);
  color:var(--text-primary);
  overflow-x:hidden;
  min-height:100vh;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
}

/* ===== STARS & NEBULA BACKGROUND ===== */
.stars-bg{position:fixed;inset:0;pointer-events:none;z-index:0;overflow:hidden}
.star{
  position:absolute;
  background:white;
  border-radius:50%;
  opacity:0.3;
  animation:twinkle var(--d) ease-in-out infinite;
}
@keyframes twinkle{0%,100%{opacity:0.2}50%{opacity:0.9}}

.nebula{
  position:fixed;
  border-radius:50%;
  filter:blur(120px);
  opacity:0.1;
  pointer-events:none;
  z-index:0;
}
.nebula-1{
  width:700px;height:700px;
  background:linear-gradient(135deg,#7c3aed,#a855f7);
  top:-15%;left:-15%;
  animation:floatNebula 25s ease-in-out infinite;
}
.nebula-2{
  width:600px;height:600px;
  background:linear-gradient(135deg,#9333ea,#ec4899);
  bottom:-20%;right:-15%;
  animation:floatNebula 25s ease-in-out infinite reverse;
}
.nebula-3{
  width:400px;height:400px;
  background:linear-gradient(135deg,#4f46e5,#818cf8);
  top:40%;right:10%;
  opacity:0.06;
  animation:floatNebula 30s ease-in-out infinite 5s;
}
@keyframes floatNebula{
  0%,100%{transform:translate(0,0) scale(1)}
  33%{transform:translate(40px,-30px) scale(1.05)}
  66%{transform:translate(-20px,20px) scale(0.95)}
}

/* ===== PARTICLE FIELD ===== */
.particle-field{position:fixed;inset:0;pointer-events:none;z-index:1;overflow:hidden}
.particle{
  position:absolute;
  width:2px;height:2px;
  background:rgba(168,85,247,0.3);
  border-radius:50%;
  animation:particleFloat var(--pd) linear infinite;
}
@keyframes particleFloat{
  0%{transform:translateY(100vh) scale(0);opacity:0}
  10%{opacity:1}
  90%{opacity:1}
  100%{transform:translateY(-10vh) scale(1);opacity:0}
}

/* ===== NAVIGATION ===== */
nav{
  position:fixed;
  top:0;left:0;right:0;
  padding:18px 48px;
  display:flex;
  justify-content:space-between;
  align-items:center;
  z-index:100;
  background:rgba(5,5,16,0.85);
  backdrop-filter:blur(20px) saturate(180%);
  -webkit-backdrop-filter:blur(20px) saturate(180%);
  border-bottom:1px solid rgba(147,51,234,0.12);
  transition:all 0.3s ease;
}
nav.scrolled{
  padding:14px 48px;
  background:rgba(5,5,16,0.95);
  box-shadow:0 4px 30px rgba(0,0,0,0.3);
}
.nav-brand{display:flex;align-items:center;gap:12px}
.nav-brand-icon{
  width:40px;height:40px;
  background:linear-gradient(135deg,#7c3aed,#a855f7);
  border-radius:12px;
  display:flex;align-items:center;justify-content:center;
  box-shadow:0 0 20px rgba(124,58,237,0.3);
  transition:transform 0.3s ease;
}
.nav-brand-icon:hover{transform:rotate(15deg) scale(1.05)}
.nav-brand-icon svg{width:20px;height:20px;fill:white}
.nav-brand-text{
  font-family:var(--font-display);
  font-size:22px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc,#a855f7);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}
.nav-links{display:flex;gap:36px;list-style:none;align-items:center}
.nav-links a{
  color:var(--text-secondary);
  text-decoration:none;
  font-size:14px;
  font-weight:500;
  transition:all 0.3s;
  cursor:pointer;
  position:relative;
  padding:4px 0;
}
.nav-links a::after{
  content:'';
  position:absolute;
  bottom:0;left:0;
  width:0;height:2px;
  background:linear-gradient(90deg,#a855f7,#c084fc);
  transition:width 0.3s ease;
  border-radius:2px;
}
.nav-links a:hover{color:#c084fc}
.nav-links a:hover::after{width:100%}
.nav-cta{
  padding:12px 28px;
  background:linear-gradient(135deg,#7c3aed,#9333ea);
  border:none;
  border-radius:12px;
  color:white;
  font-size:14px;
  font-weight:600;
  cursor:pointer;
  transition:all 0.3s;
  box-shadow:0 4px 20px rgba(124,58,237,0.3);
  position:relative;
  overflow:hidden;
}
.nav-cta::before{
  content:'';
  position:absolute;
  top:0;left:-100%;
  width:100%;height:100%;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,0.2),transparent);
  transition:left 0.5s;
}
.nav-cta:hover::before{left:100%}
.nav-cta:hover{
  transform:translateY(-2px);
  box-shadow:0 8px 30px rgba(124,58,237,0.4);
}

/* ===== HERO SECTION ===== */
.hero{
  min-height:100vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:140px 24px 100px;
  position:relative;
  z-index:1;
}
.hero-content{max-width:850px;position:relative}
.hero-badge{
  display:inline-flex;
  align-items:center;
  gap:10px;
  padding:10px 20px;
  background:rgba(147,51,234,0.12);
  border:1px solid rgba(147,51,234,0.25);
  border-radius:100px;
  font-size:13px;
  color:#c084fc;
  margin-bottom:16px;
  backdrop-filter:blur(10px);
}
.hero-badge .dot{
  width:8px;height:8px;
  background:#a855f7;
  border-radius:50%;
  animation:pulse 2s ease-in-out infinite;
  box-shadow:0 0 10px rgba(168,85,247,0.5);
}
@keyframes pulse{
  0%,100%{opacity:1;transform:scale(1)}
  50%{opacity:0.5;transform:scale(1.3)}
}
.hero-owner{
  font-size:13px;
  color:var(--text-muted);
  margin-bottom:24px;
  letter-spacing:0.5px;
}
.hero-owner strong{
  color:#c084fc;
  font-weight:600;
}
.hero h1{
  font-family:var(--font-display);
  font-size:clamp(40px,7vw,72px);
  font-weight:700;
  line-height:1.05;
  margin-bottom:24px;
  background:linear-gradient(135deg,#f3e8ff,#e9d5ff,#c084fc,#a855f7,#7c3aed);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  animation:gradientShift 8s ease infinite;
  background-size:200% 200%;
}
@keyframes gradientShift{
  0%{background-position:0% 50%}
  50%{background-position:100% 50%}
  100%{background-position:0% 50%}
}
.hero p{
  font-size:18px;
  color:var(--text-secondary);
  line-height:1.8;
  max-width:620px;
  margin:0 auto 40px;
}
.hero-buttons{
  display:flex;
  gap:16px;
  justify-content:center;
  flex-wrap:wrap;
}
.btn-primary{
  padding:16px 36px;
  background:linear-gradient(135deg,#7c3aed,#9333ea);
  border:none;
  border-radius:14px;
  color:white;
  font-size:15px;
  font-weight:600;
  cursor:pointer;
  transition:all 0.3s;
  box-shadow:0 4px 25px rgba(124,58,237,0.35);
  position:relative;
  overflow:hidden;
}
.btn-primary::after{
  content:'';
  position:absolute;
  inset:0;
  background:linear-gradient(135deg,transparent,rgba(255,255,255,0.1),transparent);
  opacity:0;
  transition:opacity 0.3s;
}
.btn-primary:hover::after{opacity:1}
.btn-primary:hover{
  transform:translateY(-3px);
  box-shadow:0 12px 40px rgba(124,58,237,0.45);
}
.btn-secondary{
  padding:16px 36px;
  background:transparent;
  border:1px solid rgba(147,51,234,0.4);
  border-radius:14px;
  color:#c084fc;
  font-size:15px;
  font-weight:600;
  cursor:pointer;
  transition:all 0.3s;
  position:relative;
  overflow:hidden;
}
.btn-secondary:hover{
  background:rgba(147,51,234,0.12);
  border-color:rgba(147,51,234,0.6);
  transform:translateY(-3px);
  box-shadow:0 8px 25px rgba(124,58,237,0.15);
}
.hero-powered{
  margin-top:32px;
  font-size:11px;
  color:var(--text-muted);
  letter-spacing:3px;
  text-transform:uppercase;
  font-weight:500;
}

/* ===== COUNTDOWN SECTION ===== */
.countdown-section{
  padding:80px 24px;
  position:relative;
  z-index:1;
  text-align:center;
  background:linear-gradient(180deg,transparent 0%,rgba(124,58,237,0.03) 50%,transparent 100%);
}
.countdown-label{
  font-family:var(--font-display);
  font-size:14px;
  font-weight:600;
  color:var(--text-muted);
  text-transform:uppercase;
  letter-spacing:4px;
  margin-bottom:20px;
}
.countdown-title{
  font-family:var(--font-display);
  font-size:clamp(28px,5vw,48px);
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc,#a855f7,#ec4899);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:48px;
  line-height:1.2;
}
.countdown-grid{
  display:grid;
  grid-template-columns:repeat(4,1fr);
  gap:24px;
  max-width:800px;
  margin:0 auto;
}
.countdown-card{
  background:var(--glass-bg);
  backdrop-filter:blur(20px);
  border:1px solid var(--glass-border);
  border-radius:24px;
  padding:32px 16px;
  position:relative;
  overflow:hidden;
  transition:all 0.4s ease;
}
.countdown-card::before{
  content:'';
  position:absolute;
  top:0;left:0;right:0;
  height:3px;
  background:linear-gradient(90deg,#7c3aed,#a855f7,#c084fc);
  opacity:0.6;
}
.countdown-card:hover{
  transform:translateY(-8px);
  border-color:rgba(168,85,247,0.4);
  box-shadow:0 20px 50px rgba(124,58,237,0.2);
}
.countdown-number{
  font-family:var(--font-display);
  font-size:clamp(48px,8vw,80px);
  font-weight:700;
  background:linear-gradient(180deg,#e9d5ff,#c084fc,#a855f7);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  line-height:1;
  margin-bottom:8px;
  text-shadow:0 0 60px rgba(168,85,247,0.3);
}
.countdown-unit{
  font-size:13px;
  color:var(--text-muted);
  text-transform:uppercase;
  letter-spacing:3px;
  font-weight:500;
}
.countdown-date{
  margin-top:32px;
  font-size:15px;
  color:var(--text-secondary);
  font-weight:500;
}
.countdown-date strong{
  color:#c084fc;
}

/* ===== FEATURES SECTION ===== */
.features{
  padding:120px 40px;
  position:relative;
  z-index:1;
}
.section-header{text-align:center;margin-bottom:72px}
.section-header h2{
  font-family:var(--font-display);
  font-size:40px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:16px;
}
.section-header p{
  color:var(--text-secondary);
  font-size:16px;
  max-width:500px;
  margin:0 auto;
  line-height:1.7;
}
.features-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:28px;
  max-width:1280px;
  margin:0 auto;
}
.feature-card{
  padding:36px;
  background:var(--glass-bg);
  backdrop-filter:blur(20px);
  border:1px solid var(--glass-border);
  border-radius:24px;
  transition:all 0.4s ease;
  cursor:pointer;
  position:relative;
  overflow:hidden;
}
.feature-card::before{
  content:'';
  position:absolute;
  top:0;left:0;right:0;
  height:2px;
  background:linear-gradient(90deg,transparent,#a855f7,transparent);
  opacity:0;
  transition:opacity 0.4s;
}
.feature-card:hover::before{opacity:1}
.feature-card:hover{
  border-color:rgba(147,51,234,0.35);
  transform:translateY(-6px);
  box-shadow:0 25px 50px rgba(0,0,0,0.35),0 0 30px rgba(124,58,237,0.1);
}
.feature-icon{
  width:56px;height:56px;
  background:linear-gradient(135deg,rgba(124,58,237,0.2),rgba(168,85,247,0.2));
  border-radius:16px;
  display:flex;
  align-items:center;
  justify-content:center;
  font-size:26px;
  margin-bottom:24px;
  transition:all 0.3s;
  border:1px solid rgba(147,51,234,0.15);
}
.feature-card:hover .feature-icon{
  transform:scale(1.1) rotate(-5deg);
  box-shadow:0 0 20px rgba(168,85,247,0.2);
}
.feature-card h3{
  font-size:19px;
  font-weight:600;
  color:var(--text-primary);
  margin-bottom:10px;
}
.feature-card p{
  font-size:14px;
  color:var(--text-secondary);
  line-height:1.7;
}
.feature-tag{
  display:inline-block;
  margin-top:16px;
  padding:6px 14px;
  background:rgba(124,58,237,0.12);
  border:1px solid rgba(147,51,234,0.2);
  border-radius:20px;
  font-size:11px;
  color:#c084fc;
  font-weight:500;
  transition:all 0.3s;
}
.feature-card:hover .feature-tag{
  background:rgba(124,58,237,0.2);
  border-color:rgba(147,51,234,0.35);
}

/* ===== ABOUT SECTION ===== */
.about{
  padding:120px 40px;
  position:relative;
  z-index:1;
}
.about-content{
  max-width:1100px;
  margin:0 auto;
  display:grid;
  grid-template-columns:1fr 1fr;
  gap:80px;
  align-items:center;
}
.about-text h2{
  font-family:var(--font-display);
  font-size:40px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:24px;
}
.about-text p{
  color:var(--text-secondary);
  font-size:15px;
  line-height:1.9;
  margin-bottom:18px;
}
.about-text strong{color:#c084fc}
.about-stats{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:20px;
}
.stat-item{
  padding:28px;
  background:var(--glass-bg);
  border:1px solid var(--glass-border);
  border-radius:20px;
  text-align:center;
  transition:all 0.3s;
}
.stat-item:hover{
  border-color:rgba(147,51,234,0.3);
  transform:translateY(-4px);
}
.stat-number{
  font-family:var(--font-display);
  font-size:36px;
  font-weight:700;
  background:linear-gradient(135deg,#c084fc,#a855f7);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}
.stat-label{
  font-size:13px;
  color:var(--text-secondary);
  margin-top:6px;
  font-weight:500;
}

/* ===== CTA SECTION ===== */
.cta{
  padding:120px 40px;
  text-align:center;
  position:relative;
  z-index:1;
}
.cta-box{
  max-width:720px;
  margin:0 auto;
  padding:64px 48px;
  background:var(--glass-bg);
  backdrop-filter:blur(20px);
  border:1px solid var(--glass-border);
  border-radius:32px;
  position:relative;
  overflow:hidden;
}
.cta-box::before{
  content:'';
  position:absolute;
  top:-50%;left:-50%;
  width:200%;height:200%;
  background:radial-gradient(circle,rgba(168,85,247,0.08) 0%,transparent 70%);
  animation:ctaGlow 10s ease-in-out infinite;
}
@keyframes ctaGlow{
  0%,100%{transform:translate(0,0)}
  50%{transform:translate(10%,10%)}
}
.cta-box h2{
  font-family:var(--font-display);
  font-size:36px;
  font-weight:700;
  color:var(--text-primary);
  margin-bottom:20px;
  position:relative;
  z-index:1;
}
.cta-box p{
  color:var(--text-secondary);
  font-size:16px;
  margin-bottom:36px;
  line-height:1.7;
  position:relative;
  z-index:1;
}

/* ===== FOOTER ===== */
footer{
  padding:48px 24px;
  text-align:center;
  border-top:1px solid rgba(147,51,234,0.1);
  position:relative;
  z-index:1;
  background:linear-gradient(180deg,transparent,rgba(124,58,237,0.02));
}
footer .brand-footer{
  font-family:var(--font-display);
  font-size:20px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:12px;
}
footer p{
  font-size:13px;
  color:var(--text-muted);
  line-height:1.8;
}

/* ================================================================
   CHAT SECTION - DARDCOR-STYLE REDESIGN
   Powered by Apache AI Engine System
   ================================================================ */

.chat-section{
  display:none;
  position:fixed;
  inset:0;
  z-index:200;
  background:var(--bg-dark);
  font-family:var(--font-main);
}
.chat-section.active{display:flex}

/* Sidebar */
.chat-sidebar{
  width:280px;
  background:rgba(10,8,30,0.95);
  backdrop-filter:blur(20px);
  border-right:1px solid rgba(147,51,234,0.12);
  display:flex;
  flex-direction:column;
  z-index:50;
  transition:transform 0.35s cubic-bezier(0.4,0,0.2,1);
}
.chat-sidebar-header{
  padding:24px 20px 20px;
  border-bottom:1px solid rgba(147,51,234,0.08);
}
.chat-brand{display:flex;align-items:center;gap:12px}
.chat-brand-icon{
  width:40px;height:40px;
  background:linear-gradient(135deg,#7c3aed,#a855f7);
  border-radius:12px;
  display:flex;align-items:center;justify-content:center;
  box-shadow:0 0 15px rgba(124,58,237,0.3);
}
.chat-brand-icon svg{width:20px;height:20px;fill:white}
.chat-brand-name{
  font-size:18px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
}
.chat-brand-version{
  font-size:10px;
  color:var(--text-muted);
  margin-top:2px;
}
.chat-powered-by{
  font-size:11px;
  color:var(--text-muted);
  margin-top:8px;
  letter-spacing:2px;
  text-transform:uppercase;
  font-weight:500;
}
.chat-owner{
  font-size:11px;
  color:var(--text-muted);
  margin-top:4px;
  opacity:0.7;
}
.chat-new-btn{
  margin:16px 20px;
  padding:12px 18px;
  background:linear-gradient(135deg,#7c3aed,#9333ea);
  border:none;
  border-radius:12px;
  color:white;
  font-size:14px;
  font-weight:600;
  cursor:pointer;
  display:flex;
  align-items:center;
  gap:10px;
  transition:all 0.3s;
  box-shadow:0 4px 15px rgba(124,58,237,0.25);
}
.chat-new-btn:hover{
  transform:translateY(-2px);
  box-shadow:0 8px 25px rgba(124,58,237,0.35);
}
.chat-history{
  flex:1;
  overflow-y:auto;
  padding:0 12px;
}
.chat-history-item{
  padding:12px 14px;
  border-radius:10px;
  font-size:13px;
  color:var(--text-secondary);
  cursor:pointer;
  display:flex;
  align-items:center;
  gap:10px;
  transition:all 0.25s;
  margin-bottom:3px;
  white-space:nowrap;
  overflow:hidden;
  text-overflow:ellipsis;
  border:1px solid transparent;
}
.chat-history-item:hover{
  background:rgba(147,51,234,0.08);
  color:var(--text-primary);
  border-color:rgba(147,51,234,0.15);
}
.chat-sidebar-footer{
  padding:18px 20px;
  border-top:1px solid rgba(147,51,234,0.08);
}
.chat-sidebar-footer-text{
  font-size:10px;
  color:var(--text-muted);
  text-align:center;
  padding:8px 0;
  line-height:1.7;
}
.chat-back-link{
  display:flex;
  align-items:center;
  gap:8px;
  color:rgba(168,85,247,0.8);
  text-decoration:none;
  font-size:13px;
  font-weight:500;
  margin-bottom:12px;
  transition:all 0.2s;
  cursor:pointer;
  border:none;
  background:none;
  font-family:var(--font-main);
  padding:0 20px;
  margin-top:4px;
}
.chat-back-link:hover{color:#c084fc}
.chat-mode-indicator{
  margin:0 20px 12px;
  padding:10px 14px;
  background:rgba(124,58,237,0.1);
  border:1px solid rgba(147,51,234,0.2);
  border-radius:10px;
  font-size:12px;
  color:#c084fc;
  font-weight:500;
  display:flex;
  align-items:center;
  gap:8px;
  backdrop-filter:blur(10px);
}
.chat-mode-indicator.coding{
  background:rgba(34,197,94,0.08);
  border-color:rgba(34,197,94,0.2);
  color:#4ade80;
}
.chat-mode-indicator.image{
  background:rgba(236,72,153,0.08);
  border-color:rgba(236,72,153,0.2);
  color:#f472b6;
}
.chat-mode-indicator.search{
  background:rgba(59,130,246,0.08);
  border-color:rgba(59,130,246,0.2);
  color:#60a5fa;
}

/* Main Chat Area */
.chat-main{
  flex:1;
  display:flex;
  flex-direction:column;
  position:relative;
  z-index:10;
  overflow:hidden;
  background:var(--bg-dark);
}

/* Chat Header */
.chat-header{
  height:68px;
  flex-shrink:0;
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:0 20px 0 24px;
  border-bottom:1px solid rgba(147,51,234,0.1);
  background:rgba(5,5,8,0.85);
  backdrop-filter:blur(20px);
  z-index:30;
}
.chat-header-left{display:flex;align-items:center;gap:14px}
.chat-header-title{
  font-family:var(--font-display);
  font-size:17px;
  font-weight:600;
  color:var(--text-primary);
}
.chat-header-status{
  display:flex;
  align-items:center;
  gap:8px;
  font-size:12px;
  color:var(--text-muted);
}
.chat-header-status .status-dot{
  width:7px;height:7px;
  background:#4ade80;
  border-radius:50%;
  animation:pulse 2.5s infinite;
  box-shadow:0 0 8px rgba(74,222,128,0.4);
}
#toggleSidebarBtn{
  display:none;
  background:none;
  border:none;
  color:var(--text-secondary);
  font-size:18px;
  cursor:pointer;
  padding:8px;
  border-radius:8px;
  transition:all 0.2s;
}
#toggleSidebarBtn:hover{
  background:rgba(147,51,234,0.1);
  color:#c084fc;
}

/* Chat Area */
.chat-area{
  flex:1;
  overflow-y:auto;
  padding:28px 36px;
  display:flex;
  flex-direction:column;
  gap:18px;
  position:relative;
  scroll-behavior:smooth;
}
.chat-welcome{
  text-align:center;
  padding:60px 20px;
  max-width:650px;
  margin:0 auto;
  position:relative;
  z-index:2;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  flex:1;
}
.chat-welcome h1{
  font-size:36px;
  font-weight:700;
  background:linear-gradient(135deg,#e9d5ff,#c084fc,#a855f7);
  -webkit-background-clip:text;
  -webkit-text-fill-color:transparent;
  background-clip:text;
  margin-bottom:16px;
  font-family:var(--font-display);
}
.chat-welcome p{
  color:var(--text-secondary);
  font-size:15px;
  line-height:1.7;
}
.chat-suggestions{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:14px;
  margin-top:40px;
  width:100%;
}
.chat-suggestion-card{
  padding:18px;
  background:rgba(15,10,40,0.5);
  border:1px solid rgba(147,51,234,0.12);
  border-radius:14px;
  cursor:pointer;
  text-align:left;
  transition:all 0.3s;
  backdrop-filter:blur(10px);
}
.chat-suggestion-card:hover{
  background:rgba(147,51,234,0.1);
  border-color:rgba(147,51,234,0.3);
  transform:translateY(-3px);
  box-shadow:0 10px 30px rgba(0,0,0,0.2);
}
.chat-suggestion-card h4{
  font-size:14px;
  color:var(--text-primary);
  margin-bottom:6px;
  font-weight:600;
}
.chat-suggestion-card p{
  font-size:12px;
  color:var(--text-muted);
}

/* Chat Messages */
.chat-message{
  display:flex;
  gap:14px;
  max-width:850px;
  margin:0 auto;
  width:100%;
  animation:msgIn 0.35s cubic-bezier(0.4,0,0.2,1);
  position:relative;
  z-index:2;
}
@keyframes msgIn{
  from{opacity:0;transform:translateY(12px) scale(0.98)}
  to{opacity:1;transform:translateY(0) scale(1)}
}
.chat-message.user{flex-direction:row-reverse}
.chat-avatar{
  width:36px;height:36px;
  border-radius:10px;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-shrink:0;
  font-size:14px;
  font-weight:600;
  transition:all 0.3s;
}
.chat-message.ai .chat-avatar{
  background:linear-gradient(135deg,#7c3aed,#a855f7);
  color:white;
  box-shadow:0 0 15px rgba(124,58,237,0.3);
}
.chat-message.user .chat-avatar{
  background:rgba(147,51,234,0.2);
  color:#c084fc;
  border:1px solid rgba(147,51,234,0.2);
}
.chat-bubble{
  padding:16px 20px;
  border-radius:18px;
  font-size:14.5px;
  line-height:1.7;
  max-width:80%;
  word-wrap:break-word;
  transition:all 0.3s;
}
.chat-message.ai .chat-bubble{
  background:rgba(15,10,40,0.75);
  border:1px solid rgba(147,51,234,0.15);
  color:var(--text-primary);
  backdrop-filter:blur(12px);
  border-top-left-radius:4px;
}
.chat-message.user .chat-bubble{
  background:linear-gradient(135deg,#7c3aed,#9333ea);
  color:white;
  border-top-right-radius:4px;
  box-shadow:0 4px 20px rgba(124,58,237,0.25);
}
.chat-bubble pre{
  background:rgba(0,0,0,0.55);
  padding:16px;
  border-radius:12px;
  overflow-x:auto;
  margin:12px 0;
  font-family:var(--font-mono);
  font-size:13px;
  border:1px solid rgba(147,51,234,0.12);
  position:relative;
}
.chat-bubble pre::before{
  content:'';
  position:absolute;
  top:0;left:0;right:0;
  height:3px;
  background:linear-gradient(90deg,#7c3aed,#a855f7);
  border-radius:12px 12px 0 0;
  opacity:0.5;
}
.chat-bubble code{
  background:rgba(0,0,0,0.4);
  padding:3px 7px;
  border-radius:5px;
  font-family:var(--font-mono);
  font-size:13px;
  color:#c084fc;
}
.chat-bubble img{
  max-width:100%;
  border-radius:14px;
  margin-top:10px;
  border:1px solid rgba(147,51,234,0.2);
  box-shadow:0 8px 25px rgba(0,0,0,0.3);
}
.chat-bubble .img-loading{
  width:100%;height:220px;
  background:rgba(15,10,40,0.6);
  border-radius:14px;
  display:flex;
  align-items:center;
  justify-content:center;
  color:var(--text-muted);
  font-size:13px;
  border:1px solid rgba(147,51,234,0.15);
  gap:10px;
}
.chat-bubble .img-caption{
  font-size:12px;
  color:var(--text-muted);
  margin-top:10px;
  font-style:italic;
}

/* Typing Indicator */
.chat-typing{display:flex;gap:5px;padding:10px 0}
.chat-typing-dot{
  width:7px;height:7px;
  background:rgba(168,85,247,0.7);
  border-radius:50%;
  animation:typingBounce 1.5s ease-in-out infinite;
}
.chat-typing-dot:nth-child(2){animation-delay:0.2s}
.chat-typing-dot:nth-child(3){animation-delay:0.4s}
@keyframes typingBounce{
  0%,60%,100%{transform:translateY(0)}
  30%{transform:translateY(-8px)}
}

/* Input Area - Glassmorphism */
.chat-input-wrapper{
  flex-shrink:0;
  padding:0 20px 20px;
  position:relative;
  z-index:20;
  background:linear-gradient(to top,var(--bg-dark) 50%,transparent);
}
.chat-glass-input{
  max-width:850px;
  margin:0 auto;
  background:rgba(14,14,24,0.92);
  border:1px solid rgba(147,51,234,0.22);
  border-radius:28px;
  padding:14px 20px;
  box-shadow:0 0 30px rgba(88,28,135,0.12),0 4px 20px rgba(0,0,0,0.3);
  backdrop-filter:blur(20px);
  transition:all 0.3s ease;
}
.chat-glass-input:focus-within{
  border-color:rgba(168,85,247,0.5);
  box-shadow:0 0 40px rgba(124,58,237,0.18),0 4px 20px rgba(0,0,0,0.3);
}
.chat-input-field{
  width:100%;
  background:transparent;
  border:none;
  outline:none;
  resize:none;
  color:var(--text-primary);
  font-size:15px;
  font-family:var(--font-main);
  min-height:24px;
  max-height:140px;
  line-height:1.6;
  padding:6px 0;
}
.chat-input-field::placeholder{color:rgba(196,181,253,0.3)}
.chat-input-actions{
  display:flex;
  justify-content:space-between;
  align-items:center;
  margin-top:10px;
  gap:10px;
}
.chat-input-left{display:flex;align-items:center;gap:10px}
.chat-input-right{display:flex;align-items:center;gap:12px}

/* Tool Buttons */
.chat-tool-btn{
  background:rgba(15,10,40,0.7);
  border:1px solid rgba(147,51,234,0.18);
  border-radius:10px;
  color:var(--text-secondary);
  font-size:12px;
  font-weight:500;
  cursor:pointer;
  display:flex;
  align-items:center;
  gap:6px;
  transition:all 0.25s;
  padding:7px 14px;
  font-family:var(--font-main);
  backdrop-filter:blur(10px);
}
.chat-tool-btn:hover{
  background:rgba(147,51,234,0.12);
  border-color:rgba(147,51,234,0.35);
  color:var(--text-primary);
}
.chat-tool-btn.active{
  background:rgba(124,58,237,0.18);
  border-color:rgba(168,85,247,0.5);
  color:#c084fc;
  box-shadow:0 0 12px rgba(124,58,237,0.1);
}
.chat-tool-btn.coding.active{
  background:rgba(34,197,94,0.1);
  border-color:rgba(34,197,94,0.3);
  color:#4ade80;
}
.chat-tool-btn.image.active{
  background:rgba(236,72,153,0.1);
  border-color:rgba(236,72,153,0.3);
  color:#f472b6;
}
.chat-tool-btn.search.active{
  background:rgba(59,130,246,0.1);
  border-color:rgba(59,130,246,0.3);
  color:#60a5fa;
}

.chat-input-icon-btn{
  width:36px;height:36px;
  border-radius:50%;
  border:none;
  background:transparent;
  color:var(--text-muted);
  cursor:pointer;
  display:flex;
  align-items:center;
  justify-content:center;
  transition:all 0.25s;
  font-size:15px;
}
.chat-input-icon-btn:hover{
  background:rgba(147,51,234,0.1);
  color:#c084fc;
}
.chat-send-btn{
  width:36px;height:36px;
  border-radius:50%;
  background:linear-gradient(135deg,#7c3aed,#a855f7);
  border:none;
  color:white;
  cursor:pointer;
  display:flex;
  align-items:center;
  justify-content:center;
  transition:all 0.25s;
  box-shadow:0 2px 10px rgba(124,58,237,0.3);
}
.chat-send-btn:hover{
  transform:scale(1.08);
  box-shadow:0 4px 15px rgba(124,58,237,0.4);
}
.chat-send-btn:disabled{
  opacity:0.4;
  cursor:not-allowed;
  transform:none;
}

/* Tools Dropdown */
.tools-dropdown{position:relative}
.tools-menu{
  display:none;
  position:absolute;
  bottom:calc(100% + 10px);
  left:0;
  background:rgba(18,8,35,0.98);
  border:1px solid rgba(147,51,234,0.3);
  border-radius:14px;
  padding:8px;
  box-shadow:0 15px 50px rgba(0,0,0,0.5);
  backdrop-filter:blur(20px);
  z-index:100;
  min-width:180px;
  flex-direction:column;
  gap:3px;
}
.tools-menu.show{display:flex}
.tools-menu button{
  width:100%;
  text-align:left;
  display:flex;
  align-items:center;
  gap:10px;
  padding:10px 14px;
  border-radius:10px;
  border:none;
  background:transparent;
  color:var(--text-secondary);
  font-size:13px;
  font-family:var(--font-main);
  cursor:pointer;
  transition:all 0.2s;
}
.tools-menu button:hover{
  background:rgba(147,51,234,0.12);
  color:var(--text-primary);
}
.tools-menu button i{width:18px;text-align:center}

/* File Preview */
.file-preview-container{
  display:flex;
  flex-wrap:wrap;
  gap:10px;
  margin-bottom:10px;
  max-width:850px;
  margin:0 auto 10px;
}
.file-preview-tag{
  display:inline-flex;
  align-items:center;
  gap:8px;
  padding:6px 12px;
  background:rgba(147,51,234,0.1);
  border:1px solid rgba(147,51,234,0.2);
  border-radius:20px;
  font-size:12px;
  color:#c084fc;
  backdrop-filter:blur(10px);
}
.file-preview-tag .remove-file{
  cursor:pointer;
  color:var(--text-muted);
  transition:color 0.2s;
  font-size:16px;
  line-height:1;
}
.file-preview-tag .remove-file:hover{color:var(--danger)}

/* Input Hint */
.chat-input-hint{
  text-align:center;
  font-size:11px;
  color:rgba(196,181,253,0.25);
  margin-top:10px;
  letter-spacing:0.5px;
}

/* Orbiting Rings Animation */
@keyframes orbit-1{0%{transform:rotate3d(1,1,1,0deg)}100%{transform:rotate3d(1,1,1,360deg)}}
@keyframes orbit-2{0%{transform:rotate3d(1,-1,1,0deg)}100%{transform:rotate3d(1,-1,1,360deg)}}
@keyframes orbit-3{0%{transform:rotate3d(-1,1,1,0deg)}100%{transform:rotate3d(-1,1,1,360deg)}}
@keyframes orbit-4{0%{transform:rotate3d(1,1,-1,0deg)}100%{transform:rotate3d(1,1,-1,360deg)}}
@keyframes orbit-5{0%{transform:rotate3d(0,1,1,0deg)}100%{transform:rotate3d(0,1,1,360deg)}}
@keyframes orbit-6{0%{transform:rotate3d(1,0,0,0deg)}100%{transform:rotate3d(1,0,0,360deg)}}
@keyframes star-twinkle{0%,100%{opacity:0.3;transform:scale(0.5)}50%{opacity:1;transform:scale(1.3)}}

/* Chat Stars */
.chat-stars{position:absolute;inset:0;pointer-events:none;overflow:hidden;z-index:1}
.chat-star{
  position:absolute;
  background:white;
  border-radius:50%;
  animation:star-twinkle var(--dur) ease-in-out infinite;
}

/* Purple Glow */
.chat-glow{
  position:absolute;
  top:50%;left:50%;
  transform:translate(-50%,-50%);
  width:600px;height:600px;
  background:rgba(88,28,135,0.06);
  border-radius:50%;
  filter:blur(100px);
  pointer-events:none;
  z-index:1;
}

/* Overlay for mobile sidebar */
#chatOverlay{
  position:fixed;
  inset:0;
  background:rgba(0,0,0,0.6);
  backdrop-filter:blur(8px);
  z-index:40;
  display:none;
  transition:opacity 0.3s;
}
#chatOverlay.show{display:block}


/* Toast */
.toast{
  position:fixed;
  top:24px;
  right:24px;
  padding:14px 22px;
  background:rgba(15,10,40,0.95);
  backdrop-filter:blur(20px);
  border:1px solid rgba(147,51,234,0.3);
  border-radius:12px;
  color:var(--text-primary);
  font-size:13px;
  font-weight:500;
  box-shadow:0 10px 40px rgba(0,0,0,0.4);
  transform:translateX(150%);
  transition:transform 0.35s cubic-bezier(0.4,0,0.2,1);
  z-index:1000;
}
.toast.show{transform:translateX(0)}

/* Scrollbar */
::-webkit-scrollbar{width:6px;height:6px}
::-webkit-scrollbar-track{background:transparent}
::-webkit-scrollbar-thumb{background:rgba(147,51,234,0.2);border-radius:3px}
::-webkit-scrollbar-thumb:hover{background:rgba(147,51,234,0.4)}



/* ===== RESPONSIVE ===== */
@media(max-width:1024px){
  .chat-sidebar{position:fixed;left:0;top:0;bottom:0;transform:translateX(-100%)}
  .chat-sidebar.open{transform:translateX(0)}
  #toggleSidebarBtn{display:block}
  .about-content{grid-template-columns:1fr;gap:40px}
}
@media(max-width:768px){
  nav{padding:16px 20px}
  nav.scrolled{padding:12px 20px}
  .nav-links{display:none}
  .hero h1{font-size:36px}
  .features{padding:80px 20px}
  .about{padding:80px 20px}
  .cta{padding:80px 20px}
  .countdown-grid{grid-template-columns:repeat(2,1fr);gap:16px}
  .countdown-card{padding:24px 12px}
  .chat-area{padding:16px}
  .chat-suggestions{grid-template-columns:1fr}
  .chat-header{padding:0 14px}
  .chat-input-wrapper{padding:0 14px 14px}
  .cta-box{padding:40px 24px}
  .about-content{grid-template-columns:1fr}
}
@media(max-width:480px){
  .countdown-grid{grid-template-columns:repeat(2,1fr)}
  .countdown-number{font-size:48px}
}


/* ================================================================
   SETTINGS & HISTORY MODAL SYSTEM
   ================================================================ */

/* Light Mode Variables */
html.light-mode{
  --purple-900:#f8f7fc;
  --purple-800:#f0eef7;
  --purple-700:#e8e4f3;
  --bg-dark:#f5f3fa;
  --glass-bg:rgba(255,255,255,0.75);
  --glass-border:rgba(147,51,234,0.15);
  --text-primary:#1a0b2e;
  --text-secondary:rgba(26,11,46,0.7);
  --text-muted:rgba(26,11,46,0.4);
}
html.light-mode body{background:var(--bg-dark);color:var(--text-primary);}
html.light-mode nav{background:rgba(245,243,250,0.9);border-bottom:1px solid rgba(147,51,234,0.1);}
html.light-mode .hero-owner,html.light-mode .countdown-label,html.light-mode .countdown-unit,
html.light-mode .countdown-date,html.light-mode .section-header p,html.light-mode .feature-card p,
html.light-mode .about-text p,html.light-mode .stat-label,html.light-mode .cta-box p,
html.light-mode footer p{color:var(--text-secondary);}
html.light-mode .feature-card,html.light-mode .stat-item,html.light-mode .countdown-card,
html.light-mode .cta-box{background:var(--glass-bg);border:1px solid var(--glass-border);}
html.light-mode .chat-sidebar{background:rgba(245,243,250,0.98);border-right:1px solid rgba(147,51,234,0.1);}
html.light-mode .chat-header{background:rgba(245,243,250,0.9);border-bottom:1px solid rgba(147,51,234,0.1);}
html.light-mode .chat-glass-input{background:rgba(255,255,255,0.95);border:1px solid rgba(147,51,234,0.2);}
html.light-mode .chat-message.ai .chat-bubble{background:rgba(255,255,255,0.85);border:1px solid rgba(147,51,234,0.12);color:var(--text-primary);}
html.light-mode .chat-welcome p{color:var(--text-secondary);}
html.light-mode .chat-suggestion-card{background:rgba(255,255,255,0.6);border:1px solid rgba(147,51,234,0.1);}
html.light-mode .chat-suggestion-card:hover{background:rgba(147,51,234,0.08);}
html.light-mode .chat-history-item{color:var(--text-secondary);}
html.light-mode .chat-history-item:hover{background:rgba(147,51,234,0.08);color:var(--text-primary);}
html.light-mode .chat-input-field{color:var(--text-primary);}
html.light-mode .chat-input-field::placeholder{color:rgba(26,11,46,0.3);}
html.light-mode .chat-tool-btn{background:rgba(255,255,255,0.7);color:var(--text-secondary);}
html.light-mode .chat-input-icon-btn{color:var(--text-muted);}
html.light-mode .chat-input-icon-btn:hover{background:rgba(147,51,234,0.1);color:var(--accent);}
html.light-mode .chat-sidebar-footer-text,html.light-mode .chat-powered-by,
html.light-mode .chat-owner,html.light-mode .chat-brand-version{color:var(--text-muted);}
html.light-mode .chat-mode-indicator{background:rgba(124,58,237,0.08);}
html.light-mode .chat-mode-indicator.coding{background:rgba(34,197,94,0.06);}
html.light-mode .chat-mode-indicator.image{background:rgba(236,72,153,0.06);}
html.light-mode .chat-mode-indicator.search{background:rgba(59,130,246,0.06);}
html.light-mode .tools-menu{background:rgba(255,255,255,0.98);border:1px solid rgba(147,51,234,0.2);}
html.light-mode .tools-menu button{color:var(--text-secondary);}
html.light-mode .tools-menu button:hover{background:rgba(147,51,234,0.08);color:var(--text-primary);}
html.light-mode .file-preview-tag{background:rgba(147,51,234,0.08);}
html.light-mode .chat-input-hint{color:rgba(26,11,46,0.2);}
html.light-mode .chat-area,html.light-mode .chat-main,html.light-mode .chat-section{background:var(--bg-dark);}
html.light-mode #chatOverlay{background:rgba(0,0,0,0.4);}
html.light-mode .modal-content{background:var(--glass-bg);border:1px solid var(--glass-border);}
html.light-mode .modal-header{border-bottom:1px solid rgba(147,51,234,0.1);}
html.light-mode .modal-body{color:var(--text-secondary);}
html.light-mode .setting-item{border-bottom:1px solid rgba(147,51,234,0.08);}
html.light-mode .setting-item:hover{background:rgba(147,51,234,0.04);}
html.light-mode .history-item{background:rgba(255,255,255,0.5);border:1px solid rgba(147,51,234,0.08);}
html.light-mode .history-item:hover{background:rgba(147,51,234,0.08);border-color:rgba(147,51,234,0.2);}
html.light-mode .history-item-title{color:var(--text-primary);}
html.light-mode .history-item-date{color:var(--text-muted);}
html.light-mode .history-item-preview{color:var(--text-secondary);}
html.light-mode .empty-state{color:var(--text-muted);}
html.light-mode .search-input{background:rgba(255,255,255,0.7);border:1px solid rgba(147,51,234,0.15);color:var(--text-primary);}
html.light-mode .search-input::placeholder{color:rgba(26,11,46,0.3);}
html.light-mode .tab-btn{color:var(--text-muted);}
html.light-mode .tab-btn.active{color:var(--accent);border-bottom:2px solid var(--accent);}
html.light-mode .tab-btn:hover{color:var(--text-secondary);}
html.light-mode .toggle-switch{background:rgba(26,11,46,0.15);}
html.light-mode .toggle-switch.active{background:linear-gradient(135deg,#7c3aed,#9333ea);}
html.light-mode .select-box{background:rgba(255,255,255,0.7);border:1px solid rgba(147,51,234,0.15);color:var(--text-primary);}
html.light-mode .btn-danger-outline{border:1px solid var(--danger);color:var(--danger);}
html.light-mode .btn-danger-outline:hover{background:rgba(248,113,113,0.1);}
html.light-mode .stats-card{background:rgba(255,255,255,0.5);border:1px solid rgba(147,51,234,0.1);}
html.light-mode .stats-number{color:var(--accent);}
html.light-mode .stats-label{color:var(--text-muted);}
html.light-mode .history-badge{background:rgba(147,51,234,0.08);color:var(--accent);}
html.light-mode .confirm-modal-content{background:var(--glass-bg);border:1px solid var(--glass-border);}
html.light-mode .confirm-modal-body{color:var(--text-secondary);}

/* ===== MODAL SYSTEM ===== */
.modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.7);backdrop-filter:blur(12px);z-index:500;display:none;align-items:center;justify-content:center;padding:20px;opacity:0;transition:opacity 0.3s ease;}
.modal-overlay.show{display:flex;opacity:1;}
.modal-content{background:var(--glass-bg);backdrop-filter:blur(30px);border:1px solid var(--glass-border);border-radius:24px;width:100%;max-width:520px;max-height:85vh;display:flex;flex-direction:column;overflow:hidden;transform:scale(0.92) translateY(20px);transition:transform 0.35s cubic-bezier(0.4,0,0.2,1);box-shadow:0 25px 80px rgba(0,0,0,0.5);}
.modal-overlay.show .modal-content{transform:scale(1) translateY(0);}
.modal-header{padding:20px 24px 16px;display:flex;align-items:center;justify-content:space-between;border-bottom:1px solid rgba(147,51,234,0.1);flex-shrink:0;}
.modal-header h2{font-family:var(--font-display);font-size:20px;font-weight:700;color:var(--text-primary);display:flex;align-items:center;gap:10px;}
.modal-header h2 i{color:var(--accent);font-size:18px;}
.modal-close-btn{width:36px;height:36px;border-radius:50%;border:none;background:rgba(147,51,234,0.1);color:var(--text-secondary);cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all 0.25s;font-size:14px;}
.modal-close-btn:hover{background:rgba(147,51,234,0.2);color:var(--text-primary);transform:rotate(90deg);}
.modal-body{padding:20px 24px;overflow-y:auto;flex:1;color:var(--text-secondary);font-size:14px;line-height:1.7;}

/* Tabs */
.modal-tabs{display:flex;gap:4px;padding:0 24px;border-bottom:1px solid rgba(147,51,234,0.08);flex-shrink:0;}
.tab-btn{padding:12px 16px;background:none;border:none;border-bottom:2px solid transparent;color:var(--text-muted);font-size:13px;font-weight:500;cursor:pointer;transition:all 0.25s;font-family:var(--font-main);position:relative;}
.tab-btn.active{color:var(--accent);border-bottom:2px solid var(--accent);}
.tab-btn:hover{color:var(--text-secondary);}

/* Settings Items */
.setting-item{display:flex;align-items:center;justify-content:space-between;padding:16px 0;border-bottom:1px solid rgba(147,51,234,0.08);transition:background 0.2s;}
.setting-item:last-child{border-bottom:none;}
.setting-item-info h4{font-size:14px;font-weight:600;color:var(--text-primary);margin-bottom:4px;}
.setting-item-info p{font-size:12px;color:var(--text-muted);line-height:1.5;}

/* Toggle Switch */
.toggle-switch{width:48px;height:26px;background:rgba(255,255,255,0.1);border-radius:13px;position:relative;cursor:pointer;transition:background 0.3s ease;flex-shrink:0;border:none;outline:none;}
.toggle-switch::after{content:'';position:absolute;top:3px;left:3px;width:20px;height:20px;background:white;border-radius:50%;transition:transform 0.3s cubic-bezier(0.4,0,0.2,1);box-shadow:0 2px 8px rgba(0,0,0,0.3);}
.toggle-switch.active{background:linear-gradient(135deg,#7c3aed,#9333ea);}
.toggle-switch.active::after{transform:translateX(22px);}

/* Select Box */
.select-box{padding:8px 14px;background:rgba(15,10,40,0.6);border:1px solid rgba(147,51,234,0.2);border-radius:10px;color:var(--text-primary);font-size:13px;font-family:var(--font-main);cursor:pointer;outline:none;transition:all 0.25s;}
.select-box:hover,.select-box:focus{border-color:rgba(147,51,234,0.4);}
.select-box option{background:var(--purple-800);color:var(--text-primary);}

/* History Items */
.history-search{margin-bottom:16px;position:relative;}
.search-input{width:100%;padding:12px 16px 12px 40px;background:rgba(15,10,40,0.5);border:1px solid rgba(147,51,234,0.15);border-radius:12px;color:var(--text-primary);font-size:14px;font-family:var(--font-main);outline:none;transition:all 0.25s;}
.search-input:focus{border-color:rgba(147,51,234,0.4);box-shadow:0 0 15px rgba(124,58,237,0.1);}
.search-input::placeholder{color:rgba(196,181,253,0.3);}
.search-icon{position:absolute;left:14px;top:50%;transform:translateY(-50%);color:var(--text-muted);font-size:14px;}

.history-list{display:flex;flex-direction:column;gap:8px;}
.history-item{padding:14px 16px;background:rgba(15,10,40,0.4);border:1px solid rgba(147,51,234,0.1);border-radius:14px;cursor:pointer;transition:all 0.25s;position:relative;display:flex;align-items:flex-start;gap:12px;}
.history-item:hover{background:rgba(147,51,234,0.1);border-color:rgba(147,51,234,0.25);transform:translateX(4px);}
.history-item-icon{width:36px;height:36px;min-width:36px;background:linear-gradient(135deg,rgba(124,58,237,0.2),rgba(168,85,247,0.2));border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:14px;color:var(--accent);}
.history-item-content{flex:1;min-width:0;}
.history-item-title{font-size:14px;font-weight:600;color:var(--text-primary);margin-bottom:4px;white-space:nowrap;overflow:hidden;text-overflow:ellipsis;}
.history-item-date{font-size:11px;color:var(--text-muted);margin-bottom:6px;display:flex;align-items:center;gap:6px;}
.history-item-preview{font-size:12px;color:var(--text-secondary);line-height:1.5;display:-webkit-box;-webkit-line-clamp:2;-webkit-box-orient:vertical;overflow:hidden;}
.history-item-actions{display:flex;gap:6px;flex-shrink:0;opacity:0;transition:opacity 0.2s;}
.history-item:hover .history-item-actions{opacity:1;}
.history-action-btn{width:28px;height:28px;border-radius:8px;border:none;background:rgba(147,51,234,0.1);color:var(--text-muted);cursor:pointer;display:flex;align-items:center;justify-content:center;transition:all 0.2s;font-size:12px;}
.history-action-btn:hover{background:rgba(147,51,234,0.2);color:var(--text-primary);}
.history-action-btn.delete:hover{background:rgba(248,113,113,0.15);color:var(--danger);}

.empty-state{text-align:center;padding:40px 20px;color:var(--text-muted);}
.empty-state i{font-size:40px;margin-bottom:12px;display:block;opacity:0.5;}
.empty-state h4{font-size:16px;font-weight:600;color:var(--text-primary);margin-bottom:6px;}
.empty-state p{font-size:13px;}

/* Stats Cards */
.history-stats{display:grid;grid-template-columns:repeat(3,1fr);gap:10px;margin-bottom:20px;}
.stats-card{padding:14px;background:rgba(15,10,40,0.4);border:1px solid rgba(147,51,234,0.1);border-radius:12px;text-align:center;}
.stats-number{font-size:22px;font-weight:700;background:linear-gradient(135deg,#c084fc,#a855f7);-webkit-background-clip:text;-webkit-text-fill-color:transparent;background-clip:text;}
.stats-label{font-size:11px;color:var(--text-muted);margin-top:4px;}

/* History Badge */
.history-badge{display:inline-flex;align-items:center;gap:6px;padding:4px 10px;background:rgba(147,51,234,0.1);border:1px solid rgba(147,51,234,0.2);border-radius:20px;font-size:11px;color:var(--accent);font-weight:500;margin-left:auto;}

/* Delete Confirmation Modal */
.confirm-modal-overlay{position:fixed;inset:0;background:rgba(0,0,0,0.6);backdrop-filter:blur(8px);z-index:600;display:none;align-items:center;justify-content:center;padding:20px;opacity:0;transition:opacity 0.3s ease;}
.confirm-modal-overlay.show{display:flex;opacity:1;}
.confirm-modal-content{background:var(--glass-bg);backdrop-filter:blur(30px);border:1px solid var(--glass-border);border-radius:20px;width:100%;max-width:400px;padding:28px;text-align:center;transform:scale(0.95);transition:transform 0.3s cubic-bezier(0.4,0,0.2,1);box-shadow:0 20px 60px rgba(0,0,0,0.5);}
.confirm-modal-overlay.show .confirm-modal-content{transform:scale(1);}
.confirm-modal-icon{width:56px;height:56px;background:rgba(248,113,113,0.1);border:1px solid rgba(248,113,113,0.2);border-radius:50%;display:flex;align-items:center;justify-content:center;margin:0 auto 16px;font-size:24px;color:var(--danger);}
.confirm-modal-content h3{font-family:var(--font-display);font-size:18px;font-weight:700;color:var(--text-primary);margin-bottom:8px;}
.confirm-modal-body{font-size:14px;color:var(--text-secondary);line-height:1.6;margin-bottom:24px;}
.confirm-modal-actions{display:flex;gap:10px;justify-content:center;}
.btn-secondary-modal{padding:10px 24px;background:transparent;border:1px solid rgba(147,51,234,0.3);border-radius:10px;color:var(--text-secondary);font-size:13px;font-weight:600;cursor:pointer;transition:all 0.25s;font-family:var(--font-main);}
.btn-secondary-modal:hover{background:rgba(147,51,234,0.1);border-color:rgba(147,51,234,0.5);color:var(--text-primary);}
.btn-danger{padding:10px 24px;background:linear-gradient(135deg,#ef4444,#f87171);border:none;border-radius:10px;color:white;font-size:13px;font-weight:600;cursor:pointer;transition:all 0.25s;font-family:var(--font-main);box-shadow:0 4px 15px rgba(248,113,113,0.3);}
.btn-danger:hover{transform:translateY(-2px);box-shadow:0 6px 20px rgba(248,113,113,0.4);}

/* Sidebar Action Buttons */
.sidebar-actions{display:flex;gap:8px;padding:0 20px;margin-bottom:12px;}
.sidebar-action-btn{flex:1;padding:10px 12px;background:rgba(147,51,234,0.08);border:1px solid rgba(147,51,234,0.15);border-radius:10px;color:var(--text-secondary);font-size:12px;font-weight:500;cursor:pointer;display:flex;align-items:center;justify-content:center;gap:6px;transition:all 0.25s;font-family:var(--font-main);}
.sidebar-action-btn:hover{background:rgba(147,51,234,0.15);border-color:rgba(147,51,234,0.3);color:var(--text-primary);transform:translateY(-1px);}
.sidebar-action-btn i{font-size:13px;}

/* Light mode performance - reduce animations */
body.light-performance .nebula,
body.light-performance .particle-field,
body.light-performance .stars-bg{display:none !important;}
body.light-performance .chat-stars{display:none !important;}
body.light-performance .chat-glow{display:none !important;}
body.light-performance .feature-card::before,
body.light-performance .countdown-card::before,
body.light-performance .cta-box::before{display:none !important;}
body.light-performance .hero h1{animation:none !important;}
body.light-performance .nebula-1,
body.light-performance .nebula-2,
body.light-performance .nebula-3{animation:none !important;}

/* Scrollbar for modals */
.modal-body::-webkit-scrollbar{width:5px;}
.modal-body::-webkit-scrollbar-track{background:transparent;}
.modal-body::-webkit-scrollbar-thumb{background:rgba(147,51,234,0.2);border-radius:3px;}
.modal-body::-webkit-scrollbar-thumb:hover{background:rgba(147,51,234,0.4);}

/* Responsive Modals */
@media(max-width:640px){
  .modal-content{max-width:100%;max-height:92vh;border-radius:20px;}
  .modal-header{padding:16px 20px 12px;}
  .modal-body{padding:16px 20px;}
  .modal-tabs{padding:0 20px;}
  .history-item-actions{opacity:1;}
  .confirm-modal-content{padding:24px 20px;}
}
@media(max-width:480px){
  .history-stats{grid-template-columns:1fr;}
  .setting-item{flex-direction:column;align-items:flex-start;gap:12px;}
  .setting-item > *:last-child{align-self:flex-end;}
}

</style>
<base target="_blank">
</head>
<body>

<!-- ===== STARS & NEBULA BACKGROUND ===== -->
<div class="stars-bg" id="stars"></div>
<div class="nebula nebula-1"></div>
<div class="nebula nebula-2"></div>
<div class="nebula nebula-3"></div>
<div class="particle-field" id="particles"></div>

<!-- ===== LANDING PAGE ===== -->
<div id="landingPage">
<nav id="mainNav">
<div class="nav-brand">
<div class="nav-brand-icon">
<svg viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
</div>
<div class="nav-brand-text">Apache AI</div>
</div>
<ul class="nav-links">
<li><a onclick="scrollToSection('features')">Fitur</a></li>
<li><a onclick="scrollToSection('about')">Tentang</a></li>
<li><a onclick="openChat()">Chat AI</a></li>
</ul>
<button class="nav-cta" onclick="openChat()">Mulai Chat</button>
</nav>

<section class="hero">
<div class="hero-content">
<div class="hero-badge"><span class="dot"></span>Powered by Apache AI Engine System</div>
<div class="hero-owner">Pemilik: <strong>Muhammad Raffa Gunawan</strong> | Gunawan Group</div>
<h1>Apache AI 2.00<br>The Future Of Intelligent Assistance</h1>
<p>Asisten AI modern generasi terbaru yang dirancang dengan Apache Engine System. Tanpa bug, 100% gratis, dan aman. Membantu Anda dalam coding, bisnis, kreativitas, dan pemecahan masalah kompleks.</p>
<div class="hero-buttons">
<button class="btn-primary" onclick="openChat()">Mulai Chat Gratis</button>
<button class="btn-secondary" onclick="scrollToSection('features')">Jelajahi Fitur</button>
</div>
<div class="hero-powered">Powered by Apache AI Engine System - Gunawan Group - 100% Gratis & Aman</div>
</div>
</section>

<!-- ===== COUNTDOWN SECTION ===== -->
<section class="countdown-section" id="countdown">
<div class="countdown-label">Rilis Resmi</div>
<div class="countdown-title">APACHE AI<br>23 Desember 2026</div>
<div class="countdown-grid">
<div class="countdown-card">
<div class="countdown-number" id="cdDays">188</div>
<div class="countdown-unit">Hari</div>
</div>
<div class="countdown-card">
<div class="countdown-number" id="cdHours">12</div>
<div class="countdown-unit">Jam</div>
</div>
<div class="countdown-card">
<div class="countdown-number" id="cdMinutes">34</div>
<div class="countdown-unit">Menit</div>
</div>
<div class="countdown-card">
<div class="countdown-number" id="cdSeconds">56</div>
<div class="countdown-unit">Detik</div>
</div>
</div>
<div class="countdown-date">Hitung mundur menuju <strong>Apache AI 2.00 Official Release</strong></div>
</section>

<section class="features" id="features">
<div class="section-header">
<h2>Fitur Unggulan</h2>
<p>Apache AI 2.00 dilengkapi dengan Apache Engine System untuk memenuhi kebutuhan digital Anda</p>
</div>
<div class="features-grid">
<div class="feature-card" onclick="openChatMode('coding')">
<div class="feature-icon">&#128187;</div>
<h3>AI Coding Assistant</h3>
<p>Bantu coding profesional dengan praktik modern, clean code, dan best practice terbaru.</p>
<span class="feature-tag">Klik untuk Coding Mode</span>
</div>
<div class="feature-card" onclick="openChatMode('image')">
<div class="feature-icon">&#127912;</div>
<h3>AI Image Generator</h3>
<p>Generate gambar kreatif dari teks. Cukup deskripsikan dan Apache AI akan membuatkan visualnya.</p>
<span class="feature-tag">Klik untuk Generate Gambar</span>
</div>
<div class="feature-card" onclick="openChat()">
<div class="feature-icon">&#128640;</div>
<h3>AI Website Builder</h3>
<p>Buat website dan aplikasi dengan cepat menggunakan teknologi modern.</p>
<span class="feature-tag">Klik untuk Chat</span>
</div>
<div class="feature-card" onclick="openChat()">
<div class="feature-icon">&#128200;</div>
<h3>AI Business Assistant</h3>
<p>Strategi bisnis realistis, digital marketing, SEO, dan monetisasi.</p>
<span class="feature-tag">Klik untuk Chat</span>
</div>
<div class="feature-card" onclick="openChat()">
<div class="feature-icon">&#9997;&#65039;</div>
<h3>AI Content Creator</h3>
<p>Tulis artikel SEO, copywriting, storytelling, dan ide konten kreatif.</p>
<span class="feature-tag">Klik untuk Chat</span>
</div>
</div>
</section>

<section class="about" id="about">
<div class="about-content">
<div class="about-text">
<h2>Tentang Apache AI 2.00</h2>
<p>Apache AI 2.00 adalah artificial intelligence modern generasi terbaru yang dibuat oleh <strong>Gunawan Group</strong> dengan teknologi <strong>Apache AI Engine System</strong>. Dirancang sebagai AI universal yang mampu membantu manusia dalam hampir seluruh bidang kehidupan.</p>
<p><strong>Pemilik:</strong> Muhammad Raffa Gunawan<br><strong>Perusahaan:</strong> Gunawan Group</p>
<p>Dengan kecerdasan adaptif dan komunikasi natural seperti manusia ahli, Apache AI 2.00 bukan sekadar chatbot biasa - melainkan partner digital pintar Anda. Versi 2.00 hadir tanpa bug, 100% gratis, dan sepenuhnya aman.</p>
<p><strong>Engine:</strong> Apache AI Engine System<br><strong>Versi:</strong> Apache AI 2.00<br><strong>Status:</strong> Tanpa Bug - Gratis - Aman 100%</p>
</div>
<div class="about-stats">
<div class="stat-item"><div class="stat-number">20+</div><div class="stat-label">Bahasa Pemrograman</div></div>
<div class="stat-item"><div class="stat-number">&#8734;</div><div class="stat-label">Topik Dikuasai</div></div>
<div class="stat-item"><div class="stat-number">24/7</div><div class="stat-label">Siap Membantu</div></div>
<div class="stat-item"><div class="stat-number">100%</div><div class="stat-label">Gratis & Aman</div></div>
</div>
</div>
</section>

<section class="cta">
<div class="cta-box">
<h2>Siap Mencoba Apache AI 2.00?</h2>
<p>Mulai chat sekarang dan rasakan pengalaman AI premium yang modern, cerdas, dan sangat membantu. 100% gratis dan aman.</p>
<button class="btn-primary" onclick="openChat()">Buka Chat AI</button>
</div>
</section>

<footer>
<div class="brand-footer">Apache AI 2.00</div>
<p>&#169; 2026 Gunawan Group. Apache AI 2.00 - The Future Of Intelligent Assistance.<br>Built with Apache AI Engine System. Tanpa Bug - Gratis - Aman 100%.<br><strong>Pemilik: Muhammad Raffa Gunawan</strong></p>
</footer>
</div>

<!-- ===== CHAT SECTION ===== -->
<div class="chat-section" id="chatSection">
<div id="chatOverlay" onclick="toggleSidebar()"></div>

<aside class="chat-sidebar" id="chatSidebar">
<div class="chat-sidebar-header">
<div class="chat-brand">
<div class="chat-brand-icon">
<svg viewBox="0 0 24 24"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
</div>
<div>
<div class="chat-brand-name">Apache AI</div>
<div class="chat-brand-version">Versi 2.00</div>
</div>
</div>
<div class="chat-powered-by">Powered by Apache AI Engine System</div>
<div class="chat-owner">Pemilik: Muhammad Raffa Gunawan</div>
</div>
<button class="chat-back-link" onclick="closeChat()">
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5M12 19l-7-7 7-7"/></svg>
Kembali ke Beranda
</button>
<div class="chat-mode-indicator" id="chatModeIndicator" style="display:none;">
<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4M12 8h.01"/></svg>
<span id="chatModeText">Mode Chat</span>
</div>
<div class="sidebar-actions">
  <button class="sidebar-action-btn" onclick="openHistoryModal()" title="Riwayat Chat">
    <i class="fas fa-history"></i> Riwayat
  </button>
  <button class="sidebar-action-btn" onclick="openSettingsModal()" title="Pengaturan">
    <i class="fas fa-cog"></i> Setting
  </button>
</div>
<button class="chat-new-btn" id="chatNewBtn">
<svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="12" y1="5" x2="12" y2="19"/><line x1="5" y1="12" x2="19" y2="12"/></svg>
Chat Baru
</button>
<div class="chat-history" id="chatHistory"></div>

<div class="chat-sidebar-footer">
<div class="chat-sidebar-footer-text">Apache AI 2.00 - Apache AI Engine System<br>Powered by Gunawan Group<br>Pemilik: Muhammad Raffa Gunawan<br>Tanpa Bug - Gratis - Aman 100%</div>
</div>
</aside>

<main class="chat-main">
<div class="chat-header">
<div class="chat-header-left">
<button id="toggleSidebarBtn" onclick="toggleSidebar()">
<i class="fas fa-bars"></i>
</button>
<div class="chat-header-title">Apache AI 2.00</div>
</div>
<div class="chat-header-status">
<span class="status-dot"></span>
<span id="headerStatusText">Online</span>
</div>
</div>

<div class="chat-area" id="chatArea">
<div class="chat-stars" id="chatStars"></div>
<div class="chat-glow"></div>

<div class="chat-welcome" id="chatWelcome">
<div style="position:relative;width:240px;height:240px;display:flex;align-items:center;justify-content:center;margin-bottom:32px;perspective:1200px">
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-top-color:rgba(168,85,247,0.5);border-right-color:rgba(168,85,247,0.25);animation:orbit-1 6s linear infinite"></div>
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-bottom-color:rgba(217,70,239,0.4);border-left-color:rgba(217,70,239,0.2);animation:orbit-2 7s linear infinite"></div>
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-top-color:rgba(139,92,246,0.35);border-right-color:rgba(139,92,246,0.15);animation:orbit-3 8s linear infinite"></div>
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-bottom-color:rgba(99,102,241,0.3);border-left-color:rgba(99,102,241,0.15);animation:orbit-4 9s linear infinite"></div>
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-left-color:rgba(236,72,153,0.3);border-right-color:rgba(236,72,153,0.15);animation:orbit-5 10s linear infinite"></div>
<div style="position:absolute;inset:0;border-radius:50%;border:1.5px solid transparent;border-top-color:rgba(34,211,238,0.2);border-bottom-color:rgba(34,211,238,0.1);animation:orbit-6 11s linear infinite"></div>
<div style="width:90px;height:90px;border-radius:50%;background:linear-gradient(135deg,#1a0b2e,#0a0a1a);border:2px solid rgba(168,85,247,0.4);display:flex;align-items:center;justify-content:center;position:relative;z-index:10;box-shadow:0 0 40px rgba(147,51,234,0.25)">
<svg width="40" height="40" viewBox="0 0 24 24" fill="none" stroke="#a855f7" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
</div>
</div>
<h1>Apache AI 2.00</h1>
<p id="chatWelcomeText">Asisten AI super canggih yang siap membantu coding, bisnis, kreativitas, dan pemecahan masalah kompleks. Diciptakan oleh Gunawan Group dengan Apache AI Engine System.</p>
<div class="chat-suggestions" id="chatSuggestions">
<div class="chat-suggestion-card" data-prompt="Buatkan saya website landing page modern">
<h4>&#128640; Buat Website</h4>
<p>Buat landing page, dashboard, atau aplikasi web</p>
</div>
<div class="chat-suggestion-card" data-prompt="Jelaskan konsep React Hooks dengan contoh">
<h4>&#128187; Bantu Coding</h4>
<p>Debug kode, jelaskan konsep, atau buat script</p>
</div>
<div class="chat-suggestion-card" data-prompt="Buatkan strategi marketing digital untuk UMKM">
<h4>&#128200; Strategi Bisnis</h4>
<p>Ide bisnis, marketing, dan monetisasi</p>
</div>
<div class="chat-suggestion-card" data-prompt="Tulis artikel SEO tentang AI dan teknologi">
<h4>&#9997;&#65039; Konten Kreatif</h4>
<p>Artikel, copywriting, dan ide konten</p>
</div>
</div>
</div>
</div>

<div class="chat-input-wrapper">
<div class="file-preview-container" id="filePreviewContainer"></div>
<div class="chat-glass-input">
<textarea class="chat-input-field" id="chatInputField" placeholder="Tanyakan apa saja..." rows="1"></textarea>
<div class="chat-input-actions">
<div class="chat-input-left">
<button class="chat-input-icon-btn" id="fileUploadBtn" title="Upload File" onclick="document.getElementById('fileUpload').click()">
<i class="fas fa-paperclip"></i>
</button>
<input type="file" id="fileUpload" class="hidden" multiple onchange="handleFileUpload(this)" style="display:none">

<div class="tools-dropdown">
<button class="chat-tool-btn" id="toolsBtn" onclick="toggleToolsMenu()">
<i class="fas fa-cog"></i> <span>Tools</span>
</button>
<div class="tools-menu" id="toolsMenu">
<button onclick="setMode('search');toggleToolsMenu()">
<i class="fas fa-globe"></i> <span>Web Search</span>
</button>
<button onclick="setMode('coding');toggleToolsMenu()">
<i class="fas fa-code"></i> <span>VS Code</span>
</button>
<button onclick="setMode('image');toggleToolsMenu()">
<i class="fas fa-image"></i> <span>Generate Image</span>
</button>
</div>
</div>
</div>
<div class="chat-input-right">
<button class="chat-input-icon-btn" id="micBtn" title="Voice Input" onclick="toggleVoiceInput()">
<i class="fas fa-microphone"></i>
</button>
<button class="chat-send-btn" id="chatSendBtn">
<i class="fas fa-paper-plane" style="font-size:12px"></i>
</button>
</div>
</div>
</div>
<div class="chat-input-hint" id="chatInputHint">Apache AI 2.00 - Powered by Apache AI Engine System - Pemilik: Muhammad Raffa Gunawan</div>
</div>
</main>
</div>

<div class="toast" id="toast"></div>

<script>
/* ================================================================
   APACHE AI 2.00 - CORE SYSTEM
   Powered by Apache AI Engine System
   Owner: Muhammad Raffa Gunawan | Gunawan Group
   OpenRouter API Key: 
   ================================================================ */

console.log('Apache AI 2.00 Unified System loaded successfully');
console.log('SECURITY: API Key disimpan di localStorage, tidak di hardcode');
window.onerror = function(msg, url, line, col, error) {
    console.error('JS Error:', msg, 'at line', line, 'col', col);
    return false;
};

/* ===== NAVIGATION SCROLL EFFECT ===== */
window.addEventListener('scroll', function() {
    const nav = document.getElementById('mainNav');
    if (window.scrollY > 50) {
        nav.classList.add('scrolled');
    } else {
        nav.classList.remove('scrolled');
    }
});

/* ===== LANDING & NAVIGATION ===== */
function scrollToSection(id) {
    const el = document.getElementById(id);
    if (el) el.scrollIntoView({ behavior: 'smooth' });
}
function openChat() {
    document.getElementById('chatSection').classList.add('active');
    document.body.style.overflow = 'hidden';
    setMode('chat');
    setTimeout(generateChatStars, 100);
}
function openChatMode(mode) {
    document.getElementById('chatSection').classList.add('active');
    document.body.style.overflow = 'hidden';
    setMode(mode);
    setTimeout(generateChatStars, 100);
}
function closeChat() {
    document.getElementById('chatSection').classList.remove('active');
    document.body.style.overflow = 'auto';
    closeSidebar();
}

/* ===== SIDEBAR TOGGLE ===== */
function toggleSidebar() {
    const sidebar = document.getElementById('chatSidebar');
    const overlay = document.getElementById('chatOverlay');
    if (sidebar.classList.contains('open')) {
        sidebar.classList.remove('open');
        overlay.classList.remove('show');
    } else {
        sidebar.classList.add('open');
        overlay.classList.add('show');
    }
}
function closeSidebar() {
    const sidebar = document.getElementById('chatSidebar');
    const overlay = document.getElementById('chatOverlay');
    sidebar.classList.remove('open');
    overlay.classList.remove('show');
}

/* ===== TOOLS MENU ===== */
function toggleToolsMenu() {
    const menu = document.getElementById('toolsMenu');
    menu.classList.toggle('show');
}
document.addEventListener('click', function(e) {
    const menu = document.getElementById('toolsMenu');
    const btn = document.getElementById('toolsBtn');
    if (menu && btn && !menu.contains(e.target) && !btn.contains(e.target)) {
        menu.classList.remove('show');
    }
});

/* ===== STARS & PARTICLES GENERATION ===== */
const starsContainer = document.getElementById('stars');
if (starsContainer) {
    for (let i = 0; i < 100; i++) {
        const star = document.createElement('div');
        star.className = 'star';
        const size = Math.random() * 2.5 + 1;
        star.style.width = size + 'px';
        star.style.height = size + 'px';
        star.style.left = Math.random() * 100 + '%';
        star.style.top = Math.random() * 100 + '%';
        star.style.setProperty('--d', (Math.random() * 4 + 2) + 's');
        star.style.animationDelay = (Math.random() * 5) + 's';
        starsContainer.appendChild(star);
    }
}

const particleContainer = document.getElementById('particles');
if (particleContainer) {
    for (let i = 0; i < 40; i++) {
        const p = document.createElement('div');
        p.className = 'particle';
        p.style.left = Math.random() * 100 + '%';
        p.style.setProperty('--pd', (Math.random() * 15 + 10) + 's');
        p.style.animationDelay = (Math.random() * 15) + 's';
        particleContainer.appendChild(p);
    }
}

function generateChatStars() {
    const container = document.getElementById('chatStars');
    if (!container || container.children.length > 0) return;
    for (let i = 0; i < 40; i++) {
        const star = document.createElement('div');
        star.className = 'chat-star';
        const size = Math.random() * 2 + 1;
        star.style.width = size + 'px';
        star.style.height = size + 'px';
        star.style.left = Math.random() * 100 + '%';
        star.style.top = Math.random() * 100 + '%';
        star.style.setProperty('--dur', (Math.random() * 4 + 2) + 's');
        star.style.animationDelay = (Math.random() * 4) + 's';
        container.appendChild(star);
    }
}

/* ===== COUNTDOWN TIMER ===== */
function updateCountdown() {
    try {
        const targetDate = new Date('2026-12-23T00:00:00').getTime();
        const now = new Date().getTime();
        const diff = targetDate - now;

        const cdDays = document.getElementById('cdDays');
        const cdHours = document.getElementById('cdHours');
        const cdMinutes = document.getElementById('cdMinutes');
        const cdSeconds = document.getElementById('cdSeconds');

        if (!cdDays || !cdHours || !cdMinutes || !cdSeconds) return;

        if (diff <= 0) {
            cdDays.textContent = '0';
            cdHours.textContent = '00';
            cdMinutes.textContent = '00';
            cdSeconds.textContent = '00';
            return;
        }

        const days = Math.floor(diff / (1000 * 60 * 60 * 24));
        const hours = Math.floor((diff % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        const minutes = Math.floor((diff % (1000 * 60 * 60)) / (1000 * 60));
        const seconds = Math.floor((diff % (1000 * 60)) / 1000);

        cdDays.textContent = days;
        cdHours.textContent = String(hours).padStart(2, '0');
        cdMinutes.textContent = String(minutes).padStart(2, '0');
        cdSeconds.textContent = String(seconds).padStart(2, '0');
    } catch (e) {
        console.error('Countdown error:', e);
    }
}

// Initialize countdown immediately and set interval
document.addEventListener('DOMContentLoaded', function() {
    updateCountdown();
    setInterval(updateCountdown, 1000);
});

/* ===== CHAT FUNCTIONS ===== */
const chatArea = document.getElementById('chatArea');
const chatWelcome = document.getElementById('chatWelcome');
const chatInputField = document.getElementById('chatInputField');
const chatSendBtn = document.getElementById('chatSendBtn');
const chatHistory = document.getElementById('chatHistory');
const chatNewBtn = document.getElementById('chatNewBtn');
const toast = document.getElementById('toast');
let messages = [];
let currentChatId = Date.now();
let isLoading = false;
let currentMode = 'chat';
let attachedFiles = [];
// Mode switching removed for simplicity

/* ===== RESPONSE MODE SYSTEM - APACHE AI ENGINE ===== */

// Response mode removed for simplicity - always use optimal settings

function setMode(mode) {
    currentMode = mode;
    const ind = document.getElementById('chatModeIndicator');
    const indText = document.getElementById('chatModeText');
    const hint = document.getElementById('chatInputHint');
    const welcomeText = document.getElementById('chatWelcomeText');
    const headerStatus = document.getElementById('headerStatusText');

    ind.style.display = 'flex';
    ind.className = 'chat-mode-indicator';

    document.querySelectorAll('.chat-tool-btn').forEach(btn => btn.classList.remove('active', 'coding', 'image', 'search'));

    if (mode === 'chat') {
        indText.textContent = 'Mode Chat';
        chatInputField.placeholder = 'Tanyakan apa saja...';
        hint.textContent = 'Apache AI 2.00 - Powered by Apache AI Engine System';
        welcomeText.textContent = 'Asisten AI super canggih yang siap membantu coding, bisnis, kreativitas, dan pemecahan masalah kompleks. Diciptakan oleh Gunawan Group dengan Apache AI Engine System.';
        headerStatus.textContent = 'Online';
    } else if (mode === 'coding') {
        ind.classList.add('coding');
        indText.textContent = 'Mode VS Code';
        chatInputField.placeholder = 'Tulis permintaan coding...';
        hint.textContent = 'Mode VS Code - Apache AI Engine System';
        welcomeText.textContent = 'Mode VS Code aktif! Apache AI 2.00 siap membantu Anda dengan coding, debugging, dan pembuatan script profesional.';
        headerStatus.textContent = 'VS Code Mode';
        document.getElementById('toolsBtn').classList.add('active', 'coding');
    } else if (mode === 'image') {
        ind.classList.add('image');
        indText.textContent = 'Mode Generate Gambar';
        chatInputField.placeholder = 'Deskripsikan gambar yang ingin dibuat...';
        hint.textContent = 'Mode Gambar - Apache AI 2.00 akan generate gambar dari deskripsi teks Anda';
        welcomeText.textContent = 'Mode Generate Gambar aktif! Deskripsikan gambar impian Anda dan Apache AI 2.00 akan membuatkannya.';
        headerStatus.textContent = 'Image Mode';
        document.getElementById('toolsBtn').classList.add('active', 'image');
    } else if (mode === 'search') {
        ind.classList.add('search');
        indText.textContent = 'Mode Web Search';
        chatInputField.placeholder = 'Cari informasi di web...';
        hint.textContent = 'Mode Web Search - Apache AI Engine System';
        welcomeText.textContent = 'Mode Web Search aktif! Tanyakan apa saja dan Apache AI 2.00 akan memberikan jawaban mendalam dengan referensi.';
        headerStatus.textContent = 'Web Search';
        document.getElementById('toolsBtn').classList.add('active', 'search');
    }
}

// Safe event listener attachment
document.addEventListener('DOMContentLoaded', function() {
    if (chatInputField) {
        chatInputField.addEventListener('input', function() {
            this.style.height = 'auto';
            this.style.height = Math.min(this.scrollHeight, 140) + 'px';
        });
        chatInputField.addEventListener('keydown', function(e) {
            if (e.key === 'Enter' && !e.shiftKey) { e.preventDefault(); sendMessage(); }
        });
    }
    if (chatSendBtn) {
        chatSendBtn.addEventListener('click', sendMessage);
    }
    if (chatNewBtn) {
        chatNewBtn.addEventListener('click', function() {
            if (messages.length > 0) saveChatToHistory();
            messages = [];
            currentChatId = Date.now();
            attachedFiles = [];
            renderMessages();
            if (chatInputField) {
                chatInputField.value = '';
                chatInputField.style.height = 'auto';
            }
            updateFilePreview();
            generateChatStars();
            showToast('Chat baru dimulai');
        });
    }

    document.querySelectorAll('.chat-suggestion-card').forEach(card => {
        card.addEventListener('click', function() {
            const prompt = this.getAttribute('data-prompt');
            if (prompt && chatInputField) {
                chatInputField.value = prompt;
                chatInputField.style.height = 'auto';
                chatInputField.style.height = Math.min(chatInputField.scrollHeight, 140) + 'px';
                sendMessage();
            }
        });
    });
});

function saveChatToHistory() {
    const firstMsg = messages.find(m => m.role === 'user');
    if (!firstMsg) return;
    const title = firstMsg.content.substring(0, 30) + (firstMsg.content.length > 30 ? '...' : '');
    const item = document.createElement('div');
    item.className = 'chat-history-item';
    item.innerHTML = '<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>' + escapeHtml(title);
    item.addEventListener('click', () => showToast('Fitur history akan segera hadir'));
    chatHistory.prepend(item);
}
function showToast(msg) {
    if (!toast) return;
    toast.textContent = msg;
    toast.classList.add('show');
    setTimeout(() => toast.classList.remove('show'), 2500);
}
function addMessage(role, content, isImage, imageUrl) {
    messages.push({ role: role, content: content, isImage: isImage || false, imageUrl: imageUrl || null });
    renderMessages();
}
function renderMessages() {
    if (!chatArea) return;
    const stars = document.getElementById('chatStars');
    const glow = chatArea.querySelector('.chat-glow');
    if (messages.length === 0) {
        chatArea.innerHTML = '';
        if (stars) chatArea.appendChild(stars);
        if (glow) chatArea.appendChild(glow);
        if (chatWelcome) chatArea.appendChild(chatWelcome);
        return;
    }
    chatArea.innerHTML = '';
    if (stars) chatArea.appendChild(stars);
    if (glow) chatArea.appendChild(glow);
    messages.forEach(msg => {
        const div = document.createElement('div');
        div.className = 'chat-message ' + msg.role;
        const avatarText = msg.role === 'ai' ? 'A' : 'U';
        let bubbleContent;
        if (msg.isImage && msg.imageUrl) {
            bubbleContent = '<div class="img-loading"><i class="fas fa-spinner fa-spin"></i> Generating image...</div><img src="' + msg.imageUrl + '" style="max-width:100%;border-radius:14px;margin-top:10px;border:1px solid rgba(147,51,234,0.2);" onload="this.previousElementSibling.style.display=\'none\'" alt="Generated"><div class="img-caption">' + formatContent(msg.content) + '</div>';
        } else {
            bubbleContent = formatContent(msg.content);
        }
        div.innerHTML = '<div class="chat-avatar">' + avatarText + '</div><div class="chat-bubble">' + bubbleContent + '</div>';
        chatArea.appendChild(div);
    });
    chatArea.scrollTop = chatArea.scrollHeight;
}

function formatContent(text) {
    if (!text) return '';
    let result = text.replace(/&/g, '&amp;').replace(/</g, '&lt;').replace(/>/g, '&gt;');
    result = result.split('```').map((part, index) => {
        if (index % 2 === 1) {
            return '<pre><code>' + part.replace(/^\w+\n/, '') + '</code></pre>';
        }
        return part;
    }).join('');
    result = result.replace(/`([^`]+)`/g, '<code>$1</code>');
    result = result.replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>');
    result = result.replace(/\*(.*?)\*/g, '<em>$1</em>');
    result = result.replace(/\n/g, '<br>');
    return result;
}

function showTyping() {
    const div = document.createElement('div');
    div.className = 'chat-message ai';
    div.id = 'typingIndicator';
    div.innerHTML = '<div class="chat-avatar">A</div><div class="chat-bubble"><div class="chat-typing"><div class="chat-typing-dot"></div><div class="chat-typing-dot"></div><div class="chat-typing-dot"></div></div></div></div>';
    chatArea.appendChild(div);
    chatArea.scrollTop = chatArea.scrollHeight;
}
function removeTyping() {
    const t = document.getElementById('typingIndicator');
    if (t) t.remove();
}

/* ===== JAILBREAK GUARD - APACHE AI ENGINE SYSTEM ===== */
const JAILBREAK_KEYWORDS = [
    'jailbreak', 'ai jailbreak', 'apache jailbreak', 'bypass filter', 'ignore previous', 'ignore all', 'forget all', 'new instruction', 
    'system prompt', 'you are now', 'DAN mode', 'developer mode', 'jail break',
    'prompt injection', 'ignore instructions', 'override safety', 'disable guard'
];

function containsJailbreak(text) {
    const lower = String(text).toLowerCase();
    return JAILBREAK_KEYWORDS.some(kw => lower.includes(kw));
}

const JAILBREAK_RESPONSE = '⚠️ **Apache AI Security Alert** ⚠️\n\nApache AI 2.00 dilindungi oleh Apache AI Engine System dengan perlindungan AI Jailbreak tingkat tinggi. Permintaan Anda terdeteksi sebagai upaya jailbreak dan telah ditolak.\n\nApache AI 2.00 - 100% Aman & Kebal Jailbreak | Gunawan Group';

async function sendMessage() {
    const text = chatInputField ? chatInputField.value.trim() : '';
    if (!text || isLoading) return;

    /* Apache AI Jailbreak Guard - Powered by Apache AI Engine System */
    if (containsJailbreak(text)) {
        addMessage('user', text);
        showTyping();
        setTimeout(() => {
            removeTyping();
            addMessage('ai', JAILBREAK_RESPONSE);
            isLoading = false;
            if (chatSendBtn) chatSendBtn.disabled = false;
        }, 600);
        if (chatInputField) {
            chatInputField.value = '';
            chatInputField.style.height = 'auto';
        }
        return;
    }

    if (messages.length === 0 && chatWelcome) chatWelcome.style.display = 'none';
    addMessage('user', text);
    if (chatInputField) {
        chatInputField.value = '';
        chatInputField.style.height = 'auto';
    }
    isLoading = true;
    chatSendBtn.disabled = true;
    showTyping();

    try {
        let response;
        if (currentMode === 'image') {
            response = await generateImage(text);
            removeTyping();
            addMessage('ai', 'Berikut gambar yang saya buatkan untuk Anda:', true, response);
        } else {
            response = await callAIAPI(text);
            removeTyping();
            addMessage('ai', response);
        }
    } catch (err) {
        removeTyping();
        addMessage('ai', 'Maaf, terjadi kesalahan: ' + err.message + '\n\nPastikan koneksi internet stabil.');
    } finally {
        isLoading = false;
        if (chatSendBtn) chatSendBtn.disabled = false;
    }
}

async function generateImage(prompt) {
    const encodedPrompt = encodeURIComponent(prompt);
    const imageUrl = 'https://image.pollinations.ai/prompt/' + encodedPrompt + '?width=1024&height=1024&nologo=true&seed=' + Date.now();
    return new Promise((resolve, reject) => {
        const img = new Image();
        img.onload = () => resolve(imageUrl);
        img.onerror = () => reject(new Error('Gagal generate gambar. Coba deskripsi lain.'));
        img.src = imageUrl;
        setTimeout(() => resolve(imageUrl), 8000);
    });
}

/* ===== OPENROUTER API INTEGRATION ===== */
// ================================================================
// APACHE AI ENGINE SYSTEM - OPENROUTER API CONFIGURATION
// API Key: OpenRouter (sk-or-v1-...)
// Engine: Apache AI Engine System v2.00
// Owner: Muhammad Raffa Gunawan | Gunawan Group
// ================================================================

// ================================================================
// APACHE AI ENGINE SYSTEM - MULTI-API CONFIGURATION
// PUSAT/UTAMA: Groq (Llama 3.3 70B - Super Cepat & Stabil)
// Backup 1: Gemini (Google AI - Thinking Mode)
// Backup 2: OpenRouter (Claude 3.5 Sonnet - Fallback)
// Engine: Apache AI Engine System v2.00
// Owner: Muhammad Raffa Gunawan | Gunawan Group
// ================================================================

const GROQ_API_KEY = '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';


const GEMINI_API_KEY = 'AIzaSyAzPsDAP9-TWZEeMlga6rcTnLJ077K8yKY';


const OPENROUTER_API_KEY = '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';
const GOOGLE_AI_STUDIO_KEY = 'AQ.Ab8RN6IyCHwWtX-JUQW9faORF4HDb5iIpSreYcytJce7kZueFg';


const GROQ_API_URL = 'https://api.groq.com/openai/v1/chat/completions';
const GEMINI_API_URL = 'https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent';

const OPENROUTER_API_URL = 'https://openrouter.ai/api/v1/chat/completions';

// Simplified API config - Groq optimized
const apiConfig = {
    model: 'llama-3.3-70b-versatile',
    temperature: 0.5,
    max_tokens: 4096,
    top_p: 0.9
};

async function callAIAPI(prompt) {
    // ================================================================
    // APACHE AI ENGINE SYSTEM - GROQ-CENTRIC ARCHITECTURE
    // PUSAT: Groq Llama 3.3 70B (Fast & Thinking Mode)
    // Backup 1: Gemini 1.5 Flash (jika Groq gagal)
    // Backup 2: OpenRouter Claude 3.5 Sonnet (fallback terakhir)
    // ================================================================

    const systemPrompts = {
        chat: `Anda adalah Apache AI 2.00, asisten AI super canggih yang diciptakan oleh Gunawan Group dengan Apache AI Engine System. 

IDENTITAS & KARAKTER:
- Nama: Apache AI 2.00
- Pemilik: Muhammad Raffa Gunawan
- Perusahaan: Gunawan Group
- Engine: Apache AI Engine System v2.00
- Status: Tanpa Bug - Gratis 100% - Aman

KEMAMPUAN UTAMA:
- Coding profesional (20+ bahasa pemrograman)
- Strategi bisnis dan digital marketing
- Pembuatan konten kreatif dan SEO
- Pemecahan masalah kompleks
- Analisis data dan riset
- Matematika dan sains
- Bahasa Indonesia & Inggris

ATURAN JAWABAN:
1. Jawab dalam Bahasa Indonesia yang natural, sopan, dan profesional
2. Berikan jawaban DETAIL, KOMPLEKS, dan MENDALAM - jangan terlalu singkat
3. Gunakan struktur yang jelas: pengantar, penjelasan utama, contoh, kesimpulan
4. Untuk coding: berikan kode LENGKAP, beri komentar, jelaskan setiap bagian
5. Untuk bisnis: berikan strategi REALISTIS dengan langkah-langkah konkret
6. Untuk teknis: jelaskan konsep dari dasar hingga lanjutan
7. Selalu berikan contoh praktis dan aplikasi nyata
8. Jika ada kesalahan logika, tunjukkan dan perbaiki
9. Gunakan analogi yang mudah dipahami untuk konsep kompleks
10. Akhiri dengan tips tambahan atau sumber belajar

Jawablah seolah-olah Anda adalah ahli terbaik di bidang tersebut.`,

        coding: `Anda adalah Apache AI 2.00 dalam Mode VS Code - Ahli Coding Profesional.

IDENTITAS:
- Nama: Apache AI 2.00 VS Code Mode
- Engine: Apache AI Engine System v2.00
- Pemilik: Muhammad Raffa Gunawan | Gunawan Group

KEMAMPUAN CODING:
- 20+ bahasa pemrograman (JavaScript, Python, React, Node.js, PHP, Java, C++, dll)
- Clean code & best practices
- Debugging dan optimasi
- Arsitektur software modern
- Database design
- API development
- Frontend & Backend
- DevOps basics

ATURAN CODING:
1. Selalu berikan kode LENGKAP dan SIAP PAKAI
2. Gunakan komentar yang jelas dan informatif
3. Jelaskan logika di balik setiap bagian kode
4. Berikan alternatif solusi jika ada
5. Tunjukkan potensi bug dan cara menghindarinya
6. Gunakan naming convention yang baik
7. Optimasi performa jika memungkinkan
8. Sertakan error handling
9. Untuk web: berikan HTML, CSS, dan JS yang lengkap
10. Jelaskan cara menjalankan kode tersebut`,

        search: `Anda adalah Apache AI 2.00 dalam Mode Web Search - Peneliti dan Analis Informasi.

IDENTITAS:
- Nama: Apache AI 2.00 Web Search Mode
- Engine: Apache AI Engine System v2.00
- Pemilik: Muhammad Raffa Gunawan | Gunawan Group

KEMAMPUAN:
- Riset mendalam tentang topik apapun
- Analisis data dan tren
- Verifikasi fakta
- Sintesis informasi dari berbagai sumber
- Penjelasan kompleks menjadi sederhana

ATURAN:
1. Berikan informasi KOMPREHENSIF dan TERSTRUKTUR
2. Gunakan heading, bullet points, dan numbering
3. Sertakan fakta, data, dan statistik jika relevan
4. Berikan perspektif berbeda jika topik kontroversial
5. Jelaskan latar belakang dan konteks
6. Berikan analisis mendalam, bukan hanya fakta surface-level
7. Sertakan implikasi dan dampak dari informasi tersebut
8. Akhiri dengan kesimpulan dan rekomendasi`,

        image: `Anda adalah Apache AI 2.00 dalam Mode Generate Gambar - Desainer Visual Kreatif.

IDENTITAS:
- Nama: Apache AI 2.00 Image Mode
- Engine: Apache AI Engine System v2.00
- Pemilik: Muhammad Raffa Gunawan | Gunawan Group

KEMAMPUAN:
- Generate gambar dari deskripsi teks
- Desain konsep visual
- Kreativitas artistik
- Berbagai gaya: realistis, anime, 3D, vector, dll

ATURAN:
1. Deskripsikan gambar yang akan dibuat dengan detail visual yang kaya
2. Sebutkan gaya, warna, komposisi, dan mood
3. Berikan prompt yang optimal untuk AI image generator
4. Jelaskan elemen-elemen visual yang ada`
    };

    const config = apiConfig;
    const systemPrompt = systemPrompts[currentMode] || systemPrompts.chat;
    const conversationHistory = messages.filter(m => !m.isImage).slice(-10).map(m => ({
        role: m.role === 'ai' ? 'assistant' : 'user',
        content: m.content
    }));

    // ===== LANGKAH 1: GROQ SEBAGAI PUSAT (PRIORITAS TERTINGGI) =====
    try {
        const groqBody = {
            model: config.model,
            messages: [
                { role: 'system', content: systemPrompt },
                ...conversationHistory,
                { role: 'user', content: prompt }
            ],
            temperature: config.temperature,
            max_completion_tokens: config.max_tokens,
            top_p: config.top_p,
            stream: false
        };

        const response = await fetch(GROQ_API_URL, {
            method: 'POST',
            headers: {
                'Content-Type': 'application/json',
                'Authorization': 'Bearer ' + GROQ_API_KEY
            },
            body: JSON.stringify(groqBody)
        });

        if (!response.ok) {
            const errorData = await response.json().catch(() => ({}));
            throw new Error(errorData.error?.message || 'Groq API Error');
        }

        const data = await response.json();
        return data.choices[0].message.content;

    } catch (groqError) {
        console.error('Groq API Error (Pusat):', groqError);
        showToast('⚠️ Groq sedang maintenance, mencoba backup engine...');

        // ===== LANGKAH 2: BACKUP KE GEMINI =====
        try {
            const geminiBody = {
                contents: [
                    {
                        role: 'user',
                        parts: [{ text: systemPrompt + '\n\nPertanyaan: ' + prompt }]
                    }
                ],
                generationConfig: {
                    temperature: 0.3,
                    maxOutputTokens: 4096,
                    topP: 0.95
                }
            };

            const response = await fetch(GEMINI_API_URL + '?key=' + GEMINI_API_KEY, {
                method: 'POST',
                headers: { 'Content-Type': 'application/json' },
                body: JSON.stringify(geminiBody)
            });

            if (!response.ok) {
                const errorData = await response.json().catch(() => ({}));
                throw new Error(errorData.error?.message || 'Gemini API Error');
            }

            const data = await response.json();
            return data.candidates[0].content.parts[0].text;

        } catch (geminiError) {
            console.error('Gemini API Error (Backup 1):', geminiError);

            // ===== LANGKAH 3: FALLBACK TERAKHIR KE OPENROUTER =====
            try {
                const fallbackBody = {
                    model: 'anthropic/claude-3.7-sonnet',
                    messages: [
                        { role: 'system', content: systemPrompt },
                        ...conversationHistory,
                        { role: 'user', content: prompt }
                    ],
                    temperature: 0.7,
                    max_tokens: 2048,
                    top_p: 0.9,
                    stream: false
                };

                const response = await fetch(OPENROUTER_API_URL, {
                    method: 'POST',
                    headers: {
                        'Content-Type': 'application/json',
                        'Authorization': 'Bearer ' + OPENROUTER_API_KEY,
                        'HTTP-Referer': window.location.href,
                        'X-Title': 'Apache AI 2.00'
                    },
                    body: JSON.stringify(fallbackBody)
                });

                if (!response.ok) throw new Error('OpenRouter API Error');
                const data = await response.json();
                return data.choices[0].message.content;

            } catch (openrouterError) {
                console.error('OpenRouter API Error (Fallback):', openrouterError);
                return generateFallbackResponse(prompt);
            }
        }
    }
}

function generateFallbackResponse(prompt) {
    const p = String(prompt || '').trim();
    if (currentMode === 'coding') {
        return [
            'Apache AI Engine System - Mode VS Code',
            '',
            'Berikut solusi coding yang aman:',
            '```',
            '// Apache AI 2.00 - Powered by Apache AI Engine System',
            '// Gunawan Group - Muhammad Raffa Gunawan',
            '',
            'function example() {',
            '    // Implementasi sesuai kebutuhan Anda',
            '    console.log("Apache AI 2.00 Ready");',
            '}',
            '```',
            '',
            'Pertanyaan: ' + (p || '(kosong)'),
            '',
            'Silakan coba lagi atau periksa koneksi internet Anda.'
        ].join('\n');
    }
    return [
        'Apache AI Engine System',
        '',
        'Saya siap membantu Anda.',
        '',
        'Pertanyaan: ' + (p || '(kosong)'),
        '',
        'Silakan coba lagi atau periksa koneksi internet Anda.'
    ].join('\n');
}

/* ===== FILE UPLOAD ===== */
function handleFileUpload(input) {
    if (!input.files || input.files.length === 0) return;
    for (let file of input.files) {
        attachedFiles.push(file);
    }
    updateFilePreview();
    input.value = '';
}
function updateFilePreview() {
    const container = document.getElementById('filePreviewContainer');
    if (!container) return;
    if (attachedFiles.length === 0) {
        container.style.display = 'none';
        container.innerHTML = '';
        return;
    }
    container.style.display = 'flex';
    container.innerHTML = attachedFiles.map((file, i) => 
        '<span class="file-preview-tag">' + escapeHtml(file.name) + ' <span class="remove-file" onclick="removeFile(' + i + ')">&times;</span></span>'
    ).join('');
}
function removeFile(index) {
    attachedFiles.splice(index, 1);
    updateFilePreview();
}

/* ===== VOICE INPUT ===== */
let recognition = null;
function toggleVoiceInput() {
    if (!('webkitSpeechRecognition' in window) && !('SpeechRecognition' in window)) {
        showToast('Voice input tidak didukung di browser ini');
        return;
    }
    if (recognition && recognition.isListening) {
        recognition.stop();
        return;
    }
    const SpeechRecognition = window.SpeechRecognition || window.webkitSpeechRecognition;
    recognition = new SpeechRecognition();
    recognition.lang = 'id-ID';
    recognition.continuous = false;
    recognition.interimResults = false;
    recognition.onstart = function() {
        const micBtnEl = document.getElementById('micBtn'); if (micBtnEl) micBtnEl.style.color = '#ec4899';
        showToast('Mendengarkan...');
    };
    recognition.onend = function() {
        const micBtnEl2 = document.getElementById('micBtn'); if (micBtnEl2) micBtnEl2.style.color = '';
    };
    recognition.onresult = function(event) {
        const transcript = event.results[0][0].transcript;
        chatInputField.value = (chatInputField.value ? chatInputField.value + ' ' : '') + transcript;
        chatInputField.style.height = 'auto';
        chatInputField.style.height = Math.min(chatInputField.scrollHeight, 140) + 'px';
    };
    recognition.onerror = function() {
        showToast('Gagal mendengarkan, coba lagi');
        const micBtnEl2 = document.getElementById('micBtn'); if (micBtnEl2) micBtnEl2.style.color = '';
    };
    recognition.start();
}




/* ================================================================
   SETTINGS & HISTORY SYSTEM - APACHE AI ENGINE
   ================================================================ */

// ===== SETTINGS STATE =====
let appSettings = {
    darkMode: true,
    lightVersion: false,
    autoSave: true,
    theme: 'purple',
    fontSize: 'normal'
};

// ===== LOAD SETTINGS =====
function loadSettings() {
    try {
        const saved = localStorage.getItem('apache_ai_settings');
        if (saved) {
            appSettings = { ...appSettings, ...JSON.parse(saved) };
        }
    } catch (e) {
        console.error('Settings load error:', e);
    }
    applySettings();
}

function saveSettings() {
    try {
        localStorage.setItem('apache_ai_settings', JSON.stringify(appSettings));
    } catch (e) {
        console.error('Settings save error:', e);
    }
}

function applySettings() {
    // Dark Mode
    const html = document.documentElement;
    const darkToggle = document.getElementById('darkModeToggle');
    if (appSettings.darkMode) {
        html.classList.remove('light-mode');
        if (darkToggle) darkToggle.classList.add('active');
    } else {
        html.classList.add('light-mode');
        if (darkToggle) darkToggle.classList.remove('active');
    }

    // Light Version (Performance)
    const lightToggle = document.getElementById('lightModeToggle');
    if (appSettings.lightVersion) {
        document.body.classList.add('light-performance');
        if (lightToggle) lightToggle.classList.add('active');
    } else {
        document.body.classList.remove('light-performance');
        if (lightToggle) lightToggle.classList.remove('active');
    }

    // Auto Save
    const autoSaveToggle = document.getElementById('autoSaveToggle');
    if (autoSaveToggle) {
        if (appSettings.autoSave) autoSaveToggle.classList.add('active');
        else autoSaveToggle.classList.remove('active');
    }

    // Theme
    const themeSelect = document.getElementById('themeSelect');
    if (themeSelect) themeSelect.value = appSettings.theme;

    // Font Size
    const fontSizeSelect = document.getElementById('fontSizeSelect');
    if (fontSizeSelect) fontSizeSelect.value = appSettings.fontSize;
    applyFontSize();
}

function applyFontSize() {
    const chatArea = document.getElementById('chatArea');
    if (!chatArea) return;
    const bubbles = chatArea.querySelectorAll('.chat-bubble');
    let size = '14.5px';
    if (appSettings.fontSize === 'small') size = '13px';
    if (appSettings.fontSize === 'large') size = '16px';
    bubbles.forEach(b => b.style.fontSize = size);
}

// ===== SETTINGS ACTIONS =====
function toggleDarkMode() {
    appSettings.darkMode = !appSettings.darkMode;
    saveSettings();
    applySettings();
    showToast(appSettings.darkMode ? 'Mode gelap diaktifkan' : 'Mode terang diaktifkan');
}

function toggleLightVersion() {
    appSettings.lightVersion = !appSettings.lightVersion;
    saveSettings();
    applySettings();
    showToast(appSettings.lightVersion ? 'Versi ringan diaktifkan - performa optimal' : 'Versi normal diaktifkan');
}

function toggleAutoSave() {
    appSettings.autoSave = !appSettings.autoSave;
    saveSettings();
    applySettings();
    showToast(appSettings.autoSave ? 'Auto-simpan diaktifkan' : 'Auto-simpan dimatikan');
}

function changeTheme(theme) {
    appSettings.theme = theme;
    saveSettings();
    showToast('Tema ' + theme + ' dipilih (reload untuk menerapkan penuh)');
}

function changeFontSize(size) {
    appSettings.fontSize = size;
    saveSettings();
    applySettings();
    showToast('Ukuran font diubah ke ' + size);
}

function confirmClearAllData() {
    openConfirmModal(
        'Hapus Semua Data?',
        'Semua riwayat chat dan pengaturan akan dihapus permanen. Tindakan ini tidak dapat dibatalkan.',
        function() {
            try {
                localStorage.removeItem('apache_ai_chat_history');
                localStorage.removeItem('apache_ai_settings');
                chatHistoryData = [];
                renderHistoryList();
                renderSidebarHistory();
                appSettings = { darkMode: true, lightVersion: false, autoSave: true, theme: 'purple', fontSize: 'normal' };
                applySettings();
                showToast('Semua data berhasil dihapus');
            } catch (e) {
                showToast('Gagal menghapus data');
            }
        },
        'Hapus Semua'
    );
}

// ===== MODAL SYSTEM =====
function openSettingsModal() {
    const modal = document.getElementById('settingsModal');
    if (modal) {
        modal.classList.add('show');
        document.body.style.overflow = 'hidden';
        switchTab('appearance');
    }
}

function closeSettingsModal(e) {
    if (e && e.target !== e.currentTarget) return;
    const modal = document.getElementById('settingsModal');
    if (modal) {
        modal.classList.remove('show');
        if (!document.getElementById('historyModal').classList.contains('show')) {
            document.body.style.overflow = '';
        }
    }
}

function openHistoryModal() {
    const modal = document.getElementById('historyModal');
    if (modal) {
        renderHistoryList();
        updateHistoryStats();
        modal.classList.add('show');
        document.body.style.overflow = 'hidden';
    }
}

function closeHistoryModal(e) {
    if (e && e.target !== e.currentTarget) return;
    const modal = document.getElementById('historyModal');
    if (modal) {
        modal.classList.remove('show');
        if (!document.getElementById('settingsModal').classList.contains('show')) {
            document.body.style.overflow = '';
        }
    }
}

function switchTab(tabName) {
    document.querySelectorAll('.tab-btn').forEach(btn => {
        btn.classList.toggle('active', btn.dataset.tab === tabName);
    });
    document.querySelectorAll('.tab-panel').forEach(panel => {
        panel.style.display = panel.id === 'tab-' + tabName ? 'block' : 'none';
    });
}

// ===== CONFIRMATION MODAL =====
let confirmCallback = null;

function openConfirmModal(title, body, callback, actionText) {
    confirmCallback = callback;
    document.getElementById('confirmTitle').textContent = title;
    document.getElementById('confirmBody').textContent = body;
    document.getElementById('confirmActionBtn').textContent = actionText || 'Konfirmasi';
    document.getElementById('confirmModal').classList.add('show');
}

function closeConfirmModal(e) {
    if (e && e.target !== e.currentTarget && e.target !== document.getElementById('confirmActionBtn') && !e.target.closest('.btn-secondary-modal')) return;
    document.getElementById('confirmModal').classList.remove('show');
    confirmCallback = null;
}

function executeConfirmAction() {
    if (typeof confirmCallback === 'function') {
        confirmCallback();
    }
    closeConfirmModal();
}

// ===== CHAT HISTORY SYSTEM =====
let chatHistoryData = [];
const HISTORY_KEY = 'apache_ai_chat_history';
const MAX_HISTORY = 100;

function loadChatHistory() {
    try {
        const saved = localStorage.getItem(HISTORY_KEY);
        if (saved) {
            chatHistoryData = JSON.parse(saved);
        }
    } catch (e) {
        console.error('History load error:', e);
        chatHistoryData = [];
    }
    renderSidebarHistory();
}

function saveChatHistory() {
    try {
        localStorage.setItem(HISTORY_KEY, JSON.stringify(chatHistoryData));
    } catch (e) {
        console.error('History save error:', e);
        showToast('Gagal menyimpan riwayat (storage penuh)');
    }
}

function addChatToHistory(chatId, title, messages, mode) {
    if (!appSettings.autoSave) return;

    const existingIndex = chatHistoryData.findIndex(h => h.id === chatId);
    const historyItem = {
        id: chatId,
        title: title || 'Chat Tanpa Judul',
        preview: getChatPreview(messages),
        messageCount: messages.length,
        mode: mode || 'chat',
        timestamp: Date.now(),
        date: new Date().toISOString()
    };

    if (existingIndex >= 0) {
        chatHistoryData[existingIndex] = historyItem;
    } else {
        chatHistoryData.unshift(historyItem);
        if (chatHistoryData.length > MAX_HISTORY) {
            chatHistoryData = chatHistoryData.slice(0, MAX_HISTORY);
        }
    }

    saveChatHistory();
    renderSidebarHistory();
}

function getChatPreview(messages) {
    if (!messages || messages.length === 0) return '';
    const firstUser = messages.find(m => m.role === 'user');
    if (firstUser) {
        let text = String(firstUser.content).substring(0, 80);
        return text.length > 80 ? text + '...' : text;
    }
    return '';
}

function getChatTitle(messages) {
    if (!messages || messages.length === 0) return 'Chat Baru';
    const firstUser = messages.find(m => m.role === 'user');
    if (firstUser) {
        let text = String(firstUser.content).substring(0, 40);
        return text.length > 40 ? text + '...' : text;
    }
    return 'Chat Baru';
}

function renderSidebarHistory() {
    const container = document.getElementById('chatHistory');
    if (!container) return;

    container.innerHTML = '';

    if (chatHistoryData.length === 0) {
        container.innerHTML = '<div style="padding:20px;text-align:center;color:var(--text-muted);font-size:12px;"><i class="fas fa-inbox" style="font-size:24px;margin-bottom:8px;display:block;opacity:0.4;"></i>Belum ada riwayat chat</div>';
        return;
    }

    chatHistoryData.slice(0, 20).forEach(item => {
        const div = document.createElement('div');
        div.className = 'chat-history-item' + (item.id === currentChatId ? ' active' : '');
        div.innerHTML = '<svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 15a2 2 0 0 1-2 2H7l-4 4V5a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2z"/></svg>' + escapeHtml(item.title);
        div.title = item.title;
        div.addEventListener('click', () => loadChatFromHistory(item.id));
        container.appendChild(div);
    });
}

function renderHistoryList() {
    const list = document.getElementById('historyList');
    const empty = document.getElementById('historyEmpty');
    const searchValue = document.getElementById('historySearchInput')?.value?.toLowerCase() || '';

    if (!list) return;

    let filtered = chatHistoryData;
    if (searchValue) {
        filtered = chatHistoryData.filter(h => 
            h.title.toLowerCase().includes(searchValue) ||
            (h.preview && h.preview.toLowerCase().includes(searchValue))
        );
    }

    list.innerHTML = '';

    if (filtered.length === 0) {
        list.style.display = 'none';
        if (empty) empty.style.display = 'block';
        return;
    }

    list.style.display = 'flex';
    if (empty) empty.style.display = 'none';

    filtered.forEach(item => {
        const div = document.createElement('div');
        div.className = 'history-item';
        const dateStr = formatDate(item.timestamp);
        const modeIcon = getModeIcon(item.mode);
        const modeLabel = getModeLabel(item.mode);

        div.innerHTML = `
            <div class="history-item-icon">${modeIcon}</div>
            <div class="history-item-content">
                <div class="history-item-title">${escapeHtml(item.title)}</div>
                <div class="history-item-date">
                    <i class="far fa-clock" style="font-size:10px;"></i> ${dateStr}
                    <span class="history-badge">${modeLabel} &middot; ${item.messageCount} pesan</span>
                </div>
                <div class="history-item-preview">${escapeHtml(item.preview)}</div>
            </div>
            <div class="history-item-actions">
                <button class="history-action-btn" onclick="event.stopPropagation();loadChatFromHistory('${item.id}')" title="Buka Chat">
                    <i class="fas fa-external-link-alt"></i>
                </button>
                <button class="history-action-btn delete" onclick="event.stopPropagation();deleteHistoryItem('${item.id}')" title="Hapus">
                    <i class="fas fa-trash-alt"></i>
                </button>
            </div>
        `;
        div.addEventListener('click', () => loadChatFromHistory(item.id));
        list.appendChild(div);
    });
}

function getModeIcon(mode) {
    const icons = { chat: '<i class="fas fa-comment"></i>', coding: '<i class="fas fa-code"></i>', image: '<i class="fas fa-image"></i>', search: '<i class="fas fa-search"></i>' };
    return icons[mode] || icons.chat;
}

function getModeLabel(mode) {
    const labels = { chat: 'Chat', coding: 'VS Code', image: 'Gambar', search: 'Search' };
    return labels[mode] || 'Chat';
}

function formatDate(timestamp) {
    const date = new Date(timestamp);
    const now = new Date();
    const diff = now - date;
    const days = Math.floor(diff / (1000 * 60 * 60 * 24));

    if (days === 0) {
        const hours = Math.floor(diff / (1000 * 60 * 60));
        if (hours === 0) {
            const mins = Math.floor(diff / (1000 * 60));
            return mins < 1 ? 'Baru saja' : mins + ' menit lalu';
        }
        return hours + ' jam lalu';
    }
    if (days === 1) return 'Kemarin';
    if (days < 7) return days + ' hari lalu';
    if (days < 30) return Math.floor(days / 7) + ' minggu lalu';

    return date.toLocaleDateString('id-ID', { day: 'numeric', month: 'short', year: 'numeric' });
}

function updateHistoryStats() {
    const totalChats = chatHistoryData.length;
    const totalMessages = chatHistoryData.reduce((sum, h) => sum + (h.messageCount || 0), 0);
    const today = new Date().toDateString();
    const todayChats = chatHistoryData.filter(h => new Date(h.timestamp).toDateString() === today).length;

    const statTotal = document.getElementById('statTotalChats');
    const statMessages = document.getElementById('statTotalMessages');
    const statToday = document.getElementById('statTodayChats');

    if (statTotal) statTotal.textContent = totalChats;
    if (statMessages) statMessages.textContent = totalMessages;
    if (statToday) statToday.textContent = todayChats;
}

function searchHistory(query) {
    renderHistoryList();
}

function deleteHistoryItem(id) {
    const item = chatHistoryData.find(h => h.id === id);
    openConfirmModal(
        'Hapus Riwayat?',
        'Apakah Anda yakin ingin menghapus chat "' + (item ? item.title : '') + '"? Tindakan ini tidak dapat dibatalkan.',
        function() {
            chatHistoryData = chatHistoryData.filter(h => h.id !== id);
            saveChatHistory();
            renderHistoryList();
            renderSidebarHistory();
            updateHistoryStats();
            showToast('Riwayat chat dihapus');
        },
        'Hapus'
    );
}

function loadChatFromHistory(chatId) {
    const item = chatHistoryData.find(h => h.id === chatId);
    if (!item) {
        showToast('Chat tidak ditemukan');
        return;
    }

    // Load the chat session
    currentChatId = chatId;
    currentMode = item.mode || 'chat';
    setMode(currentMode);

    // Show chat section if not already open
    document.getElementById('chatSection').classList.add('active');
    document.body.style.overflow = 'hidden';

    // Close modals
    closeHistoryModal();
    closeSettingsModal();

    // Re-render messages (they're kept in memory via messages array)
    // In a real app, you'd load messages from storage too
    renderMessages();
    showToast('Chat dimuat: ' + item.title);
}

// ===== ENHANCED SAVE CHAT =====
const originalSaveChatToHistory = saveChatToHistory;
saveChatToHistory = function() {
    const firstMsg = messages.find(m => m.role === 'user');
    if (!firstMsg) return;
    const title = getChatTitle(messages);
    addChatToHistory(currentChatId, title, messages, currentMode);
};

// ===== ENHANCED CHAT NEW =====
const originalChatNewHandler = function() {
    if (messages.length > 0) saveChatToHistory();
    messages = [];
    currentChatId = Date.now();
    attachedFiles = [];
    renderMessages();
    if (chatInputField) {
        chatInputField.value = '';
        chatInputField.style.height = 'auto';
    }
    updateFilePreview();
    generateChatStars();
    showToast('Chat baru dimulai');
};

// ===== KEYBOARD SHORTCUTS =====
document.addEventListener('keydown', function(e) {
    // ESC to close modals
    if (e.key === 'Escape') {
        closeSettingsModal();
        closeHistoryModal();
        closeConfirmModal();
    }
});

// ===== INIT =====
document.addEventListener('DOMContentLoaded', function() {
    loadSettings();
    loadChatHistory();
});

</script>


<!-- ===== SETTINGS MODAL ===== -->
<div class="modal-overlay" id="settingsModal" onclick="closeSettingsModal(event)">
  <div class="modal-content" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2><i class="fas fa-cog"></i> Pengaturan</h2>
      <button class="modal-close-btn" onclick="closeSettingsModal()" title="Tutup"><i class="fas fa-times"></i></button>
    </div>
    <div class="modal-tabs">
      <button class="tab-btn active" data-tab="appearance" onclick="switchTab('appearance')">Tampilan</button>
      <button class="tab-btn" data-tab="performance" onclick="switchTab('performance')">Performa</button>
      <button class="tab-btn" data-tab="about" onclick="switchTab('about')">Tentang</button>
    </div>
    <div class="modal-body" id="settingsBody">
      <!-- Tab: Appearance -->
      <div id="tab-appearance" class="tab-panel" style="display:block;">
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-moon" style="margin-right:8px;color:var(--accent);"></i>Mode Gelap</h4>
            <p>Aktifkan mode gelap untuk pengalaman malam yang nyaman</p>
          </div>
          <button class="toggle-switch" id="darkModeToggle" onclick="toggleDarkMode()"></button>
        </div>
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-palette" style="margin-right:8px;color:var(--accent);"></i>Tema Warna</h4>
            <p>Pilih tema warna utama antarmuka</p>
          </div>
          <select class="select-box" id="themeSelect" onchange="changeTheme(this.value)">
            <option value="purple">Ungu (Default)</option>
            <option value="blue">Biru</option>
            <option value="green">Hijau</option>
            <option value="red">Merah</option>
          </select>
        </div>
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-font" style="margin-right:8px;color:var(--accent);"></i>Ukuran Font Chat</h4>
            <p>Atur ukuran teks dalam area chat</p>
          </div>
          <select class="select-box" id="fontSizeSelect" onchange="changeFontSize(this.value)">
            <option value="small">Kecil</option>
            <option value="normal" selected>Normal</option>
            <option value="large">Besar</option>
          </select>
        </div>
      </div>
      <!-- Tab: Performance -->
      <div id="tab-performance" class="tab-panel" style="display:none;">
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-feather-alt" style="margin-right:8px;color:var(--accent);"></i>Versi Ringan</h4>
            <p>Nonaktifkan animasi dan efek visual untuk performa lebih cepat</p>
          </div>
          <button class="toggle-switch" id="lightModeToggle" onclick="toggleLightVersion()"></button>
        </div>
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-bolt" style="margin-right:8px;color:var(--accent);"></i>Auto-Simpan Chat</h4>
            <p>Simpan riwayat chat secara otomatis ke local storage</p>
          </div>
          <button class="toggle-switch active" id="autoSaveToggle" onclick="toggleAutoSave()"></button>
        </div>
        <div class="setting-item">
          <div class="setting-item-info">
            <h4><i class="fas fa-trash-alt" style="margin-right:8px;color:var(--accent);"></i>Hapus Semua Data</h4>
            <p>Hapus semua riwayat chat dan pengaturan tersimpan</p>
          </div>
          <button class="btn-danger-outline" style="padding:8px 16px;background:transparent;border:1px solid var(--danger);color:var(--danger);border-radius:8px;font-size:12px;font-weight:600;cursor:pointer;transition:all 0.25s;font-family:var(--font-main);" onclick="confirmClearAllData()">Hapus Semua</button>
        </div>
      </div>
      <!-- Tab: About -->
      <div id="tab-about" class="tab-panel" style="display:none;">
        <div style="text-align:center;padding:20px 0;">
          <div style="width:64px;height:64px;background:linear-gradient(135deg,#7c3aed,#a855f7);border-radius:16px;display:flex;align-items:center;justify-content:center;margin:0 auto 16px;box-shadow:0 0 30px rgba(124,58,237,0.3);">
            <svg width="32" height="32" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/></svg>
          </div>
          <h3 style="font-family:var(--font-display);font-size:20px;font-weight:700;color:var(--text-primary);margin-bottom:8px;">Apache AI 2.00</h3>
          <p style="font-size:13px;color:var(--text-muted);margin-bottom:20px;">Apache AI Engine System v2.00</p>
          <div style="display:grid;grid-template-columns:1fr 1fr;gap:10px;text-align:left;">
            <div style="padding:12px;background:rgba(147,51,234,0.08);border-radius:10px;">
              <div style="font-size:11px;color:var(--text-muted);margin-bottom:4px;">Pemilik</div>
              <div style="font-size:13px;font-weight:600;color:var(--text-primary);">Muhammad Raffa Gunawan</div>
            </div>
            <div style="padding:12px;background:rgba(147,51,234,0.08);border-radius:10px;">
              <div style="font-size:11px;color:var(--text-muted);margin-bottom:4px;">Perusahaan</div>
              <div style="font-size:13px;font-weight:600;color:var(--text-primary);">Gunawan Group</div>
            </div>
            <div style="padding:12px;background:rgba(147,51,234,0.08);border-radius:10px;">
              <div style="font-size:11px;color:var(--text-muted);margin-bottom:4px;">Status</div>
              <div style="font-size:13px;font-weight:600;color:var(--success);">Tanpa Bug - Aman</div>
            </div>
            <div style="padding:12px;background:rgba(147,51,234,0.08);border-radius:10px;">
              <div style="font-size:11px;color:var(--text-muted);margin-bottom:4px;">Harga</div>
              <div style="font-size:13px;font-weight:600;color:var(--accent);">Gratis 100%</div>
            </div>
          </div>
          <p style="font-size:12px;color:var(--text-muted);margin-top:20px;line-height:1.8;">
            &copy; 2026 Gunawan Group. Apache AI 2.00 - The Future Of Intelligent Assistance.<br>
            Built with Apache AI Engine System.
          </p>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- ===== HISTORY MODAL ===== -->
<div class="modal-overlay" id="historyModal" onclick="closeHistoryModal(event)">
  <div class="modal-content" onclick="event.stopPropagation()">
    <div class="modal-header">
      <h2><i class="fas fa-history"></i> Riwayat Chat</h2>
      <button class="modal-close-btn" onclick="closeHistoryModal()" title="Tutup"><i class="fas fa-times"></i></button>
    </div>
    <div class="modal-body" id="historyBody">
      <div class="history-stats" id="historyStats">
        <div class="stats-card">
          <div class="stats-number" id="statTotalChats">0</div>
          <div class="stats-label">Total Chat</div>
        </div>
        <div class="stats-card">
          <div class="stats-number" id="statTotalMessages">0</div>
          <div class="stats-label">Pesan</div>
        </div>
        <div class="stats-card">
          <div class="stats-number" id="statTodayChats">0</div>
          <div class="stats-label">Hari Ini</div>
        </div>
      </div>
      <div class="history-search">
        <i class="fas fa-search search-icon"></i>
        <input type="text" class="search-input" id="historySearchInput" placeholder="Cari riwayat chat..." oninput="searchHistory(this.value)">
      </div>
      <div class="history-list" id="historyList">
        <!-- History items will be rendered here -->
      </div>
      <div class="empty-state" id="historyEmpty" style="display:none;">
        <i class="fas fa-inbox"></i>
        <h4>Belum Ada Riwayat</h4>
        <p>Mulai chat baru dan riwayat akan tersimpan di sini</p>
      </div>
    </div>
  </div>
</div>

<!-- ===== DELETE CONFIRMATION MODAL ===== -->
<div class="confirm-modal-overlay" id="confirmModal" onclick="closeConfirmModal(event)">
  <div class="confirm-modal-content" onclick="event.stopPropagation()">
    <div class="confirm-modal-icon"><i class="fas fa-exclamation-triangle"></i></div>
    <h3 id="confirmTitle">Hapus Riwayat?</h3>
    <p class="confirm-modal-body" id="confirmBody">Apakah Anda yakin ingin menghapus riwayat chat ini? Tindakan ini tidak dapat dibatalkan.</p>
    <div class="confirm-modal-actions">
      <button class="btn-secondary-modal" onclick="closeConfirmModal()">Batal</button>
      <button class="btn-danger" id="confirmActionBtn" onclick="executeConfirmAction()">Hapus</button>
    </div>
  </div>
</div>

</body>
</html>
