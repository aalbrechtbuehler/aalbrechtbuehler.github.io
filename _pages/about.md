---
permalink: /
title: "ABOUT"
author_profile: false
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* =========================================
     1. STATIC LIGHT THEME VARIABLES (Locked)
     ========================================= */


  /* =========================================
     2. GLOBAL HEADER FIXES (Matches Portfolio)
     ========================================= */
  .masthead, 
  .masthead__inner-wrap, 
  .masthead__menu, 
  .masthead__menu ul, 
  .greedy-nav {
    background-color: #ffffff !important;
    background: #ffffff !important;
  }
  
  .masthead {
    border-bottom: 1px solid var(--port-border) !important;
  }

  .masthead a, 
  .masthead__menu-item,
  .masthead__menu-item a,
  .greedy-nav a, 
  .greedy-nav .visible-links,
  .greedy-nav .visible-links li,
  .greedy-nav .visible-links a {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-text) !important;
  }

  .masthead a:hover,
  .greedy-nav a:hover,
  .greedy-nav .visible-links a:hover,
  .greedy-nav .visible-links li.masthead__menu-item--current a,
  .greedy-nav .visible-links li.masthead__menu-item--current a:hover {
    background-color: transparent !important;
    background: transparent !important;
    color: var(--port-primary) !important;
  }

  h1.page__title, .page__title {
    color: var(--port-primary) !important;
    font-weight: 700 !important;
  }

  /* =========================================
     3. BIOGRAPHY LAYOUT STYLES
     ========================================= */
  /* Standardized Section Titles */
  .section-title {
    margin-top: 45px; 
    border-bottom: 1px solid var(--port-border); 
    padding-bottom: 8px; 
    text-transform: uppercase; 
    color: var(--port-primary) !important;
    font-size: 1.15em !important; 
    letter-spacing: 0.1em;
    font-weight: 700;
  }

  /* Standardized Text Style for Bio */
  .content-text {
    text-align: justify !important; 
    text-justify: inter-word !important;
    font-size: 0.95em; 
    line-height: 1.7; 
    margin-bottom: 20px; 
    color: var(--port-text);
  }

  /* Collaboration Alert */
  .collab-box {
    background-color: var(--accent-color);
    border-left: 4px solid var(--port-primary);
    padding: 14px 18px;
    font-size: 0.95em;
    color: var(--port-primary);
    font-weight: 500;
    margin: 30px 0;
    border-radius: 0 4px 4px 0;
    box-shadow: 0 1px 3px rgba(0,0,0,0.03);
    line-height: 1.6;
  }

  /* Research Interest Badges */
  .interest-pills {
    display: flex;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 15px;
    margin-bottom: 30px;
  }
  
  .pill {
    background-color: var(--port-primary); 
    color: #ffffff; 
    font-size: 0.85em; 
    font-weight: 600;
    padding: 6px 14px;
    border-radius: 4px; 
    letter-spacing: 0.03em;
    box-shadow: 0 2px 4px rgba(0,0,0,0.05);
  }

  /* News Timeline Styling */
  .news-scroll-container {
    max-height: 500px; 
    overflow-y: auto; 
    margin-top: 20px;
    padding-right: 15px;
  }
  
  .news-scroll-container::-webkit-scrollbar { width: 5px; }
  .news-scroll-container::-webkit-scrollbar-track { background: var(--port-bg); }
  .news-scroll-container::-webkit-scrollbar-thumb { background: #d1d5db; border-radius: 10px; }
  .news-scroll-container::-webkit-scrollbar-thumb:hover { background: #9ca3af; }

  .timeline-item {
    display: flex; 
    margin-bottom: 14px; 
    font-size: 0.9em; 
    line-height: 1.5;
    padding: 4px 0;
    align-items: baseline; 
  }
  
  .timeline-date {
    min-width: 95px; 
    font-weight: 700; 
    color: var(--port-muted); 
  }
  
  .timeline-content {
    flex: 1; 
    color: var(--port-text);
    word-wrap: break-word; /* Prevents text cutoff */
  }

  /* Highlighted Milestones */
  .timeline-item.milestone {
    background-color: var(--accent-color); 
    border-radius: 4px;
    padding: 8px 12px; /* Added horizontal padding to prevent cutoff */
    margin-left: -12px; /* Offsets the padding to align visually */
    margin-top: 2px;
    margin-bottom: 12px;
  }

  /* Mobile & Tablet Responsiveness */
  @media (max-width: 768px) {
    .timeline-item { 
      flex-direction: column; 
      margin-bottom: 18px;
    }
    .timeline-date { 
      margin-bottom: 4px; 
      font-size: 0.85em; 
      color: var(--port-primary);
    }
    .timeline-item.milestone { 
      margin-left: 0; 
      padding: 10px 12px;
    }
  }
</style>

<div class="content-text">
  <p>I am a PhD student in the Cognitive Science and Pragmatics Group at the University of Tübingen, working in the SFB 1718 Common Ground Project A7 (Modeling Great Ape Signaling Behavior: Evolutionary Roots of Common Ground). My general interests lie in animal communication and linguistic modeling, and I have worked with many model species including pigeons, bumblebees, Bengalese finches, and cichlids. My current research investigates multimodal communication in great apes using game- and information-theoretic approaches. </p>
    <p>I previously received a BA in Experimental Psychology from the University of Oxford, and an M.Sc. in Quantitative Data Science Methods with a specialization in Machine Learning from the University of Tübingen. </p>
      <p>Outside of my research, I enjoy playing classical piano, bouldering, and photography.</p>
</div>


<h2 class="section-title">Research Interests</h2>
<div class="interest-pills">
  <span class="pill">Animal Communication</span>
  <span class="pill">Linguistics</span>
  <span class="pill">Game Theory</span>
  <span class="pill">Information Theory</span>
  <span class="pill">Machine Learning</span>
</div>
