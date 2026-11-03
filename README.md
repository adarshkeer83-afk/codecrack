<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
<!-- This site is hosted on Netlify. Anyone can build and deploy a site
     like this one for free: https://netlify.new/?utm_campaign=loops&utm_source=ai-legible&utm_medium=owned&utm_content=comment&utm_id=4861bbfd-0bfa-4e52-9af4-fa61e37332bd
     Netlify hosting facts for this site: static/SSR served via Netlify Edge. -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CosmoFest 2026 | SATI College Festival</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Barlow+Condensed:wght@600;700;800;900&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        orbitron: ['Barlow Condensed', 'sans-serif'],
                        sans: ['DM Sans', 'sans-serif'],
                    },
                    colors: {
                        space: {
                            900: '#171916',
                            800: '#1e211c',
                            700: '#292d25',
                            600: '#414639',
                        },
                        neon: {
                            cyan: '#f5a45d',
                            purple: '#f5a45d',
                            pink: '#c4d99a',
                            blue: '#f5a45d'
                        }
                    },
                    boxShadow: {
                        'glow-cyan': '0 0 20px rgba(0, 240, 255, 0.35)',
                        'glow-purple': '0 0 20px rgba(112, 0, 255, 0.35)',
                        'glow-pink': '0 0 20px rgba(255, 0, 127, 0.35)',
                    }
                }
            }
        }
    </script>
    <style>
        :root {color-scheme:dark;--accent:#f5a45d;--ink:#171916;--muted:#a5aa9d}
        body{background:var(--ink);color:#f1f0e6;font-family:'DM Sans',sans-serif}
        .font-orbitron{font-family:'Barlow Condensed',sans-serif}
        .glass-nav{background:rgba(23,25,22,.94);border-bottom:1px solid #363a31;backdrop-filter:blur(18px)}
        .glass-nav>div{min-height:86px}.glass-nav a{transition:color .2s}.glass-nav nav a:hover{color:var(--accent)}
        .brand{font-size:27px;letter-spacing:-.5px;text-transform:uppercase}.brand-mark{display:inline-block;color:var(--accent);margin-right:8px;font-size:32px}
        .nav-register{background:var(--accent);color:var(--ink);padding:11px 22px;border-radius:5px;font-weight:700}
        .glass-card{background:#20231e;border:1px solid #383d32;box-shadow:none}
        .max-w-7xl{max-width:1240px}
        .text-gray-300{color:#c3c6bb}.text-gray-400{color:#a5aa9d}
        [class*="shadow-glow"]{box-shadow:none}
        [class*="text-blue-300"]{color:#c4d99a}[class*="bg-blue-500/20"]{background:#c4d99a15}
        section{scroll-margin-top:85px}
        #home{padding:62px 0 0;background:radial-gradient(ellipse at 80% 35%,#39402b45,transparent 53%)}
        .hero-grid{display:grid;grid-template-columns:1.15fr 1fr;gap:25px;align-items:center;min-height:510px}
        .eyebrow{display:flex;align-items:center;gap:10px;font-size:10px;letter-spacing:2px;text-transform:uppercase;font-weight:700;color:#c4d99a}
        .eyebrow:before{content:'';width:7px;height:7px;border-radius:50%;background:#c4d99a}
        #home h1{font-size:clamp(74px,8.2vw,116px);line-height:.87;letter-spacing:-2px;font-weight:800;text-transform:uppercase;margin:27px 0 24px}
        #home h1 em{font-style:normal;color:var(--accent)}
        .hero-copy{max-width:405px;font-size:14px;line-height:1.85;color:#b7bcae}
        .hero-actions{display:flex;gap:14px;margin-top:29px;align-items:center}.primary-cta{background:var(--accent);color:var(--ink);padding:16px 24px;border-radius:5px;font-size:12px;font-weight:700;display:inline-flex;gap:25px;align-items:center;transition:transform .2s,background .2s}.primary-cta:hover{transform:translateY(-3px);background:#ffba7a}.secondary-cta{font-size:12px;padding:15px;color:#e6e8dd}.secondary-cta i{margin-left:12px}
        .hero-art{position:relative;aspect-ratio:1;display:grid;place-items:center;isolation:isolate}.hero-art svg{width:100%;height:auto;overflow:visible;animation:arrive 1s ease-out both}.art-label{position:absolute;font-size:10px;letter-spacing:2px;text-transform:uppercase;color:#b8beab}.label-top{top:8%;left:5%}.label-bottom{bottom:9%;right:0}.art-sticker{position:absolute;right:0;top:25%;background:#c4d99a;color:var(--ink);width:85px;height:85px;display:grid;place-content:center;text-align:center;border-radius:50%;transform:rotate(13deg);font-size:10px;font-weight:700;line-height:1.5;box-shadow:0 0 0 6px #171916}.art-sticker strong{font-family:'Barlow Condensed';font-size:25px}
        .hero-meta{display:grid;grid-template-columns:1fr 1fr 1fr auto;gap:25px;border-top:1px solid #3b4034;padding:27px 0;margin-top:32px}.hero-meta small{display:block;font-size:9px;color:#939b87;letter-spacing:1.8px;margin-bottom:6px}.hero-meta strong{font-size:12px;font-weight:500}.hero-meta i{color:var(--accent);margin-right:8px}.edition{font-family:'Barlow Condensed';font-size:35px;line-height:1;color:#c4d99a;align-self:center}
        .festival-strip{background:#c4d99a;color:#20261c;overflow:hidden;padding:13px 0;display:flex;justify-content:space-around;gap:28px;white-space:nowrap;font-family:'Barlow Condensed';font-weight:700;font-size:19px;letter-spacing:2px}.festival-strip span{color:#536344}
        #events,#register{background:#1b1e19}#events,#schedule,#register{padding-top:85px;padding-bottom:85px}h3.font-orbitron{font-size:54px;line-height:1;text-transform:uppercase}h2.font-orbitron{font-family:'DM Sans';font-size:10px;letter-spacing:2px}
        #events .glass-card.p-4{border-radius:8px;padding:15px;background:transparent;margin-bottom:28px}.filter-cat-btn,.filter-day-btn{font-family:'DM Sans';border-radius:4px;font-size:11px}.filter-cat-btn:focus-visible,.filter-day-btn:focus-visible{outline:2px solid var(--accent)}
        #events-grid{grid-template-columns:repeat(4,minmax(0,1fr));gap:16px}#events-grid>.glass-card{padding:20px;border-radius:8px;position:relative;overflow:hidden;transition:transform .25s,border-color .25s}#events-grid>.glass-card:hover{transform:translateY(-5px);border-color:#8b9577}#events-grid h4{font-size:25px;line-height:1.1}#events-grid p{font-size:11px;line-height:1.8}#events-grid .event-top{align-items:flex-start;gap:8px;flex-wrap:wrap}#events-grid .event-top>span{font-size:9px}#events-grid .event-title{display:block}#events-grid .event-title>div{width:100%;height:110px;border:0;border-radius:5px;margin-bottom:21px;background:repeating-linear-gradient(0deg,transparent,transparent 15px,#65725116 16px),repeating-linear-gradient(90deg,transparent,transparent 15px,#65725116 16px),#292f23;color:#c4d99a}#events-grid .event-title i{font-size:43px;transform:rotate(-8deg)}#events-grid>div:nth-child(3n+1) .event-title>div{background-color:#3a2b22;color:#f5a45d}#events-grid>div:nth-child(3n) .event-title>div{background-color:#303126;color:#e0d7a1}#events-grid .border-t{gap:8px}#events-grid .border-t>span{font-size:9px}#events-grid .border-t>a{font-size:11px;font-family:'DM Sans';background:transparent;padding:5px 0;color:var(--accent)}
        #schedule>.max-w-7xl>.text-center{text-align:left;margin-left:0}#schedule-timeline{display:grid;grid-template-columns:1fr 1fr;gap:16px;max-width:none}#schedule-timeline:before{display:none}#schedule-timeline>div{margin:0;display:block}#schedule-timeline>div>div:first-child{width:100%;padding:0;margin:0;text-align:left}#schedule-timeline>div>div:last-child{display:none}#schedule-timeline .glass-card{border-radius:8px;height:100%}#schedule-timeline .glass-card>span{border:0;background:transparent;padding:0;color:var(--accent)}
        #register .max-w-4xl{max-width:900px}#register .glass-card{border-radius:12px;padding:48px}#register input,#register select,#register textarea{background:#171916;color:#f1f0e6;border-color:#424939;border-radius:5px}#register label{font-family:'DM Sans';font-size:11px}#register button[type=submit]{background:var(--accent);color:var(--ink);font-family:'DM Sans';font-size:12px;border-radius:5px}#register .text-center>span{background:transparent;border:0;letter-spacing:2px;color:#c4d99a;padding:0;font-size:10px}
        #confirmation-modal{background:#10140ed9}#confirmation-modal>.glass-card{border-radius:12px}footer{padding:35px 0}button,a,input,select,textarea{touch-action:manipulation}:focus-visible{outline:2px solid var(--accent);outline-offset:4px}
        @keyframes arrive{from{opacity:0;transform:translateY(18px) rotate(-8deg)}to{opacity:1;transform:translateY(0) rotate(0)}}
        @media(min-width:900px){.hero-text{animation:arrive .8s ease-out both}}
        @media(max-width:1000px){#events-grid{grid-template-columns:repeat(2,minmax(0,1fr))}.hero-grid{grid-template-columns:1.1fr 1fr}.art-sticker{width:68px;height:68px}#home h1{font-size:82px}}
        @media(max-width:640px){.glass-nav>div{min-height:70px;padding-top:12px;padding-bottom:12px}.hero-grid{grid-template-columns:1fr;gap:5px}#home{padding-top:40px}#home h1{font-size:82px}.hero-art{max-width:360px;width:100%;margin:0 auto}.hero-meta{grid-template-columns:1fr 1fr;gap:22px;margin-top:0}.edition{font-size:30px}.festival-strip{justify-content:flex-start;padding-left:20px;font-size:16px}#events,#schedule,#register{padding-top:54px;padding-bottom:54px}h3.font-orbitron{font-size:42px}#events-grid{grid-template-columns:1fr}#events-grid .event-title>div{height:135px}#events-grid h4{font-size:29px}#schedule-timeline{grid-template-columns:1fr}#register .glass-card{padding:25px 20px}.hero-actions{gap:4px}.primary-cta{padding:15px 20px}}
        @media(prefers-reduced-motion:reduce){*,*:before,*:after{animation:none!important;transition:none!important;scroll-behavior:auto!important}}
        .theme-toggle{border:1px solid #59604e;border-radius:5px;padding:8px 11px;font-size:12px;white-space:nowrap}.nav-tools{display:flex;align-items:center;gap:14px}
        .explorer{display:grid;grid-template-columns:1.3fr 1fr;gap:28px;margin-bottom:28px;padding:25px;border:1px solid #414639;border-radius:9px;background:#20231e}.explorer label{display:block;font-size:11px;font-weight:700;margin-bottom:10px}.search-box{display:flex;align-items:center;gap:12px;border:1px solid #59604e;padding:12px;border-radius:5px;background:#171916}.search-box i{color:var(--accent)}.search-box input{background:transparent;min-width:0;width:100%;font-size:13px;outline:none}.search-box:focus-within{outline:2px solid var(--accent);outline-offset:2px}.search-box input:focus-visible{outline:none}.explorer-note{font-size:10px;color:#a5aa9d;margin-top:10px}.dashboard-title{font-size:11px;font-weight:700;margin-bottom:13px}.dashboard-stats{display:flex;gap:30px}.dashboard-stats strong{display:block;font-family:'Barlow Condensed';font-size:36px;line-height:1;color:var(--accent)}.dashboard-stats span{font-size:10px;color:#b7bcae}.results-toolbar{display:flex;align-items:center;justify-content:space-between;gap:15px;margin-bottom:20px;flex-wrap:wrap}.results-toolbar p{font-size:12px;color:#b7bcae}.export-actions{display:flex;gap:9px;flex-wrap:wrap}.export-actions button{border:1px solid #59604e;border-radius:5px;padding:9px 13px;font-size:11px}.export-actions button:hover{border-color:var(--accent);color:var(--accent)}.export-actions button:disabled{opacity:.4;cursor:not-allowed}.event-enter{animation:arrive .35s ease-out both}
        html[data-theme=light]{color-scheme:light;--ink:#f5f3e9;--accent:#99501d}html[data-theme=light] body{background:#f5f3e9;color:#272e22}html[data-theme=light] .glass-nav{background:#f5f3e9f2;border-color:#cccdbd}html[data-theme=light] .glass-card,html[data-theme=light] .explorer{background:#fffdf5;border-color:#cccdbd}html[data-theme=light] #events,html[data-theme=light] #register{background:#eaece0}html[data-theme=light] #home{background:radial-gradient(ellipse at 80% 35%,#c4d99a60,transparent 53%)}html[data-theme=light] .text-white,html[data-theme=light] .text-gray-200,html[data-theme=light] .text-gray-300,html[data-theme=light] .text-gray-400,html[data-theme=light] .hero-copy,html[data-theme=light] .secondary-cta,html[data-theme=light] .results-toolbar p,html[data-theme=light] .dashboard-stats span,html[data-theme=light] .explorer-note{color:#515a46}html[data-theme=light] .text-neon-cyan,html[data-theme=light] .text-neon-purple,html[data-theme=light] .text-neon-pink,html[data-theme=light] .brand-mark,html[data-theme=light] .eyebrow,html[data-theme=light] .edition{color:#765121}html[data-theme=light] [class*="bg-space-900"],html[data-theme=light] .search-box,html[data-theme=light] #register input,html[data-theme=light] #register textarea,html[data-theme=light] #register select{background:#f5f3e9;color:#272e22}html[data-theme=light] [class*="bg-space-700"]{background:#dfe4d2;color:#35422b}html[data-theme=light] .filter-cat-btn[aria-pressed=true],html[data-theme=light] .filter-day-btn[aria-pressed=true]{background:#99501d;color:#fffdf5}html[data-theme=light] .nav-register,html[data-theme=light] .primary-cta,html[data-theme=light] #register button[type=submit]{background:#99501d;color:#fffdf5}html[data-theme=light] .hero-meta small,html[data-theme=light] .art-label{color:#566247}html[data-theme=light] .hero-meta{border-color:#bec5af}html[data-theme=light] .art-sticker{box-shadow:0 0 0 6px #f5f3e9;color:#272e22}html[data-theme=light] #events-grid .event-title>div{color:#d8e9b6}html[data-theme=light] #events-grid .border-t>a{color:#8a4518}html[data-theme=light] #register .text-center>span{color:#526b32}
        @media(max-width:640px){.explorer{grid-template-columns:1fr;padding:19px;gap:23px}.dashboard-stats{justify-content:space-between;gap:15px}.theme-toggle{font-size:11px;padding:7px}.nav-tools{gap:8px}.glass-nav>div{gap:8px}.brand{font-size:23px}.brand-mark{margin-right:3px}}
    </style>
</head>
<body class="font-sans antialiased min-h-screen flex flex-col selection:bg-neon-cyan selection:text-space-900">

    <!-- HEADER / NAVIGATION -->
    <header class="sticky top-0 z-50 glass-nav">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex items-center justify-between gap-6 py-5">
            <a href="#home" class="font-orbitron font-bold brand"><span class="brand-mark" aria-hidden="true">✳</span>CosmoFest <span class="text-neon-cyan">’26</span></a>
            <nav aria-label="Main navigation" class="hidden md:flex gap-6 text-sm">
                <a href="#home">Home</a><a href="#events">Events</a><a href="#schedule">Schedule</a><a href="#register" class="nav-register">Get your pass ↗</a>
            </nav>
            <div class="nav-tools"><button id="theme-toggle" class="theme-toggle" type="button" aria-pressed="false" onclick="toggleTheme()"><i class="fa-regular fa-sun" aria-hidden="true"></i> <span id="theme-label">Light mode</span></button>
            <button id="mobile-menu-btn" type="button" class="md:hidden p-2" aria-label="Toggle navigation" aria-expanded="false" aria-controls="mobile-menu"><i class="fa-solid fa-bars" aria-hidden="true"></i></button></div>
        </div>
        <nav id="mobile-menu" aria-label="Mobile navigation" class="hidden md:hidden px-4 pb-4 space-y-3">
            <a href="#home" class="mobile-nav-link block">Home</a><a href="#events" class="mobile-nav-link block">Events</a><a href="#schedule" class="mobile-nav-link block">Schedule</a><a href="#register" class="mobile-nav-link block">Register</a>
        </nav>
    </header>

    <!-- HERO SECTION -->
    <section id="home" class="relative overflow-hidden">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="hero-grid">
          <div class="hero-text">
            <div class="eyebrow">SATI's technical & cultural festival</div>
            <h1>Less ordinary.<br>More <em>cosmic.</em></h1>
            <p class="hero-copy">Two days. One campus. Endless possibilities. Code something wild, take the stage, and make memories that outlive the fest.</p>
            <div class="hero-actions"><a href="#events" class="primary-cta">Find your event <i class="fa-solid fa-arrow-up-right-from-square" aria-hidden="true"></i></a><a href="#schedule" class="secondary-cta">The line-up <i class="fa-solid fa-arrow-right" aria-hidden="true"></i></a></div>
          </div>
          <div class="hero-art" role="img" aria-label="Sculptural orange planet with tilted orbital rings">
            <span class="art-label label-top">A little out of this world.</span>
            <svg viewBox="0 0 500 500" aria-hidden="true">
              <defs><radialGradient id="planet" cx="32%" cy="26%" r="78%"><stop stop-color="#ffd9a0"/><stop offset=".38" stop-color="#f4a35d"/><stop offset=".73" stop-color="#b95329"/><stop offset="1" stop-color="#44271d"/></radialGradient><linearGradient id="orbit"><stop stop-color="#c4d99a"/><stop offset=".5" stop-color="#77885d"/><stop offset="1" stop-color="#d9e9ba"/></linearGradient><pattern id="lines" width="7" height="7" patternUnits="userSpaceOnUse"><path d="M0 0h7" stroke="#3e241c" stroke-opacity=".15"/></pattern><clipPath id="sphere"><circle cx="250" cy="250" r="125"/></clipPath></defs>
              <circle cx="250" cy="250" r="208" fill="none" stroke="#7a8660" stroke-opacity=".15" stroke-dasharray="3 8"/>
              <path d="M45 250h410M250 45v410" stroke="#7a8660" stroke-opacity=".16"/>
              <g transform="rotate(-32 250 250)"><ellipse cx="250" cy="250" rx="222" ry="76" fill="none" stroke="#80935f" stroke-width="1"/><ellipse cx="250" cy="250" rx="200" ry="63" fill="none" stroke="url(#orbit)" stroke-width="16"/></g>
              <circle cx="250" cy="250" r="125" fill="url(#planet)"/>
              <g clip-path="url(#sphere)"><path d="M100 173q145 110 300 0M100 200q145 110 300 0M100 227q145 110 300 0M100 254q145 110 300 0M100 281q145 110 300 0M100 308q145 110 300 0" fill="none" stroke="#6b361f" stroke-opacity=".2" stroke-width="2"/><circle cx="250" cy="250" r="125" fill="url(#lines)"/></g>
              <g transform="rotate(-32 250 250)"><path d="M50 250a200 63 0 0 0 400 0" fill="none" stroke="url(#orbit)" stroke-width="16"/><path d="M28 250a222 76 0 0 0 444 0" fill="none" stroke="#a5bc7d" stroke-width="1"/></g>
              <g fill="#c4d99a"><path d="M102 91l3 12 12 3-12 3-3 12-3-12-12-3 12-3z"/><path d="M387 368l2 9 9 2-9 2-2 9-2-9-9-2 9-2z"/><circle cx="90" cy="352" r="4"/><circle cx="350" cy="77" r="2"/></g>
            </svg>
            <div class="art-sticker">MAKE SOME<strong>NOISE.</strong>15—16 APR</div>
            <span class="art-label label-bottom">CosmoFest / Edition 2026</span>
          </div>
        </div>
        <div class="hero-meta"><div><small>MARK YOUR CALENDAR</small><strong><i class="fa-regular fa-calendar" aria-hidden="true"></i>15 & 16 April 2026</strong></div><div><small>MEET US HERE</small><strong><i class="fa-solid fa-location-dot" aria-hidden="true"></i>SATI Main Campus</strong></div><div><small>FIND YOUR PEOPLE</small><strong>Tech. Culture. Everything between.</strong></div><div class="edition">CF / 26 ↗</div></div>
      </div>
    </section>
    <div class="festival-strip" aria-hidden="true">CREATE. <span>✳</span> COMPETE. <span>✳</span> CONNECT. <span>✳</span> CELEBRATE. <span>✳</span> COSMOFEST 2026. <span>✳</span></div>

    <!-- EVENTS SECTION WITH DYNAMIC FILTERS -->
    <section id="events" class="py-16 bg-space-800/40 relative border-t border-space-700/60">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <!-- Section Title -->
            <div class="flex flex-col md:flex-row md:items-end justify-between mb-10 gap-6">
                <div>
                    <h2 class="text-xs font-orbitron font-bold text-neon-cyan uppercase tracking-widest mb-2">What’s on</h2>
                    <h3 class="text-3xl sm:text-4xl font-orbitron font-extrabold text-white">Find your kind of chaos.</h3>
                </div>
                <p class="text-gray-400 text-sm max-w-md">From your first line of code to your last encore. Pick your arena.</p>
            </div>

            <div class="explorer">
                <div><label for="event-search">YOUR FEST, YOUR WAY</label><div class="search-box"><i class="fa-solid fa-magnifying-glass" aria-hidden="true"></i><input id="event-search" type="search" placeholder="Try coding, dance, Lab 2…" autocomplete="off" aria-controls="events-grid" oninput="renderEvents()"></div><p class="explorer-note">Search by event, topic, category or venue. Combine with filters below.</p></div>
                <div><h4 class="dashboard-title">YOUR EVENT EXPLORER</h4><div class="dashboard-stats"><div><strong id="stat-events">8</strong><span>Matching events</span></div><div><strong id="stat-categories">3</strong><span>Categories</span></div><div><strong id="stat-days">2</strong><span>Festival days</span></div></div></div>
            </div>
            <!-- Filters Bar -->
            <div class="glass-card p-4 rounded-2xl mb-10 flex flex-wrap items-center justify-between gap-4 border border-space-600">
                <!-- Category Filter -->
                <div class="flex items-center gap-2 flex-wrap">
                    <span class="text-xs font-semibold text-gray-400 uppercase tracking-wider mr-2"><i class="fa-solid fa-filter text-neon-cyan mr-1"></i> Category:</span>
                    <button onclick="setCategoryFilter('all')" id="cat-all" class="filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-neon-cyan text-space-900 shadow-glow-cyan">
                        All
                    </button>
                    <button onclick="setCategoryFilter('Code Crack')" id="cat-codecrack" class="filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600">
                        Code Crack
                    </button>
                    <button onclick="setCategoryFilter('Technical')" id="cat-technical" class="filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600">
                        Technical
                    </button>
                    <button onclick="setCategoryFilter('Cultural')" id="cat-cultural" class="filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600">
                        Cultural
                    </button>
                </div>

                <!-- Day Filter -->
                <div class="flex items-center gap-2 flex-wrap">
                    <span class="text-xs font-semibold text-gray-400 uppercase tracking-wider mr-2"><i class="fa-solid fa-calendar-day text-neon-purple mr-1"></i> Date:</span>
                    <button onclick="setDayFilter('all')" id="day-all" class="filter-day-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-neon-purple text-white shadow-glow-purple">
                        All Days
                    </button>
                    <button onclick="setDayFilter('15 Apr')" id="day-15" class="filter-day-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600">
                        15 Apr (Day 1)
                    </button>
                    <button onclick="setDayFilter('16 Apr')" id="day-16" class="filter-day-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600">
                        16 Apr (Day 2)
                    </button>
                </div>
            </div>

            <div class="results-toolbar"><p id="results-count" role="status" aria-live="polite" aria-atomic="true"></p><div class="export-actions"><button id="export-csv" type="button" onclick="downloadSchedule('csv')"><i class="fa-solid fa-download" aria-hidden="true"></i> Download CSV</button><button id="export-calendar" type="button" onclick="downloadSchedule('ics')"><i class="fa-regular fa-calendar-plus" aria-hidden="true"></i> Add results to calendar</button></div></div>
            <p class="explorer-note mb-5">Downloads include only matching events. Calendar times use India Standard Time (IST).</p>
            <!-- Event Cards Grid -->
            <div id="events-grid" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Javascript will dynamically inject event cards here -->
            </div>

            <!-- Empty State Fallback -->
            <div id="no-events-msg" class="hidden text-center py-16 glass-card rounded-2xl">
                <i class="fa-solid fa-ghost text-4xl text-gray-500 mb-3"></i>
                <h4 class="text-lg font-orbitron font-bold text-gray-300">No Events Found</h4>
                <p class="text-sm text-gray-400 mt-1">Try resetting your filter criteria.</p>
                <button onclick="resetFilters()" class="mt-4 px-4 py-2 rounded-xl bg-space-700 text-neon-cyan text-xs font-bold font-orbitron border border-neon-cyan/40">Reset Filters</button>
            </div>
        </div>
    </section>

    <!-- SCHEDULE SECTION WITH ANALYTICAL READABILITY SOLUTION -->
    <section id="schedule" class="py-16 relative">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="text-center max-w-3xl mx-auto mb-12">
                <h2 class="text-xs font-orbitron font-bold text-neon-pink uppercase tracking-widest mb-2">15 & 16 April</h2>
                <h3 class="text-3xl sm:text-4xl font-orbitron font-extrabold text-white">Two days. All in.</h3>
                <p class="text-gray-400 text-sm mt-3">Explore the chronological timeline for Day 1 & Day 2 of CosmoFest 2026.</p>
            </div>

            <p class="text-sm text-gray-400 mb-6 text-center">Some events run at the same time. Check the venue before heading over.</p>
            <!-- Timeline Render Container -->
            <div id="schedule-timeline" class="space-y-8 relative before:absolute before:inset-0 before:left-4 sm:before:left-1/2 before:-ml-px before:w-0.5 before:bg-space-700">
                <!-- Javascript populates schedule cards here -->
            </div>

        </div>
    </section>

    <!-- Register for an event FORM SECTION -->
    <section id="register" class="py-16 bg-space-800/40 relative border-t border-space-700/60">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            
            <div class="glass-card p-6 sm:p-10 rounded-3xl border border-neon-cyan/20 shadow-glow-purple relative overflow-hidden">
                <div class="text-center mb-8">
                    <span class="px-3 py-1 rounded-full bg-neon-cyan/10 border border-neon-cyan/30 text-neon-cyan text-xs font-mono font-semibold uppercase">Get Your Entry Pass</span>
                    <h3 class="text-2xl sm:text-3xl font-orbitron font-extrabold text-white mt-3">Register for an event</h3>
                    <p class="text-gray-400 text-xs sm:text-sm mt-1">Choose your event and preview your pass. This form is currently a demo.</p>
                </div>

                <form id="registration-form" onsubmit="handleRegistration(event)" class="space-y-5" novalidate>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                        <div>
                            <label for="fullName" class="block text-sm mb-2">Full name *</label>
                            <input id="fullName" name="fullName" autocomplete="name" class="w-full p-3 rounded border border-space-600" placeholder="Your full name">
                            <span id="err-fullName" class="text-neon-pink text-xs mt-1 block hidden">Please enter your full name.</span>
                        </div>
                        <div>
                            <label for="email" class="block text-sm mb-2">Email address *</label>
                            <input type="email" id="email" name="email" autocomplete="email" class="w-full p-3 rounded border border-space-600" placeholder="you@example.com">
                            <span id="err-email" class="text-neon-pink text-xs mt-1 block hidden">Enter a valid email address.</span>
                        </div>
                    </div>

                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-5">
                        <!-- Phone Number -->
                        <div>
                            <label for="phone" class="block text-xs font-orbitron font-semibold text-gray-300 uppercase mb-2">Phone Number *</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3.5 flex items-center text-gray-500"><i class="fa-solid fa-phone"></i></span>
                                <input type="tel" id="phone" name="phone" placeholder="+91 98765 43210" 
                                    class="w-full pl-10 pr-4 py-3 rounded-xl bg-space-900/80 border border-space-600 text-white text-sm focus:outline-none focus:border-neon-cyan focus:ring-1 focus:ring-neon-cyan transition-all">
                            </div>
                            <span id="err-phone" class="text-neon-pink text-xs mt-1 block hidden">Please enter a valid phone number.</span>
                        </div>

                        <!-- Event Select -->
                        <div>
                            <label for="selectedEvent" class="block text-xs font-orbitron font-semibold text-gray-300 uppercase mb-2">Select Event *</label>
                            <div class="relative">
                                <span class="absolute inset-y-0 left-0 pl-3.5 flex items-center text-gray-500"><i class="fa-solid fa-gamepad"></i></span>
                                <select id="selectedEvent" name="selectedEvent" 
                                    class="w-full pl-10 pr-4 py-3 rounded-xl bg-space-900 border border-space-600 text-white text-sm focus:outline-none focus:border-neon-cyan focus:ring-1 focus:ring-neon-cyan transition-all">
                                    <option value="">-- Choose an Event --</option>
                                    <!-- Options populated dynamically by JS -->
                                </select>
                            </div>
                            <span id="err-selectedEvent" class="text-neon-pink text-xs mt-1 block hidden">Please select an event.</span>
                        </div>
                    </div>

                    <!-- Message / Query -->
                    <div>
                        <label for="message" class="block text-xs font-orbitron font-semibold text-gray-300 uppercase mb-2">Special Requests / Queries (Optional)</label>
                        <textarea id="message" rows="3" placeholder="Mention team details or queries here..." 
                            class="w-full p-4 rounded-xl bg-space-900/80 border border-space-600 text-white text-sm focus:outline-none focus:border-neon-cyan focus:ring-1 focus:ring-neon-cyan transition-all"></textarea>
                    </div>

                    <!-- Submit Button -->
                    <div class="pt-2">
                        <button type="submit" class="w-full py-4 rounded-xl font-orbitron text-sm font-bold uppercase tracking-wider text-space-900 bg-gradient-to-r from-neon-cyan via-cyan-400 to-neon-purple hover:shadow-glow-cyan transition-all transform hover:-translate-y-0.5">
                            Preview my pass <i class="fa-solid fa-paper-plane ml-2"></i>
                        </button>
                    </div>
                </form>

            </div>
        </div>
    </section>

    <!-- CONFIRMATION MODAL -->
    <div id="confirmation-modal" role="dialog" aria-modal="true" aria-label="Event pass preview" tabindex="-1" class="fixed inset-0 z-50 flex items-center justify-center p-4 bg-space-900/80 backdrop-blur-md hidden transition-opacity">
        <div class="glass-card max-w-md w-full p-6 sm:p-8 rounded-3xl border border-neon-cyan shadow-glow-cyan text-center relative animate-float">
            <div class="w-16 h-16 rounded-full bg-neon-cyan/20 border border-neon-cyan text-neon-cyan flex items-center justify-center text-3xl mx-auto mb-4">
                <i class="fa-solid fa-circle-check"></i>
            </div>
            
            <h3 class="font-orbitron font-extrabold text-2xl text-white">Your preview pass</h3>
            <p class="text-xs text-neon-cyan font-mono mt-1" id="modal-pass-id">PASS ID: #COSMO-2026-X9Y2</p>

            <div class="mt-4 p-4 rounded-xl bg-space-900/90 text-left space-y-2 text-xs text-gray-300 border border-space-700">
                <p><strong>Name:</strong> <span id="modal-name" class="text-white"></span></p>
                <p><strong>Email:</strong> <span id="modal-email" class="text-white"></span></p>
                <p><strong>Registered Event:</strong> <span id="modal-event" class="text-neon-cyan font-bold"></span></p>
            </div>

            <p class="text-xs text-gray-400 mt-4">This is a demo pass preview. Your details have not been submitted, and no email has been sent.</p>

            <button onclick="closeModal()" class="mt-6 w-full py-3 rounded-xl font-orbitron text-xs font-bold uppercase text-space-900 bg-neon-cyan hover:bg-cyan-300 transition-all">
                Close & Return
            </button>
        </div>
    </div>

    <!-- FOOTER -->
    <footer class="bg-space-900 border-t border-space-700/80 py-10 mt-auto">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center justify-between gap-6">
                <div class="flex items-center gap-3">
                    <span class="font-orbitron font-extrabold text-xl tracking-wider text-white">COSMO<span class="text-neon-cyan">FEST</span></span>
                    <span class="text-xs text-gray-400">| SATI Main Campus Technical & Cultural Committee</span>
                </div>
                
                <div class="text-xs text-gray-400 text-center md:text-right">
                    <p>Official Contact: <a href="mailto:sati@satiengg.in" class="text-neon-cyan hover:underline font-mono">sati@satiengg.in</a></p>
                    <p class="mt-1">&copy; 2026 CosmoFest. SATI Main Campus. All rights reserved.</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // Sample Event Data (8 events, 3 categories, 2 dates)
        const eventsData = [
            {
                id: 1,
                title: "Code Crack Sprint",
                category: "Code Crack",
                date: "15 Apr",
                time: "10:00 AM",
                venue: "Lab 2 (CS Block)",
                description: "High-speed algorithmic problem solving sprint using AI tools & live competitive leaderboards.",
                icon: "fa-terminal"
            },
            {
                id: 2,
                title: "Cyber Hunt (CTF)",
                category: "Code Crack",
                date: "15 Apr",
                time: "02:00 PM",
                venue: "Lab 5 (IT Block)",
                description: "Capture-The-Flag ethical hacking tournament. Crack security challenges, decrypt flags & win prizes.",
                icon: "fa-shield-halved"
            },
            {
                id: 3,
                title: "Battle of the Bands",
                category: "Cultural",
                date: "15 Apr",
                time: "10:00 AM",
                venue: "SATI Main Auditorium",
                description: "Watch student bands perform live at the main auditorium.",
                icon: "fa-guitar"
            },
            {
                id: 4,
                title: "Robo Wars Arena",
                category: "Technical",
                date: "15 Apr",
                time: "03:00 PM",
                venue: "SATI Open Arena",
                description: "Custom combat robots fight inside a heavy metal cage for ultimate destruction and glory.",
                icon: "fa-robot"
            },
            {
                id: 5,
                title: "Code Crack Hack-Fest",
                category: "Code Crack",
                date: "16 Apr",
                time: "11:00 AM",
                venue: "Lab 1 & 2",
                description: "Rapid full-stack building sprint. Turn high-level prompts into fully deployed web applications.",
                icon: "fa-laptop-code"
            },
            {
                id: 6,
                title: "UI/UX Designathon",
                category: "Technical",
                date: "16 Apr",
                time: "11:00 AM",
                venue: "Design Lab 3",
                description: "Design a mobile or web interface in a four-hour team challenge.",
                icon: "fa-palette"
            },
            {
                id: 7,
                title: "Cosmic Dance Clash",
                category: "Cultural",
                date: "16 Apr",
                time: "02:00 PM",
                venue: "SATI Main Stage",
                description: "Solo and crew dance battles featuring hip-hop, contemporary, and futuristic fusion beats.",
                icon: "fa-person-dancing"
            },
            {
                id: 8,
                title: "Star Night Gala",
                category: "Cultural",
                date: "16 Apr",
                time: "06:00 PM",
                venue: "SATI Central Grounds",
                description: "Celebrity musical night, laser fireworks show, and grand festival prize distribution.",
                icon: "fa-star"
            }
        ];

        let activeCategory = 'all';
        let activeDay = 'all';

        function getFilteredEvents() {
            const query = document.getElementById('event-search').value.trim().toLowerCase();
            const terms = query.split(/\s+/).filter(Boolean);
            return eventsData.filter(event => {
                const searchable = [event.title, event.description, event.category, event.venue].join(' ').toLowerCase();
                return (activeCategory === 'all' || event.category === activeCategory) &&
                    (activeDay === 'all' || event.date === activeDay) && terms.every(term => searchable.includes(term));
            });
        }

        function renderEvents() {
            const grid = document.getElementById('events-grid');
            const noMsg = document.getElementById('no-events-msg');
            const filtered = getFilteredEvents();
            document.getElementById('stat-events').textContent = filtered.length;
            document.getElementById('stat-categories').textContent = new Set(filtered.map(e => e.category)).size;
            document.getElementById('stat-days').textContent = new Set(filtered.map(e => e.date)).size;
            document.getElementById('results-count').textContent = `Showing ${filtered.length} of ${eventsData.length} events`;
            document.getElementById('export-csv').disabled = filtered.length === 0;
            document.getElementById('export-calendar').disabled = filtered.length === 0;
            document.querySelectorAll('.filter-cat-btn').forEach(button => {
                const category = button.id === 'cat-all' ? 'all' : button.textContent.trim();
                button.setAttribute('aria-pressed', String(category === activeCategory));
            });
            document.querySelectorAll('.filter-day-btn').forEach(button => {
                const day = button.id === 'day-all' ? 'all' : button.id === 'day-15' ? '15 Apr' : '16 Apr';
                button.setAttribute('aria-pressed', String(day === activeDay));
            });

            if (filtered.length === 0) {
                grid.innerHTML = '';
                noMsg.classList.remove('hidden');
                return;
            }

            noMsg.classList.add('hidden');
            grid.innerHTML = filtered.map(ev => {
                let badgeColor = ev.category === 'Code Crack' ? 'bg-neon-cyan/20 border-neon-cyan/50 text-neon-cyan' :
                                 ev.category === 'Technical' ? 'bg-blue-500/20 border-blue-400/50 text-blue-300' :
                                 'bg-neon-purple/20 border-neon-purple/50 text-neon-pink';

                return `
                    <div class="event-enter glass-card rounded-2xl p-6 flex flex-col justify-between hover:scale-[1.02] transition-all duration-300">
                        <div>
                            <div class="event-top flex items-center justify-between mb-4">
                                <span class="px-3 py-1 rounded-full text-xs font-mono font-semibold border ${badgeColor}">
                                    ${ev.category}
                                </span>
                                <span class="text-xs text-gray-400 font-mono"><i class="fa-regular fa-clock text-neon-cyan mr-1"></i> ${ev.date}, ${ev.time}</span>
                            </div>

                            <div class="event-title flex items-center gap-3 mb-3">
                                <div class="w-10 h-10 rounded-xl bg-space-900 border border-space-600 flex items-center justify-center text-neon-cyan">
                                    <i class="fa-solid ${ev.icon} text-lg"></i>
                                </div>
                                <h4 class="font-orbitron font-bold text-lg text-white">${ev.title}</h4>
                            </div>

                            <p class="text-xs text-gray-300 leading-relaxed mb-4">${ev.description}</p>
                        </div>

                        <div class="pt-4 border-t border-space-700/60 flex items-center justify-between">
                            <span class="text-xs font-semibold text-gray-400"><i class="fa-solid fa-location-dot text-neon-pink mr-1"></i> ${ev.venue}</span>
                            <a href="#register" onclick="preselectEvent('${ev.title}')" class="px-3 py-1.5 rounded-lg bg-space-700 hover:bg-neon-cyan hover:text-space-900 text-neon-cyan text-xs font-orbitron font-bold transition-all">
                                Register
                            </a>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function renderSchedule() {
            const timeline = document.getElementById('schedule-timeline');
            
            // Group events by date and time
            const timeGroups = {};
            eventsData.forEach(ev => {
                const key = `${ev.date} - ${ev.time}`;
                if (!timeGroups[key]) timeGroups[key] = [];
                timeGroups[key].push(ev);
            });

            timeline.innerHTML = Object.keys(timeGroups).map((timeSlot, idx) => {
                const events = timeGroups[timeSlot];
                const isEven = idx % 2 === 0;

                return `
                    <div class="relative flex flex-col sm:flex-row items-center">
                        <div class="flex items-center justify-start sm:justify-center w-full sm:w-1/2 ${isEven ? 'sm:pr-8 sm:text-right' : 'sm:pl-8 sm:order-last'} pl-10 mb-4 sm:mb-0">
                            <div class="glass-card p-5 rounded-2xl border border-space-600 w-full">
                                <span class="px-3 py-1 rounded-full bg-space-900 text-neon-cyan font-mono text-xs font-bold border border-neon-cyan/30 inline-block mb-3">
                                    <i class="fa-solid fa-clock mr-1"></i> ${timeSlot}
                                </span>
                                
                                <div class="grid grid-cols-1 ${events.length > 1 ? 'gap-3' : ''}">
                                    ${events.map(e => `
                                        <div class="p-3 rounded-xl bg-space-900/70 border border-space-700">
                                            <div class="flex items-center justify-between gap-2">
                                                <h5 class="font-orbitron font-bold text-sm text-white">${e.title}</h5>
                                                <span class="text-[10px] px-2 py-0.5 rounded font-mono ${e.category === 'Code Crack' ? 'bg-neon-cyan/20 text-neon-cyan' : e.category === 'Technical' ? 'bg-blue-500/20 text-blue-300' : 'bg-neon-purple/20 text-neon-pink'}">${e.category}</span>
                                            </div>
                                            <span class="text-xs text-gray-400 block mt-1"><i class="fa-solid fa-map-pin text-neon-pink mr-1"></i> ${e.venue}</span>
                                        </div>
                                    `).join('')}
                                </div>
                            </div>
                        </div>
                        
                        <!-- Timeline Node Dot -->
                        <div class="absolute left-4 sm:left-1/2 -ml-3 w-6 h-6 rounded-full bg-space-900 border-2 border-neon-cyan shadow-glow-cyan flex items-center justify-center z-10">
                            <div class="w-2 h-2 rounded-full bg-neon-cyan"></div>
                        </div>
                    </div>
                `;
            }).join('');
        }

        function populateFormDropdown() {
            const select = document.getElementById('selectedEvent');
            select.innerHTML = '<option value="">-- Choose an Event --</option>' + 
                eventsData.map(e => `<option value="${e.title}">${e.title} (${e.category}) - ${e.date}</option>`).join('');
        }

        function setCategoryFilter(cat) {
            activeCategory = cat;
            document.querySelectorAll('.filter-cat-btn').forEach(btn => {
                btn.className = "filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600";
            });
            const btnId = cat === 'all' ? 'cat-all' : cat === 'Code Crack' ? 'cat-codecrack' : cat === 'Technical' ? 'cat-technical' : 'cat-cultural';
            const activeBtn = document.getElementById(btnId);
            if(activeBtn) {
                activeBtn.className = "filter-cat-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-neon-cyan text-space-900 shadow-glow-cyan";
            }
            renderEvents();
        }

        function setDayFilter(day) {
            activeDay = day;
            document.querySelectorAll('.filter-day-btn').forEach(btn => {
                btn.className = "filter-day-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-space-700 text-gray-300 hover:text-white hover:bg-space-600";
            });
            const btnId = day === 'all' ? 'day-all' : day === '15 Apr' ? 'day-15' : 'day-16';
            const activeBtn = document.getElementById(btnId);
            if(activeBtn) {
                activeBtn.className = "filter-day-btn px-4 py-2 rounded-xl text-xs font-bold font-orbitron transition-all bg-neon-purple text-white shadow-glow-purple";
            }
            renderEvents();
        }

        function resetFilters() {
            document.getElementById('event-search').value = '';
            setCategoryFilter('all');
            setDayFilter('all');
        }

        function toggleTheme() {
            const light = document.documentElement.dataset.theme !== 'light';
            document.documentElement.dataset.theme = light ? 'light' : 'dark';
            document.getElementById('theme-toggle').setAttribute('aria-pressed', String(light));
            document.getElementById('theme-label').textContent = light ? 'Dark mode' : 'Light mode';
        }

        function calendarEscape(value) {
            return value.replace(/\\/g, '\\\\').replace(/\n/g, '\\n').replace(/,/g, '\\,').replace(/;/g, '\\;');
        }

        function createScheduleFile(format, events) {
            if (format === 'csv') {
                const rows = [['Event', 'Category', 'Date', 'Time (IST)', 'Venue', 'Description'], ...events.map(e => [e.title, e.category, e.date + ' 2026', e.time, e.venue, e.description])];
                return '\uFEFF' + rows.map(row => row.map(value => '"' + value.replace(/"/g, '""') + '"').join(',')).join('\r\n');
            }
            const lines = ['BEGIN:VCALENDAR', 'VERSION:2.0', 'PRODID:-//CosmoFest//Event Explorer//EN', 'CALSCALE:GREGORIAN'];
            events.forEach(e => {
                const [clock, period] = e.time.split(' ');
                const [hours, minutes] = clock.split(':').map(Number);
                const utc = new Date(Date.UTC(2026, 3, parseInt(e.date), hours % 12 + (period === 'PM' ? 12 : 0), minutes) - 330 * 60000);
                const stamp = utc.toISOString().replace(/[-:]/g, '').replace(/\.\d{3}/, '');
                lines.push('BEGIN:VEVENT', `UID:cosmofest-2026-${e.id}@benevolent-kleicha-4c6187.netlify.app`, 'DTSTAMP:' + new Date().toISOString().replace(/[-:]/g, '').replace(/\.\d{3}/, ''), 'DTSTART:' + stamp, 'SUMMARY:' + calendarEscape(e.title), 'LOCATION:' + calendarEscape(e.venue), 'DESCRIPTION:' + calendarEscape(e.description + ' Start time only; confirm duration with the organizers.'), 'END:VEVENT');
            });
            lines.push('END:VCALENDAR');
            return lines.map(line => {
                const chunks = [];
                while (line.length > 70) { chunks.push(line.slice(0, 70)); line = ' ' + line.slice(70); }
                chunks.push(line);
                return chunks.join('\r\n');
            }).join('\r\n') + '\r\n';
        }

        function downloadSchedule(format) {
            const events = getFilteredEvents();
            if (!events.length) return;
            const blob = new Blob([createScheduleFile(format, events)], {type: format === 'csv' ? 'text/csv;charset=utf-8' : 'text/calendar;charset=utf-8'});
            const url = URL.createObjectURL(blob);
            const link = document.createElement('a');
            link.href = url;
            link.download = `cosmofest-2026-schedule.${format}`;
            document.body.appendChild(link);
            link.click();
            link.remove();
            setTimeout(() => URL.revokeObjectURL(url), 1000);
        }

        function preselectEvent(title) {
            const select = document.getElementById('selectedEvent');
            if(select) select.value = title;
        }

        // Form Validation & Handling
        function handleRegistration(e) {
            e.preventDefault();
            let isValid = true;

            const name = document.getElementById('fullName').value.trim();
            const email = document.getElementById('email').value.trim();
            const phone = document.getElementById('phone').value.trim();
            const eventVal = document.getElementById('selectedEvent').value;

            // Simple validation
            if (!name) {
                document.getElementById('err-fullName').classList.remove('hidden');
                isValid = false;
            } else {
                document.getElementById('err-fullName').classList.add('hidden');
            }

            const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;
            if (!email || !emailRegex.test(email)) {
                document.getElementById('err-email').classList.remove('hidden');
                isValid = false;
            } else {
                document.getElementById('err-email').classList.add('hidden');
            }

            if (!phone || phone.length < 8) {
                document.getElementById('err-phone').classList.remove('hidden');
                isValid = false;
            } else {
                document.getElementById('err-phone').classList.add('hidden');
            }

            if (!eventVal) {
                document.getElementById('err-selectedEvent').classList.remove('hidden');
                isValid = false;
            } else {
                document.getElementById('err-selectedEvent').classList.add('hidden');
            }

            if (isValid) {
                document.getElementById('modal-name').textContent = name;
                document.getElementById('modal-email').textContent = email;
                document.getElementById('modal-event').textContent = eventVal;
                document.getElementById('modal-pass-id').textContent = 'PASS ID: #COSMO-2026-' + Math.random().toString(36).substring(2, 6).toUpperCase();
                
                document.getElementById('confirmation-modal').classList.remove('hidden');
                document.getElementById('confirmation-modal').focus();
                document.getElementById('registration-form').reset();
            }
        }

        function closeModal() {
            document.getElementById('confirmation-modal').classList.add('hidden');
            document.querySelector('#registration-form button[type=submit]').focus();
        }

        document.addEventListener('keydown', (e) => {
            const modal = document.getElementById('confirmation-modal');
            if (modal.classList.contains('hidden')) return;
            if (e.key === 'Escape') closeModal();
            if (e.key === 'Tab') { e.preventDefault(); modal.querySelector('button').focus(); }
        });
        document.getElementById('confirmation-modal').addEventListener('click', (e) => {
            if (e.target.id === 'confirmation-modal') closeModal();
        });
        // Mobile Menu Toggle
        document.getElementById('mobile-menu-btn').addEventListener('click', () => {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
            document.getElementById('mobile-menu-btn').setAttribute('aria-expanded', String(!menu.classList.contains('hidden')));
        });

        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => {
                document.getElementById('mobile-menu').classList.add('hidden');
                document.getElementById('mobile-menu-btn').setAttribute('aria-expanded', 'false');
            });
        });

        // Initialize App
        window.onload = function() {
            renderEvents();
            renderSchedule();
            populateFormDropdown();
        };
    </script>
</body>
</html><script async src="/.netlify/scripts/ar" data-netlify-deploy-id="6ae97d182f193870dd6910ba" data-netlify-site-id="4861bbfd-0bfa-4e52-9af4-fa61e37332bd" data-agent-runner-id="6ae97c6224d58a35170313f4"></script>
<script async src="/.netlify/scripts/hud?variant=public" data-nf-variant="public" data-netlify-site-id="4861bbfd-0bfa-4e52-9af4-fa61e37332bd" data-app-host="app.netlify.com" data-account-tier="free"></script>
