<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Shree Parth Academy™ · An Emperor of Knowledge</title>
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&family=Playfair+Display:wght@400;700;900&family=Noto+Sans+Devanagari:wght@400;500;600;700&display=swap" rel="stylesheet" />
    <style>
        /* ===== COMPLETE STYLES (same as before, with extra About styles) ===== */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        :root {
            --primary: #0a1628;
            --primary-light: #1a2d4a;
            --secondary: #c0392b;
            --gold: #d4a843;
            --gold-light: #f0d080;
            --gold-gradient: linear-gradient(135deg, #d4a843, #f0d080, #d4a843);
            --white: #ffffff;
            --light-bg: #f5f0eb;
            --shadow: 0 20px 60px rgba(0, 0, 0, 0.08);
            --shadow-hover: 0 30px 80px rgba(0, 0, 0, 0.15);
            --radius: 24px;
            --radius-sm: 14px;
            --transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            --font-serif: 'Playfair Display', serif;
            --font-marathi: 'Noto Sans Devanagari', sans-serif;
        }
        body {
            font-family: 'Inter', sans-serif;
            background: var(--light-bg);
            color: var(--primary);
            line-height: 1.6;
            overflow-x: hidden;
        }
        /* ===== NAVIGATION ===== */
        .navbar {
            background: var(--primary);
            padding: 0.8rem 2.5rem;
            display: flex;
            align-items: center;
            justify-content: space-between;
            flex-wrap: wrap;
            gap: 1rem;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 4px 30px rgba(0, 0, 0, 0.3);
            border-bottom: 3px solid var(--gold);
        }
        .logo {
            display: flex;
            align-items: center;
            gap: 14px;
            color: white;
            font-weight: 800;
            font-size: 1.6rem;
            font-family: var(--font-serif);
        }
        .logo img {
            height: 60px;
            width: auto;
            border-radius: 12px;
            border: 2px solid var(--gold);
            padding: 4px;
            background: white;
            object-fit: contain;
        }
        .logo .logo-text {
            display: flex;
            flex-direction: column;
            line-height: 1.2;
        }
        .logo .logo-text .sub {
            font-size: 0.6rem;
            font-weight: 400;
            color: var(--gold);
            letter-spacing: 3px;
            font-family: 'Inter', sans-serif;
        }
        .logo .trademark {
            font-size: 0.7rem;
            vertical-align: super;
            color: var(--gold);
        }
        .nav-links {
            display: flex;
            align-items: center;
            gap: 0.5rem 1.5rem;
            flex-wrap: wrap;
        }
        .nav-links a {
            color: rgba(255, 255, 255, 0.7);
            font-weight: 500;
            font-size: 0.9rem;
            padding: 0.5rem 0.8rem;
            border-radius: 10px;
            transition: var(--transition);
            display: inline-flex;
            align-items: center;
            gap: 8px;
            cursor: pointer;
            text-decoration: none;
            position: relative;
        }
        .nav-links a:hover,
        .nav-links a.active {
            color: white;
            background: rgba(255, 255, 255, 0.08);
        }
        .nav-links a.active::after {
            content: '';
            position: absolute;
            bottom: -2px;
            left: 50%;
            transform: translateX(-50%);
            width: 24px;
            height: 3px;
            background: var(--gold);
            border-radius: 4px;
        }
        .lang-switcher {
            display: flex;
            gap: 0.3rem;
            background: rgba(255, 255, 255, 0.1);
            padding: 0.2rem;
            border-radius: 60px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .lang-btn {
            padding: 0.3rem 0.8rem;
            border-radius: 60px;
            border: none;
            background: transparent;
            color: rgba(255, 255, 255, 0.6);
            font-weight: 600;
            font-size: 0.7rem;
            cursor: pointer;
            transition: var(--transition);
            text-transform: uppercase;
        }
        .lang-btn.active {
            background: var(--gold);
            color: var(--primary);
        }
        .lang-btn:hover:not(.active) {
            color: white;
        }
        .auth-btn {
            background: var(--gold);
            color: var(--primary) !important;
            padding: 0.5rem 1.6rem !important;
            border-radius: 60px !important;
            font-weight: 700 !important;
            transition: var(--transition);
        }
        .auth-btn:hover {
            background: #e8c050 !important;
            transform: scale(1.05);
        }
        .user-badge {
            color: white;
            background: rgba(255, 255, 255, 0.1);
            padding: 0.3rem 1rem 0.3rem 1.2rem;
            border-radius: 60px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 500;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        .user-badge i {
            color: var(--gold);
        }
        .user-badge .role-badge {
            font-size: 0.6rem;
            background: var(--gold);
            color: var(--primary);
            padding: 0.1rem 0.5rem;
            border-radius: 60px;
            font-weight: 700;
        }
        .logout-btn {
            background: transparent;
            color: rgba(255, 255, 255, 0.6);
            border: none;
            padding: 0.2rem 0.5rem;
            border-radius: 8px;
            cursor: pointer;
            transition: var(--transition);
            font-size: 0.9rem;
        }
        .logout-btn:hover {
            color: white;
            background: rgba(255, 255, 255, 0.1);
        }
        /* ===== PAGE CONTAINER ===== */
        .page-container {
            max-width: 1440px;
            margin: 0 auto;
            padding: 2rem;
            min-height: 80vh;
        }
        .page {
            display: none;
            animation: fadeIn 0.5s ease;
        }
        .page.active {
            display: block;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .hidden { display: none !important; }
        /* ===== LOGIN ===== */
        .login-wrapper {
            display: flex;
            align-items: center;
            justify-content: center;
            min-height: 70vh;
        }
        .login-card {
            max-width: 480px;
            width: 100%;
            padding: 3rem 2.5rem;
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            border: 1px solid rgba(212, 168, 67, 0.2);
        }
        .login-card .logo-icon {
            font-size: 4rem;
            color: var(--gold);
            margin-bottom: 0.5rem;
        }
        .login-card h2 {
            font-size: 2rem;
            font-weight: 800;
            color: var(--primary);
            font-family: var(--font-serif);
        }
        .login-card .sub {
            color: #64748b;
            margin-bottom: 2rem;
        }
        .input-group {
            text-align: left;
            margin-bottom: 1.2rem;
        }
        .input-group label {
            font-weight: 600;
            color: var(--primary);
            display: block;
            margin-bottom: 0.3rem;
            font-size: 0.9rem;
        }
        .input-group input,
        .input-group select {
            width: 100%;
            padding: 0.9rem 1.2rem;
            border: 2px solid #e2e8f0;
            border-radius: 12px;
            font-size: 1rem;
            transition: var(--transition);
            background: #f8fafc;
        }
        .input-group input:focus,
        .input-group select:focus {
            outline: none;
            border-color: var(--gold);
            box-shadow: 0 0 0 4px rgba(212, 168, 67, 0.15);
        }
        .role-selector {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 0.5rem;
            margin-bottom: 1rem;
        }
        .role-option {
            padding: 0.6rem;
            text-align: center;
            border: 2px solid #e2e8f0;
            border-radius: 10px;
            cursor: pointer;
            transition: var(--transition);
            font-weight: 500;
            font-size: 0.85rem;
        }
        .role-option:hover {
            border-color: var(--gold);
        }
        .role-option.active {
            border-color: var(--gold);
            background: rgba(212, 168, 67, 0.1);
        }
        .role-option i {
            display: block;
            font-size: 1.5rem;
            margin-bottom: 0.2rem;
        }
        .btn-gold {
            background: var(--gold-gradient);
            color: var(--primary);
            padding: 0.8rem 2rem;
            border-radius: 12px;
            font-weight: 700;
            transition: var(--transition);
            border: none;
            cursor: pointer;
            width: 100%;
        }
        .btn-gold:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(212, 168, 67, 0.4);
        }
        /* ===== HERO ===== */
        .hero-section {
            background: linear-gradient(135deg, var(--primary) 0%, #1a2d4a 100%);
            border-radius: var(--radius);
            padding: 4rem 3rem;
            color: white;
            margin-bottom: 3rem;
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(212, 168, 67, 0.2);
        }
        .hero-section .hero-bg {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            opacity: 0.2;
            z-index: 0;
        }
        .hero-section .hero-content {
            position: relative;
            z-index: 1;
        }
        .hero-section h1 {
            font-size: 3.5rem;
            font-weight: 900;
            letter-spacing: -1px;
            margin-bottom: 0.5rem;
            font-family: var(--font-serif);
        }
        .hero-section h1 span {
            color: var(--gold);
        }
        .hero-section .tagline {
            font-size: 1.6rem;
            color: var(--gold);
            font-weight: 600;
            margin-bottom: 1rem;
            font-family: var(--font-serif);
        }
        .hero-section p {
            font-size: 1.1rem;
            max-width: 600px;
            opacity: 0.9;
            margin-bottom: 1.5rem;
        }
        .hero-stats {
            display: flex;
            gap: 3rem;
            margin-top: 2rem;
            flex-wrap: wrap;
        }
        .hero-stats .stat {
            text-align: center;
        }
        .hero-stats .stat .number {
            font-size: 2.8rem;
            font-weight: 900;
            color: var(--gold);
            display: block;
            font-family: var(--font-serif);
        }
        .hero-stats .stat .label {
            font-size: 0.9rem;
            opacity: 0.7;
            text-transform: uppercase;
            letter-spacing: 1px;
        }
        /* ===== LOGO DISPLAY CARD ===== */
        .logo-display {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 2rem;
            flex-wrap: wrap;
            padding: 2rem;
            background: white;
            border-radius: var(--radius);
            box-shadow: var(--shadow);
            border: 3px solid var(--gold);
            margin-bottom: 2rem;
        }
        .logo-display img {
            height: 120px;
            width: auto;
            object-fit: contain;
        }
        .logo-display .logo-text {
            font-family: var(--font-serif);
            font-size: 2.5rem;
            font-weight: 900;
            color: var(--primary);
        }
        .logo-display .logo-text span {
            color: var(--gold);
        }
        .logo-display .logo-text .sub {
            font-size: 0.9rem;
            font-weight: 400;
            color: #64748b;
            font-family: 'Inter', sans-serif;
            letter-spacing: 3px;
        }
        .logo-display .trademark {
            font-size: 1rem;
            vertical-align: super;
            color: var(--gold);
        }
        /* ===== CARDS ===== */
        .card {
            background: var(--card-bg);
            border-radius: var(--radius);
            padding: 2rem;
            box-shadow: var(--shadow);
            transition: var(--transition);
            border: 1px solid rgba(255, 255, 255, 0.3);
        }
        .card:hover {
            box-shadow: var(--shadow-hover);
            transform: translateY(-4px);
        }
        .card-premium {
            background: linear-gradient(145deg, #ffffff, #f8f4ef);
            border: 1px solid var(--gold);
            position: relative;
            overflow: hidden;
        }
        .grid-2col {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 2rem;
        }
        .grid-3col {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }
        .grid-4col {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 1.5rem;
        }
        @media (max-width: 768px) {
            .grid-2col { grid-template-columns: 1fr; }
            .hero-section { padding: 2rem 1.5rem; }
            .hero-section h1 { font-size: 2rem; }
            .navbar { padding: 0.8rem 1rem; }
            .page-container { padding: 1rem; }
            .hero-stats { gap: 1.5rem; }
            .logo img { height: 40px; }
            .logo-display img { height: 80px; }
            .logo-display .logo-text { font-size: 1.8rem; }
            .role-selector { grid-template-columns: 1fr 1fr; }
        }
        /* ===== SECTION TITLES ===== */
        .section-title {
            font-size: 2.2rem;
            font-weight: 800;
            color: var(--primary);
            margin-bottom: 2rem;
            display: flex;
            align-items: center;
            gap: 14px;
            font-family: var(--font-serif);
        }
        .section-title i {
            color: var(--gold);
        }
        .section-title::after {
            content: '';
            flex: 1;
            height: 2px;
            background: linear-gradient(to right, var(--gold), transparent);
            margin-left: 1rem;
        }
        /* ===== TRADITION CARDS ===== */
        .tradition-card {
            background: white;
            padding: 2rem;
            border-radius: var(--radius-sm);
            box-shadow: var(--shadow);
            text-align: center;
            transition: var(--transition);
            border-top: 4px solid var(--gold);
        }
        .tradition-card:hover {
            transform: translateY(-6px);
            box-shadow: var(--shadow-hover);
        }
        .tradition-card .card-img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 10px;
            margin-bottom: 0.8rem;
            border: 2px solid var(--gold);
            background: #e2e8f0;
        }
        .tradition-card h3 {
            font-size: 1.3rem;
            color: var(--primary);
            margin-bottom: 0.3rem;
            font-family: var(--font-serif);
        }
        .tradition-card .marathi {
            color: var(--secondary);
            font-weight: 600;
            font-size: 0.95rem;
        }
        .tradition-card p {
            color: #64748b;
            font-size: 0.95rem;
            margin-top: 0.5rem;
        }
        /* ===== IMAGE GALLERY ===== */
        .image-gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 1.5rem;
        }
        .gallery-item {
            position: relative;
            border-radius: var(--radius-sm);
            overflow: hidden;
            box-shadow: var(--shadow);
            transition: var(--transition);
            cursor: pointer;
            aspect-ratio: 1/1;
            border: 2px solid transparent;
        }
        .gallery-item:hover {
            transform: scale(1.03);
            border-color: var(--gold);
            box-shadow: var(--shadow-hover);
        }
        .gallery-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
            background: #e2e8f0;
        }
        .gallery-item .overlay {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            background: linear-gradient(transparent, rgba(10, 22, 40, 0.8));
            padding: 1.5rem 1rem 0.8rem;
            color: white;
            font-weight: 600;
            font-size: 0.9rem;
            transform: translateY(100%);
            transition: var(--transition);
        }
        .gallery-item:hover .overlay {
            transform: translateY(0);
        }
        .gallery-item .badge {
            position: absolute;
            top: 10px;
            right: 10px;
            background: var(--gold);
            color: var(--primary);
            padding: 0.2rem 0.8rem;
            border-radius: 60px;
            font-size: 0.7rem;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.5px;
        }
        /* ===== UPLOAD ZONE ===== */
        .upload-zone {
            border: 3px dashed #cbd5e1;
            border-radius: var(--radius-sm);
            padding: 3rem 2rem;
            text-align: center;
            background: #fafdff;
            transition: var(--transition);
            cursor: pointer;
        }
        .upload-zone:hover,
        .upload-zone.dragover {
            border-color: var(--gold);
            background: #fefcf5;
        }
        .upload-zone i {
            font-size: 3.5rem;
            color: var(--gold);
            opacity: 0.5;
            margin-bottom: 0.5rem;
        }
        .upload-zone input[type="file"] {
            border: 1px solid #d0d9e6;
            border-radius: 60px;
            padding: 0.5rem 1rem;
            background: white;
            margin-top: 1rem;
        }
        /* ===== ACTIVITIES ===== */
        .activity-item {
            background: #f8fafc;
            padding: 1rem 1.5rem;
            border-radius: 12px;
            display: flex;
            align-items: center;
            gap: 1rem;
            transition: var(--transition);
            border-left: 4px solid var(--gold);
        }
        .activity-item:hover {
            background: #f1f5f9;
            transform: translateX(4px);
        }
        .activity-item i {
            color: var(--secondary);
            width: 1.8rem;
            font-size: 1.2rem;
        }
        .activity-item .date {
            margin-left: auto;
            color: #94a3b8;
            font-size: 0.85rem;
            font-weight: 500;
        }
        .activity-item .status {
            padding: 0.2rem 0.8rem;
            border-radius: 60px;
            font-size: 0.75rem;
            font-weight: 600;
        }
        .status.upcoming { background: #dbeafe; color: #1d4ed8; }
        .status.ongoing { background: #fef3c7; color: #d97706; }
        .status.completed { background: #d1fae5; color: #059669; }
        /* ===== FEATURES ===== */
        .features-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 0.8rem;
            list-style: none;
            padding: 0;
        }
        .features-list li {
            padding: 0.8rem 1rem;
            background: #f8fafc;
            border-radius: 10px;
            display: flex;
            align-items: center;
            gap: 10px;
            font-weight: 500;
            border: 1px solid rgba(212, 168, 67, 0.1);
        }
        .features-list li::before {
            content: '✦';
            color: var(--gold);
            font-weight: 700;
            font-size: 1.2rem;
        }
        /* ===== STAT CARDS ===== */
        .stat-card {
            background: white;
            padding: 1.5rem;
            border-radius: var(--radius-sm);
            box-shadow: var(--shadow);
            text-align: center;
            transition: var(--transition);
            border: 1px solid rgba(212, 168, 67, 0.1);
        }
        .stat-card:hover {
            transform: translateY(-4px);
            box-shadow: var(--shadow-hover);
            border-color: var(--gold);
        }
        .stat-card .number {
            font-size: 2.5rem;
            font-weight: 900;
            color: var(--secondary);
            display: block;
            font-family: var(--font-serif);
        }
        .stat-card .label {
            color: #64748b;
            font-weight: 500;
        }
        .stat-card .icon {
            font-size: 2rem;
            color: var(--gold);
            margin-bottom: 0.3rem;
        }
        /* ===== SOCIAL LINKS ===== */
        .social-links {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
            justify-content: center;
        }
        .social-link {
            display: inline-flex;
            align-items: center;
            gap: 0.5rem;
            padding: 0.6rem 1.5rem;
            border-radius: 60px;
            color: white;
            font-weight: 600;
            text-decoration: none;
            transition: var(--transition);
        }
        .social-link:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
        }
        .social-link.whatsapp { background: #25D366; }
        .social-link.telegram { background: #0088cc; }
        .social-link.phone { background: var(--secondary); }
        .social-link.email { background: #ea4335; }
        /* ===== MAP ===== */
        .map-container {
            border-radius: var(--radius-sm);
            overflow: hidden;
            border: 3px solid var(--gold);
            height: 300px;
        }
        .map-container iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
        /* ===== TOPPERS TABLE ===== */
        .toppers-table {
            width: 100%;
            border-collapse: collapse;
            font-size: 0.9rem;
        }
        .toppers-table th {
            background: var(--primary);
            color: white;
            padding: 0.8rem;
            text-align: left;
            font-weight: 600;
        }
        .toppers-table td {
            padding: 0.6rem 0.8rem;
            border-bottom: 1px solid #e2e8f0;
        }
        .toppers-table tr:hover {
            background: rgba(212, 168, 67, 0.05);
        }
        .toppers-table .rank {
            font-weight: 700;
            color: var(--gold);
        }
        /* ===== PAYMENT ===== */
        .payment-options {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 1rem;
        }
        .payment-option {
            padding: 1.5rem;
            text-align: center;
            background: #f8fafc;
            border-radius: var(--radius-sm);
            border: 2px solid #e2e8f0;
            transition: var(--transition);
            cursor: pointer;
        }
        .payment-option:hover {
            border-color: var(--gold);
            background: rgba(212, 168, 67, 0.05);
        }
        .payment-option i {
            font-size: 2.5rem;
            color: var(--gold);
            display: block;
            margin-bottom: 0.3rem;
        }
        .payment-option .label {
            font-weight: 600;
        }
        /* ===== FOOTER ===== */
        .footer {
            background: var(--primary);
            color: rgba(255, 255, 255, 0.7);
            padding: 3rem 2rem 1.5rem;
            margin-top: 4rem;
            border-top: 4px solid var(--gold);
        }
        .footer-grid {
            max-width: 1440px;
            margin: 0 auto;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 2.5rem;
        }
        .footer h4 {
            color: white;
            font-size: 1.1rem;
            margin-bottom: 1rem;
            border-bottom: 2px solid var(--gold);
            padding-bottom: 0.5rem;
            display: inline-block;
            font-family: var(--font-serif);
        }
        .footer p {
            margin: 0.5rem 0;
            font-size: 0.95rem;
        }
        .footer .footer-logo {
            display: flex;
            align-items: center;
            gap: 12px;
        }
        .footer .footer-logo img {
            height: 50px;
            width: auto;
            border-radius: 8px;
            border: 2px solid var(--gold);
            padding: 2px;
            background: white;
            object-fit: contain;
        }
        .footer-bottom {
            text-align: center;
            margin-top: 2.5rem;
            padding-top: 1.5rem;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            font-size: 0.9rem;
            opacity: 0.6;
        }
        /* ===== TOAST ===== */
        .toast {
            position: fixed;
            bottom: 2rem;
            right: 2rem;
            background: var(--primary);
            color: white;
            padding: 1rem 2rem;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.2);
            transform: translateY(100px);
            opacity: 0;
            transition: all 0.5s ease;
            z-index: 9999;
            border-left: 4px solid var(--gold);
            max-width: 400px;
        }
        .toast.show {
            transform: translateY(0);
            opacity: 1;
        }
        .toast i {
            margin-right: 10px;
            color: var(--gold);
        }
        .mt-2 { margin-top: 1.5rem; }
        .mb-2 { margin-bottom: 1.5rem; }
        .text-center { text-align: center; }
        .flex { display: flex; align-items: center; gap: 1rem; flex-wrap: wrap; }
        .text-gold { color: var(--gold); }
        .btn-outline {
            background: transparent;
            border: 2px solid var(--primary);
            color: var(--primary);
            padding: 0.6rem 1.6rem;
            border-radius: 12px;
            font-weight: 600;
            cursor: pointer;
            transition: var(--transition);
        }
        .btn-outline:hover {
            background: var(--primary);
            color: white;
        }
        /* ===== ABOUT PAGE EXTRA STYLES ===== */
        .about-highlight {
            background: var(--gold-gradient);
            color: var(--primary);
            padding: 1.5rem;
            border-radius: var(--radius-sm);
            text-align: center;
            font-family: var(--font-serif);
            font-size: 1.2rem;
            font-weight: 700;
            margin: 1rem 0;
        }
        .timeline-item {
            display: flex;
            gap: 1.5rem;
            padding: 1rem 0;
            border-bottom: 1px solid #e2e8f0;
        }
        .timeline-item:last-child {
            border-bottom: none;
        }
        .timeline-item .year {
            font-weight: 800;
            color: var(--gold);
            min-width: 80px;
            font-size: 1.1rem;
            font-family: var(--font-serif);
        }
        .about-marathi-quote {
            font-size: 1.3rem;
            font-family: var(--font-marathi);
            color: var(--secondary);
            font-weight: 600;
            text-align: center;
            padding: 1rem;
            background: rgba(212, 168, 67, 0.08);
            border-radius: var(--radius-sm);
            border-left: 4px solid var(--gold);
        }
    </style>
</head>
<body>

    <!-- ===== TOAST ===== -->
    <div id="toast" class="toast"><i class="fas fa-check-circle"></i> <span id="toastMessage">Success!</span></div>

    <!-- ===== NAVIGATION ===== -->
    <nav class="navbar">
        <div class="logo">
            <!-- LOGO IMAGE (first URL) -->
            <img src="http://192.0.0.2:5600/uploads/9ef2c6a4fcd04765b5d4ecde996e7f4c.jpg" alt="Shree Parth Academy Logo" />
            <div class="logo-text">
                <span>Shree Parth<span class="trademark">™</span></span>
                <span class="sub">✦ EMPEROR OF KNOWLEDGE ✦</span>
            </div>
        </div>
        <div class="nav-links">
            <a class="active" data-page="home"><i class="fas fa-home"></i> Home</a>
            <a data-page="about"><i class="fas fa-info-circle"></i> About</a>
            <a data-page="toppers"><i class="fas fa-trophy"></i> Toppers</a>
            <a data-page="gallery"><i class="fas fa-images"></i> Gallery</a>
            <a data-page="activities"><i class="fas fa-calendar-alt"></i> Activities</a>
            <a data-page="payment"><i class="fas fa-credit-card"></i> Pay</a>

            <div class="lang-switcher">
                <button class="lang-btn active" data-lang="en">EN</button>
                <button class="lang-btn" data-lang="mr">मर</button>
                <button class="lang-btn" data-lang="semi">SEMI</button>
            </div>

            <span id="userDisplay" class="user-badge hidden">
                <i class="fas fa-user-circle"></i> <span id="usernameLabel">User</span>
                <span class="role-badge" id="roleBadge">Student</span>
                <button class="logout-btn" id="logoutBtn"><i class="fas fa-sign-out-alt"></i></button>
            </span>
            <a id="loginNavBtn" class="auth-btn"><i class="fas fa-lock"></i> Login</a>
        </div>
    </nav>

    <!-- ===== PAGE CONTAINER ===== -->
    <div class="page-container">

        <!-- ===== LOGIN PAGE ===== -->
        <div id="loginPage" class="page active">
            <div class="login-wrapper">
                <div class="login-card">
                    <div class="logo-icon"><i class="fas fa-crown"></i></div>
                    <h2>Welcome Back</h2>
                    <p class="sub">Sign in to the academy portal</p>
                    <form id="loginForm">
                        <div class="role-selector">
                            <div class="role-option active" data-role="student">
                                <i class="fas fa-user-graduate"></i> Student
                            </div>
                            <div class="role-option" data-role="teacher">
                                <i class="fas fa-chalkboard-teacher"></i> Teacher
                            </div>
                            <div class="role-option" data-role="admin">
                                <i class="fas fa-user-cog"></i> Admin
                            </div>
                            <div class="role-option" data-role="parent">
                                <i class="fas fa-user-friends"></i> Parent
                            </div>
                        </div>
                        <div class="input-group">
                            <label>Username / Email</label>
                            <input type="text" id="usernameInput" placeholder="Enter username" value="student" required />
                        </div>
                        <div class="input-group">
                            <label>Password</label>
                            <input type="password" id="passwordInput" placeholder="Enter password" value="password" required />
                        </div>
                        <button type="submit" class="btn-gold"><i class="fas fa-arrow-right-to-bracket"></i> Sign In</button>
                        <p style="margin-top:1rem; font-size:0.85rem; color:#94a3b8;">Demo: any role / password</p>
                    </form>
                </div>
            </div>
        </div>

        <!-- ===== HOME PAGE ===== -->
        <div id="homePage" class="page">
            <!-- Hero with background (second URL) -->
            <div class="hero-section">
                <img src="http://192.0.0.2:5600/uploads/82d66aec04ce4fb581b5905b5781a4af.jpg" alt="Hero Background" class="hero-bg" />
                <div class="hero-content">
                    <h1>An Emperor of <span>Knowledge</span></h1>
                    <div class="tagline">⚜️ Shree Parth Academy™</div>
                    <p>Established Since 2009 • "We strive for our student's success."</p>
                    <p style="font-style:italic; font-size:1rem; opacity:0.8;">"उद्याच्या सुवर्ण भविष्यासाठी एक उत्कृष्ट शैक्षणिक संस्था"</p>
                    <div class="hero-stats">
                        <div class="stat"><span class="number">2009</span><span class="label">Established</span></div>
                        <div class="stat"><span class="number">5000+</span><span class="label">Students</span></div>
                        <div class="stat"><span class="number">98%</span><span class="label">Success Rate</span></div>
                        <div class="stat"><span class="number">50+</span><span class="label">Expert Teachers</span></div>
                    </div>
                </div>
            </div>

            <!-- Prominent Logo Display -->
            <div class="logo-display">
                <img src="http://192.0.0.2:5600/uploads/9ef2c6a4fcd04765b5d4ecde996e7f4c.jpg" alt="Shree Parth Academy Logo" />
                <div class="logo-text">
                    Shree Parth <span>Academy</span><span class="trademark">™</span>
                    <div class="sub">AN EMPEROR OF KNOWLEDGE</div>
                </div>
            </div>

            <!-- Traditions with images (URLs 3-6) -->
            <h2 class="section-title"><i class="fas fa-landmark"></i> Our Academic Traditions</h2>
            <div class="grid-4col">
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/7e0db4323a3f4b1d8290c0df468efe30.jpg" alt="Success" class="card-img" />
                    <h3>Success History</h3>
                    <div class="marathi">यशस्वी निकालाची परंपरा</div>
                    <p>A rich heritage of excellent student outcomes.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/11e26e04bc81462cbb52e239566f8282.jpg" alt="Blueprint" class="card-img" />
                    <h3>Our Blueprint</h3>
                    <div class="marathi">आमचा निकाल हेच आमचे वैशिष्ट्ये</div>
                    <p>Uncompromising quality delivery is our identity.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/bdc648100a594967894c69c8fec8b484.jpg" alt="Character" class="card-img" />
                    <h3>Character Building</h3>
                    <div class="marathi">आम्ही स्पर्धक नाही, गुणवंत विद्यार्थी घडवतो</div>
                    <p>We cultivate meritorious individuals.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/6fa342602bc048029f7871c64da5c815.jpg" alt="Foundation" class="card-img" />
                    <h3>Our Foundation</h3>
                    <div class="marathi">शिस्त आणि अनुभव हीच आमची ओळख</div>
                    <p>Strict discipline & deep teaching knowledge.</p>
                </div>
            </div>

            <!-- Features -->
            <h2 class="section-title mt-2"><i class="fas fa-list-check"></i> World-Class Features</h2>
            <div class="card card-premium">
                <ul class="features-list">
                    <li>Well Qualified, Experienced and Expert Teachers</li>
                    <li>Personal Attention to every student</li>
                    <li>Focus on Basic Concepts</li>
                    <li>All Subjects Preparation in class</li>
                    <li>Library facilities available freely</li>
                    <li>Weekly & Chapter wise test series</li>
                    <li>Group Discussion during the Exam</li>
                    <li>Personality Development for the students</li>
                    <li>E-Learning Capabilities</li>
                    <li>Limited Strength / Batch Capacity</li>
                    <li>10th Moderator Interaction Sessions</li>
                    <li>Individual Career Counseling Track</li>
                </ul>
            </div>

            <!-- Quality vs Quantity -->
            <div class="card mt-2" style="background: linear-gradient(135deg, var(--primary), var(--primary-light)); color: white; text-align: center;">
                <h2 style="color: var(--gold); font-family: var(--font-serif);">What do you prefer? Quality or Quantity?</h2>
                <p style="max-width: 600px; margin: 0.5rem auto;">If your primary requirement is focused, premium-tier individual academic support, call our enrollment desk today!</p>
                <button class="btn-gold" onclick="showToast('📞 Call us at +91 8605688883')"><i class="fas fa-phone"></i> Contact Now</button>
            </div>

            <!-- Social Connect -->
            <h2 class="section-title mt-2"><i class="fas fa-share-alt"></i> Connect With Us</h2>
            <div class="card text-center">
                <div class="social-links">
                    <a href="https://wa.me/918605688883" target="_blank" class="social-link whatsapp"><i class="fab fa-whatsapp"></i> WhatsApp</a>
                    <a href="https://t.me/ShreeParthAcademy" target="_blank" class="social-link telegram"><i class="fab fa-telegram-plane"></i> Telegram</a>
                    <a href="tel:+918605688883" class="social-link phone"><i class="fas fa-phone"></i> Call Now</a>
                    <a href="mailto:shreeparthacademy2009@gmail.com" class="social-link email"><i class="fas fa-envelope"></i> Email</a>
                </div>
            </div>
        </div>

        <!-- ===== ABOUT PAGE (DETAILED) ===== -->
        <div id="aboutPage" class="page">
            <h2 class="section-title"><i class="fas fa-building-columns"></i> About Us – The Emperor of Knowledge</h2>

            <!-- Introduction -->
            <div class="card card-premium">
                <p style="font-size:1.2rem; line-height:1.8;">
                    <strong>Shree Parth Academy</strong>, established in <strong>2009</strong>, is a premier educational institution dedicated to shaping the future of students with excellence, discipline, and a passion for learning. 
                    We believe in <strong>"An Emperor of the Knowledge"</strong> – a philosophy that drives us to nurture not just academic brilliance but also character, creativity, and leadership.
                </p>
                <div class="about-marathi-quote">
                    "उद्याच्या सुवर्ण भविष्यासाठी एक उत्कृष्ट शैक्षणिक संस्था."
                </div>
                <p style="margin-top:1rem;">
                    Our journey began with a simple yet powerful vision: to provide world-class education that empowers students to become responsible citizens and lifelong learners. Over the past 15+ years, we have consistently delivered outstanding results, earning the trust of thousands of parents and students.
                </p>
            </div>

            <!-- Mission, Vision, Motive -->
            <div class="grid-2col mt-2">
                <div>
                    <div class="card card-premium">
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-bullseye"></i> Our Mission</h3>
                        <p style="font-size:1.05rem;">To Enable The Students Success Beyond Excellence In Their Life Long Pursuit Of Knowledge And In Their Contribution As Responsible Citizens In A Rapidly Changing Globalized World.</p>
                        <br>
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-eye"></i> Our Vision</h3>
                        <p style="font-size:1.05rem;">To Become A Standard Of Excellence Fostering Intellect, Creativity And Character In An Active, Student Centered Learning Community.</p>
                        <br>
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-heart"></i> Our Motive</h3>
                        <p style="font-size:1.1rem; font-style:italic; color:var(--primary);">"In Every Child There Is A Hidden Warrior. It Only Requires Self Confidence And Proper Guidance."</p>
                    </div>
                </div>
                <div>
                    <div class="card card-premium">
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-clock"></i> Our Journey</h3>
                        <div class="timeline-item">
                            <span class="year">2009</span>
                            <span>Founded with a vision of excellence – started with a small batch of dedicated students.</span>
                        </div>
                        <div class="timeline-item">
                            <span class="year">2015</span>
                            <span>Expanded to 500+ students, introduced new streams and facilities.</span>
                        </div>
                        <div class="timeline-item">
                            <span class="year">2020</span>
                            <span>Embraced digital transformation & E-Learning to reach students beyond the classroom.</span>
                        </div>
                        <div class="timeline-item">
                            <span class="year">2024</span>
                            <span>Achieved World-Class curriculum status with state-of-the-art infrastructure and a holistic approach.</span>
                        </div>
                        <div class="about-highlight" style="margin-top:1rem;">
                            🏆 Over 5000+ students have been part of our success story!
                        </div>
                    </div>
                </div>
            </div>

            <!-- Our Academic Traditions (expanded) -->
            <h2 class="section-title mt-2"><i class="fas fa-landmark"></i> Our Academic Traditions</h2>
            <div class="grid-4col">
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/7e0db4323a3f4b1d8290c0df468efe30.jpg" alt="Success" class="card-img" />
                    <h3>Success History</h3>
                    <div class="marathi">यशस्वी निकालाची परंपरा</div>
                    <p>A legacy of outstanding board results and competitive exam achievements.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/11e26e04bc81462cbb52e239566f8282.jpg" alt="Blueprint" class="card-img" />
                    <h3>Our Blueprint</h3>
                    <div class="marathi">आमचा निकाल हेच आमचे वैशिष्ट्ये</div>
                    <p>Our results speak for themselves – consistent top rankings and academic excellence.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/bdc648100a594967894c69c8fec8b484.jpg" alt="Character" class="card-img" />
                    <h3>Character Building</h3>
                    <div class="marathi">आम्ही स्पर्धक नाही, गुणवंत विद्यार्थी घडवतो</div>
                    <p>We don't just create competitors; we build meritorious individuals with strong values.</p>
                </div>
                <div class="tradition-card">
                    <img src="http://192.0.0.2:5600/uploads/6fa342602bc048029f7871c64da5c815.jpg" alt="Foundation" class="card-img" />
                    <h3>Our Foundation</h3>
                    <div class="marathi">शिस्त आणि अनुभव हीच आमची ओळख</div>
                    <p>Discipline and deep teaching experience form the bedrock of our institution.</p>
                </div>
            </div>

            <!-- Salient Features -->
            <h2 class="section-title mt-2"><i class="fas fa-list-check"></i> Our Salient Features</h2>
            <div class="card card-premium">
                <ul class="features-list">
                    <li>Well Qualified, Experienced and Expert Teachers</li>
                    <li>Personal Attention to every student</li>
                    <li>Focus on Basic Concepts</li>
                    <li>All Subjects Preparation in class</li>
                    <li>Library facilities available freely</li>
                    <li>Weekly & Chapter wise test series</li>
                    <li>Group Discussion during the Exam</li>
                    <li>Personality Development for the students</li>
                    <li>E-Learning Capabilities</li>
                    <li>Limited Strength / Batch Capacity</li>
                    <li>10th Moderator Interaction Sessions</li>
                    <li>Individual Career Counseling Track</li>
                    <li>Open Day & Parents Seminar</li>
                    <li>Matru Pitru Din (Parents' Day) celebrations</li>
                    <li>Social & Cultural events</li>
                </ul>
            </div>

            <!-- Quality vs Quantity Philosophy -->
            <div class="card mt-2" style="background: linear-gradient(135deg, var(--primary), var(--primary-light)); color: white; text-align: center;">
                <h2 style="color: var(--gold); font-family: var(--font-serif);">What do you prefer? Quality or Quantity?</h2>
                <p style="max-width: 700px; margin: 0.5rem auto; font-size:1.1rem;">
                    At Shree Parth Academy, we believe in <strong>quality over quantity</strong>. 
                    We limit batch sizes to ensure every student receives individual attention and a focused learning experience. 
                    Our results are a testament to this philosophy – consistently high percentages and top ranks.
                </p>
                <p style="font-weight:600; color:var(--gold-light);">If you value quality education, call us today!</p>
                <button class="btn-gold" onclick="showToast('📞 Call us at +91 8605688883')" style="width:auto; margin-top:0.5rem;">
                    <i class="fas fa-phone"></i> Contact Now
                </button>
            </div>

            <!-- Location & Contact -->
            <div class="grid-2col mt-2">
                <div>
                    <div class="card card-premium">
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-location-dot"></i> Our Location</h3>
                        <p>
                            <strong>Ground Floor, Tryambak Heaven 2,</strong><br>
                            Beside Of Holy Spirit High School,<br>
                            Surval Chowk, Midc Shirgaon,<br>
                            Badlapur (E) – 421503.
                        </p>
                        <div class="map-container mt-2">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m17!1m12!1m3!1d3769.456789012345!2d73.12345678901234!3d19.12345678901234!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m2!1m1!2zMTnCsDA3JzI0LjUiTiA3M8KwMDcnMjQuNSJF!5e0!3m2!1sen!2sin!4v1700000000000" allowfullscreen="" loading="lazy"></iframe>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="card card-premium">
                        <h3 style="color: var(--gold); font-family: var(--font-serif);"><i class="fas fa-address-card"></i> Contact Details</h3>
                        <p><i class="fas fa-phone" style="color:var(--gold);"></i> <strong>Phone:</strong><br>
                        +91 8605688883<br>
                        +91 9221838267<br>
                        +91 9011395913<br>
                        +91 7709935795</p>
                        <p><i class="fas fa-envelope" style="color:var(--gold);"></i> <strong>Email:</strong><br>
                        shreeparthacademy2009@gmail.com</p>
                        <p><i class="fas fa-clock" style="color:var(--gold);"></i> <strong>Timings:</strong><br>
                        Mon-Sat: Regular Batches<br>
                        Sunday: Moderator Sessions & Test Series</p>
                        <p style="margin-top:1rem; background:var(--gold-gradient); padding:0.5rem; border-radius:8px; color:var(--primary); font-weight:700; text-align:center;">
                            ✦ ESTD: 2009 – 15+ Years of Excellence ✦
                        </p>
                    </div>
                </div>
            </div>

            <!-- Our Jewels (Toppers) Summary -->
            <div class="card card-premium mt-2">
                <h3 style="color:var(--gold);"><i class="fas fa-trophy"></i> Our Jewels – SSC Toppers</h3>
                <p>Every year, our students shine in the SSC board exams with remarkable results. Here are some of our top performers:</p>
                <div style="display:grid; grid-template-columns:repeat(auto-fit, minmax(180px,1fr)); gap:0.5rem; margin-top:0.5rem;">
                    <div style="background:#f8fafc; padding:0.5rem; border-radius:8px; text-align:center;"><strong>Vaishnavi Sawant</strong> – 95.80%</div>
                    <div style="background:#f8fafc; padding:0.5rem; border-radius:8px; text-align:center;"><strong>Vaishnavi Patil</strong> – 95.20%</div>
                    <div style="background:#f8fafc; padding:0.5rem; border-radius:8px; text-align:center;"><strong>Sushmita Ahirrao</strong> – 94.73%</div>
                    <div style="background:#f8fafc; padding:0.5rem; border-radius:8px; text-align:center;"><strong>Anand Khismatrao</strong> – 93.82%</div>
                </div>
                <p style="margin-top:0.5rem; text-align:center;">
                    <a href="#" onclick="document.querySelector('.nav-links a[data-page=\'toppers\']').click(); return false;" style="color:var(--gold); font-weight:600;">View full toppers list →</a>
                </p>
            </div>
        </div>

        <!-- ===== TOPPERS PAGE ===== -->
        <div id="toppersPage" class="page">
            <h2 class="section-title"><i class="fas fa-trophy"></i> Our Jewels of SSC</h2>
            <div class="card card-premium">
                <h3 style="color:var(--gold);"><i class="fas fa-medal"></i> SSC TOPPERS IN SPA</h3>
                <div style="overflow-x:auto;">
                    <table class="toppers-table">
                        <thead><tr><th>Rank</th><th>Name</th><th>Percentage</th></tr></thead>
                        <tbody>
                            <tr><td class="rank">1</td><td>Vaishnavi Sawant</td><td>95.80%</td></tr>
                            <tr><td class="rank">2</td><td>Vaishnavi Patil</td><td>95.20%</td></tr>
                            <tr><td class="rank">3</td><td>Sushmita Ahirrao</td><td>94.73%</td></tr>
                            <tr><td class="rank">4</td><td>Anand Khismatrao</td><td>93.82%</td></tr>
                            <tr><td class="rank">5</td><td>Bhawna Chouhan</td><td>93.40%</td></tr>
                            <tr><td class="rank">6</td><td>Srushti Agnihotri</td><td>93.00%</td></tr>
                            <tr><td class="rank">7</td><td>Katrap Vidyalaya</td><td>93.00%</td></tr>
                            <tr><td class="rank">8</td><td>Heaven Bell</td><td>93.00%</td></tr>
                        </tbody>
                    </table>
                </div>
            </div>
            <div class="card card-premium mt-2">
                <h3 style="color:var(--gold);"><i class="fas fa-star"></i> SSC TOPPERS IN SPA (Extended)</h3>
                <div style="overflow-x:auto;">
                    <table class="toppers-table">
                        <thead><tr><th>Rank</th><th>Name</th><th>Percentage</th></tr></thead>
                        <tbody>
                            <tr><td class="rank">1</td><td>Priyanka Thite</td><td>92.91%</td></tr>
                            <tr><td class="rank">2</td><td>Samiksha Yelve</td><td>91.60%</td></tr>
                            <tr><td class="rank">3</td><td>Abhijeet Howal</td><td>92.91%</td></tr>
                            <tr><td class="rank">4</td><td>Tejal Jadhav</td><td>92.91%</td></tr>
                            <tr><td class="rank">5</td><td>Sonal Surve</td><td>92.60%</td></tr>
                            <tr><td class="rank">6</td><td>Divya Gaikwad</td><td>92.40%</td></tr>
                            <tr><td class="rank">7</td><td>Ankita Shankpal</td><td>92.40%</td></tr>
                            <tr><td class="rank">8</td><td>Aditya Narayane</td><td>92.40%</td></tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>

        <!-- ===== GALLERY PAGE ===== -->
        <div id="galleryPage" class="page">
            <h2 class="section-title"><i class="fas fa-images"></i> Premium Image Gallery</h2>
            <div class="card no-print">
                <h3><i class="fas fa-cloud-upload-alt" style="color:var(--gold);"></i> Upload Images</h3>
                <div class="upload-zone" id="imageUploadZone">
                    <i class="fas fa-image"></i>
                    <p><strong>Drop your images here</strong> or click to browse</p>
                    <div class="file-input">
                        <input type="file" id="imageFileInput" accept="image/*" multiple />
                    </div>
                    <button class="btn-gold" id="uploadImageBtn" style="width:auto; padding:0.6rem 2rem; margin-top:1rem;">
                        <i class="fas fa-upload"></i> Upload Images
                    </button>
                </div>
                <div id="imageUploadStatus" style="margin-top:0.5rem; font-weight:500; color:var(--gold);"></div>
            </div>

            <!-- Gallery images -->
            <div class="image-gallery" id="imageGallery">
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/1ef7dfef89bd4c7b8341cd82deaa5ddd.jpg" alt="Campus" />
                    <div class="badge">Campus</div>
                    <div class="overlay">Main Campus • 2024</div>
                </div>
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/b557634d17544e1fb5766c75cd0e528e.jpg" alt="Teachers" />
                    <div class="badge">Faculty</div>
                    <div class="overlay">Expert Teachers • 2024</div>
                </div>
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/97050c4faaef45b5872f42c8b6ecd34e.jpg" alt="Students" />
                    <div class="badge">Students</div>
                    <div class="overlay">Top Performers • 2024</div>
                </div>
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/556c20067c4343e888bdf8b8739bbacc.jpg" alt="Library" />
                    <div class="badge">Library</div>
                    <div class="overlay">Digital Library • 2024</div>
                </div>
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/1c73d89899ca4b3784be40931bf78135.jpg" alt="Events" />
                    <div class="badge">Events</div>
                    <div class="overlay">Van Bhojan Excursion • 2024</div>
                </div>
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/3bed272f96df4dcbb5e8c5e0f7b7d36c.jpg" alt="Awards" />
                    <div class="badge">Awards</div>
                    <div class="overlay">Prize Distribution • 2024</div>
                </div>
                <!-- Extra image (13th) -->
                <div class="gallery-item">
                    <img src="http://192.0.0.2:5600/uploads/ae15e1a7e1464396ac89233e9bd66a4f.jpg" alt="Extra" />
                    <div class="badge">Extra</div>
                    <div class="overlay">Special Moment • 2024</div>
                </div>
            </div>
        </div>

        <!-- ===== ACTIVITIES PAGE ===== -->
        <div id="activitiesPage" class="page">
            <h2 class="section-title"><i class="fas fa-calendar-alt"></i> Activities & Events</h2>
            <div class="grid-2col">
                <div>
                    <div class="card card-premium">
                        <h3><i class="fas fa-list" style="color:var(--gold);"></i> Upcoming Activities</h3>
                        <div class="activity-list" id="activityList">
                            <div class="activity-item"><i class="fas fa-chalkboard-teacher"></i><span>10th Moderator Session</span><span class="date">Today 4pm</span><span class="status ongoing">Ongoing</span></div>
                            <div class="activity-item"><i class="fas fa-users"></i><span>Parent-Teacher Meet</span><span class="date">Fri 10am</span><span class="status upcoming">Upcoming</span></div>
                            <div class="activity-item"><i class="fas fa-pencil-alt"></i><span>Weekly Test Series</span><span class="date">Sat 8am</span><span class="status upcoming">Upcoming</span></div>
                            <div class="activity-item"><i class="fas fa-tree"></i><span>Van Bhojan Excursion</span><span class="date">Next Mon</span><span class="status upcoming">Upcoming</span></div>
                            <div class="activity-item"><i class="fas fa-star"></i><span>Career Counseling</span><span class="date">Wed 2pm</span><span class="status upcoming">Upcoming</span></div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="card card-premium">
                        <h3><i class="fas fa-plus-circle" style="color:var(--gold);"></i> Manage Activities</h3>
                        <div class="flex">
                            <button class="btn-gold" id="addActivityBtn" style="width:auto; padding:0.6rem 1.5rem;"><i class="fas fa-plus"></i> Add Activity</button>
                            <button class="btn-outline" id="resetActivitiesBtn"><i class="fas fa-sync-alt"></i> Reset</button>
                        </div>
                        <div id="activityFeedback" style="margin-top:1rem; font-weight:500; color:var(--gold);"></div>
                        <hr style="margin:1.5rem 0; border-color:#e2e8f0;">
                        <h4><i class="fas fa-calendar-check" style="color:var(--gold);"></i> Quick Stats</h4>
                        <div class="grid-3col" style="margin-top:0.5rem;">
                            <div class="stat-card" style="padding:1rem;"><span class="number" style="font-size:1.8rem;">12</span><span class="label">Total Activities</span></div>
                            <div class="stat-card" style="padding:1rem;"><span class="number" style="font-size:1.8rem; color:var(--gold);">5</span><span class="label">This Month</span></div>
                            <div class="stat-card" style="padding:1rem;"><span class="number" style="font-size:1.8rem; color:#2a9d8f;">3</span><span class="label">Completed</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- ===== PAYMENT PAGE ===== -->
        <div id="paymentPage" class="page">
            <h2 class="section-title"><i class="fas fa-credit-card"></i> Payment Portal</h2>
            <div class="grid-2col">
                <div>
                    <div class="card card-premium">
                        <h3><i class="fas fa-hand-holding-usd" style="color:var(--gold);"></i> Make a Payment</h3>
                        <div class="input-group">
                            <label>Amount (₹)</label>
                            <input type="number" placeholder="Enter amount" value="5000" />
                        </div>
                        <div class="input-group">
                            <label>Payment For</label>
                            <select>
                                <option>Tuition Fees</option>
                                <option>Exam Fees</option>
                                <option>Library Fees</option>
                                <option>Other</option>
                            </select>
                        </div>
                        <button class="btn-gold" style="width:100%;" onclick="showToast('💳 Payment processing... (Demo)')">
                            <i class="fas fa-lock"></i> Pay Now
                        </button>
                    </div>
                </div>
                <div>
                    <div class="card card-premium">
                        <h3><i class="fas fa-qrcode" style="color:var(--gold);"></i> Quick Pay Options</h3>
                        <div class="payment-options">
                            <div class="payment-option" onclick="showToast('📱 UPI: shreeparth@upi')"><i class="fas fa-mobile-alt"></i><span class="label">UPI</span></div>
                            <div class="payment-option" onclick="showToast('💳 Card payment coming soon')"><i class="fas fa-credit-card"></i><span class="label">Card</span></div>
                            <div class="payment-option" onclick="showToast('🏦 Bank Transfer: HDFC Bank - 1234567890')"><i class="fas fa-university"></i><span class="label">Bank</span></div>
                            <div class="payment-option" onclick="showToast('📱 PhonePe: +91 8605688883')"><i class="fas fa-phone"></i><span class="label">PhonePe</span></div>
                        </div>
                        <div class="mt-2 text-center" style="background:#f8fafc; padding:1rem; border-radius:12px;">
                            <p style="color:#64748b; font-size:0.9rem;"><i class="fas fa-shield-alt" style="color:var(--gold);"></i> Secure payments powered by encrypted gateway</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ===== FOOTER ===== -->
    <footer class="footer">
        <div class="footer-grid">
            <div>
                <div class="footer-logo">
                    <img src="http://192.0.0.2:5600/uploads/9ef2c6a4fcd04765b5d4ecde996e7f4c.jpg" alt="Shree Parth Academy Logo" />
                    <div>
                        <h4 style="border:none; margin:0;">Shree Parth Academy™</h4>
                        <p style="color:var(--gold);">An Emperor of Knowledge</p>
                    </div>
                </div>
                <p style="margin-top:0.5rem;">ESTD: 2009</p>
                <p style="color:var(--gold);">"We strive for our student's success."</p>
            </div>
            <div>
                <h4>Contact</h4>
                <p><i class="fas fa-phone"></i> +91 8605688883</p>
                <p><i class="fas fa-phone"></i> +91 9221838267</p>
                <p><i class="fas fa-phone"></i> +91 9011395913</p>
                <p><i class="fas fa-phone"></i> +91 7709935795</p>
                <p><i class="fas fa-envelope"></i> shreeparthacademy2009@gmail.com</p>
            </div>
            <div>
                <h4>Location</h4>
                <p>Ground Floor, Tryambak Heaven 2,<br>Beside Holy Spirit High School,<br>Surval Chowk, Midc Shirgaon,<br>Badlapur (E).</p>
            </div>
            <div>
                <h4>Timings</h4>
                <p>Mon-Sat: Regular Batches</p>
                <p>Sunday: Moderator Sessions</p>
                <p style="color:var(--gold); font-weight:700; font-family:var(--font-serif);">✦ ESTD: 2009 ✦</p>
            </div>
        </div>
        <div class="footer-bottom">
            <p>&copy; 2026 Shree Parth Academy™. All Rights Reserved. Premium World-Class Education.</p>
        </div>
    </footer>

    <script>
        // ============================================================
        // LANGUAGE SYSTEM (simplified)
        // ============================================================
        let currentLang = 'en';
        document.querySelectorAll('.lang-btn').forEach(btn => {
            btn.addEventListener('click', function() {
                document.querySelectorAll('.lang-btn').forEach(b => b.classList.remove('active'));
                this.classList.add('active');
                currentLang = this.dataset.lang;
                showToast('🌐 Language switched to ' + this.textContent);
            });
        });

        // ============================================================
        // AUTH SYSTEM
        // ============================================================
        let isLoggedIn = false;
        const loginForm = document.getElementById('loginForm');
        const loginNavBtn = document.getElementById('loginNavBtn');
        const logoutBtn = document.getElementById('logoutBtn');
        const userDisplay = document.getElementById('userDisplay');
        const usernameLabel = document.getElementById('usernameLabel');
        const roleBadge = document.getElementById('roleBadge');

        function login(username, role) {
            isLoggedIn = true;
            usernameLabel.textContent = username;
            roleBadge.textContent = role.charAt(0).toUpperCase() + role.slice(1);
            userDisplay.classList.remove('hidden');
            loginNavBtn.classList.add('hidden');
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('homePage').classList.add('active');
            document.querySelectorAll('.nav-links a[data-page]').forEach(a => a.classList.remove('active'));
            document.querySelector('.nav-links a[data-page="home"]').classList.add('active');
            showToast('👋 Welcome ' + username + ' (' + role + ')');
        }

        function logout() {
            isLoggedIn = false;
            userDisplay.classList.add('hidden');
            loginNavBtn.classList.remove('hidden');
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('loginPage').classList.add('active');
            showToast('👋 Logged out');
        }

        loginForm.addEventListener('submit', function(e) {
            e.preventDefault();
            const user = document.getElementById('usernameInput').value.trim();
            const pass = document.getElementById('passwordInput').value.trim();
            if (user && pass) {
                const role = document.querySelector('.role-option.active').dataset.role;
                login(user, role);
            } else {
                showToast('⚠️ Please enter username and password');
            }
        });

        loginNavBtn.addEventListener('click', function() {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('loginPage').classList.add('active');
        });
        logoutBtn.addEventListener('click', logout);

        // Role selector
        document.querySelectorAll('.role-option').forEach(opt => {
            opt.addEventListener('click', function() {
                document.querySelectorAll('.role-option').forEach(o => o.classList.remove('active'));
                this.classList.add('active');
            });
        });

        // ============================================================
        // TOAST
        // ============================================================
        function showToast(message) {
            const toast = document.getElementById('toast');
            document.getElementById('toastMessage').textContent = message;
            toast.classList.add('show');
            clearTimeout(toast._timeout);
            toast._timeout = setTimeout(() => toast.classList.remove('show'), 3000);
        }

        // ============================================================
        // IMAGE UPLOAD (Gallery)
        // ============================================================
        document.getElementById('uploadImageBtn').addEventListener('click', function() {
            const files = document.getElementById('imageFileInput').files;
            if (!files || files.length === 0) {
                document.getElementById('imageUploadStatus').textContent = '⚠️ Please select image files first.';
                return;
            }
            const gallery = document.getElementById('imageGallery');
            Array.from(files).forEach(file => {
                const reader = new FileReader();
                reader.onload = function(e) {
                    const item = document.createElement('div');
                    item.className = 'gallery-item';
                    item.innerHTML = `
                        <img src="${e.target.result}" alt="${file.name}" />
                        <div class="badge">Uploaded</div>
                        <div class="overlay">${file.name}</div>
                    `;
                    gallery.prepend(item);
                };
                reader.readAsDataURL(file);
            });
            document.getElementById('imageUploadStatus').textContent = `✅ ${files.length} image(s) uploaded!`;
            document.getElementById('imageFileInput').value = '';
            setTimeout(() => document.getElementById('imageUploadStatus').textContent = '', 4000);
        });

        // Drag & drop
        const zone = document.getElementById('imageUploadZone');
        zone.addEventListener('dragover', e => { e.preventDefault(); zone.classList.add('dragover'); });
        zone.addEventListener('dragleave', () => zone.classList.remove('dragover'));
        zone.addEventListener('drop', e => {
            e.preventDefault();
            zone.classList.remove('dragover');
            const files = e.dataTransfer.files;
            if (files.length) {
                document.getElementById('imageFileInput').files = files;
                document.getElementById('imageUploadStatus').textContent = `📎 ${files.length} file(s) selected`;
            }
        });

        // ============================================================
        // ACTIVITIES MANAGEMENT
        // ============================================================
        const defaultActivities = [
            { icon: 'fa-chalkboard-teacher', text: '10th Moderator Session', date: 'Today 4pm', status: 'ongoing' },
            { icon: 'fa-users', text: 'Parent-Teacher Meet', date: 'Fri 10am', status: 'upcoming' },
            { icon: 'fa-pencil-alt', text: 'Weekly Test Series', date: 'Sat 8am', status: 'upcoming' },
            { icon: 'fa-tree', text: 'Van Bhojan Excursion', date: 'Next Mon', status: 'upcoming' },
            { icon: 'fa-star', text: 'Career Counseling', date: 'Wed 2pm', status: 'upcoming' }
        ];
        let activities = [...defaultActivities];
        const activityList = document.getElementById('activityList');
        const activityFeedback = document.getElementById('activityFeedback');

        function renderActivities() {
            activityList.innerHTML = '';
            activities.forEach(act => {
                const div = document.createElement('div');
                div.className = 'activity-item';
                div.innerHTML = `
                    <i class="fas ${act.icon}"></i>
                    <span>${act.text}</span>
                    <span class="date">${act.date}</span>
                    <span class="status ${act.status}">${act.status}</span>
                `;
                activityList.appendChild(div);
            });
        }

        document.getElementById('addActivityBtn').addEventListener('click', function() {
            activities.push({ icon: 'fa-calendar-plus', text: `New Activity #${activities.length+1}`, date: 'Just now', status: 'upcoming' });
            renderActivities();
            activityFeedback.textContent = '✅ Activity added!';
            setTimeout(() => activityFeedback.textContent = '', 3000);
        });

        document.getElementById('resetActivitiesBtn').addEventListener('click', function() {
            activities = [...defaultActivities];
            renderActivities();
            activityFeedback.textContent = '↺ Reset to default.';
            setTimeout(() => activityFeedback.textContent = '', 3000);
        });
        renderActivities();

        // ============================================================
        // NAVIGATION (page switching)
        // ============================================================
        document.querySelectorAll('.nav-links a[data-page]').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const page = this.dataset.page;
                if (!isLoggedIn && page !== 'home' && page !== 'about' && page !== 'toppers') {
                    showToast('🔒 Please login first');
                    return;
                }
                document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
                document.getElementById(page + 'Page').classList.add('active');
                document.querySelectorAll('.nav-links a[data-page]').forEach(a => a.classList.remove('active'));
                this.classList.add('active');
            });
        });

        // If logged out, default to login page
        if (!isLoggedIn) {
            document.querySelectorAll('.page').forEach(p => p.classList.remove('active'));
            document.getElementById('loginPage').classList.add('active');
        }

        console.log('🏛️ Shree Parth Academy™ · Detailed About Us page added');
        console.log('📸 All images loaded from http://192.0.0.2:5600/uploads/');
        console.log('🌐 Bilingual ready (EN, MR, SEMI)');
        console.log('👥 Roles: Student, Teacher, Admin, Parent');
        console.log('🔐 Login: any username/password');
    </script>
</body>
</html>
