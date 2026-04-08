<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Semih KABA | Siber Güvenlik Uzmanı - 3D Ultimate Cyber Card</title>
    
    <!-- Google Fonts & Font Awesome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:opsz,wght@14..32,300;14..32,400;14..32,600;14..32,700;14..32,800&family=Share+Tech+Mono&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    
    <!-- Three.js -->
    <script type="importmap">
        {
            "imports": {
                "three": "https://cdn.jsdelivr.net/npm/three@0.128.0/build/three.module.js"
            }
        }
    </script>
    
    <style>
        /* =========================================
           TEMEL AYARLAR & TYPOGRAPHY
           ========================================= */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Inter', 'Share Tech Mono', monospace;
            overflow-x: hidden; /* Dikey scroll izni verilir, yatay scroll engellenir */
            background-color: #010a14;
            color: #eef5ff;
        }

        /* =========================================
           3D CANVAS ARKA PLAN
           ========================================= */
        #canvas-container {
            position: fixed;
            top: 0;
            left: 0;
            width: 100vw;
            height: 100vh;
            z-index: 0;
            pointer-events: none; /* Arka planın tıklamaları engellememesi için */
        }

        /* =========================================
           İÇERİK VE KARTVİZİT DÜZENİ
           ========================================= */
        .content {
            position: relative;
            z-index: 10;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 2rem;
            /* Arka planın çok hafif bulanıklaşması içeriği öne çıkarır */
            background: radial-gradient(circle at center, transparent 0%, rgba(1, 10, 20, 0.4) 100%);
        }

        /* Ana Kart - Gelişmiş Glassmorphism & Cyberpunk Neon */
        .business-card {
            background: rgba(5, 15, 25, 0.65);
            backdrop-filter: blur(20px);
            -webkit-backdrop-filter: blur(20px);
            border-radius: 2rem;
            border: 1px solid rgba(0, 255, 255, 0.3);
            /* İç gölge ile cama derinlik katma */
            box-shadow: 
                inset 0 0 20px rgba(0, 255, 255, 0.05), 
                0 30px 60px rgba(0, 0, 0, 0.8), 
                0 0 30px rgba(0, 255, 255, 0.15);
            max-width: 600px;
            width: 100%;
            padding: 3rem 2.5rem;
            transition: transform 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275), box-shadow 0.4s ease, border-color 0.4s ease;
            animation: floatCard 8s infinite ease-in-out;
        }

        .business-card:hover {
            transform: translateY(-12px) scale(1.02);
            box-shadow: 
                inset 0 0 30px rgba(0, 255, 255, 0.1), 
                0 40px 70px rgba(0, 0, 0, 0.9), 
                0 0 50px rgba(0, 255, 255, 0.4);
            border-color: rgba(0, 255, 255, 0.8);
        }

        @keyframes floatCard {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-12px); }
            100% { transform: translateY(0px); }
        }

        /* =========================================
           KART BAŞLIĞI (Rozet ve Buton İçerir)
           ========================================= */
        .card-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 1.5rem;
            flex-wrap: wrap; /* Dar ekranlarda alt alta geçmesi için */
            gap: 1rem;
        }

        /* Rozet: Siber Güvenlik Uzmanı */
        .badge-cyber {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: rgba(0, 30, 50, 0.8);
            backdrop-filter: blur(4px);
            border-radius: 50px;
            padding: 0.5rem 1.2rem;
            font-size: 0.75rem;
            font-weight: 700;
            letter-spacing: 1px;
            color: #0ff;
            border: 1px solid rgba(0, 255, 255, 0.5);
            text-transform: uppercase;
            font-family: 'Share Tech Mono', monospace;
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.2);
        }

        /* YENİ: Kart İçi Devam Et Butonu */
        .continue-btn-card {
            display: inline-flex;
            align-items: center;
            gap: 8px;
            background: linear-gradient(135deg, rgba(0, 255, 255, 0.1) 0%, rgba(0, 100, 200, 0.1) 100%);
            backdrop-filter: blur(8px);
            padding: 0.6rem 1.4rem;
            border-radius: 50px;
            text-decoration: none;
            font-weight: 700;
            font-size: 0.85rem;
            font-family: 'Inter', sans-serif;
            letter-spacing: 1px;
            color: #0ff;
            border: 1px solid rgba(0, 255, 255, 0.6);
            box-shadow: 0 0 15px rgba(0, 255, 255, 0.2);
            transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
            text-transform: uppercase;
            position: relative;
            overflow: hidden;
        }

        /* Buton Hover Efekti */
        .continue-btn-card::before {
            content: '';
            position: absolute;
            top: 0; left: -100%;
            width: 100%; height: 100%;
            background: linear-gradient(90deg, transparent, rgba(0, 255, 255, 0.4), transparent);
            transition: left 0.5s ease;
        }

        .continue-btn-card:hover {
            background: rgba(0, 255, 255, 0.2);
            box-shadow: 0 0 25px rgba(0, 255, 255, 0.6);
            color: #fff;
            transform: translateY(-2px);
            border-color: #0ff;
        }

        .continue-btn-card:hover::before {
            left: 100%;
        }

        .continue-btn-card i {
            transition: transform 0.3s ease;
        }

        .continue-btn-card:hover i {
            transform: translateX(4px);
        }

        /* =========================================
           İSİM VE ÜNVANLAR
           ========================================= */
        h1 {
            font-size: 3.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #ffffff 0%, #00ffff 50%, #3c8aff 100%);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            letter-spacing: -1px;
            margin-bottom: 0.3rem;
            text-shadow: 0 0 20px rgba(0, 255, 255, 0.2);
        }

        .title-main {
            font-size: 1.05rem;
            font-weight: 500;
            color: #b3ecff;
            border-left: 3px solid #0ff;
            padding-left: 1rem;
            margin: 0.8rem 0 1.5rem;
            font-family: 'Share Tech Mono', monospace;
            letter-spacing: 0.5px;
        }

        /* =========================================
           BİLGİ IZGARASI (Info Grid)
           ========================================= */
        .info-grid {
            display: flex;
            flex-direction: column;
            gap: 1.2rem;
            margin: 2rem 0;
        }

        .info-item {
            display: flex;
            align-items: center;
            gap: 1.2rem;
            background: rgba(0, 20, 35, 0.6);
            border-radius: 1.2rem;
            padding: 1rem 1.5rem;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(0, 255, 255, 0.15);
            transition: all 0.3s ease;
        }

        .info-item:hover {
            border-color: rgba(0, 255, 255, 0.4);
            background: rgba(0, 35, 55, 0.7);
            transform: translateX(5px);
        }

        .info-item i {
            font-size: 1.6rem;
            width: 2rem;
            color: #0ff;
            text-align: center;
            text-shadow: 0 0 10px rgba(0, 255, 255, 0.6);
        }

        .info-item .label {
            font-weight: 600;
            font-size: 0.75rem;
            text-transform: uppercase;
            letter-spacing: 1.5px;
            color: #7fc9ff;
            margin-bottom: 2px;
        }

        .info-item .value {
            font-weight: 700;
            font-size: 1.05rem;
            color: #fff;
        }

        /* =========================================
           YETENEKLER (Skills Section)
           ========================================= */
        .skills-section {
            margin: 2.5rem 0;
        }

        .skill {
            margin-bottom: 1.5rem;
        }

        .skill-header {
            display: flex;
            justify-content: space-between;
            font-size: 0.9rem;
            font-weight: 600;
            margin-bottom: 8px;
            color: #d4f1ff;
            letter-spacing: 0.5px;
        }

        .skill-header i {
            color: #0ff;
            width: 24px;
            text-shadow: 0 0 5px rgba(0, 255, 255, 0.5);
        }

        .skill-bar-bg {
            height: 8px;
            background: rgba(0, 20, 35, 0.8);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: inset 0 2px 4px rgba(0,0,0,0.6);
            border: 1px solid rgba(0, 255, 255, 0.1);
        }

        .skill-bar {
            height: 100%;
            width: 0%;
            background: linear-gradient(90deg, #0055ff, #00ffff, #ffffff);
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 255, 255, 0.8), 0 0 20px rgba(0, 255, 255, 0.4);
            transition: width 1.5s cubic-bezier(0.22, 1, 0.36, 1); /* Daha yumuşak dolum */
            position: relative;
        }
        
        /* Bar uçlarındaki parlak nokta */
        .skill-bar::after {
            content: '';
            position: absolute;
            right: 0;
            top: 0;
            height: 100%;
            width: 15px;
            background: rgba(255, 255, 255, 0.8);
            box-shadow: 0 0 15px #fff;
            border-radius: 50%;
            filter: blur(2px);
        }

        /* =========================================
           SOSYAL MEDYA LİNKLERİ
           ========================================= */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 2.5rem;
            flex-wrap: wrap;
        }

        .social-btn {
            background: rgba(0, 20, 35, 0.7);
            backdrop-filter: blur(6px);
            border-radius: 3rem;
            padding: 0.8rem 1.6rem;
            display: inline-flex;
            align-items: center;
            gap: 0.8rem;
            text-decoration: none;
            font-weight: 600;
            font-size: 0.95rem;
            color: #eef5ff;
            border: 1px solid rgba(0, 255, 255, 0.3);
            transition: all 0.3s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            font-family: 'Inter', sans-serif;
            box-shadow: 0 5px 15px rgba(0,0,0,0.3);
        }

        .social-btn i {
            font-size: 1.3rem;
            color: #0ff;
            transition: color 0.3s ease;
        }

        .social-btn:hover {
            background: rgba(0, 150, 255, 0.2);
            border-color: #0ff;
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 255, 255, 0.3), 0 0 15px rgba(0, 255, 255, 0.2);
            color: #fff;
        }

        .social-btn:hover i {
            color: #fff;
            text-shadow: 0 0 10px #fff;
        }

        /* =========================================
           FOOTER BÖLÜMÜ
           ========================================= */
        .security-footer {
            margin-top: 2.5rem;
            text-align: center;
            font-size: 0.75rem;
            color: #5aa9dd;
            border-top: 1px dashed rgba(0, 255, 255, 0.2);
            padding-top: 1.5rem;
            display: flex;
            justify-content: center;
            gap: 1.5rem;
            flex-wrap: wrap;
            font-family: 'Share Tech Mono', monospace;
        }

        .security-footer span {
            display: flex;
            align-items: center;
            gap: 5px;
            transition: color 0.3s ease;
        }
        
        .security-footer span:hover {
            color: #0ff;
            text-shadow: 0 0 5px #0ff;
        }

        /* =========================================
           MEDYA SORGULARI (RESPONSIVE TASARIM)
           ========================================= */
        @media (max-width: 650px) {
            .business-card {
                padding: 2.5rem 1.8rem;
            }
            h1 { font-size: 2.8rem; }
            .card-header { justify-content: center; flex-direction: column; text-align: center; }
        }

        @media (max-width: 550px) {
            .content { padding: 1rem; }
            .business-card {
                padding: 2rem 1.2rem;
                border-radius: 1.5rem;
            }
            h1 { font-size: 2.2rem; text-align: center; }
            .title-main { font-size: 0.85rem; text-align: center; border-left: none; padding-left: 0; }
            
            .card-header {
                flex-direction: column;
                align-items: stretch;
                gap: 12px;
            }
            .badge-cyber { justify-content: center; font-size: 0.7rem; }
            .continue-btn-card { justify-content: center; width: 100%; }
            
            .social-btn { padding: 0.6rem 1.2rem; font-size: 0.85rem; width: 100%; justify-content: center; }
            .info-item { padding: 0.8rem; flex-direction: column; text-align: center; gap: 0.5rem; }
            .info-item i { width: 100%; }
        }

        /* İkon Efektleri */
        .fa-shield-haltered, .fa-skull, .fa-shield-alt, .fa-microchip {
            filter: drop-shadow(0 0 4px cyan);
        }
    </style>
