#Cam's Repository
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Name] | Class of 2027 Baseball Recruiting</title>
    <style>
        :root {
            --primary: #0f2027;
            --accent: #c8102e;
            --light: #f4f6f9;
            --text: #222222;
        }
        * { box-sizing: border-box; margin: 0; padding: 0; font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif; }
        body { background-color: var(--light); color: var(--text); line-height: 1.6; }
        
        /* Header / Hero */
        header {
            background: var(--primary);
            color: white;
            padding: 3rem 1.5rem;
            text-align: center;
            border-bottom: 5px solid var(--accent);
        }
        header h1 { font-size: 2.5rem; letter-spacing: 1px; text-transform: uppercase; }
        header p { font-size: 1.1rem; color: #d1d5db; margin-top: 0.5rem; }

        /* Container */
        .container { max-width: 960px; margin: 2rem auto; padding: 0 1.5rem; }

        /* Quick Stats Bar */
        .stats-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
            gap: 1rem;
            margin-bottom: 2.5rem;
        }
        .stat-card {
            background: white;
            padding: 1.25rem;
            border-radius: 8px;
            text-align: center;
            box-shadow: 0 2px 6px rgba(0,0,0,0.06);
        }
        .stat-card h3 { font-size: 0.85rem; text-transform: uppercase; color: #6b7280; }
        .stat-card p { font-size: 1.4rem; font-weight: bold; color: var(--primary); margin-top: 0.25rem; }

        /* Sections */
        section { margin-bottom: 3rem; }
        h2 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #e5e7eb;
            color: var(--primary);
        }

        /* Video Grid */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
        }
        .video-card {
            background: white;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 6px rgba(0,0,0,0.06);
        }
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
        }
        .video-wrapper iframe {
            position: absolute;
            top: 0; left: 0;
            width: 100%; height: 100%;
            border: 0;
        }
        .video-info { padding: 1rem; }
        .video-info h3 { font-size: 1.1rem; margin-bottom: 0.25rem; }
        .video-info p { font-size: 0.9rem; color: #4b5563; }

        /* Bio & Contact Box */
        .info-box {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 6px rgba(0,0,0,0.06);
        }
        .info-list { list-style: none; display: grid; grid-template-columns: repeat(auto-fit, minmax(220px, 1fr)); gap: 0.75rem; }
        .info-list li strong { color: var(--primary); }

        footer { text-align: center; padding: 2rem; color: #6b7280; font-size: 0.9rem; }
    </style>
</head>
<body>

    <header>
        <h1>[Your Full Name]</h1>
        <p>Class of [2027] &bull; [Primary Pos / Secondary Pos] &bull; Bats/Throws: [R/R]</p>
    </header>

    <div class="container">
        <!-- Key Metrics -->
        <div class="stats-grid">
            <div class="stat-card"><h3>Height / Weight</h3><p>[6'1" / 185 lbs]</p></div>
            <div class="stat-card"><h3>60-Yard Dash</h3><p>[6.75 sec]</p></div>
            <div class="stat-card"><h3>Exit Velocity</h3><p>[94 mph]</p></div>
            <div class="stat-card"><h3>Fastball / INF Velo</h3><p>[88 mph]</p></div>
            <div class="stat-card"><h3>GPA</h3><p>[3.85]</p></div>
        </div>

        <!-- Game & Showcase Footage -->
        <section>
            <h2>Recruiting &amp; Game Footage</h2>
            <div class="video-grid">
                
                <!-- Video 1 -->
                <div class="video-card">
                    <div class="video-wrapper">
                        <!-- Replace VIDEO_ID_1 with your YouTube video ID -->
                        <iframe src="https://youtube.com" allowfullscreen></iframe>
                    </div>
                    <div class="video-info">
                        <h3>Fall 2026 Skills &amp; Bullpen Showcase</h3>
                        <p>Hitting rounds, defensive footwork, and full bullpen session with TrackMan metrics.</p>
                    </div>
                </div>

                <!-- Video 2 -->
                <div class="video-card">
                    <div class="video-wrapper">
                        <!-- Replace VIDEO_ID_2 with your YouTube video ID -->
                        <iframe src="https://youtube.com" allowfullscreen></iframe>
                    </div>
                    <div class="video-info">
                        <h3>Summer Travel Ball Game Highlights</h3>
                        <p>In-game at-bats and defensive plays from [Tournament Name].</p>
                    </div>
                </div>

            </div>
        </section>

        <!-- Player & Coach Contact -->
        <section>
            <h2>Player &amp; Coach Contact</h2>
            <div class="info-box">
                <ul class="info-list">
                    <li><strong>High School:</strong> [Your High School, State]</li>
                    <li><strong>Travel Team:</strong> [Your Travel Org]</li>
                    <li><strong>Player Email:</strong> [your.email@example.com]</li>
                    <li><strong>Player Phone:</strong> [(555) 123-4567]</li>
                    <li><strong>HS Coach:</strong> [Coach Name] ([coach@school.edu])</li>
                    <li><strong>Travel Coach:</strong> [Coach Name] ([coach@travel.com])</li>
                </ul>
            </div>
        </section>
    </div>

    <footer>
        &copy; 2026 [Your Full Name] Baseball Recruiting
    </footer>

</body>
</html>
