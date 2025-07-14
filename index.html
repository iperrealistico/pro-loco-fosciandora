// Pro Loco Fosciandora - JavaScript

// Mobile menu toggle
document.addEventListener('DOMContentLoaded', function() {
    const navToggle = document.getElementById('navToggle');
    const navMenu = document.getElementById('navMenu');
    
    navToggle.addEventListener('click', function() {
        navToggle.classList.toggle('active');
        navMenu.classList.toggle('active');
    });
    
    // Close menu when clicking on a link
    const navLinks = document.querySelectorAll('.nav-link');
    navLinks.forEach(link => {
        link.addEventListener('click', () => {
            navToggle.classList.remove('active');
            navMenu.classList.remove('active');
        });
    });
    
    // Navbar scroll effect
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', function() {
        if (window.scrollY > 100) {
            navbar.classList.add('scrolled');
        } else {
            navbar.classList.remove('scrolled');
        }
    });
    
    // Animate on scroll
    const observerOptions = {
        threshold: 0.1,
        rootMargin: '0px 0px -100px 0px'
    };
    
    const observer = new IntersectionObserver(function(entries) {
        entries.forEach(entry => {
            if (entry.isIntersecting) {
                entry.target.classList.add('visible');
            }
        });
    }, observerOptions);
    
    const animatedElements = document.querySelectorAll('.animate-on-scroll');
    animatedElements.forEach(el => {
        observer.observe(el);
    });
});

// Open Google Maps
function openMaps(from) {
    const destination = 'Fosciandora, LU, Italia';
    let origin = '';
    
    switch(from) {
        case 'lucca':
            origin = 'Lucca, LU, Italia';
            break;
        case 'pisa':
            origin = 'Pisa, PI, Italia';
            break;
        case 'firenze':
            origin = 'Firenze, FI, Italia';
            break;
    }
    
    const url = `https://www.google.com/maps/dir/${encodeURIComponent(origin)}/${encodeURIComponent(destination)}`;
    window.open(url, '_blank');
}

// Request info
function richiestaInfo() {
    const subject = encodeURIComponent('Richiesta Tesseramento Pro Loco');
    const body = encodeURIComponent('Salve, vorrei ricevere informazioni sul tesseramento alla Pro Loco Fosciandora.\n\nNome:\nCognome:\nTelefono:\n\nGrazie');
    window.location.href = `mailto:info@prolocofosciandora.it?subject=${subject}&body=${body}`;
}

// Smooth scroll for anchor links
document.querySelectorAll('a[href^="#"]').forEach(anchor => {
    anchor.addEventListener('click', function (e) {
        e.preventDefault();
        const target = document.querySelector(this.getAttribute('href'));
        if (target) {
            const offset = 80;
            const targetPosition = target.offsetTop - offset;
            window.scrollTo({
                top: targetPosition,
                behavior: 'smooth'
            });
        }
    });
});
