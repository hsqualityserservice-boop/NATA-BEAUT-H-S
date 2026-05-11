# NATA-BEAUT-H-S
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mery Key | Institut de Beauté & Espace Pro - Genève</title>
    <meta name="description" content="Mery Key - Institut de beauté à Genève : onglerie, massage, épilation à la cire. Location de cabines pour professionnelles. Salles de réunion.">
    <link rel="stylesheet" href="css/style.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Lato:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Navigation -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <a href="index.html" class="logo">
                <span class="logo-main">Mery Key</span>
                <span class="logo-sub">Institut de Beauté & Espace Pro</span>
            </a>
            <button class="nav-toggle" id="navToggle" aria-label="Menu">
                <span></span>
                <span></span>
                <span></span>
            </button>
            <ul class="nav-menu" id="navMenu">
                <li><a href="#accueil" class="nav-link active">Accueil</a></li>
                <li><a href="#services" class="nav-link">Nos Services</a></li>
                <li><a href="#galerie" class="nav-link">Galerie</a></li>
                <li><a href="#equipe" class="nav-link">L'Équipe</a></li>
                <li><a href="#espace-pro" class="nav-link">Espace Pro</a></li>
                <li><a href="#salles" class="nav-link">Salles de Réunion</a></li>
                <li><a href="#avis" class="nav-link">Avis</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
                <li><a href="pages/reservation.html" class="btn-reserver-nav">Réserver</a></li>
            </ul>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="accueil" class="hero">
        <div class="hero-overlay"></div>
        <div class="hero-content">
            <h1 class="hero-title">Mery Key</h1>
            <p class="hero-subtitle">Votre sanctuaire de beauté au cœur de Genève</p>
            <p class="hero-desc">Onglerie · Massage · Épilation à la cire · Location d'espaces professionnels</p>
            <div class="hero-buttons">
                <a href="pages/reservation.html" class="btn btn-primary">
                    <i class="fas fa-calendar-check"></i> Réserver un soin
                </a>
                <a href="#espace-pro" class="btn btn-secondary">
                    <i class="fas fa-briefcase"></i> Espace Professionnel
                </a>
            </div>
            <div class="hero-features">
                <div class="feature-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>Genève, Suisse</span>
                </div>
                <div class="feature-item">
                    <i class="fas fa-clock"></i>
                    <span>Lun-Sam : 9h-19h</span>
                </div>
                <div class="feature-item">
                    <i class="fas fa-star"></i>
                    <span>4.9/5 - 120+ avis</span>
                </div>
            </div>
        </div>
        <div class="hero-scroll">
            <a href="#services"><i class="fas fa-chevron-down"></i></a>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="services">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Nos Prestations</span>
                <h2 class="section-title">Des soins sur mesure</h2>
                <p class="section-desc">Des professionnelles expérimentées vous accueillent dans un cadre chaleureux et raffiné</p>
            </div>
            
            <div class="services-grid">
                <!-- Onglerie -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-hand-sparkles"></i>
                    </div>
                    <h3>Onglerie</h3>
                    <p class="service-desc">Manucure, pose de gel, nail art, soins des mains et des pieds</p>
                    <ul class="service-list">
                        <li><span>Manucure classique</span><span>35 CHF</span></li>
                        <li><span>Pose gel (mains)</span><span>65 CHF</span></li>
                        <li><span>Pose gel + nail art</span><span>85 CHF</span></li>
                        <li><span>Pédicure spa</span><span>55 CHF</span></li>
                        <li><span>Remplissage gel</span><span>50 CHF</span></li>
                    </ul>
                    <a href="pages/reservation.html?service=onglerie" class="btn-service">Réserver <i class="fas fa-arrow-right"></i></a>
                </div>

                <!-- Massage -->
                <div class="service-card featured">
                    <div class="service-badge">Populaire</div>
                    <div class="service-icon">
                        <i class="fas fa-spa"></i>
                    </div>
                    <h3>Massage</h3>
                    <p class="service-desc">Massages relaxants, drainants et thérapeutiques par des praticiennes certifiées</p>
                    <ul class="service-list">
                        <li><span>Massage relaxant (30min)</span><span>55 CHF</span></li>
                        <li><span>Massage relaxant (60min)</span><span>95 CHF</span></li>
                        <li><span>Massage aux pierres chaudes</span><span>120 CHF</span></li>
                        <li><span>Massage drainant</span><span>110 CHF</span></li>
                        <li><span>Massage dos & épaules</span><span>70 CHF</span></li>
                    </ul>
                    <a href="pages/reservation.html?service=massage" class="btn-service">Réserver <i class="fas fa-arrow-right"></i></a>
                </div>

                <!-- Épilation -->
                <div class="service-card">
                    <div class="service-icon">
                        <i class="fas fa-sun"></i>
                    </div>
                    <h3>Épilation à la Cire</h3>
                    <p class="service-desc">Épilation traditionnelle à la cire chaude pour une peau douce et satinée</p>
                    <ul class="service-list">
                        <li><span>Maillot intégral</span><span>45 CHF</span></li>
                        <li><span>Demi-jambes</span><span>35 CHF</span></li>
                        <li><span>Jambes complètes</span><span>55 CHF</span></li>
                        <li><span>Aisselles</span><span>20 CHF</span></li>
                        <li><span>Sourcils</span><span>15 CHF</span></li>
                        <li><span>Visage complet</span><span>35 CHF</span></li>
                    </ul>
                    <a href="pages/reservation.html?service=epilation" class="btn-service">Réserver <i class="fas fa-arrow-right"></i></a>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="stats">
        <div class="container">
            <div class="stats-grid">
                <div class="stat-item">
                    <span class="stat-number" data-count="500">0</span>
                    <span class="stat-suffix">+</span>
                    <p>Clientes satisfaites</p>
                </div>
                <div class="stat-item">
                    <span class="stat-number" data-count="3">0</span>
                    <p>Professionnelles</p>
                </div>
                <div class="stat-item">
                    <span class="stat-number" data-count="120">0</span>
                    <span class="stat-suffix">+</span>
                    <p>Avis 5 étoiles</p>
                </div>
                <div class="stat-item">
                    <span class="stat-number" data-count="5">0</span>
                    <p>Années d'expérience</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Galerie Section -->
    <section id="galerie" class="galerie">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Nos Réalisations</span>
                <h2 class="section-title">Galerie</h2>
                <p class="section-desc">Découvrez l'expertise de nos professionnelles</p>
            </div>
            
            <div class="gallery-filters">
                <button class="filter-btn active" data-filter="all">Tout</button>
                <button class="filter-btn" data-filter="ongles">Onglerie</button>
                <button class="filter-btn" data-filter="massage">Massage</button>
                <button class="filter-btn" data-filter="epilation">Épilation</button>
                <button class="filter-btn" data-filter="salon">Le Salon</button>
            </div>
            
            <div class="gallery-grid">
                <div class="gallery-item" data-category="ongles">
                    <div class="gallery-placeholder ongles">
                        <i class="fas fa-hand-sparkles"></i>
                        <span>Nail Art Floral</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>Nail Art Floral</h4>
                        <p>Pose gel + décoration florale</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="ongles">
                    <div class="gallery-placeholder ongles">
                        <i class="fas fa-hand-sparkles"></i>
                        <span>French Manucure</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>French Élégante</h4>
                        <p>Classique intemporelle</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="massage">
                    <div class="gallery-placeholder massage">
                        <i class="fas fa-spa"></i>
                        <span>Massage Pierres Chaudes</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>Massage Pierres Chaudes</h4>
                        <p>Détente profonde</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="epilation">
                    <div class="gallery-placeholder epilation">
                        <i class="fas fa-sun"></i>
                        <span>Épilation Maillot</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>Épilation Maillot</h4>
                        <p>Cire chaude premium</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="salon">
                    <div class="gallery-placeholder salon">
                        <i class="fas fa-store"></i>
                        <span>Notre Cabine Onglerie</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>Cabine Onglerie</h4>
                        <p>Espace lumineux et équipé</p>
                    </div>
                </div>
                <div class="gallery-item" data-category="salon">
                    <div class="gallery-placeholder salon">
                        <i class="fas fa-store"></i>
                        <span>Salle de Massage</span>
                    </div>
                    <div class="gallery-overlay">
                        <h4>Salle de Massage</h4>
                        <p>Ambiance zen et apaisante</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Équipe Section -->
    <section id="equipe" class="equipe">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Notre Équipe</span>
                <h2 class="section-title">Les Professionnelles</h2>
                <p class="section-desc">Des expertes passionnées à votre service</p>
            </div>
            
            <div class="team-grid">
                <!-- Manager -->
                <div class="team-card manager">
                    <div class="team-photo manager-photo">
                        <i class="fas fa-user-tie"></i>
                    </div>
                    <div class="team-info">
                        <h3>Mery</h3>
                        <span class="team-role">Fondatrice & Manager</span>
                        <p>Cheffe de projets et responsable d'équipe, Mery a créé Mery Key pour offrir un espace de beauté collaboratif et chaleureux à Genève.</p>
                        <div class="team-social">
                            <a href="#"><i class="fab fa-instagram"></i></a>
                            <a href="#"><i class="fab fa-facebook"></i></a>
                        </div>
                    </div>
                </div>

                <!-- Professionnelle 1 - Onglerie -->
                <div class="team-card">
                    <div class="team-photo">
                        <i class="fas fa-hand-sparkles"></i>
                    </div>
                    <div class="team-info">
                        <h3>Sophie</h3>
                        <span class="team-role">Experte Onglerie</span>
                        <p>Spécialiste en nail art et poses gel. 8 ans d'expérience. Formée aux dernières techniques tendance.</p>
                        <div class="team-tags">
                            <span>Gel</span>
                            <span>Nail Art</span>
                            <span>Manucure</span>
                        </div>
                        <a href="pages/reservation.html?pro=sophie" class="btn-team">Prendre RDV</a>
                    </div>
                </div>

                <!-- Professionnelle 2 - Onglerie -->
                <div class="team-card">
                    <div class="team-photo">
                        <i class="fas fa-hand-sparkles"></i>
                    </div>
                    <div class="team-info">
                        <h3>Emma</h3>
                        <span class="team-role">Experte Onglerie</span>
                        <p>Experte en pédicure médicale et soins des ongles naturels. Approche douce et minutieuse.</p>
                        <div class="team-tags">
                            <span>Pédicure</span>
                            <span>Soins</span>
                            <span>Manucure</span>
                        </div>
                        <a href="pages/reservation.html?pro=emma" class="btn-team">Prendre RDV</a>
                    </div>
                </div>

                <!-- Professionnelle 3 - Épilation -->
                <div class="team-card">
                    <div class="team-photo">
                        <i class="fas fa-sun"></i>
                    </div>
                    <div class="team-info">
                        <h3>Clara</h3>
                        <span class="team-role">Experte Épilation</span>
                        <p>Spécialiste de l'épilation à la cire chaude. Technique rapide et efficace pour un confort optimal.</p>
                        <div class="team-tags">
                            <span>Cire Chaude</span>
                            <span>Maillot</span>
                            <span>Visage</span>
                        </div>
                        <a href="pages/reservation.html?pro=clara" class="btn-team">Prendre RDV</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Espace Pro Section -->
    <section id="espace-pro" class="espace-pro">
        <div class="container">
            <div class="pro-content">
                <div class="pro-text">
                    <span class="section-tag">Location</span>
                    <h2>Espace Professionnel</h2>
                    <p class="pro-lead">Vous êtes esthéticienne, onglerie ou praticienne de bien-être ? Louez une cabine équipée au cœur de Genève.</p>
                    
                    <div class="pro-features">
                        <div class="pro-feature">
                            <i class="fas fa-check-circle"></i>
                            <div>
                                <h4>Cabines équipées</h4>
                                <p>Espace lumineux, mobilier professionnel, matériel de base fourni</p>
                            </div>
                        </div>
                        <div class="pro-feature">
                            <i class="fas fa-check-circle"></i>
                            <div>
                                <h4>Commission 20%</h4>
                                <p>Sur les clients que vous apportez. Pas de loyer fixe contraignant</p>
                            </div>
                        </div>
                        <div class="pro-feature">
                            <i class="fas fa-check-circle"></i>
                            <div>
                                <h4>Flexibilité horaire</h4>
                                <p>Aménagez vos créneaux selon vos disponibilités et celles de vos clientes</p>
                            </div>
                        </div>
                        <div class="pro-feature">
                            <i class="fas fa-check-circle"></i>
                            <div>
                                <h4>Contrat de confidentialité</h4>
                                <p>Respect et professionnalisme garantis entre toutes les collaboratrices</p>
                            </div>
                        </div>
                    </div>
                    
                    <div class="pro-cta">
                        <a href="pages/contact-pro.html" class="btn btn-primary">
                            <i class="fas fa-envelope"></i> Devenir locataire
                        </a>
                        <a href="#contact" class="btn btn-outline">Nous appeler</a>
                    </div>
                </div>
                <div class="pro-visual">
                    <div class="pro-image">
                        <i class="fas fa-store"></i>
                        <span>Votre future cabine à Genève</span>
                    </div>
                    <div class="pro-stats">
                        <div class="pro-stat">
                            <span>3</span>
                            <p>Cabines disponibles</p>
                        </div>
                        <div class="pro-stat">
                            <span>20%</span>
                            <p>Commission</p>
                        </div>
                        <div class="pro-stat">
                            <span>Genève</span>
                            <p>Emplacement premium</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Salles de Réunion Section -->
    <section id="salles" class="salles">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Coworking</span>
                <h2 class="section-title">Salles de Réunion</h2>
                <p class="section-desc">Un espace calme et professionnel pour vos rendez-vous</p>
            </div>
            
            <div class="salles-content">
                <div class="salles-info">
                    <div class="salle-card">
                        <div class="salle-header">
                            <i class="fas fa-door-open"></i>
                            <h3>Salle de Réunion Mery Key</h3>
                        </div>
                        <div class="salle-details">
                            <div class="salle-detail">
                                <i class="fas fa-users"></i>
                                <span>Jusqu'à 6 personnes</span>
                            </div>
                            <div class="salle-detail">
                                <i class="fas fa-wifi"></i>
                                <span>WiFi haut débit</span>
                            </div>
                            <div class="salle-detail">
                                <i class="fas fa-tv"></i>
                                <span>Écran / Vidéoprojecteur</span>
                            </div>
                            <div class="salle-detail">
                                <i class="fas fa-coffee"></i>
                                <span>Café & thé inclus</span>
                            </div>
                        </div>
                    </div>
                    
                    <div class="tarifs-salle">
                        <h4>Tarification</h4>
                        <div class="tarif-item">
                            <div class="tarif-info">
                                <span class="tarif-name">1ère heure</span>
                                <span class="tarif-desc">Tarif standard</span>
                            </div>
                            <span class="tarif-prix">60 CHF</span>
                        </div>
                        <div class="tarif-item highlight">
                            <div class="tarif-info">
                                <span class="tarif-name">2ème heure</span>
                                <span class="tarif-desc">Réduction spéciale</span>
                            </div>
                            <span class="tarif-prix">30 CHF <span class="tarif-reduc">-50%</span></span>
                        </div>
                        <div class="tarif-item">
                            <div class="tarif-info">
                                <span class="tarif-name">3ème heure et +</span>
                                <span class="tarif-desc">Tarif dégressif</span>
                            </div>
                            <span class="tarif-prix">50 CHF/h</span>
                        </div>
                    </div>
                    
                    <a href="pages/reservation-salle.html" class="btn btn-primary btn-full">
                        <i class="fas fa-calendar-alt"></i> Réserver la salle
                    </a>
                </div>
                
                <div class="salles-visual">
                    <div class="salle-image">
                        <i class="fas fa-chalkboard-teacher"></i>
                        <span>Salle de réunion moderne et lumineuse</span>
                    </div>
                    <div class="salle-ideal">
                        <h4>Idéal pour :</h4>
                        <ul>
                            <li><i class="fas fa-check"></i> Réunions d'affaires</li>
                            <li><i class="fas fa-check"></i> Consultations privées</li>
                            <li><i class="fas fa-check"></i> Formations & ateliers</li>
                            <li><i class="fas fa-check"></i> Entretiens d'embauche</li>
                            <li><i class="fas fa-check"></i> Coaching & thérapie</li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Avis Section -->
    <section id="avis" class="avis">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Témoignages</span>
                <h2 class="section-title">Ce que disent nos clientes</h2>
            </div>
            
            <div class="avis-grid">
                <div class="avis-card">
                    <div class="avis-stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="avis-text">"Sophie est une magicienne des ongles ! Mon nail art tient parfaitement depuis 3 semaines. L'ambiance du salon est super chaleureuse."</p>
                    <div class="avis-author">
                        <span class="avis-name">Marie L.</span>
                        <span class="avis-service">Onglerie - Nail Art</span>
                    </div>
                </div>
                
                <div class="avis-card">
                    <div class="avis-stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="avis-text">"Le massage aux pierres chaudes était divin. J'ai enfin trouvé un endroit à Genève où je peux vraiment me détendre. À refaire très vite !"</p>
                    <div class="avis-author">
                        <span class="avis-name">Catherine D.</span>
                        <span class="avis-service">Massage Pierres Chaudes</span>
                    </div>
                </div>
                
                <div class="avis-card">
                    <div class="avis-stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <p class="avis-text">"Clara est très professionnelle et rapide. L'épilation à la cire est nettement moins douloureuse qu'ailleurs. Je recommande à 100%."</p>
                    <div class="avis-author">
                        <span class="avis-name">Aurélie B.</span>
                        <span class="avis-service">Épilation Maillot</span>
                    </div>
                </div>
                
                <div class="avis-card">
                    <div class="avis-stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                    <p class="avis-text">"J'ai loué la salle de réunion pour un entretien avec un client. Parfaitement équipée, calme, et le tarif dégressif est très avantageux."</p>
                    <div class="avis-author">
                        <span class="avis-name">Thomas R.</span>
                        <span class="avis-service">Location Salle de Réunion</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <div class="container">
            <div class="section-header">
                <span class="section-tag">Contact</span>
                <h2 class="section-title">Nous trouver</h2>
            </div>
            
            <div class="contact-content">
                <div class="contact-info">
                    <div class="contact-card">
                        <i class="fas fa-map-marker-alt"></i>
                        <h4>Adresse</h4>
                        <p>Mery Key<br>Rue de la Beauté 12<br>1205 Genève, Suisse</p>
                    </div>
                    <div class="contact-card">
                        <i class="fas fa-phone"></i>
                        <h4>Téléphone</h4>
                        <p><a href="tel:+41221234567">+41 22 123 45 67</a></p>
                    </div>
                    <div class="contact-card">
                        <i class="fas fa-envelope"></i>
                        <h4>Email</h4>
                        <p><a href="mailto:contact@merykey.ch">contact@merykey.ch</a></p>
                    </div>
                    <div class="contact-card">
                        <i class="fas fa-clock"></i>
                        <h4>Horaires</h4>
                        <p>Lundi - Samedi : 9h00 - 19h00<br>Dimanche : Fermé</p>
                    </div>
                    <div class="contact-social">
                        <h4>Suivez-nous</h4>
                        <div class="social-links">
                            <a href="#" aria-label="Instagram"><i class="fab fa-instagram"></i></a>
                            <a href="#" aria-label="Facebook"><i class="fab fa-facebook-f"></i></a>
                            <a href="#" aria-label="WhatsApp"><i class="fab fa-whatsapp"></i></a>
                        </div>
                    </div>
                </div>
                
                <div class="contact-map">
                    <div class="map-placeholder">
                        <i class="fas fa-map-marked-alt"></i>
                        <span>Carte Google Maps</span>
                        <p>Intégrez votre Google Maps ici</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="footer">
        <div class="container">
            <div class="footer-content">
                <div class="footer-brand">
                    <h3>Mery Key</h3>
                    <p>Votre institut de beauté et espace professionnel au cœur de Genève.</p>
                </div>
                <div class="footer-links">
                    <h4>Navigation</h4>
                    <ul>
                        <li><a href="#services">Nos Services</a></li>
                        <li><a href="#galerie">Galerie</a></li>
                        <li><a href="#equipe">L'Équipe</a></li>
                        <li><a href="#espace-pro">Espace Pro</a></li>
                        <li><a href="#salles">Salles de Réunion</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Services</h4>
                    <ul>
                        <li><a href="pages/reservation.html?service=onglerie">Onglerie</a></li>
                        <li><a href="pages/reservation.html?service=massage">Massage</a></li>
                        <li><a href="pages/reservation.html?service=epilation">Épilation</a></li>
                        <li><a href="pages/reservation-salle.html">Location Salle</a></li>
                    </ul>
                </div>
                <div class="footer-links">
                    <h4>Légal</h4>
                    <ul>
                        <li><a href="pages/mentions.html">Mentions légales</a></li>
                        <li><a href="pages/confidentialite.html">Politique de confidentialité</a></li>
                        <li><a href="pages/cgv.html">CGV</a></li>
                    </ul>
                </div>
            </div>
            <div class="footer-bottom">
                <p>&copy; 2026 Mery Key. Tous droits réservés.</p>
            </div>
        </div>
    </footer>

    <!-- Bouton retour en haut -->
    <button class="back-to-top" id="backToTop" aria-label="Retour en haut">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script src="js/main.js"></script>
</body>
</html>
