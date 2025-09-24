<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aleix Rodriguez Muñoz | DAW Developer</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #f0f6fc;
            line-height: 1.6;
        }
        
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Header */
        header {
            background: linear-gradient(135deg, #238636, #2ea043);
            padding: 60px 0 40px;
            text-align: center;
            margin-bottom: 40px;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid white;
            margin: 0 auto 20px;
            background: #161b22;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 60px;
            color: #f0f6fc;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .social-links a {
            color: white;
            font-size: 1.5rem;
        }
        
        /* Sections */
        section {
            margin-bottom: 40px;
            padding: 30px;
            background: #161b22;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #58a6ff;
            border-bottom: 2px solid #238636;
            padding-bottom: 10px;
        }
        
        h3 {
            margin: 15px 0 10px;
            color: #f0f6fc;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        /* Skills */
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .skill-category {
            background: #0d1117;
            padding: 15px;
            border-radius: 8px;
            border-left: 4px solid #238636;
        }
        
        .skill-list {
            list-style: none;
        }
        
        .skill-list li {
            margin: 8px 0;
            display: flex;
            align-items: center;
        }
        
        .skill-list li::before {
            content: "▹";
            color: #238636;
            margin-right: 10px;
        }
        
        /* Projects */
        .project {
            background: #0d1117;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            border-left: 4px solid #58a6ff;
        }
        
        .project-links {
            margin-top: 15px;
        }
        
        .project-links a {
            color: #58a6ff;
            text-decoration: none;
            margin-right: 15px;
            display: inline-flex;
            align-items: center;
        }
        
        .project-links a:hover {
            text-decoration: underline;
        }
        
        .project-links i {
            margin-right: 5px;
        }
        
        /* Contact */
        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 15px;
        }
        
        .contact-item i {
            font-size: 1.2rem;
            color: #238636;
            margin-right: 10px;
            width: 30px;
        }
        
        /* Footer */
        footer {
            text-align: center;
            padding: 30px 0;
            margin-top: 40px;
            border-top: 1px solid #30363d;
            color: #8b949e;
        }
        
        /* Responsive */
        @media (max-width: 600px) {
            h1 {
                font-size: 2rem;
            }
            
            .profile-img {
                width: 120px;
                height: 120px;
                font-size: 50px;
            }
            
            section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <div class="container">
            <div class="profile-img">
                <i class="fas fa-code"></i>
            </div>
            <h1>Aleix Rodriguez Muñoz</h1>
            <p class="tagline">Desarrollador Web | Enfocado en el Diseño Visual</p>
            <div class="social-links">
                <a href="https://github.com/rodriguezalek" title="GitHub">
                    <i class="fab fa-github"></i>
                </a>
                <a href="#" title="LinkedIn">
                    <i class="fab fa-linkedin"></i>
                </a>
                <a href="#" title="Twitter">
                    <i class="fab fa-twitter"></i>
                </a>
                <a href="#" title="Portfolio">
                    <i class="fas fa-globe"></i>
                </a>
            </div>
        </div>
    </header>

    <div class="container">
        <!-- About Section -->
        <section id="about">
            <h2>Sobre Mí</h2>
            <p>¡Hola! Soy Aleix, un estudiante de Desarrollo de Aplicaciones Web (DAW) apasionado por la creación de experiencias web visualmente atractivas y funcionales.</p>
            <p>Lo que más me gusta es programar páginas web, especialmente la parte visual y de diseño. Disfruto creando interfaces que sean intuitivas y agradables para los usuarios.</p>
            <p>Actualmente estoy ampliando mis conocimientos en desarrollo frontend y diseño UI/UX.</p>
        </section>

        <!-- Skills Section -->
        <section id="skills">
            <h2>Habilidades</h2>
            <div class="skills-grid">
                <div class="skill-category">
                    <h3>Frontend</h3>
                    <ul class="skill-list">
                        <li>HTML5 & CSS3</li>
                        <li>JavaScript</li>
                        <li>React</li>
                        <li>Responsive Design</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Backend</h3>
                    <ul class="skill-list">
                        <li>PHP</li>
                        <li>Node.js</li>
                        <li>MySQL</li>
                        <li>APIs REST</li>
                    </ul>
                </div>
                <div class="skill-category">
                    <h3>Diseño</h3>
                    <ul class="skill-list">
                        <li>UI/UX Design</li>
                        <li>Figma</li>
                        <li>Adobe XD</li>
                        <li>Photoshop</li>
                    </ul>
                </div>
            </div>
        </section>

        <!-- Projects Section -->
        <section id="projects">
            <h2>Proyectos Destacados</h2>
            
            <div class="project">
                <h3>Portfolio Personal</h3>
                <p>Diseño y desarrollo de mi portfolio web con enfoque en la experiencia visual y usabilidad.</p>
                <div class="project-links">
                    <a href="#"><i class="fab fa-github"></i> Ver código</a>
                    <a href="#"><i class="fas fa-external-link-alt"></i> Ver demo</a>
                </div>
            </div>
            
            <div class="project">
                <h3>Tienda Online</h3>
                <p>E-commerce desarrollado con React y Node.js, con diseño responsive y interfaz intuitiva.</p>
                <div class="project-links">
                    <a href="#"><i class="fab fa-github"></i> Ver código</a>
                    <a href="#"><i class="fas fa-external-link-alt"></i> Ver demo</a>
                </div>
            </div>
            
            <div class="project">
                <h3>App de Tareas</h3>
                <p>Aplicación web para gestión de tareas con diseño moderno y funcionalidades avanzadas.</p>
                <div class="project-links">
                    <a href="#"><i class="fab fa-github"></i> Ver código</a>
                    <a href="#"><i class="fas fa-external-link-alt"></i> Ver demo</a>
                </div>
            </div>
        </section>

        <!-- Contact Section -->
        <section id="contact">
            <h2>Contacto</h2>
            <p>¿Tienes un proyecto interesante? ¡Me encantaría saber de ti!</p>
            
            <div class="contact-info">
                <div>
                    <div class="contact-item">
                        <i class="fas fa-envelope"></i>
                        <span>aleix@email.com</span>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-map-marker-alt"></i>
                        <span>España</span>
                    </div>
                </div>
                <div>
                    <div class="contact-item">
                        <i class="fas fa-graduation-cap"></i>
                        <span>Estudiante de DAW</span>
                    </div>
                    <div class="contact-item">
                        <i class="fas fa-heart"></i>
                        <span>Desarrollo Frontend & Diseño Visual</span>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <!-- Footer -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Aleix Rodriguez Muñoz. Hecho con ❤️ y mucho CSS.</p>
            <p>
                <a href="https://github.com/rodriguezalek" style="color: #58a6ff; text-decoration: none;">
                    Visita mi GitHub
                </a>
            </p>
        </div>
    </footer>
</body>
</html>
