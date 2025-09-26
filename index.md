---
layout: default
title: Home
---

<section class="hero">
    <div class="hero-content">
        <img src="{{ '/assets/images/image_3.png' | relative_url }}" alt="Yousef Taheri" class="hero-avatar">
        <h1 class="hero-title">Yousef Taheri</h1>
        <p class="hero-subtitle">AI/ML Researcher & Developer</p>
        <p class="hero-description">
            PhD in Responsible AI with expertise in ethical machine learning, compliance automation, 
            and multi-agent systems. Transforming complex ideas into responsible, innovative solutions 
            that bridge the gap between AI research and real-world applications.
        </p>
        <div class="hero-buttons">
            <a href="{{ '/about/' | relative_url }}" class="btn btn-primary">About Me</a>
            <a href="#projects" class="btn btn-secondary">View Projects</a>
            <a href="https://calendly.com/ytaheris/30min" target="_blank" class="btn btn-secondary">Book a Call</a>
        </div>
    </div>
</section>

<section id="projects" class="section">
    <div class="container">
        <h2 class="section-title">Technical Projects</h2>
        <div class="projects-grid">
            <article class="project-card">
                <h3 class="project-title">NovaMart — Demand Forecasting & Stock Optimization</h3>
                <p class="project-description">
                    Time series forecasting with Prophet/ARIMA and inventory optimization logic. 
                    Implements advanced demand prediction algorithms with real-time stock management.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Prophet</span>
                    <span class="tech-tag">ARIMA</span>
                    <span class="tech-tag">Pandas</span>
                    <span class="tech-tag">Plotly</span>
                </div>
                <div class="project-links">
                    <a href="https://novamart.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/novamart-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">StyleHive — Fashion Recommender System</h3>
                <p class="project-description">
                    Product recommendations using association rules and collaborative filtering. 
                    Advanced ML algorithms for personalized fashion recommendations with real-time processing.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Scikit-learn</span>
                    <span class="tech-tag">Apriori</span>
                    <span class="tech-tag">Collaborative Filtering</span>
                </div>
                <div class="project-links">
                    <a href="https://stylehive.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/stylehive-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">InsightBank — Customer Segmentation & Churn Prediction</h3>
                <p class="project-description">
                    Customer clustering with KMeans and churn prediction with ML classifiers. 
                    Comprehensive customer analytics with predictive modeling for retention strategies.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Scikit-learn</span>
                    <span class="tech-tag">KMeans</span>
                    <span class="tech-tag">Logistic Regression</span>
                    <span class="tech-tag">Random Forest</span>
                </div>
                <div class="project-links">
                    <a href="https://insightbank.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/insightbank-churn-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">Roomify — Dynamic Pricing Engine</h3>
                <p class="project-description">
                    Price elasticity modeling and revenue maximization via demand forecasting. 
                    Advanced optimization algorithms for dynamic pricing strategies in hospitality.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Regression Models</span>
                    <span class="tech-tag">Optimization Logic</span>
                </div>
                <div class="project-links">
                    <a href="https://roomify-pricing.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/roomify-pricing-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">TransacGuard — Real-Time Anomaly Detection</h3>
                <p class="project-description">
                    Real-time anomaly detection using Isolation Forest and One-Class SVM. 
                    Advanced streaming analytics for fraud detection and transaction monitoring.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Scikit-learn</span>
                    <span class="tech-tag">Isolation Forest</span>
                    <span class="tech-tag">One-Class SVM</span>
                    <span class="tech-tag">Streaming Simulation</span>
                </div>
                <div class="project-links">
                    <a href="https://transacguard.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/transacguard-anomaly-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">AdOptima — Marketing Campaign Optimizer</h3>
                <p class="project-description">
                    Predictive modeling of sales vs spend and budget reallocation for ROI. 
                    Advanced ML models with SHAP explainability for marketing campaign optimization.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Scikit-learn</span>
                    <span class="tech-tag">Random Forest</span>
                    <span class="tech-tag">XGBoost</span>
                    <span class="tech-tag">SHAP</span>
                </div>
                <div class="project-links">
                    <a href="https://adoptima.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/adoptima-marketing-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">ShiftWise — Workforce Scheduling & Optimization</h3>
                <p class="project-description">
                    Workforce scheduling using linear programming and optimization under constraints. 
                    Advanced OR techniques for optimal staff allocation and scheduling efficiency.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">OR-Tools</span>
                    <span class="tech-tag">PuLP</span>
                    <span class="tech-tag">Linear Programming</span>
                </div>
                <div class="project-links">
                    <a href="https://shiftwise.streamlit.app/" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/shiftwise-scheduling-dashboard" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>

            <article class="project-card">
                <h3 class="project-title">BrandBoost — AI-Powered Marketing Content Generator</h3>
                <p class="project-description">
                    Content generation for product descriptions, social posts, and emails with tone and language control. 
                    Advanced LLM integration with Hugging Face for automated marketing content creation.
                </p>
                <div class="project-tech">
                    <span class="tech-tag">Python</span>
                    <span class="tech-tag">Streamlit</span>
                    <span class="tech-tag">Hugging Face API</span>
                    <span class="tech-tag">Mistral 7B</span>
                    <span class="tech-tag">LLM</span>
                </div>
                <div class="project-links">
                    <a href="https://huggingface.co/spaces/youtah/brandboost-content-generator" target="_blank" class="project-link">Live Demo</a>
                    <a href="https://github.com/heritai/brandboost-content-generator" target="_blank" class="project-link">GitHub</a>
                </div>
            </article>
        </div>
    </div>
