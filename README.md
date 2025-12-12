<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>James Kariuki - Cloud & DevOps Engineer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
            color: #e2e8f0;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(15, 23, 42, 0.95);
            border: 1px solid rgba(148, 163, 184, 0.2);
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.5);
        }
        
        .header {
            background: linear-gradient(135deg, #1e40af 0%, #7c3aed 100%);
            padding: 60px 40px;
            text-align: center;
            position: relative;
            overflow: hidden;
        }
        
        .header::before {
            content: '';
            position: absolute;
            top: -50%;
            right: -10%;
            width: 400px;
            height: 400px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 50%;
        }
        
        .header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            position: relative;
            z-index: 1;
        }
        
        .title {
            font-size: 1.3em;
            color: #c7d2e0;
            margin-bottom: 20px;
            position: relative;
            z-index: 1;
        }
        
        .contact-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            position: relative;
            z-index: 1;
            font-size: 0.95em;
        }
        
        .contact-links a {
            color: #e0f2fe;
            text-decoration: none;
            transition: color 0.3s;
        }
        
        .contact-links a:hover {
            color: #fff;
        }
        
        .content {
            padding: 50px 40px;
        }
        
        .section {
            margin-bottom: 45px;
        }
        
        .section-title {
            font-size: 1.5em;
            color: #60a5fa;
            margin-bottom: 20px;
            padding-bottom: 10px;
            border-bottom: 2px solid rgba(96, 165, 250, 0.3);
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .icon {
            font-size: 1.3em;
        }
        
        .about-text {
            color: #cbd5e1;
            font-size: 1em;
            line-height: 1.8;
            margin-bottom: 15px;
        }
        
        .skills-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 25px;
        }
        
        .skill-category {
            background: rgba(30, 41, 59, 0.8);
            padding: 20px;
            border-radius: 8px;
            border-left: 4px solid #60a5fa;
            transition: transform 0.3s, border-color 0.3s;
        }
        
        .skill-category:hover {
            transform: translateY(-3px);
            border-left-color: #a78bfa;
        }
        
        .skill-category h3 {
            color: #60a5fa;
            margin-bottom: 12px;
            font-size: 1.1em;
        }
        
        .skill-tags {
            display: flex;
            flex-wrap: wrap;
            gap: 8px;
        }
        
        .tag {
            background: rgba(96, 165, 250, 0.2);
            color: #93c5fd;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.9em;
            border: 1px solid rgba(96, 165, 250, 0.4);
            transition: all 0.3s;
        }
        
        .tag:hover {
            background: rgba(96, 165, 250, 0.3);
            border-color: #60a5fa;
        }
        
        .links-section {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
        }
        
        .link-card {
            background: rgba(30, 41, 59, 0.8);
            padding: 20px;
            border-radius: 8px;
            text-align: center;
            transition: all 0.3s;
            border: 1px solid rgba(148, 163, 184, 0.2);
        }
        
        .link-card:hover {
            background: rgba(30, 41, 59, 0.95);
            border-color: #60a5fa;
            transform: translateY(-2px);
        }
        
        .link-card a {
            color: #60a5fa;
            text-decoration: none;
            font-weight: 600;
        }
        
        .link-card a:hover {
            color: #93c5fd;
        }
        
        .link-label {
            color: #94a3b8;
            font-size: 0.85em;
            margin-bottom: 8px;
        }
        
        .footer {
            background: rgba(15, 23, 42, 0.5);
            padding: 25px 40px;
            text-align: center;
            color: #64748b;
            font-size: 0.9em;
            border-top: 1px solid rgba(148, 163, 184, 0.1);
        }
        
        @media (max-width: 768px) {
            .header {
                padding: 40px 25px;
            }
            
            .header h1 {
                font-size: 2em;
            }
            
            .content {
                padding: 30px 25px;
            }
            
            .contact-links {
                font-size: 0.85em;
                gap: 10px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Header -->
        <div class="header">
            <h1>James Kariuki</h1>
            <p class="title">Cloud & DevOps Engineer | Full-Stack Developer</p>
            <div class="contact-links">
                <a href="mailto:jameikariuki18@gmail.com">✉️ Email</a>
                <a href="https://james-kariuki.vercel.app">🌐 Portfolio</a>
                <a href="https://github.com/jamiekariuki">💻 GitHub</a>
                <a href="https://linkedin.com/in/james-kariuki-devops">🔗 LinkedIn</a>
                <a href="https://medium.com/@jamiekariuki18">📝 Blog</a>
            </div>
        </div>
        
        <!-- Content -->
        <div class="content">
            <!-- About Section -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">👋</span>
                    About Me
                </div>
                <p class="about-text">
                    Cloud & DevOps Engineer and Full-Stack Developer with 3+ years of hands-on experience designing and automating scalable, secure, and highly available infrastructures. I specialize in building CI/CD pipelines, container orchestration, and infrastructure as code while ensuring robust monitoring, logging, and compliance. My focus is on automation, observability, and cost-efficient architectures that enable teams to move fast without compromising stability.
                </p>
            </div>
            
            <!-- Skills Section -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">⚙️</span>
                    Technical Skills
                </div>
                <div class="skills-grid">
                    <div class="skill-category">
                        <h3>☁️ Cloud Platforms</h3>
                        <div class="skill-tags">
                            <span class="tag">AWS</span>
                            <span class="tag">Azure</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>🔄 DevOps & CI/CD</h3>
                        <div class="skill-tags">
                            <span class="tag">Jenkins</span>
                            <span class="tag">GitHub Actions</span>
                            <span class="tag">GitLab CI</span>
                            <span class="tag">ArgoCD</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>📦 Containers & Orchestration</h3>
                        <div class="skill-tags">
                            <span class="tag">Docker</span>
                            <span class="tag">Kubernetes</span>
                            <span class="tag">Helm</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>🏗️ IaC & Configuration</h3>
                        <div class="skill-tags">
                            <span class="tag">Terraform</span>
                            <span class="tag">Ansible</span>
                            <span class="tag">CloudFormation</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>📊 Monitoring & Observability</h3>
                        <div class="skill-tags">
                            <span class="tag">Prometheus</span>
                            <span class="tag">Grafana</span>
                            <span class="tag">ELK Stack</span>
                            <span class="tag">Loki</span>
                            <span class="tag">Jaeger</span>
                            <span class="tag">Tempo</span>
                            <span class="tag">CloudWatch</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>💻 Programming & Scripting</h3>
                        <div class="skill-tags">
                            <span class="tag">Python</span>
                            <span class="tag">JavaScript</span>
                            <span class="tag">TypeScript</span>
                            <span class="tag">Bash</span>
                            <span class="tag">Java</span>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3>🗄️ Databases</h3>
                        <div class="skill-tags">
                            <span class="tag">PostgreSQL</span>
                            <span class="tag">MongoDB</span>
                            <span class="tag">MySQL</span>
                            <span class="tag">DynamoDB</span>
                        </div>
                    </div>
                </div>
            </div>
            
            <!-- Links Section -->
            <div class="section">
                <div class="section-title">
                    <span class="icon">🔗</span>
                    Find Me Online
                </div>
                <div class="links-section">
                    <div class="link-card">
                        <div class="link-label">Personal Portfolio</div>
                        <a href="https://james-kariuki.vercel.app">View My Work</a>
                    </div>
                    <div class="link-card">
                        <div class="link-label">GitHub Projects</div>
                        <a href="https://github.com/jamiekariuki">jamiekariuki</a>
                    </div>
                    <div class="link-card">
                        <div class="link-label">Technical Blog</div>
                        <a href="https://medium.com/@jamiekariuki18">Read Articles</a>
                    </div>
                    <div class="link-card">
                        <div class="link-label">Professional Network</div>
                        <a href="https://linkedin.com/in/james-kariuki-devops">Connect</a>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Footer -->
        <div class="footer">
            <p>📍 Kenya | 📞 +254 719 481 930 | 💌 jameikariuki18@gmail.com</p>
        </div>
    </div>
</body>
</html>
