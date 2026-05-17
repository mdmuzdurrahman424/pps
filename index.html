<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Premium Member Portal - Exclusive Access</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #ff0055;
            --primary-hover: #e6004c;
            --secondary: #1e293b;
            --dark: #0f172a;
            --card-bg: #1e293b;
            --border: rgba(255, 255, 255, 0.1);
        }

        * { box-sizing: border-box; margin: 0; padding: 0; }

        body {
            background-color: var(--dark);
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
            color: #ffffff;
            padding-bottom: 40px;
        }

        /* Header section with radial gradient */
        .header {
            text-align: center;
            padding: 50px 20px;
            background: radial-gradient(circle at top, rgba(255, 0, 85, 0.15), transparent);
            border-bottom: 1px solid var(--border);
        }

        .profile-container { position: relative; width: 120px; height: 120px; margin: 0 auto 20px; }
        .profile-img { width: 100%; height: 100%; border-radius: 50%; border: 3px solid var(--primary); object-fit: cover; box-shadow: 0 0 20px rgba(255, 0, 85, 0.4); }
        .status-badge { position: absolute; bottom: 5px; right: 5px; background: #22c55e; color: white; padding: 4px 12px; border-radius: 20px; font-size: 11px; font-weight: bold; border: 2px solid var(--dark); }

        h1 { font-size: 28px; font-weight: 800; margin-bottom: 10px; letter-spacing: -0.5px; }
        .sub-text { color: #94a3b8; font-size: 15px; max-width: 500px; margin: 0 auto; line-height: 1.5; }

        /* Main CTA Container */
        .cta-container { max-width: 500px; margin: 30px auto; padding: 0 20px; }
        .main-link-btn { 
            display: block; 
            width: 100%; 
            background: linear-gradient(135deg, var(--primary) 0%, #ff4d6d 100%); 
            color: #ffffff; 
            text-decoration: none; 
            text-align: center; 
            padding: 18px 25px; 
            border-radius: 50px; 
            font-size: 16px; 
            font-weight: 700; 
            letter-spacing: 0.5px; 
            box-shadow: 0 10px 25px rgba(255, 0, 85, 0.3); 
            transition: transform 0.2s, opacity 0.2s; 
        }
        .main-link-btn:hover { transform: translateY(-2px); opacity: 0.95; }

        /* Premium Media Gallery Grid */
        .gallery-heading { max-width: 1000px; margin: 40px auto 15px; padding: 0 20px; font-size: 14px; text-transform: uppercase; letter-spacing: 1px; color: #64748b; font-weight: 700; }
        .gallery-container { max-width: 1000px; margin: 0 auto; padding: 0 20px; display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 20px; }
        
        .video-card { 
            background: var(--card-bg); 
            border-radius: 16px; 
            overflow: hidden; 
            border: 1px solid var(--border); 
            transition: transform 0.3s, border-color 0.3s; 
            color: white; 
            position: relative; 
            display: block; 
            cursor: pointer; 
            text-decoration: none;
        }
        .video-card:hover { transform: scale(1.03); border-color: var(--primary); }
        
        .thumbnail { width: 100%; aspect-ratio: 16/9; background: #0f172a; position: relative; display: flex; align-items: center; justify-content: center; }
        .thumb-img { position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; opacity: 0.6; }
        
        .lock-overlay { position: absolute; top: 12px; right: 12px; background: rgba(0,0,0,0.6); padding: 6px 10px; border-radius: 8px; font-size: 12px; display: flex; align-items: center; gap: 5px; backdrop-filter: blur(4px); }
        .play-btn { position: absolute; background: var(--primary); width: 44px; height: 44px; border-radius: 50%; display: flex; align-items: center; justify-content: center; box-shadow: 0 4px 15px rgba(255, 0, 85, 0.4); z-index: 2; }
        .play-triangle { width: 0; height: 0; border-top: 8px solid transparent; border-left: 14px solid white; border-bottom: 8px solid transparent; margin-left: 4px; }
        
        .video-info { padding: 15px; font-size: 14px; background: #1e293b; font-weight: 600; border-top: 1px solid var(--border); }

        /* Layout Footer */
        .site-footer { text-align: center; padding: 40px 20px; margin-top: 60px; border-top: 1px solid var(--border); background: #0b0f19; }
        .footer-text { font-size: 12px; color: #475569; line-height: 1.8; max-width: 600px; margin: 0 auto; }

        /* Subscription Modal Mechanism */
        .modal-overlay { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.8); backdrop-filter: blur(4px); display: none; align-items: center; justify-content: center; z-index: 9999; padding: 20px; }
        .modal-content { background: #1e293b; border: 1px solid var(--border); border-radius: 24px; max-width: 450px; width: 100%; padding: 35px 25px; text-align: center; position: relative; animation: popIn 0.3s ease-out forwards; }
        @keyframes popIn { 0% { transform: scale(0.9); opacity: 0; } 100% { transform: scale(1); opacity: 1; } }
        
        .close-btn { position: absolute; top: 15px; right: 15px; background: rgba(255,255,255,0.1); border: none; color: white; width: 32px; height: 32px; border-radius: 50%; cursor: pointer; font-size: 14px; }
        .modal-icon { font-size: 48px; color: var(--primary); margin-bottom: 15px; }
        .modal-title { font-size: 24px; font-weight: 800; color: #ffffff; margin-bottom: 12px; }
        .modal-desc { font-size: 15px; color: #cbd5e1; line-height: 1.6; margin-bottom: 25px; }

        @media (max-width: 600px) {
            .gallery-container { grid-template-columns: repeat(1, 1fr); }
            h1 { font-size: 24px; }
        }
    </style>
</head>
<body>

    <div class="header">
        <div class="profile-container">
            <img src="https://github.com/mizan000321-ops/newv/blob/main/G3UZgO_XMAAzE6N.jpg?raw=true" alt="Creator Profile" class="profile-img">
            <span class="status-badge">ONLINE</span>
        </div>
        <h1>Exclusive Member Portal</h1>
        <p class="sub-text">Welcome to my private content hub. Unlock premium access to explore all exclusive updates, high-quality streams, and archival content.</p>
    </div>

    <div class="cta-container">
        <a href="YOUR_AFFILIATE_OR_PORTAL_LINK_HERE" class="main-link-btn">
            <i class="fa-solid fa-unlock-keyhole" style="margin-right: 8px;"></i> UNLOCK FULL PORTAL ACCESS
        </a>
    </div>

    <div class="gallery-heading">Premium Archive Grid:</div>
    <div class="gallery-container">
        
        <div class="video-card" onclick="openModal()">
            <div class="thumbnail">
                <img src="https://github.com/mizan000321-ops/newv/blob/main/G3UZgO_XMAAzE6N.jpg?raw=true" class="thumb-img">
                <div class="lock-overlay"><i class="fa-solid fa-lock"></i> Premium</div>
                <div class="play-btn"><div class="play-triangle"></div></div>
            </div>
            <div class="video-info">Exclusive Vault Video #01</div>
        </div>

        <div class="video-card" onclick="openModal()">
            <div class="thumbnail">
                <img src="https://github.com/mizan000321-ops/newv/blob/main/GoWoZl9X0AA1I6V.jpg?raw=true" class="thumb-img">
                <div class="lock-overlay"><i class="fa-solid fa-lock"></i> Premium</div>
                <div class="play-btn"><div class="play-triangle"></div></div>
            </div>
            <div class="video-info">Exclusive Vault Video #02</div>
        </div>

        <div class="video-card" onclick="openModal()">
            <div class="thumbnail">
                <img src="https://github.com/mizan000321-ops/newv/blob/main/Gv2LKn_XwAAsWou.jpg?raw=true" class="thumb-img">
                <div class="lock-overlay"><i class="fa-solid fa-lock"></i> Premium</div>
                <div class="play-btn"><div class="play-triangle"></div></div>
            </div>
            <div class="video-info">Exclusive Vault Video #03</div>
        </div>

    </div>

    <div class="site-footer">
        <div class="footer-text">
            <strong>SECURE & ENCRYPTED HUB CONNECTION</strong><br><br>
            Please ensure you comply with standard registration terms and legal age guidelines applicable in your jurisdiction. All data transmission is handled safely under standard web privacy protocols.<br><br>
            © 2026 Member Portal Node Access. All rights reserved.
        </div>
    </div>

    <div id="premiumModal" class="modal-overlay">
        <div class="modal-content">
            <button class="close-btn" onclick="closeModal()">✕</button>
            <div class="modal-icon"><i class="fa-solid fa-lock"></i></div>
            <div class="modal-title">Premium Verification Required</div>
            <div class="modal-desc">
                This media content is reserved exclusively for registered premium community members. Complete your network verification setup to unlock full grid streams and updates.
            </div>
            
            <a href="YOUR_AFFILIATE_OR_PORTAL_LINK_HERE" class="main-link-btn" style="box-shadow: none;">
                <i class="fa-solid fa-key" style="margin-right: 8px;"></i> PROCEED TO VERIFICATION
            </a>
        </div>
    </div>

    <script>
        function openModal() { document.getElementById("premiumModal").style.display = "flex"; }
        function closeModal() { document.getElementById("premiumModal").style.display = "none"; }
    </script>
</body>
</html>
