<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luis Antonio Santiago-Ramirez - GISP Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        .hero-section {
            background: linear-gradient(135deg, #0066cc, #004499);
            min-height: 70vh;
        }
        .stat-card {
            background: rgba(255,255,255,0.1);
            border-radius: 10px;
            padding: 20px;
            margin: 10px;
        }
        .alert-lg {
            padding: 2rem;
            font-size: 1.1rem;
        }
        .progress {
            height: 20px;
        }
        .btn-group .btn {
            margin: 5px;
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-primary">
        <div class="container">
            <a class="navbar-brand" href="#"><i class="fas fa-map-marked-alt"></i> Luis A. Santiago-Ramirez</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <div class="navbar-nav ms-auto">
                    <a class="nav-link" href="#home">Home</a>
                    <a class="nav-link" href="#gisp-ready">GISP Ready</a>
                    <a class="nav-link" href="#projects">Projects</a>
                    <a class="nav-link" href="#contact">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-section text-white py-5">
        <div class="container text-center">
            <h1 class="display-4 fw-bold mb-3">Luis Antonio Santiago-Ramirez</h1>
            <h2 class="h3 mb-4">Senior GIS Analyst & Data Scientist</h2>
            
            <!-- GISP Status Badge -->
            <div class="row justify-content-center mb-4">
                <div class="col-md-10">
                    <div class="alert alert-success alert-lg border-0 shadow">
                        <h4><i class="fas fa-certificate me-2"></i>GISP Certification Ready</h4>
                        <p class="mb-2"><strong>All Requirements Met - Exam Scheduled Fall 2025</strong></p>
                        <div class="progress mb-2">
                            <div class="progress-bar bg-success" style="width: 100%">100% Complete</div>
                        </div>
                        <small>✓ Education: 4+ points | ✓ Experience: 6+ points | ✓ Contributions: 2+ points</small>
                    </div>
                </div>
            </div>

            <p class="lead mb-4">6+ Years Utility GIS Experience | Environmental Justice Analytics | Emergency Response Specialist</p>
            
            <!-- Stats Cards -->
            <div class="row text-center mb-4">
                <div class="col-md-3">
                    <div class="stat-card">
                        <h3 class="display-6">6+</h3>
                        <p>Years GIS Experience</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="stat-card">
                        <h3 class="display-6">$2.3M</h3>
                        <p>Savings Identified</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="stat-card">
                        <h3 class="display-6">100%</h3>
                        <p>ML Model Accuracy</p>
                    </div>
                </div>
                <div class="col-md-3">
                    <div class="stat-card">
                        <h3 class="display-6">15</h3>
                        <p>Priority Areas Identified</p>
                    </div>
                </div>
            </div>

            <!-- Action Buttons -->
            <div class="btn-group-vertical btn-group-lg" role="group">
                <a href="#gisp-ready" class="btn btn-light btn-lg mb-2">
                    <i class="fas fa-certificate me-2"></i>GISP Qualifications
                </a>
                <a href="#projects" class="btn btn-outline-light btn-lg mb-2">
                    <i class="fas fa-folder-open me-2"></i>View Projects
                </a>
                <a href="https://github.com/SantRamLAnt" class="btn btn-outline-light btn-lg">
                    <i class="fab fa-github me-2"></i>GitHub Profile
                </a>
            </div>
        </div>
    </section>

    <!-- GISP Ready Section -->
    <section id="gisp-ready" class="py-5 bg-light">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center mb-5">
                    <h2 class="display-5 fw-bold">GISP Certification Readiness</h2>
                    <p class="lead">All qualification requirements exceeded - exam scheduled for Fall 2025</p>
                </div>
            </div>
            
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card h-100 border-success">
                        <div class="card-header bg-success text-white">
                            <h5><i class="fas fa-graduation-cap me-2"></i>Education: 4+ Points</h5>
                        </div>
                        <div class="card-body">
                            <h6>Bachelor of Science - Geography</h6>
                            <p>Westfield State University (2019)</p>
                            <ul class="list-unstyled">
                                <li>✓ Regional Planning Major</li>
                                <li>✓ GIS Minor</li>
                                <li>✓ Spatial Analysis Focus</li>
                            </ul>
                            <hr>
                            <h6>Additional Education</h6>
                            <p>Master of Engineering - Computer Engineering<br>
                            <small>Dartmouth College (Spring 2026)</small></p>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="card h-100 border-success">
                        <div class="card-header bg-success text-white">
                            <h5><i class="fas fa-briefcase me-2"></i>Experience: 6+ Points</h5>
                        </div>
                        <div class="card-body">
                            <h6>Eversource Energy (2023-Present)</h6>
                            <p>GIS Associate Technician</p>
                            <ul class="list-unstyled">
                                <li>✓ Utility Infrastructure Analysis</li>
                                <li>✓ Emergency Response Support</li>
                                <li>✓ Advanced Analytics Projects</li>
                            </ul>
                            <hr>
                            <h6>Previous Experience</h6>
                            <ul class="list-unstyled">
                                <li>• GIS Analyst (2021-2023)</li>
                                <li>• Construction Inspector (2020-2021)</li>
                                <li>• GIS Intern (2019)</li>
                            </ul>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-4 mb-4">
                    <div class="card h-100 border-success">
                        <div class="card-header bg-success text-white">
                            <h5><i class="fas fa-star me-2"></i>Contributions: 2+ Points</h5>
                        </div>
                        <div class="card-body">
                            <h6>Professional Innovation</h6>
                            <ul class="list-unstyled">
                                <li>✓ Open Source GIS Projects</li>
                                <li>✓ Environmental Justice Analytics</li>
                                <li>✓ Technical Training & Mentorship</li>
                                <li>✓ FAA Part 107 Drone License</li>
                            </ul>
                            <hr>
                            <h6>Key Projects</h6>
                            <ul class="list-unstyled">
                                <li>• PowerGrid Vulnerability Analysis</li>
                                <li>• Grid Asset Predictive Maintenance</li>
                                <li>• Emergency Response Systems</li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="py-5">
        <div class="container">
            <div class="row">
                <div class="col-lg-12 text-center mb-5">
                    <h2 class="display-5 fw-bold">Featured Projects</h2>
                    <p class="lead">Demonstrating GISP-level technical expertise and professional impact</p>
                </div>
            </div>
            
            <div class="row">
                <div class="col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h5 class="card-title">PowerGrid Vulnerability Analysis</h5>
                            <h6 class="card-subtitle mb-2 text-muted">Climate Resilience & Environmental Justice</h6>
                            <p class="card-text">Comprehensive GIS analytics platform examining power grid infrastructure vulnerability in environmental justice communities across Massachusetts.</p>
                            <ul class="list-unstyled">
                                <li><strong>Technologies:</strong> Python, ArcGIS Pro, PostGIS</li>
                                <li><strong>Impact:</strong> $2.3M potential savings identified</li>
                                <li><strong>Scope:</strong> 67% of EJ communities analyzed</li>
                            </ul>
                            <a href="https://github.com/SantRamLAnt/PowerGrid-Vulnerability-Analysis" class="btn btn-primary">
                                <i class="fab fa-github me-2"></i>View Project
                            </a>
                        </div>
                    </div>
                </div>
                
                <div class="col-md-6 mb-4">
                    <div class="card h-100">
                        <div class="card-body">
                            <h5 class="card-title">Grid Asset Predictive Maintenance</h5>
                            <h6 class="card-subtitle mb-2 text-muted">Machine Learning for Infrastructure</h6>
                            <p class="card-text">Random Forest model achieving 100% recall for failure prediction across electrical grid assets using advanced analytics.</p>
                            <ul class="list-unstyled">
                                <li><strong>Technologies:</strong> Python, Azure ML, Power BI</li>
                                <li><strong>Accuracy:</strong> 100% recall for failure prediction</li>
                                <li><strong>Scale:</strong> 9,000+ sensor readings analyzed</li>
                            </ul>
                            <a href="https://github.com/SantRamLAnt/grid-asset-predictive-maintenance" class="btn btn-primary">
                                <i class="fab fa-github me-2"></i>View Project
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-5 bg-primary text-white">
        <div class="container text-center">
            <h2 class="display-5 fw-bold mb-4">Professional Contact</h2>
            <p class="lead mb-4">GISP-Ready Professional Available for Advanced GIS Opportunities</p>
            
            <div class="row justify-content-center">
                <div class="col-md-8">
                    <div class="row">
                        <div class="col-md-6 mb-3">
                            <i class="fas fa-map-marker-alt fa-2x mb-2"></i>
                            <h5>Location</h5>
                            <p>Springfield, Massachusetts<br>Available for MA/CT/NH travel</p>
                        </div>
                        <div class="col-md-6 mb-3">
                            <i class="fas fa-certificate fa-2x mb-2"></i>
                            <h5>GISP Status</h5>
                            <p>All requirements met<br>Exam scheduled Fall 2025</p>
                        </div>
                    </div>
                    
                    <div class="mt-4">
                        <a href="https://www.linkedin.com/in/luisantoniosantiago-ramirez70b418196" class="btn btn-outline-light btn-lg me-3">
                            <i class="fab fa-linkedin me-2"></i>LinkedIn
                        </a>
                        <a href="https://github.com/SantRamLAnt" class="btn btn-outline-light btn-lg">
                            <i class="fab fa-github me-2"></i>GitHub
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Bootstrap JS -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
