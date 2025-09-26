---
layout: default
title: About
---

<section class="hero">
    <div class="hero-content">
        <h1 class="hero-title">About Me</h1>
        <p class="hero-subtitle">Machine Learning Engineer & AI Researcher</p>
    </div>
</section>

<section class="section">
    <div class="container">
        <div class="about-content">
            <div class="about-image">
                <img src="{{ '/assets/images/image_3.png' | relative_url }}" alt="Yousef Taheri" style="width: 100%; border-radius: 12px; box-shadow: var(--shadow-lg);">
            </div>
            <div class="about-text">
                <h2>Hello, I'm Yousef Taheri</h2>
                <p>
                    I'm a passionate AI/ML researcher and developer with a PhD in Responsible AI, specializing 
                    in ethical machine learning, compliance automation, and multi-agent systems. My journey 
                    in artificial intelligence began with a deep curiosity about how technology can be 
                    developed responsibly and ethically.
                </p>
                
                <p>
                    As a Data Scientist and AI developer, I transform complex ideas into concrete, responsible 
                    solutions. Driven by rigor, curiosity, and impact, I engage in projects that combine 
                    data science with innovation while maintaining the highest ethical standards.
                </p>
                
                <p>
                    My research focuses on automating legal and ethical compliance for trustworthy AI systems. 
                    I believe that the future of AI lies not just in technical advancement, but in ensuring 
                    these systems are fair, transparent, and aligned with human values.
                </p>
                
                <h3>Research Interests</h3>
                <ul class="research-interests">
                    <li><strong>Responsible AI:</strong> Developing frameworks for ethical AI development and deployment</li>
                    <li><strong>Compliance Automation:</strong> Building systems that ensure AI models meet regulatory and ethical standards</li>
                    <li><strong>Multi-Agent Systems:</strong> Creating intelligent agent architectures for complex problem-solving</li>
                    <li><strong>Fairness & Bias Detection:</strong> Implementing automated bias detection and mitigation techniques</li>
                    <li><strong>Explainable AI:</strong> Making AI decision-making processes transparent and interpretable</li>
                </ul>
                
                <h3>Professional Philosophy</h3>
                <p>
                    I believe that technology should serve humanity's best interests. Every AI system I develop 
                    or research I conduct is guided by principles of fairness, transparency, accountability, 
                    and human-centered design. My goal is to bridge the gap between cutting-edge AI research 
                    and practical, responsible applications that benefit society.
                </p>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <h2 class="section-title">Education & Background</h2>
        <div class="timeline">
            <div class="timeline-item">
                <div class="timeline-marker"></div>
                <div class="timeline-content">
                    <h3>PhD in Artificial Intelligence</h3>
                    <p class="timeline-meta">Sorbonne University • 2024</p>
                    <p><strong>Thesis:</strong> "Automatisation de la conformité légale et éthique pour une IA de confiance"</p>
                    <p><strong>Supervisors:</strong> Prof. Jean-Gabriel Ganascia & Dr. Gauvain Bourgne</p>
                    <p>Focused on developing automated compliance mechanisms for trustworthy AI systems, with emphasis on legal and ethical frameworks.</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-marker"></div>
                <div class="timeline-content">
                    <h3>Research & Development</h3>
                    <p class="timeline-meta">2020 - Present</p>
                    <p>Conducted extensive research in responsible AI, multi-agent systems, and compliance automation. Published multiple peer-reviewed papers and developed practical AI solutions.</p>
                </div>
            </div>
            
            <div class="timeline-item">
                <div class="timeline-marker"></div>
                <div class="timeline-content">
                    <h3>Industry Experience</h3>
                    <p class="timeline-meta">2018 - Present</p>
                    <p>Worked on various AI/ML projects spanning cybersecurity, legal compliance, and cloud-based ML operations. Developed expertise in both research and practical implementation.</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <h2 class="section-title">Key Achievements</h2>
        <div class="achievements-grid">
            <div class="achievement-card">
                <div class="achievement-icon">🎓</div>
                <h3>Doctoral Research</h3>
                <p>Completed PhD in Responsible AI with focus on automated compliance for trustworthy AI systems</p>
            </div>
            
            <div class="achievement-card">
                <div class="achievement-icon">📚</div>
                <h3>Publications</h3>
                <p>Multiple peer-reviewed publications in top AI conferences and workshops</p>
            </div>
            
            <div class="achievement-card">
                <div class="achievement-icon">🔬</div>
                <h3>Research Impact</h3>
                <p>Developed novel approaches to AI compliance and ethical decision-making systems</p>
            </div>
            
            <div class="achievement-card">
                <div class="achievement-icon">💻</div>
                <h3>Open Source</h3>
                <p>Contributed to open-source AI projects and developed innovative ML solutions</p>
            </div>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <h2 class="section-title">Let's Connect</h2>
        <div class="contact-section">
            <p>I'm always excited to discuss new opportunities, collaborations, and innovative projects in AI/ML and responsible technology.</p>
            <div class="contact-actions">
                <a href="mailto:contact@youseftaheri.com" class="btn btn-primary">Send Email</a>
                <a href="https://calendly.com/ytaheris/30min" target="_blank" class="btn btn-secondary">Schedule a Call</a>
                <a href="https://linkedin.com/in/yousef-taheri" target="_blank" class="btn btn-secondary">LinkedIn</a>
            </div>
        </div>
    </div>
