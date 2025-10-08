[index.html](https://github.com/user-attachments/files/22758364/index.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Justine - Digital Marketing Manager & Lead Generation Specialist</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
            line-height: 1.6;
            color: #2c3e50;
        }
        
        /* Hero Section */
        .hero {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 120px 20px 80px;
            text-align: center;
        }
        
        .hero h1 {
            font-size: 3em;
            margin-bottom: 20px;
            font-weight: 700;
        }
        
        .hero p {
            font-size: 1.3em;
            margin-bottom: 30px;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            opacity: 0.95;
        }
        
        .hero .cta-buttons {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
        }
        
        .btn {
            padding: 15px 35px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: 600;
            transition: transform 0.3s, box-shadow 0.3s;
            display: inline-block;
        }
        
        .btn-primary {
            background: white;
            color: #667eea;
        }
        
        .btn-secondary {
            background: transparent;
            color: white;
            border: 2px solid white;
        }
        
        .btn:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }
        
        /* Stats Section */
        .stats {
            background: #f8f9fa;
            padding: 60px 20px;
            text-align: center;
        }
        
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 40px;
            max-width: 1000px;
            margin: 0 auto;
        }
        
        .stat-item h3 {
            font-size: 2.5em;
            color: #667eea;
            margin-bottom: 10px;
        }
        
        .stat-item p {
            color: #6c757d;
            font-size: 1.1em;
        }
        
        /* About Section */
        .about {
            padding: 80px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .about h2 {
            font-size: 2.5em;
            margin-bottom: 30px;
            text-align: center;
            color: #2c3e50;
        }
        
        .about-content {
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.1em;
            line-height: 1.8;
            color: #495057;
        }
        
        /* Services Section */
        .services {
            background: #f8f9fa;
            padding: 80px 20px;
        }
        
        .services h2 {
            font-size: 2.5em;
            margin-bottom: 50px;
            text-align: center;
            color: #2c3e50;
        }
        
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .service-card {
            background: white;
            padding: 35px;
            border-radius: 12px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
            transition: transform 0.3s, box-shadow 0.3s;
        }
        
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 30px rgba(0,0,0,0.15);
        }
        
        .service-card h3 {
            font-size: 1.5em;
            margin-bottom: 15px;
            color: #667eea;
        }
        
        .service-card ul {
            list-style: none;
            padding-left: 0;
        }
        
        .service-card li {
            padding: 8px 0;
            padding-left: 25px;
            position: relative;
        }
        
        .service-card li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
        }
        
        /* Case Studies Section */
        .case-studies {
            padding: 80px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .case-studies h2 {
            font-size: 2.5em;
            margin-bottom: 50px;
            text-align: center;
            color: #2c3e50;
        }
        
        .case-study {
            background: white;
            border-radius: 12px;
            padding: 40px;
            margin-bottom: 40px;
            box-shadow: 0 5px 20px rgba(0,0,0,0.08);
        }
        
        .case-study h3 {
            font-size: 1.8em;
            color: #667eea;
            margin-bottom: 15px;
        }
        
        .case-study .company {
            color: #6c757d;
            font-size: 1.1em;
            margin-bottom: 20px;
        }
        
        .case-study .results {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            margin-top: 25px;
            padding-top: 25px;
            border-top: 2px solid #f8f9fa;
        }
        
        .result-item {
            text-align: center;
        }
        
        .result-item strong {
            display: block;
            font-size: 1.8em;
            color: #667eea;
            margin-bottom: 5px;
        }
        
        .result-item span {
            color: #6c757d;
        }
        
        /* Testimonials Section */
        .testimonials {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 80px 20px;
        }
        
        .testimonials h2 {
            font-size: 2.5em;
            margin-bottom: 50px;
            text-align: center;
        }
        
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .testimonial-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 12px;
            border: 1px solid rgba(255,255,255,0.2);
        }
        
        .testimonial-card p {
            font-style: italic;
            margin-bottom: 20px;
            font-size: 1.05em;
            line-height: 1.7;
        }
        
        .testimonial-author {
            font-weight: 600;
            font-style: normal;
        }
        
        .testimonial-title {
            font-size: 0.9em;
            opacity: 0.9;
        }
        
        /* Pricing Section */
        .pricing {
            padding: 80px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        .pricing h2 {
            font-size: 2.5em;
            margin-bottom: 50px;
            text-align: center;
            color: #2c3e50;
        }
        
        .pricing-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .pricing-card {
            background: white;
            border: 2px solid #e9ecef;
            border-radius: 12px;
            padding: 40px;
            text-align: center;
            transition: border-color 0.3s, box-shadow 0.3s;
        }
        
        .pricing-card:hover {
            border-color: #667eea;
            box-shadow: 0 10px 30px rgba(102, 126, 234, 0.15);
        }
        
        .pricing-card h3 {
            font-size: 1.8em;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .price {
            font-size: 2.5em;
            color: #667eea;
            font-weight: 700;
            margin-bottom: 10px;
        }
        
        .price-note {
            color: #6c757d;
            margin-bottom: 30px;
        }
        
        .pricing-card ul {
            list-style: none;
            text-align: left;
            margin-bottom: 30px;
        }
        
        .pricing-card li {
            padding: 10px 0;
            padding-left: 30px;
            position: relative;
        }
        
        .pricing-card li:before {
            content: "✓";
            position: absolute;
            left: 0;
            color: #667eea;
            font-weight: bold;
            font-size: 1.2em;
        }
        
        /* CTA Section */
        .cta-section {
            background: #f8f9fa;
            padding: 80px 20px;
            text-align: center;
        }
        
        .cta-section h2 {
            font-size: 2.5em;
            margin-bottom: 20px;
            color: #2c3e50;
        }
        
        .cta-section p {
            font-size: 1.2em;
            margin-bottom: 30px;
            color: #6c757d;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }
        
        /* Footer */
        footer {
            background: #2c3e50;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        
        footer p {
            margin-bottom: 15px;
        }
        
        footer a {
            color: #667eea;
            text-decoration: none;
        }
        
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2em;
            }
            
            .hero p {
                font-size: 1.1em;
            }
            
            .stats-grid {
                grid-template-columns: 1fr 1fr;
            }
        }
    </style>
</head>
<body>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Digital Marketing Manager & Lead Generation Specialist</h1>
        <p>I help B2B companies generate qualified leads, close high-value deals, and grow their online presence through proven digital marketing systems.</p>
        <div class="cta-buttons">
            <a href="#contact" class="btn btn-primary">Hire Me</a>
            <a href="#case-studies" class="btn btn-secondary">View My Work</a>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
        <div class="stats-grid">
            <div class="stat-item">
                <h3>800+</h3>
                <p>Qualified Leads Generated</p>
            </div>
            <div class="stat-item">
                <h3>4+</h3>
                <p>Years Experience</p>
            </div>
            <div class="stat-item">
                <h3>30+</h3>
                <p>Sales Calls Booked</p>
            </div>
            <div class="stat-item">
                <h3>300K</h3>
                <p>Social Media Views</p>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section class="about">
        <h2>About Me</h2>
        <div class="about-content">
            <p>I'm Justine, a digital marketing manager and lead generation specialist with 4+ years of experience helping B2B companies grow through strategic online marketing.</p>
            
            <p>My expertise spans <strong>LinkedIn lead generation, social media management, paid advertising, e-commerce management, and content creation</strong>. I've worked with construction companies, service agencies, e-commerce brands, and local businesses—generating over 800 qualified leads, closing high-value deals, and creating viral content that drives real business results.</p>
            
            <p>What sets me apart: I don't just execute tactics—I build <strong>systems that deliver measurable outcomes</strong>. Whether it's generating 500+ leads through LinkedIn outreach, creating a viral video with 300K views, or managing complex marketing campaigns across multiple platforms, I focus on what actually moves the needle for your business.</p>
            
            <p><strong>Currently available for contract work</strong> (hourly or retainer-based) with companies that value results-driven marketing.</p>
        </div>
    </section>

    <!-- Services Section -->
    <section class="services">
        <h2>What I Do</h2>
        <div class="services-grid">
            <div class="service-card">
                <h3>Lead Generation</h3>
                <ul>
                    <li>LinkedIn outreach & prospecting</li>
                    <li>Sales Navigator lead mining</li>
                    <li>CRM & pipeline management</li>
                    <li>Qualified call booking</li>
                    <li>Follow-up sequences</li>
                </ul>
            </div>
            
            <div class="service-card">
                <h3>Social Media Management</h3>
                <ul>
                    <li>Content strategy & creation</li>
                    <li>Multi-platform management</li>
                    <li>Community engagement</li>
                    <li>Brand building & awareness</li>
                    <li>Viral content creation</li>
                </ul>
            </div>
            
            <div class="service-card">
                <h3>Paid Advertising</h3>
                <ul>
                    <li>Meta Ads (Facebook/Instagram)</li>
                    <li>Campaign strategy & setup</li>
                    <li>Ad creative design</li>
                    <li>Performance optimization</li>
                    <li>ROI tracking & reporting</li>
                </ul>
            </div>
            
            <div class="service-card">
                <h3>E-commerce Management</h3>
                <ul>
                    <li>Shopify store management</li>
                    <li>Product listing optimization</li>
                    <li>Sales funnel development</li>
                    <li>Email marketing campaigns</li>
                    <li>Conversion optimization</li>
                </ul>
            </div>
            
            <div class="service-card">
                <h3>Brand & Content Strategy</h3>
                <ul>
                    <li>Brand positioning & messaging</li>
                    <li>Content calendar planning</li>
                    <li>Graphic design & visuals</li>
                    <li>Video content creation</li>
                    <li>Copywriting & storytelling</li>
                </ul>
            </div>
            
            <div class="service-card">
                <h3>Client Relations & Growth</h3>
                <ul>
                    <li>Client onboarding & retention</li>
                    <li>Relationship management</li>
                    <li>Performance reporting</li>
                    <li>Strategic consultation</li>
                    <li>Growth planning & execution</li>
                </ul>
            </div>
        </div>
    </section>

    <!-- Case Studies Section -->
    <section id="case-studies" class="case-studies">
        <h2>Proven Results</h2>
        
        <div class="case-study">
            <h3>Social Concierge Agency - LinkedIn Lead Generation</h3>
            <p class="company">Startachat Social Concierge (Service Agency) | 12 Months</p>
            <p>Executed comprehensive LinkedIn outreach campaign targeting high-value clients for a social concierge agency. Managed lead generation, client relations, and brand positioning across digital platforms.</p>
            <div class="results">
                <div class="result-item">
                    <strong>500+</strong>
                    <span>Qualified Leads</span>
                </div>
                <div class="result-item">
                    <strong>20+</strong>
                    <span>Sales Calls Booked</span>
                </div>
                <div class="result-item">
                    <strong>10</strong>
                    <span>Clients Closed</span>
                </div>
                <div class="result-item">
                    <strong>3</strong>
                    <span>Personally Managed</span>
                </div>
            </div>
        </div>
        
        <div class="case-study">
            <h3>Construction Company - From Zero to Government Contracts</h3>
            <p class="company">Mana Civil (Civil Construction) | 12 Months</p>
            <p>Built LinkedIn presence from scratch for a civil construction company with zero online visibility. Implemented strategic outreach, content creation, and relationship-building systems that secured major projects including government contracts.</p>
            <div class="results">
                <div class="result-item">
                    <strong>300+</strong>
                    <span>Qualified Leads</span>
                </div>
                <div class="result-item">
                    <strong>500+</strong>
                    <span>Connections Built</span>
                </div>
                <div class="result-item">
                    <strong>1</strong>
                    <span>Gov't Contract</span>
                </div>
                <div class="result-item">
                    <strong>90 Days</strong>
                    <span>To First Results</span>
                </div>
            </div>
        </div>
        
        <div class="case-study">
            <h3>Cultural Clothing Brand - Viral Social Media Growth</h3>
            <p class="company">Local Cultural Clothing Manufacturer | 6 Months</p>
            <p>Built social media presence from ground up for a cultural clothing manufacturer. Created content strategy, designed visuals, and managed community engagement that led to viral growth and increased sales.</p>
            <div class="results">
                <div class="result-item">
                    <strong>300K</strong>
                    <span>Video Views</span>
                </div>
                <div class="result-item">
                    <strong>Bulk Orders</strong>
                    <span>Generated</span>
                </div>
                <div class="result-item">
                    <strong>1 Week</strong>
                    <span>To Go Viral</span>
                </div>
                <div class="result-item">
                    <strong>Sales Increased</strong>
                    <span>Measurably</span>
                </div>
            </div>
        </div>
        
        <div class="case-study">
            <h3>E-commerce Brand - Shopify & Meta Ads</h3>
            <p class="company">E-commerce Brand | 1 Month Project</p>
            <p>Managed Shopify store operations, launched Meta advertising campaigns, and built social media presence across multiple platforms for an e-commerce brand launching new products.</p>
            <div class="results">
                <div class="result-item">
                    <strong>Meta Ads</strong>
                    <span>Launched</span>
                </div>
                <div class="result-item">
                    <strong>Shopify</strong>
                    <span>Managed</span>
                </div>
                <div class="result-item">
                    <strong>Multi-Platform</strong>
                    <span>Social Media</span>
                </div>
                <div class="result-item">
                    <strong>30 Days</strong>
                    <span>Fast Execution</span>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="testimonials">
        <h2>What Clients Say</h2>
        <div class="testimonials-grid">
            <div class="testimonial-card">
                <p>"Thank you so much for all your hard work and creativity, we are so grateful to have you on our team and I am really looking forward to being more involved again next year! We finally won a big project so 2025 is looking up!!"</p>
                <p class="testimonial-author">Louise Sullivan Forde</p>
                <p class="testimonial-title">Director, Mana Civil Pty Ltd</p>
            </div>
            
            <div class="testimonial-card">
                <p>"I was very pleased to see your work on the LinkedIn space. Your constant work there is beginning to bare fruit. You will be happy to know we are in talks with potential new clients due to your work there."</p>
                <p class="testimonial-author">Craig Norman</p>
                <p class="testimonial-title">Managing Director, Mana Civil Pty Ltd</p>
            </div>
            
            <div class="testimonial-card">
                <p>"Just spoke with them, they said it all looks good! WELL DONE! Thanks so much for a huge effort to get it across the line!"</p>
                <p class="testimonial-author">Louise Sullivan Forde</p>
                <p class="testimonial-title">Director, Mana Civil Pty Ltd</p>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section class="pricing">
        <h2>Working Together</h2>
        <div class="pricing-grid">
            <div class="pricing-card">
                <h3>Hourly Rate</h3>
                <div class="price">$10/hr</div>
                <p class="price-note">Flexible hours, perfect for project-based work</p>
                <ul>
                    <li>Minimum 10 hours/week</li>
                    <li>Weekly time tracking</li>
                    <li>Flexible scheduling</li>
                    <li>Easy to scale up/down</li>
                    <li>Perfect for testing fit</li>
                </ul>
                <a href="#contact" class="btn btn-primary">Get Started</a>
            </div>
            
            <div class="pricing-card">
                <h3>Part-Time Retainer</h3>
                <div class="price">$800/mo</div>
                <p class="price-note">20 hours/week dedicated support</p>
                <ul>
                    <li>80 hours per month</li>
                    <li>Priority support</li>
                    <li>Weekly check-ins</li>
                    <li>Consistent availability</li>
                    <li>Monthly reporting</li>
                </ul>
                <a href="#contact" class="btn btn-primary">Get Started</a>
            </div>
            
            <div class="pricing-card">
                <h3>Full-Time Dedicated</h3>
                <div class="price">$1,500/mo</div>
                <p class="price-note">40 hours/week, your dedicated marketing manager</p>
                <ul>
                    <li>160 hours per month</li>
                    <li>Daily availability</li>
                    <li>Strategic planning included</li>
                    <li>Comprehensive reporting</li>
                    <li>Full marketing support</li>
                </ul>
                <a href="#contact" class="btn btn-primary">Get Started</a>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section id="contact" class="cta-section">
        <h2>Ready to Grow Your Business?</h2>
        <p>Let's discuss how I can help you generate more leads, close more deals, and build a stronger online presence.</p>
        <div class="cta-buttons">
            <a href="mailto:your.email@example.com" class="btn btn-primary">Email Me</a>
            <a href="https://linkedin.com/in/yourprofile" class="btn btn-secondary">Connect on LinkedIn</a>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p><strong>Justine</strong> - Digital Marketing Manager & Lead Generation Specialist</p>
        <p>Available for contract work | Based in Philippines</p>
        <p><a href="mailto:your.email@example.com">your.email@example.com</a> | <a href="https://linkedin.com/in/yourprofile">LinkedIn</a></p>
        <p style="margin-top: 20px; font-size: 0.9em; opacity: 0.8;">&copy; 2025 All Rights Reserved</p>
    </footer>

</body>
</html>