</section>

<section class="section">
    <div class="container">
        <h2 class="section-title">Technical Expertise</h2>
        <div class="skills-grid">
            <div class="skill-category">
                <h3>Core Competencies</h3>
                <ul class="skill-list">
                    <li>Machine Learning & Deep Learning</li>
                    <li>Natural Language Processing</li>
                    <li>Large Language Models (LLMs)</li>
                    <li>Agentic AI & Multi-Agent Systems</li>
                    <li>Reinforcement Learning</li>
                    <li>Responsible AI & Ethics</li>
                    <li>Data Analysis & Visualization</li>
                    <li>Knowledge Representation</li>
                </ul>
            </div>
            
            <div class="skill-category">
                <h3>Programming Languages</h3>
                <ul class="skill-list">
                    <li>Python (Advanced)</li>
                    <li>R (Advanced)</li>
                    <li>Java (Intermediate)</li>
                    <li>Prolog (Intermediate)</li>
                    <li>Visual Basic (Intermediate)</li>
                </ul>
            </div>
            
            <div class="skill-category">
                <h3>Frameworks & Libraries</h3>
                <ul class="skill-list">
                    <li>PyTorch & TensorFlow</li>
                    <li>Scikit-learn</li>
                    <li>LangChain & LangGraph</li>
                    <li>NumPy, Pandas, Matplotlib</li>
                    <li>MLflow</li>
                    <li>Gymnasium (RL)</li>
                    <li>Neo4j & Graph Databases</li>
                    <li>Apache Spark</li>
                </ul>
            </div>
            
            <div class="skill-category">
                <h3>Tools & Platforms</h3>
                <ul class="skill-list">
                    <li>AWS (SageMaker, EC2, S3)</li>
                    <li>Tableau & Data Visualization</li>
                    <li>SPSS, Minitab, SAS</li>
                    <li>KNIME</li>
                    <li>Microsoft Office Suite</li>
                    <li>Adobe Creative Suite</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section id="publications" class="section">
    <div class="container">
        <h2 class="section-title">Recent Publications</h2>
        <div class="publications-list">
            <article class="publication-item">
                <h3>Responsible AI in the Cloud: Automating ML Audits on AWS</h3>
                <p class="publication-meta">Medium Blog Post • August 2025</p>
                <p class="publication-description">
                    A comprehensive guide to implementing automated compliance auditing for machine learning 
                    pipelines in cloud environments, focusing on fairness, transparency, and bias detection.
                </p>
                <a href="https://medium.com/p/responsible-ai-in-the-cloud-automating-ml-audits-on-aws-872b761093cb" target="_blank" class="publication-link">Read Article</a>
            </article>
            
            <article class="publication-item">
                <h3>Automatisation de la conformité légale et éthique pour une IA de confiance</h3>
                <p class="publication-meta">Doctoral Thesis • 2024</p>
                <p class="publication-description">
                    Doctoral research on automating legal and ethical compliance for trustworthy AI systems, 
                    supervised by Prof. Jean-Gabriel Ganascia and Dr. Gauvain Bourgne.
                </p>
                <a href="http://theses.fr/2024SORUS225" target="_blank" class="publication-link">View Thesis</a>
            </article>
            
            <article class="publication-item">
                <h3>Modelling integration of responsible AI values for ethical decision making</h3>
                <p class="publication-meta">2nd Workshop on Computational Machine Ethics - KR • 2023</p>
                <p class="publication-description">
                    Research on integrating responsible AI values into automated decision-making systems 
                    for ethical compliance and transparency.
                </p>
                <a href="https://scholar.google.com/citations?user=IN72HckAAAAJ" target="_blank" class="publication-link">View on Scholar</a>
            </article>
        </div>
        <div class="publications-footer">
            <a href="https://scholar.google.com/citations?user=IN72HckAAAAJ" target="_blank" class="btn btn-secondary">View All Publications</a>
        </div>
    </div>
</section>

<section id="contact" class="section">
    <div class="container">
        <h2 class="section-title">Get In Touch</h2>
        <div class="contact-content">
            <div class="contact-info">
                <p>I'm always interested in discussing new opportunities, collaborations, and innovative projects in AI/ML and responsible technology.</p>
                <div class="contact-links">
                    <a href="mailto:contact@youseftaheri.com" class="contact-link">
                        <span>📧</span> contact@youseftaheri.com
                    </a>
                    <a href="https://calendly.com/ytaheris/30min" target="_blank" class="contact-link">
                        <span>📅</span> Schedule a Call
                    </a>
                    <a href="https://linkedin.com/in/yousef-taheri" target="_blank" class="contact-link">
                        <span>💼</span> LinkedIn
                    </a>
                    <a href="https://github.com/heritai" target="_blank" class="contact-link">
                        <span>💻</span> GitHub
                    </a>
                </div>
            </div>
        </div>
    </div>
</section>