</section>

<style>
.about-content {
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 3rem;
    align-items: start;
    margin-bottom: 4rem;
}

.research-interests {
    list-style: none;
    padding: 0;
}

.research-interests li {
    margin-bottom: 1rem;
    padding-left: 1rem;
    position: relative;
}

.research-interests li::before {
    content: '▸';
    color: var(--accent-primary);
    position: absolute;
    left: 0;
    font-weight: bold;
}

.timeline {
    position: relative;
    padding-left: 2rem;
}

.timeline::before {
    content: '';
    position: absolute;
    left: 1rem;
    top: 0;
    bottom: 0;
    width: 2px;
    background: var(--gradient-primary);
}

.timeline-item {
    position: relative;
    margin-bottom: 2rem;
}

.timeline-marker {
    position: absolute;
    left: -2.5rem;
    top: 0.5rem;
    width: 1rem;
    height: 1rem;
    background: var(--accent-primary);
    border-radius: 50%;
    border: 3px solid var(--bg-primary);
}

.timeline-content {
    background: var(--bg-card);
    padding: 1.5rem;
    border-radius: var(--radius-lg);
    border: 1px solid rgba(255, 255, 255, 0.1);
}

.timeline-meta {
    color: var(--accent-primary);
    font-weight: 600;
    margin-bottom: 0.5rem;
}

.achievements-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 2rem;
}

.achievement-card {
    background: var(--bg-card);
    padding: 2rem;
    border-radius: var(--radius-lg);
    text-align: center;
    border: 1px solid rgba(255, 255, 255, 0.1);
    transition: var(--transition-normal);
}

.achievement-card:hover {
    transform: translateY(-4px);
    box-shadow: var(--shadow-lg);
}

.achievement-icon {
    font-size: 3rem;
    margin-bottom: 1rem;
}

.contact-section {
    text-align: center;
    max-width: 600px;
    margin: 0 auto;
}

.contact-actions {
    display: flex;
    gap: 1rem;
    justify-content: center;
    flex-wrap: wrap;
    margin-top: 2rem;
}

@media (max-width: 768px) {
    .about-content {
        grid-template-columns: 1fr;
        gap: 2rem;
    }
    
    .timeline {
        padding-left: 1rem;
    }
    
    .timeline-marker {
        left: -1.5rem;
    }
    
    .achievements-grid {
        grid-template-columns: 1fr;
    }
    
    .contact-actions {
        flex-direction: column;
        align-items: center;
    }
}
</style>