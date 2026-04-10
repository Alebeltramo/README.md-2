<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Alessandro Beltramo - Desenvolvedor de Software | Freelancer | Análise e Desenvolvimento de Sistemas">
    <title>Alessandro Beltramo | Desenvolvedor de Software</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=JetBrains+Mono:wght@400;500;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Animated Background Particles -->
    <canvas id="particles-canvas"></canvas>

    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="#" class="nav-logo">
                <span class="logo-bracket">&lt;</span>AB<span class="logo-bracket">/&gt;</span>
            </a>
            <ul class="nav-links">
                <li><a href="#home" class="nav-link active">Início</a></li>
                <li><a href="#about" class="nav-link">Sobre</a></li>
                <li><a href="#skills" class="nav-link">Skills</a></li>
                <li><a href="#projects" class="nav-link">Projetos</a></li>
                <li><a href="#stats" class="nav-link">Estatísticas</a></li>
                <li><a href="#contact" class="nav-link">Contato</a></li>
            </ul>
            <button class="nav-toggle" id="nav-toggle" aria-label="Menu de navegação">
                <span></span>
                <span></span>
                <span></span>
            </button>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero" id="home">
        <div class="hero-content">
            <div class="hero-text">
                <div class="hero-greeting">
                    <span class="greeting-line"></span>
                    <span class="greeting-text">Olá, mundo! Eu sou</span>
                </div>
                <h1 class="hero-name">
                    Alessandro<br>
                    <span class="name-highlight">Beltramo</span>
                </h1>
                <div class="hero-typing">
                    <span class="typing-prefix">&gt; </span>
                    <span class="typing-text" id="typing-text"></span>
                    <span class="typing-cursor">|</span>
                </div>
                <p class="hero-description">
                    Apaixonado por projetos na área de desenvolvimento de software.
                    Cursando Análise e Desenvolvimento de Sistemas.
                </p>
                <div class="hero-badges">
                    <span class="badge badge-oracle">Oracle ONE</span>
                    <span class="badge badge-alura">Alura</span>
                    <span class="badge badge-java">Java</span>
                </div>
                <div class="hero-cta">
                    <a href="#projects" class="btn btn-primary">
                        <span>Ver Projetos</span>
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                    <a href="#contact" class="btn btn-outline">Entre em contato</a>
                </div>
            </div>
            <div class="hero-visual">
                <div class="avatar-container">
                    <div class="avatar-ring"></div>
                    <div class="avatar-ring avatar-ring-2"></div>
                    <img src="assets/avatar.png" alt="Alessandro Beltramo" class="avatar-img">
                    <div class="avatar-status">
                        <span class="status-dot"></span>
                        <span>Disponível</span>
                    </div>
                </div>
                <div class="floating-card card-1">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"/>
                    </svg>
                    <span>6 Repos</span>
                </div>
                <div class="floating-card card-2">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M20 21v-2a4 4 0 0 0-4-4H8a4 4 0 0 0-4 4v2M12 3a4 4 0 1 0 0 8 4 4 0 0 0 0-8z"/>
                    </svg>
                    <span>Freelancer</span>
                </div>
                <div class="floating-card card-3">
                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                        <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
                        <circle cx="12" cy="10" r="3"/>
                    </svg>
                    <span>São Paulo</span>
                </div>
            </div>
        </div>
        <div class="hero-scroll">
            <span>Scroll</span>
            <div class="scroll-indicator">
                <div class="scroll-dot"></div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="section about" id="about">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">&lt;sobre&gt;</span>
                <h2 class="section-title">Quem sou eu</h2>
                <div class="section-line"></div>
            </div>
            <div class="about-grid">
                <div class="about-text">
                    <p class="about-intro">
                        Sou um desenvolvedor de software e freelancer baseado em 
                        <strong>Taboão da Serra, São Paulo</strong>. Atualmente cursando 
                        <strong>Análise e Desenvolvimento de Sistemas</strong>, estou sempre 
                        buscando novos desafios e oportunidades para crescer na área de tecnologia.
                    </p>
                    <p>
                        Minha jornada no desenvolvimento inclui formações pela 
                        <strong>Oracle Next Education (ONE)</strong> e <strong>Alura</strong>, 
                        com foco especial em <strong>Java</strong>, <strong>Python</strong> e 
                        <strong>JavaScript</strong>. Tenho paixão por criar soluções eficientes 
                        e automações que simplificam processos.
                    </p>
                    <div class="about-details">
                        <div class="detail-item">
                            <div class="detail-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"/>
                                    <circle cx="12" cy="10" r="3"/>
                                </svg>
                            </div>
                            <div>
                                <span class="detail-label">Localização</span>
                                <span class="detail-value">Taboão da Serra, SP</span>
                            </div>
                        </div>
                        <div class="detail-item">
                            <div class="detail-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <rect x="2" y="7" width="20" height="14" rx="2"/>
                                    <path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/>
                                </svg>
                            </div>
                            <div>
                                <span class="detail-label">Trabalho</span>
                                <span class="detail-value">Freelancer Home Office</span>
                            </div>
                        </div>
                        <div class="detail-item">
                            <div class="detail-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M22 10v6M2 10l10-5 10 5-10 5z"/>
                                    <path d="M6 12v5c3 3 6 3 6 3s3 0 6-3v-5"/>
                                </svg>
                            </div>
                            <div>
                                <span class="detail-label">Formação</span>
                                <span class="detail-value">Análise e Dev. de Sistemas</span>
                            </div>
                        </div>
                        <div class="detail-item">
                            <div class="detail-icon">
                                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <circle cx="12" cy="12" r="10"/>
                                    <path d="M12 6v6l4 2"/>
                                </svg>
                            </div>
                            <div>
                                <span class="detail-label">Fuso horário</span>
                                <span class="detail-value">UTC -03:00 (BRT)</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="about-cards">
                    <div class="info-card">
                        <div class="info-card-icon">🎓</div>
                        <h3>Oracle ONE</h3>
                        <p>Formação completa pelo programa Oracle Next Education em parceria com a Alura</p>
                    </div>
                    <div class="info-card">
                        <div class="info-card-icon">☕</div>
                        <h3>Java Developer</h3>
                        <p>Especialização em desenvolvimento Java com foco em backend e automações</p>
                    </div>
                    <div class="info-card">
                        <div class="info-card-icon">🤖</div>
                        <h3>Automação</h3>
                        <p>Experiência em automação de processos com Python e ferramentas Microsoft</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section class="section skills" id="skills">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">&lt;skills&gt;</span>
                <h2 class="section-title">Tecnologias que eu uso</h2>
                <div class="section-line"></div>
            </div>
            <div class="skills-grid">
                <div class="skill-card" data-skill="python">
                    <div class="skill-icon">
                        <svg viewBox="0 0 128 128" width="48" height="48">
                            <linearGradient id="python-a" x1="70.252" x2="170.659" y1="1237.476" y2="1151.089" gradientTransform="matrix(.563 0 0 -.568 -29.215 707.817)" gradientUnits="userSpaceOnUse">
                                <stop offset="0" stop-color="#5A9FD4"/>
                                <stop offset="1" stop-color="#306998"/>
                            </linearGradient>
                            <linearGradient id="python-b" x1="209.474" x2="173.62" y1="1098.811" y2="1149.537" gradientTransform="matrix(.563 0 0 -.568 -29.215 707.817)" gradientUnits="userSpaceOnUse">
                                <stop offset="0" stop-color="#FFD43B"/>
                                <stop offset="1" stop-color="#FFE873"/>
                            </linearGradient>
                            <path fill="url(#python-a)" d="M63.391 1.988c-4.222.02-8.252.379-11.8 1.007-10.45 1.846-12.346 5.71-12.346 12.837v9.411h24.693v3.137H29.977c-7.176 0-13.46 4.313-15.426 12.521-2.268 9.405-2.368 15.275 0 25.096 1.755 7.311 5.947 12.519 13.124 12.519h8.491V67.234c0-8.151 7.051-15.34 15.426-15.34h24.665c6.866 0 12.346-5.654 12.346-12.548V15.833c0-6.693-5.646-11.72-12.346-12.837-4.244-.706-8.645-1.027-12.866-1.008zM50.037 9.557c2.55 0 4.634 2.117 4.634 4.721 0 2.593-2.083 4.69-4.634 4.69-2.56 0-4.633-2.097-4.633-4.69-.001-2.604 2.073-4.721 4.633-4.721z"/>
                            <path fill="url(#python-b)" d="M91.682 28.38v10.966c0 8.5-7.208 15.655-15.426 15.655H51.591c-6.756 0-12.346 5.783-12.346 12.549v23.515c0 6.691 5.818 10.628 12.346 12.547 7.816 2.297 15.312 2.713 24.665 0 6.216-1.801 12.346-5.423 12.346-12.547v-9.412H63.938v-3.138h37.012c7.176 0 9.852-5.005 12.348-12.519 2.578-7.735 2.467-15.174 0-25.096-1.774-7.145-5.161-12.521-12.348-12.521h-9.268zM77.809 87.927c2.561 0 4.634 2.097 4.634 4.692 0 2.602-2.074 4.719-4.634 4.719-2.55 0-4.633-2.117-4.633-4.719 0-2.595 2.083-4.692 4.633-4.692z"/>
                        </svg>
                    </div>
                    <h3>Python</h3>
                    <p>Automação & Scripts</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 80%"></div>
                    </div>
                </div>
                <div class="skill-card" data-skill="javascript">
                    <div class="skill-icon">
                        <svg viewBox="0 0 128 128" width="48" height="48">
                            <path fill="#F0DB4F" d="M1.408 1.408h125.184v125.185H1.408z"/>
                            <path fill="#323330" d="M116.347 96.736c-.917-5.711-4.641-10.508-15.672-14.981-3.832-1.761-8.104-3.022-9.377-5.886-.452-1.69-.512-2.642-.225-3.68.821-3.317 4.004-4.287 6.644-3.369 1.695.613 3.272 2.105 4.258 4.565 4.504-2.968 4.504-2.968 7.646-4.939-1.166-1.842-1.758-2.663-2.537-3.478-2.729-3.046-5.998-4.597-11.519-4.45l-2.88.514c-2.754.694-5.375 2.24-6.911 4.101-4.508 5.327-3.198 14.631 2.251 18.458 5.371 4.131 13.245 5.046 14.252 8.938 1.007 4.608-3.395 6.097-7.696 5.411-3.188-.647-4.948-2.064-6.865-4.7l-7.868 4.56c.899 1.892 1.896 2.726 3.405 4.38 7.271 7.311 25.437 6.936 28.673-4.17.131-.374 1.014-3.026.339-7.074zM78.167 33.039l-9.586.001v30.219c0 6.414.344 12.296-.768 14.098-1.803 3.46-6.475 3.054-8.6 2.442-2.172-1.025-3.249-2.456-4.548-4.51l-.001-.002-7.835 4.82c1.322 2.709 3.223 5.031 5.804 6.545 3.854 2.26 9.023 2.987 14.476 1.773 3.556-1.003 6.613-3.065 8.238-6.149 2.361-4.219 1.846-9.37 1.819-15.157l.001-34.079z"/>
                        </svg>
                    </div>
                    <h3>JavaScript</h3>
                    <p>Web Development</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 75%"></div>
                    </div>
                </div>
                <div class="skill-card" data-skill="java">
                    <div class="skill-icon">
                        <svg viewBox="0 0 128 128" width="48" height="48">
                            <path fill="#0074BD" d="M47.617 98.12s-4.767 2.774 3.397 3.71c9.892 1.13 14.947.968 25.845-1.092 0 0 2.871 1.795 6.873 3.351-24.439 10.47-55.308-.607-36.115-5.969zm-2.988-13.665s-5.348 3.959 2.823 4.805c10.567 1.091 18.91 1.18 33.354-1.6 0 0 1.993 2.025 5.132 3.131-29.542 8.64-62.446.68-41.309-6.336z"/>
                            <path fill="#EA2D2E" d="M69.802 61.271c6.025 6.935-1.58 13.17-1.58 13.17s15.289-7.891 8.269-17.777c-6.559-9.215-11.587-13.793 15.635-29.58 0 .001-42.731 10.67-22.324 34.187z"/>
                            <path fill="#0074BD" d="M102.123 108.229s3.529 2.91-3.888 5.159c-14.102 4.272-58.706 5.56-71.094.171-4.451-1.938 3.899-4.625 6.526-5.192 2.739-.593 4.303-.485 4.303-.485-4.953-3.487-32.013 6.85-13.743 9.815 49.821 8.076 90.817-3.637 77.896-9.468zM49.912 70.294s-22.686 5.389-8.033 7.348c6.188.828 18.518.638 30.011-.326 9.39-.789 18.813-2.474 18.813-2.474s-3.308 1.419-5.704 3.053c-23.042 6.061-67.544 3.238-54.731-2.958 10.832-5.239 19.644-4.643 19.644-4.643zm40.697 22.747c23.421-12.167 12.591-23.86 5.032-22.285-1.848.385-2.677.72-2.677.72s.688-1.079 2-1.543c14.953-5.255 26.451 15.503-4.823 23.725 0-.002.359-.327.468-.617z"/>
                            <path fill="#EA2D2E" d="M76.491 1.587S89.459 14.563 64.188 33.21c-20.266 14.98-4.621 23.528-.003 33.294-11.83-10.676-20.506-20.074-14.681-28.82C57.864 25.075 81.396 19.048 76.491 1.587z"/>
                            <path fill="#0074BD" d="M52.214 126.021c22.476 1.437 56.992-.794 57.818-11.347 0 0-1.571 4.032-18.577 7.231-19.186 3.612-42.854 3.191-56.887.874 0 .001 2.875 2.381 17.646 3.242z"/>
                        </svg>
                    </div>
                    <h3>Java</h3>
                    <p>Backend & Aplicações</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 70%"></div>
                    </div>
                </div>
                <div class="skill-card" data-skill="c">
                    <div class="skill-icon">
                        <svg viewBox="0 0 128 128" width="48" height="48">
                            <path fill="#659AD2" d="M115.4 30.7L67.1 2.9c-.8-.5-1.9-.7-3.1-.7-1.2 0-2.3.3-3.1.7l-48 27.9c-1.7 1-2.9 3.5-2.9 5.4v55.7c0 1.1.2 2.4 1 3.5l106.8-62c-.6-1.2-1.5-2.1-2.4-2.7z"/>
                            <path fill="#03599C" d="M10.7 95.3c.5.8 1.2 1.5 1.9 1.9l48.2 27.9c.8.5 1.9.7 3.1.7 1.2 0 2.3-.3 3.1-.7l48-27.9c1.7-1 2.9-3.5 2.9-5.4V36.1c0-.9-.1-1.9-.6-2.8l-106.6 62z"/>
                            <path fill="#fff" d="M85.3 76.3C81.1 83.5 73.1 88.5 64 88.5c-13.5 0-24.5-11-24.5-24.5s11-24.5 24.5-24.5c9.1 0 17.1 5 21.3 12.5l13-7.5c-6.8-11.9-19.6-20-34.3-20-21.8 0-39.5 17.7-39.5 39.5s17.7 39.5 39.5 39.5c14.6 0 27.4-8 34.2-19.8l-12.9-7.4z"/>
                        </svg>
                    </div>
                    <h3>C</h3>
                    <p>Programação de Sistemas</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 60%"></div>
                    </div>
                </div>
                <div class="skill-card" data-skill="html-css">
                    <div class="skill-icon">
                        <svg viewBox="0 0 128 128" width="48" height="48">
                            <path fill="#E44D26" d="M19.037 113.876L9.032 1.661h109.936l-10.016 112.198-45.019 12.48z"/>
                            <path fill="#F16529" d="M64 116.8l36.378-10.086 8.559-95.878H64z"/>
                            <path fill="#EBEBEB" d="M64 52.455H45.788L44.53 38.361H64V24.599H29.489l.33 3.692 3.382 37.927H64zm0 35.743l-.061.017-15.327-4.14-.979-10.975H33.816l1.928 21.609 28.193 7.826.063-.017z"/>
                            <path fill="#fff" d="M63.952 52.455v13.763h16.947l-1.597 17.849-15.35 4.143v14.319l28.215-7.82.207-2.325 3.234-36.233.335-3.696h-3.708zm0-27.856v13.762h33.244l.276-3.092.628-6.978.329-3.692z"/>
                        </svg>
                    </div>
                    <h3>HTML & CSS</h3>
                    <p>Frontend & Design</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 85%"></div>
                    </div>
                </div>
                <div class="skill-card" data-skill="tools">
                    <div class="skill-icon">
                        <svg viewBox="0 0 24 24" width="48" height="48" fill="none" stroke="#00A4EF" stroke-width="1.5">
                            <rect x="1" y="1" width="10" height="10" fill="#F25022" stroke="none"/>
                            <rect x="13" y="1" width="10" height="10" fill="#7FBA00" stroke="none"/>
                            <rect x="1" y="13" width="10" height="10" fill="#00A4EF" stroke="none"/>
                            <rect x="13" y="13" width="10" height="10" fill="#FFB900" stroke="none"/>
                        </svg>
                    </div>
                    <h3>Microsoft</h3>
                    <p>Excel, Windows & Tools</p>
                    <div class="skill-level">
                        <div class="skill-bar" style="--skill-width: 90%"></div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section class="section projects" id="projects">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">&lt;projetos&gt;</span>
                <h2 class="section-title">Meus Projetos</h2>
                <div class="section-line"></div>
            </div>
            <div class="projects-grid">
                <div class="project-card featured">
                    <div class="project-header">
                        <div class="project-icon">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
                            </svg>
                        </div>
                        <div class="project-links">
                            <a href="https://github.com/Alebeltramo/Overclock-Performance" target="_blank" rel="noopener" aria-label="Ver repositório">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="project-title">Overclock Performance</h3>
                    <p class="project-desc">Projeto de performance e otimização de sistemas, focado em melhorias de hardware e software.</p>
                    <div class="project-tags">
                        <span class="tag">Performance</span>
                        <span class="tag">Otimização</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <div class="project-icon">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
                            </svg>
                        </div>
                        <div class="project-links">
                            <a href="https://github.com/Alebeltramo/Interface" target="_blank" rel="noopener" aria-label="Ver repositório">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="project-title">Interface</h3>
                    <p class="project-desc">Projeto de interface de usuário com foco em design moderno e experiência do usuário.</p>
                    <div class="project-tags">
                        <span class="tag">UI/UX</span>
                        <span class="tag">Interface</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <div class="project-icon">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
                            </svg>
                        </div>
                        <div class="project-links">
                            <a href="https://github.com/Alebeltramo/NugConnect" target="_blank" rel="noopener" aria-label="Ver repositório">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="project-title">NugConnect</h3>
                    <p class="project-desc">Projeto de conectividade e criação de funções para integração de sistemas.</p>
                    <div class="project-tags">
                        <span class="tag">Funções</span>
                        <span class="tag">Conectividade</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <div class="project-icon">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
                            </svg>
                        </div>
                        <div class="project-links">
                            <a href="https://github.com/Alebeltramo/Alebeltramo-automacao-excel" target="_blank" rel="noopener" aria-label="Ver repositório">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="project-title">Automação Excel</h3>
                    <p class="project-desc">Automação de planilhas Excel para otimização de processos e produtividade.</p>
                    <div class="project-tags">
                        <span class="tag">Python</span>
                        <span class="tag">Excel</span>
                        <span class="tag">Automação</span>
                    </div>
                </div>
                <div class="project-card">
                    <div class="project-header">
                        <div class="project-icon">
                            <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                <path d="M22 19a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h5l2 3h9a2 2 0 0 1 2 2z"/>
                            </svg>
                        </div>
                        <div class="project-links">
                            <a href="https://github.com/Alebeltramo/amigo-secreto" target="_blank" rel="noopener" aria-label="Ver repositório">
                                <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                                    <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22"/>
                                </svg>
                            </a>
                        </div>
                    </div>
                    <h3 class="project-title">Amigo Secreto</h3>
                    <p class="project-desc">Meu primeiro projeto desenvolvido com HTML, CSS e JavaScript através das aulas da Alura.</p>
                    <div class="project-tags">
                        <span class="tag">HTML</span>
                        <span class="tag">CSS</span>
                        <span class="tag">JavaScript</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- GitHub Stats Section -->
    <section class="section stats" id="stats">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">&lt;estatísticas&gt;</span>
                <h2 class="section-title">Estatísticas GitHub</h2>
                <div class="section-line"></div>
            </div>
            <div class="stats-grid">
                <div class="stat-card">
                    <img src="https://github-readme-stats.vercel.app/api?username=Alebeltramo&show_icons=true&theme=tokyonight&bg_color=0d1117&border_color=1a1f35&title_color=a78bfa&icon_color=818cf8&text_color=c9d1d9&count_private=true&hide_border=true" alt="GitHub Stats" loading="lazy">
                </div>
                <div class="stat-card">
                    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Alebeltramo&layout=compact&theme=tokyonight&bg_color=0d1117&border_color=1a1f35&title_color=a78bfa&text_color=c9d1d9&hide_border=true" alt="Top Languages" loading="lazy">
                </div>
                <div class="stat-card streak-card">
                    <img src="https://github-readme-streak-stats.herokuapp.com/?user=Alebeltramo&theme=tokyonight&background=0d1117&border=1a1f35&ring=a78bfa&fire=818cf8&currStreakLabel=a78bfa&hide_border=true" alt="GitHub Streak" loading="lazy">
                </div>
            </div>
            <div class="contribution-graph">
                <img src="https://ghchart.rshah.org/8b5cf6/Alebeltramo" alt="Contribution Chart" loading="lazy">
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="section contact" id="contact">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">&lt;contato&gt;</span>
                <h2 class="section-title">Vamos conversar!</h2>
                <div class="section-line"></div>
            </div>
            <p class="contact-subtitle">Estou sempre aberto a novas oportunidades e projetos interessantes.</p>
            <div class="contact-grid">
                <a href="https://www.linkedin.com/in/alessandro-beltramo/" target="_blank" rel="noopener" class="contact-card" id="contact-linkedin">
                    <div class="contact-icon linkedin">
                        <svg width="28" height="28" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433a2.062 2.062 0 0 1-2.063-2.065 2.064 2.064 0 1 1 2.063 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
                        </svg>
                    </div>
                    <div class="contact-info">
                        <h3>LinkedIn</h3>
                        <span>alessandro-beltramo</span>
                    </div>
                    <div class="contact-arrow">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7v10"/>
                        </svg>
                    </div>
                </a>
                <a href="https://www.youtube.com/@overclockperformance" target="_blank" rel="noopener" class="contact-card" id="contact-youtube">
                    <div class="contact-icon youtube">
                        <svg width="28" height="28" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/>
                        </svg>
                    </div>
                    <div class="contact-info">
                        <h3>YouTube</h3>
                        <span>@overclockperformance</span>
                    </div>
                    <div class="contact-arrow">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7v10"/>
                        </svg>
                    </div>
                </a>
                <a href="https://www.tiktok.com/@beltramossm?lang=pt-BR" target="_blank" rel="noopener" class="contact-card" id="contact-tiktok">
                    <div class="contact-icon tiktok">
                        <svg width="28" height="28" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/>
                        </svg>
                    </div>
                    <div class="contact-info">
                        <h3>TikTok</h3>
                        <span>@beltramossm</span>
                    </div>
                    <div class="contact-arrow">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7v10"/>
                        </svg>
                    </div>
                </a>
                <a href="https://github.com/Alebeltramo" target="_blank" rel="noopener" class="contact-card" id="contact-github">
                    <div class="contact-icon github">
                        <svg width="28" height="28" viewBox="0 0 24 24" fill="currentColor">
                            <path d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12"/>
                        </svg>
                    </div>
                    <div class="contact-info">
                        <h3>GitHub</h3>
                        <span>Alebeltramo</span>
                    </div>
                    <div class="contact-arrow">
                        <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                            <path d="M7 17L17 7M17 7H7M17 7v10"/>
                        </svg>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-logo">
                    <span class="logo-bracket">&lt;</span>AB<span class="logo-bracket">/&gt;</span>
                </div>
                <p class="footer-text">Feito com <span class="heart">❤</span> por Alessandro Beltramo</p>
                <p class="footer-copyright">&copy; 2026 — Todos os direitos reservados</p>
            </div>
        </div>
    </footer>

    <script src="script.js"></script>
</body>
</html>