</head>
<body>

    <!-- 3D Arka Plan Konteyneri -->
    <div id="canvas-container"></div>

    <!-- İçerik Başlangıcı -->
    <div class="content">
        <div class="business-card">
            
            <!-- ÜST BAŞLIK (ROZET VE BUTON BİR ARADA) -->
            <div class="card-header">
                <div class="badge-cyber">
                    <i class="fas fa-shield-haltered"></i> SİBER GÜVENLİK UZMANI <i class="fas fa-lock"></i>
                </div>
                
                <!-- YENİ EKLENEN KART İÇİ DEVAM ET BUTONU -->
                <a href="https://semihkaba.com/d.html" id="continueLink" class="continue-btn-card" target="_blank" rel="noopener noreferrer">
                    <span>DEVAM ET</span>
                    <i class="fas fa-arrow-right"></i>
                </a>
            </div>

            <!-- Kişisel Bilgiler -->
            <h1>Semih KABA</h1>
            <div class="title-main">
                <i class="fas fa-terminal"></i> CYBER SECURITY EXPERT | Red & Blue Team | Digital Forensics
            </div>

            <!-- Veri Izgarası -->
            <div class="info-grid">
                <div class="info-item">
                    <i class="fas fa-user-astronaut"></i>
                    <div>
                        <div class="label">YAŞ</div>
                        <div class="value">23</div>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fas fa-globe-europe"></i>
                    <div>
                        <div class="label">KONUM / LOCATION</div>
                        <div class="value">İstanbul, Türkiye / Remote</div>
                    </div>
                </div>
                <div class="info-item">
                    <i class="fas fa-certificate"></i>
                    <div>
                        <div class="label">UZMANLIK ALANI</div>
                        <div class="value">Siber Güvenlik Uzmanı (Offensive & Defensive)</div>
                    </div>
                </div>
            </div>

            <!-- Yetenek Barları -->
            <div class="skills-section">
                <div class="skill">
                    <div class="skill-header">
                        <span><i class="fas fa-skull"></i> RED TEAM (Offensive Security)</span>
                        <span>94%</span>
                    </div>
                    <div class="skill-bar-bg"><div class="skill-bar" data-width="94"></div></div>
                </div>
                <div class="skill">
                    <div class="skill-header">
                        <span><i class="fas fa-shield-alt"></i> BLUE TEAM (Defense & Monitoring)</span>
                        <span>90%</span>
                    </div>
                    <div class="skill-bar-bg"><div class="skill-bar" data-width="90"></div></div>
                </div>
                <div class="skill">
                    <div class="skill-header">
                        <span><i class="fas fa-search"></i> DIGITAL FORENSICS (Adli Bilişim)</span>
                        <span>88%</span>
                    </div>
                    <div class="skill-bar-bg"><div class="skill-bar" data-width="88"></div></div>
                </div>
                <div class="skill">
                    <div class="skill-header">
                        <span><i class="fas fa-code-branch"></i> SECURE SOFTWARE DEV (Güvenli Yazılım)</span>
                        <span>86%</span>
                    </div>
                    <div class="skill-bar-bg"><div class="skill-bar" data-width="86"></div></div>
                </div>
            </div>

            <!-- Sosyal Linkler -->
            <div class="social-links">
                <a href="https://linkedin.com/in/semihkaba" target="_blank" class="social-btn" rel="noopener noreferrer">
                    <i class="fab fa-linkedin-in"></i> LinkedIn
                </a>
                <a href="https://github.com/mrsemihkaba" target="_blank" class="social-btn" rel="noopener noreferrer">
                    <i class="fab fa-github"></i> GitHub
                </a>
                <a href="mailto:semih.kaba@cyberdefense.com" class="social-btn">
                    <i class="fas fa-envelope"></i> E-posta
                </a>
                <a href="#" class="social-btn" id="cyberCvBtn">
                    <i class="fas fa-file-alt"></i> Cyber Profile
                </a>
            </div>

            <!-- Alt Güvenlik Sembolleri -->
            <div class="security-footer">
                <span><i class="fas fa-shield-virus"></i> Red Team Ops</span>
                <span><i class="fas fa-chart-line"></i> Blue Team SIEM</span>
                <span><i class="fas fa-fingerprint"></i> Forensic Readiness</span>
                <span><i class="fas fa-lock"></i> Zero Trust</span>
            </div>
        </div>
    </div>

    <!-- Etkileşim ve 3D Modül Scripti -->
    <script type="module">
        import * as THREE from 'three';

        // ==========================================
        // 1. 3D SAHNE KURULUMU - ULTIMATE CYBER VIBE
        // ==========================================
        const container = document.getElementById('canvas-container');
        const scene = new THREE.Scene();
        scene.background = new THREE.Color(0x010a14);
        scene.fog = new THREE.FogExp2(0x010a14, 0.005);

        const camera = new THREE.PerspectiveCamera(42, window.innerWidth / window.innerHeight, 0.1, 1000);
        camera.position.set(0, 1.6, 8.5); // Kamerayı biraz geriye çektik
        camera.lookAt(0, 0.5, 0);

        const renderer = new THREE.WebGLRenderer({ antialias: true, alpha: false });
        renderer.setSize(window.innerWidth, window.innerHeight);
        renderer.setPixelRatio(Math.min(window.devicePixelRatio, 2)); // Performans optimizasyonu
        container.appendChild(renderer.domElement);

        // ==========================================
        // 2. IŞIKLANDIRMA: NEON CYBERPUNK
        // ==========================================
        const ambientLight = new THREE.AmbientLight(0x0a1428, 1.5);
        scene.add(ambientLight);
        
        const keyLight = new THREE.DirectionalLight(0xffffff, 1.2);
        keyLight.position.set(2, 4, 3);
        scene.add(keyLight);
        
        const backLight = new THREE.PointLight(0x2266ff, 1);
        backLight.position.set(-2, 1.5, -5);
        scene.add(backLight);
        
        const fillCyan = new THREE.PointLight(0x00ffff, 0.8);
        fillCyan.position.set(2.5, 2, 2.5);
        scene.add(fillCyan);
        
        const movingLight = new THREE.PointLight(0xff00aa, 0.6);
        movingLight.position.set(1, 1, 2);
        scene.add(movingLight);

        // ==========================================
        // 3. 3D NESNELER: SİBER ÇEKİRDEK & HALKALAR
        // ==========================================
        const coreGroup = new THREE.Group();
        
        // Merkez Küre (Veri Çekirdeği)
        const sphereGeo = new THREE.SphereGeometry(1.05, 64, 64);
        const sphereMat = new THREE.MeshStandardMaterial({ 
            color: 0x0a2a4a, 
            emissive: 0x004466, 
            emissiveIntensity: 0.5, 
            metalness: 0.9, 
            roughness: 0.1, 
            transparent: true, 
            opacity: 0.7 
        });
        const coreSphere = new THREE.Mesh(sphereGeo, sphereMat);
        coreGroup.add(coreSphere);
        
        // Dış Wireframe Küre
        const wireframeGeo = new THREE.SphereGeometry(1.22, 32, 32);
        const wireframeMat = new THREE.MeshBasicMaterial({ 
            color: 0x00ffff, 
            wireframe: true, 
            transparent: true, 
            opacity: 0.25 
        });
        const wireframeSphere = new THREE.Mesh(wireframeGeo, wireframeMat);
        coreGroup.add(wireframeSphere);
        
        // Kırmızı Halka (Red Team Temsili)
        const ringRedPoints = [];
        const ringRadius = 1.6;
        const seg = 100;
        for (let i = 0; i <= seg; i++) {
            const ang = (i / seg) * Math.PI * 2;
            ringRedPoints.push(new THREE.Vector3(Math.cos(ang) * ringRadius, 0.1, Math.sin(ang) * ringRadius));
        }
        const ringRedGeo = new THREE.BufferGeometry().setFromPoints(ringRedPoints);
        const ringRedMat = new THREE.LineBasicMaterial({ color: 0xff0055, linewidth: 2 });
        const redRing = new THREE.LineLoop(ringRedGeo, ringRedMat);
        coreGroup.add(redRing);
        
        // Mavi Halka (Blue Team Temsili)
        const ringBluePoints = [];
        for (let i = 0; i <= seg; i++) {
            const ang = (i / seg) * Math.PI * 2;
            ringBluePoints.push(new THREE.Vector3(0.1, Math.sin(ang) * ringRadius, Math.cos(ang) * ringRadius));
        }
        const ringBlueGeo = new THREE.BufferGeometry().setFromPoints(ringBluePoints);
        const ringBlueMat = new THREE.LineBasicMaterial({ color: 0x00aaff, linewidth: 2 });
        const blueRing = new THREE.LineLoop(ringBlueGeo, ringBlueMat);
        coreGroup.add(blueRing);
        
        // Parçacık Bulutu (Veri Akışı)
        const particleCount = 2000;
        const particlesGeo = new THREE.BufferGeometry();
        const positions = new Float32Array(particleCount * 3);
        for (let i = 0; i < particleCount; i++) {
            const rad = 1.8 + Math.random() * 1.5;
            const theta2 = Math.random() * Math.PI * 2;
            const phi2 = Math.acos(2 * Math.random() - 1);
            positions[i*3] = rad * Math.sin(phi2) * Math.cos(theta2);
            positions[i*3+1] = rad * Math.sin(phi2) * Math.sin(theta2);
            positions[i*3+2] = rad * Math.cos(phi2);
        }
        particlesGeo.setAttribute('position', new THREE.BufferAttribute(positions, 3));
        const particleMat = new THREE.PointsMaterial({ 
            color: 0x00ffff, 
            size: 0.03, 
            transparent: true, 
            opacity: 0.6,
            blending: THREE.AdditiveBlending 
        });
        const particleSys = new THREE.Points(particlesGeo, particleMat);
        coreGroup.add(particleSys);
        
        // Merkez Torus Knot (Kalkan/Çekirdek Sembolü)
        const knotGeo = new THREE.TorusKnotGeometry(0.65, 0.08, 128, 16, 3, 4);
        const knotMat = new THREE.MeshStandardMaterial({ 
            color: 0x00ffff, 
            emissive: 0x0088aa, 
            emissiveIntensity: 0.8, 
            metalness: 1.0 
        });
        const knotMesh = new THREE.Mesh(knotGeo, knotMat);
        coreGroup.add(knotMesh);
        
        // Parlayan Neon Halkalar
        const glowRingGeo = new THREE.TorusGeometry(1.4, 0.015, 64, 200);
        const neonMat = new THREE.MeshStandardMaterial({ color: 0x00ffff, emissive: 0x00ffff, emissiveIntensity: 1 });
        const neonRing = new THREE.Mesh(glowRingGeo, neonMat);
        neonRing.rotation.x = Math.PI / 2;
        coreGroup.add(neonRing);
        
        const neonRing2 = new THREE.Mesh(glowRingGeo, neonMat);
        neonRing2.rotation.z = Math.PI / 2.5;
        neonRing2.rotation.x = 0.8;
        coreGroup.add(neonRing2);
        
        // Grubu sahnenin hafif sağına alıyoruz ki mobilde tam ortalansın
        coreGroup.position.x = 0; 
        scene.add(coreGroup);

        // ==========================================
        // 4. ARKA PLAN: MATRİS IZGARALARI & KOD PARÇACIKLARI
        // ==========================================
        const gridHelper = new THREE.GridHelper(30, 40, 0x00ffff, 0x003366);
        gridHelper.position.y = -3;
        gridHelper.material.transparent = true;
        gridHelper.material.opacity = 0.15;
        scene.add(gridHelper);
        
        const codeParticleCount = 1500;
        const codeParticlesGeo = new THREE.BufferGeometry();
        const codePositionsArray = new Float32Array(codeParticleCount * 3);
        for (let i = 0; i < codeParticleCount; i++) {
            codePositionsArray[i*3] = (Math.random() - 0.5) * 40;
            codePositionsArray[i*3+1] = (Math.random() - 0.5) * 20;
            codePositionsArray[i*3+2] = (Math.random() - 0.5) * 30 - 10;
        }
        codeParticlesGeo.setAttribute('position', new THREE.BufferAttribute(codePositionsArray, 3));
        const codePointMat = new THREE.PointsMaterial({ color: 0x00ccff, size: 0.05, transparent: true, opacity: 0.5 });
        const codeParticlesObj = new THREE.Points(codeParticlesGeo, codePointMat);
        scene.add(codeParticlesObj);

        // ==========================================
        // 5. ANİMASYON DÖNGÜSÜ (RENDER LOOP)
        // ==========================================
        let time = 0;
        
        function animate3D() {
            requestAnimationFrame(animate3D);
            time += 0.005; // Animasyon hızını biraz yavaşlattım (daha asil bir his için)
            
            // Çekirdek Dönüşleri
            coreGroup.rotation.y = time * 0.4;
            coreGroup.rotation.x = Math.sin(time * 0.2) * 0.15;
            coreGroup.rotation.z = Math.cos(time * 0.3) * 0.1;
            
            // İç Objelerin Bağımsız Hareketi
            redRing.rotation.z += 0.005;
            blueRing.rotation.x += 0.007;
            neonRing.rotation.z += 0.008;
            neonRing2.rotation.y -= 0.006;
            knotMesh.rotation.x = time * 0.6;
            knotMesh.rotation.y = time * 0.9;
            particleSys.rotation.y = time * 0.15;
            
            // Dinamik Işık Renk Değişimi
            const hueVal = (time * 0.5) % (Math.PI * 2);
            movingLight.color.setHSL(hueVal / (Math.PI * 2), 1, 0.5);
            fillCyan.intensity = 0.6 + Math.sin(time * 2) * 0.3;
            
            // Arka Plan Hareketi
            codeParticlesObj.rotation.y += 0.0005;
            codeParticlesObj.position.y = Math.sin(time) * 0.5;

            // Farenin konumuna göre çok hafif kamera paralaks efekti eklenebilir (opsiyonel)
            
            renderer.render(scene, camera);
        }
        
        // Yüklenir yüklenmez animasyonu başlat
        window.onload = function() {
            animate3D();
            
            // Yetenek Barlarını Doldur
            setTimeout(() => {
                const bars = document.querySelectorAll('.skill-bar');
                bars.forEach(bar => {
                    const widthVal = bar.getAttribute('data-width');
                    if (widthVal) bar.style.width = widthVal + '%';
                });
            }, 500);
        };
        
        // ==========================================
        // 6. EKRAN BOYUTU DEĞİŞİMİ (RESPONSIVE 3D)
        // ==========================================
        window.addEventListener('resize', () => {
            camera.aspect = window.innerWidth / window.innerHeight;
            camera.updateProjectionMatrix();
            renderer.setSize(window.innerWidth, window.innerHeight);
        });
        
        // ==========================================
        // 7. ETKİLEŞİMLER VE BUTON KONTROLLERİ
        // ==========================================
        console.log("%c🔥 SEMIH KABA | RED & BLUE TEAM | DIGITAL FORENSICS | SİBER GÜVENLİK UZMANI 🔥", "color: #0ff; font-size: 14px; font-weight: bold; background: #000; padding: 4px; border-radius: 4px;");
        
        const continueBtn = document.getElementById('continueLink');
        continueBtn.addEventListener('click', (e) => {
            // href="#" bırakılırsa uyarı ver
            if(continueBtn.getAttribute('href') === "#") {
                e.preventDefault();
                alert("Yönlendirilecek bağlantı URL'si henüz tanımlanmadı. HTML içindeki href='...' kısmını düzenleyebilirsiniz.");
            }
        });

        const cyberProfileBtn = document.getElementById('cyberCvBtn');
        if(cyberProfileBtn) {
            cyberProfileBtn.addEventListener('click', (e) => {
                e.preventDefault();
                alert("[ YETKİLİ ERİŞİMİ SAĞLANDI ]\n\nSemih KABA | Siber Güvenlik Uzmanı \nRed Team, Blue Team, Adli Bilişim alanlarında aktif. \nDetaylı CV için LinkedIn üzerinden iletişime geçiniz.");
            });
        }
    </script>
</body>
</html>
