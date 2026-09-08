<svg fill="none" viewBox="0 0 1200 2800" width="1200" height="2800" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        * {
          box-sizing: border-box;
          margin: 0;
          padding: 0;
        }

        .wrapper {
          width: 1200px;
          height: 2800px;
          background-color: #0d1117;
          background-image: 
            linear-gradient(90deg, #1a1f2e 1px, transparent 1px),
            linear-gradient(180deg, #1a1f2e 1px, transparent 1px);
          background-size: 40px 40px;
          background-position: -1px -1px;
          position: relative;
          font-family: 'Inter', system-ui, -apple-system, BlinkMacSystemFont, Helvetica, Arial, sans-serif;
          color: #e6edf3;
          overflow: hidden;
          border: 4px solid #e32636;
        }

        .mark { position: absolute; width: 24px; height: 24px; z-index: 20; }
        .m-tl { top: 16px; left: 16px; border-top: 3px solid #e32636; border-left: 3px solid #e32636; }
        .m-tr { top: 16px; right: 16px; border-top: 3px solid #e32636; border-right: 3px solid #e32636; }
        .m-bl { bottom: 16px; left: 16px; border-bottom: 3px solid #e32636; border-left: 3px solid #e32636; }
        .m-br { bottom: 16px; right: 16px; border-bottom: 3px solid #e32636; border-right: 3px solid #e32636; }

        .container {
          position: absolute;
          top: 40px;
          left: 60px;
          width: calc(100% - 120px);
          height: calc(100% - 80px);
          z-index: 10;
          display: flex;
          flex-direction: column;
        }

        .header-section {
          display: flex;
          justify-content: space-between;
          height: 520px;
          position: relative;
        }

        .col-main { display: flex; flex-direction: column; justify-content: space-between; width: 65%; }
        .col-art { width: 30%; display: flex; flex-direction: column; justify-content: space-between; align-items: flex-end; position: relative; }

        .header-block { margin-top: 10px; }
        .bauhaus-red-block { width: 80px; height: 16px; background-color: #e32636; margin-bottom: 24px; }

        h1 {
          font-family: 'Inter', system-ui, -apple-system, sans-serif;
          font-size: 82px;
          font-weight: 900;
          line-height: 0.85;
          letter-spacing: -4px;
          text-transform: uppercase;
          color: #e6edf3;
          margin: 0 0 24px 0;
        }

        .roles-container { display: flex; align-items: center; background-color: #e32636; padding: 12px 20px; width: fit-content; }
        .role { font-family: 'Space Grotesk', ui-monospace, SFMono-Regular, monospace; font-size: 16px; font-weight: 700; color: #0d1117; letter-spacing: 2px; }
        .separator { color: #0d1117; font-size: 10px; margin: 0 16px; }

        .manifest-list { display: flex; flex-direction: column; gap: 0; margin-bottom: 10px; width: 85%; }
        .manifest-item { display: flex; align-items: center; padding: 12px 0; border-bottom: 2px solid #30363d; font-size: 15px; font-weight: 700; letter-spacing: 1.5px; text-transform: uppercase; color: #e6edf3; }
        .manifest-item:first-child { border-top: 2px solid #30363d; }
        .item-num { font-family: ui-monospace, SFMono-Regular, monospace; color: #e32636; font-weight: 700; font-size: 14px; width: 40px; }

        .geometry-container { position: absolute; top: -20px; right: -20px; width: 320px; height: 320px; z-index: 1; }
        .geo-circle { position: absolute; top: 20px; right: 20px; width: 200px; height: 200px; background-color: #e32636; border-radius: 50%; opacity: 0.3; }
        .geo-square { position: absolute; bottom: 20px; left: 20px; width: 160px; height: 160px; background-color: #2d9cdb; opacity: 0.3; }
        .geo-lines {
          position: absolute; top: 80px; left: -40px; width: 240px; height: 180px;
          background-image: repeating-linear-gradient(-45deg, transparent, transparent 12px, #f2c94c 12px, #f2c94c 16px);
          opacity: 0.3;
        }

        .sys-container { display: flex; flex-direction: column; align-items: flex-end; margin-top: auto; margin-bottom: 10px; z-index: 10; }
        .barcode { display: flex; height: 48px; margin-bottom: 12px; }
        .bar { background: #e6edf3; height: 100%; margin-left: 4px; }
        .b1{width:6px;} .b2{width:14px;} .b3{width:4px;} .b4{width:10px;} .b5{width:24px;} .b6{width:8px;} .b7{width:4px;} .b8{width:18px;} .b9{width:6px;}

        .sys-data { font-family: ui-monospace, SFMono-Regular, monospace; font-size: 11px; color: #e6edf3; text-align: right; font-weight: 700; letter-spacing: 1px; line-height: 1.6; }
        @keyframes mechanical-blink { 0%, 49% { opacity: 1; } 50%, 100% { opacity: 0; } }
        .status-dot { display: inline-block; width: 10px; height: 10px; background-color: #2d9cdb; border-radius: 50%; margin-right: 8px; animation: mechanical-blink 2s infinite linear; }

        .content-block {
          margin-top: 60px;
          padding-top: 40px;
          border-top: 4px solid #30363d;
        }

        .section-header {
          display: flex;
          align-items: center;
          margin-bottom: 48px;
        }
        
        .section-title {
          font-family: 'Inter', system-ui, sans-serif;
          font-size: 42px;
          font-weight: 900;
          letter-spacing: -2px;
          text-transform: uppercase;
          color: #e6edf3;
        }

        .section-dot {
          width: 16px;
          height: 16px;
          background-color: #e32636;
          margin-right: 20px;
        }

        .grid-2-col {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 60px;
        }

        .sub-heading {
          font-family: 'Inter', system-ui, sans-serif;
          font-size: 20px;
          font-weight: 700;
          text-transform: uppercase;
          letter-spacing: 1px;
          border-bottom: 2px solid #30363d;
          padding-bottom: 12px;
          margin-bottom: 24px;
          display: flex;
          align-items: center;
          justify-content: space-between;
          color: #e6edf3;
        }

        .text-body {
          font-size: 17px;
          line-height: 1.6;
          font-weight: 500;
          margin-bottom: 24px;
          color: #c9d1d9;
        }

        .bold-hl { font-weight: 900; background-color: #e32636; color: #0d1117; padding: 2px 6px; }

        .timeline-item {
          border-left: 3px solid #e32636;
          padding-left: 24px;
          margin-bottom: 32px;
          position: relative;
        }
        .timeline-item::before {
          content: ''; position: absolute; left: -9px; top: 0; width: 15px; height: 15px; background: #e32636; border: 2px solid #e6edf3;
        }
        
        .timeline-title { font-size: 20px; font-weight: 900; margin-bottom: 8px; color: #e6edf3; }
        .timeline-date { font-family: ui-monospace, SFMono-Regular, monospace; font-size: 14px; font-weight: 700; color: #e32636; margin-bottom: 12px; display: block; }
        .timeline-desc { font-size: 16px; line-height: 1.5; font-weight: 500; color: #c9d1d9; }

        .win-row {
          display: flex;
          align-items: center;
          padding: 16px 0;
          border-bottom: 1px solid rgba(48, 54, 61, 0.5);
        }
        .win-row:last-child { border-bottom: none; }
        .win-rank {
          font-family: ui-monospace, SFMono-Regular, monospace;
          font-size: 24px;
          font-weight: 900;
          color: #e32636;
          width: 90px;
        }
        .win-rank.gold { color: #f2c94c; text-shadow: 0 0 20px rgba(242, 201, 76, 0.3); }
        .win-title { font-size: 18px; font-weight: 700; flex-grow: 1; color: #e6edf3; }
        .win-year { font-family: ui-monospace, SFMono-Regular, monospace; font-size: 14px; font-weight: 700; color: #8b949e; }

        .tech-category { margin-bottom: 40px; }
        .tech-category-title {
          font-family: ui-monospace, SFMono-Regular, monospace;
          font-size: 14px;
          font-weight: 700;
          text-transform: uppercase;
          letter-spacing: 2px;
          margin-bottom: 16px;
          color: #8b949e;
        }
        .tech-grid {
          display: flex;
          flex-wrap: wrap;
          gap: 12px;
        }
        .tech-tag {
          font-family: 'Inter', system-ui, sans-serif;
          font-size: 15px;
          font-weight: 700;
          padding: 8px 16px;
          border: 2px solid #30363d;
          background: transparent;
          color: #e6edf3;
          text-transform: uppercase;
        }
        .tech-tag.primary { background: #e32636; color: #0d1117; border-color: #e32636; }
        .tech-tag.accent { background: #2d9cdb; color: #0d1117; border-color: #2d9cdb; }
        .tech-tag.blue { background: #1f6feb; color: #e6edf3; border-color: #1f6feb; }
        .tech-tag.yellow { background: #f2c94c; color: #0d1117; border-color: #f2c94c; }
        .tech-tag.green { background: #2ea043; color: #0d1117; border-color: #2ea043; }

        .footer-block {
          margin-top: auto;
          background: #161b22;
          color: #e6edf3;
          padding: 20px;
          display: flex;
          justify-content: space-between;
          align-items: center;
          border-top: 2px solid #30363d;
        }
        .contact-info { display: flex; flex-direction: column; gap: 12px; }
        .contact-item { font-family: ui-monospace, SFMono-Regular, monospace; font-size: 16px; font-weight: 700; color: #c9d1d9; }
        .contact-item a { color: #e32636; text-decoration: none; }
        .contact-item a:hover { text-decoration: underline; }
        .quote { font-size: 18px; font-style: italic; max-width: 500px; text-align: right; line-height: 1.5; color: #8b949e; }
      </style>

      <div class="wrapper">
        <div class="mark m-tl"></div>
        <div class="mark m-tr"></div>
        <div class="mark m-bl"></div>
        <div class="mark m-br"></div>

        <div class="container">
          
          <div class="header-section">
            <div class="col-main">
              <div class="header-block">
                <div class="bauhaus-red-block"></div>
                <h1>JOHN<br/>YAZBECK</h1>
                <div class="roles-container">
                  <span class="role">SOFTWARE ENGINEER</span>
                  <span class="separator">■</span>
                  <span class="role">FULL-STACK</span>
                  <span class="separator">■</span>
                  <span class="role">CTF HUNTER</span>
                </div>
              </div>

              <div class="manifest-list">
                <div class="manifest-item"><span class="item-num">01</span><span>BUILDING SCALABLE SYSTEMS</span></div>
                <div class="manifest-item"><span class="item-num">02</span><span>BREAKING THINGS LEGALLY</span></div>
                <div class="manifest-item"><span class="item-num">03</span><span>MOBILE &amp; WEB CRAFTSMAN</span></div>
                <div class="manifest-item"><span class="item-num">04</span><span>LIFELONG LEARNER</span></div>
              </div>
            </div>

            <div class="col-art">
              <div class="geometry-container">
                <div class="geo-lines"></div>
                <div class="geo-square"></div>
                <div class="geo-circle"></div>
              </div>
              <div class="sys-container">
                <div class="barcode">
                  <div class="bar b1"></div><div class="bar b2"></div><div class="bar b3"></div>
                  <div class="bar b4"></div><div class="bar b5"></div><div class="bar b6"></div>
                  <div class="bar b7"></div><div class="bar b8"></div><div class="bar b9"></div>
                </div>
                <div class="sys-data">
                  REF_ID: JY-2026<br/>
                  <span class="status-dot"></span>SYS_STATUS: ACTIVE<br/>
                  MODE: BUILDING
                </div>
              </div>
            </div>
          </div>

          <div class="content-block">
            <div class="section-header">
              <div class="section-dot"></div>
              <h2 class="section-title">Operations &amp; Objectives</h2>
            </div>
            
            <div class="grid-2-col">
              <div>
                <div class="sub-heading">Current Scope</div>
                <p class="text-body">
                  <span class="bold-hl">Software Engineering Graduate</span> from HELB Ilya Prigogine (Brussels) with a strong foundation in computer science and hands-on experience through academic projects and an internship at <span class="bold-hl">MyGridEnergy</span>. Passionate about backend development, software architecture, and AI-powered applications.
                </p>
                <div class="timeline-item">
                  <div class="timeline-title">MyGridEnergy</div>
                  <span class="timeline-date">Internship 2026</span>
                  <div class="timeline-desc">Applied academic knowledge in a professional environment, working on real-world software development projects and gaining industry experience.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">Independent Development</div>
                  <span class="timeline-date">Ongoing</span>
                  <div class="timeline-desc">Building full-stack applications with <strong>Java, C#, Python, React &amp; Django</strong>. Creating cross-platform mobile apps with <strong>.NET MAUI &amp; React Native</strong>.</div>
                </div>
              </div>

              <div>
                <div class="sub-heading">CTF Engagements</div>
                <div class="win-row">
                  <div class="win-rank gold">🏆</div>
                  <div class="win-title">Federal Police CTF Belgium</div>
                  <div class="win-year">2024 / 2025</div>
                </div>
                <div class="win-row">
                  <div class="win-rank gold">🏆</div>
                  <div class="win-title">CyberCrusade CTF HELB</div>
                  <div class="win-year">2024 / 2025</div>
                </div>
                <div class="win-row">
                  <div class="win-rank">⚡</div>
                  <div class="win-title">CyberWeek Wallonia (Pro)</div>
                  <div class="win-year">2024 / 2025</div>
                </div>
                <div class="win-row">
                  <div class="win-rank">⚡</div>
                  <div class="win-title">HACK'N WOW</div>
                  <div class="win-year">2024 / 2025</div>
                </div>
                <div class="win-row">
                  <div class="win-rank">⚡</div>
                  <div class="win-title">Odoo Hackathon - "UI Without Text"</div>
                  <div class="win-year">2025</div>
                </div>
              </div>
            </div>
          </div>

          <div class="content-block">
            <div class="section-header">
              <div class="section-dot" style="background-color: #2d9cdb;"></div>
              <h2 class="section-title">Technical Arsenal</h2>
            </div>
            
            <div class="grid-2-col">
              <div>
                <div class="tech-category">
                  <div class="tech-category-title">Core Languages</div>
                  <div class="tech-grid">
                    <div class="tech-tag primary">Java</div>
                    <div class="tech-tag primary">C#</div>
                    <div class="tech-tag primary">Python</div>
                    <div class="tech-tag yellow">JavaScript</div>
                    <div class="tech-tag blue">PHP</div>
                    <div class="tech-tag">C++</div>
                    <div class="tech-tag">HTML / CSS</div>
                  </div>
                </div>
                <div class="tech-category">
                  <div class="tech-category-title">Frameworks &amp; Libraries</div>
                  <div class="tech-grid">
                    <div class="tech-tag primary">.NET MAUI</div>
                    <div class="tech-tag primary">.NET Framework</div>
                    <div class="tech-tag">Entity Framework</div>
                    <div class="tech-tag accent">React</div>
                    <div class="tech-tag accent">React Native</div>
                    <div class="tech-tag blue">Django</div>
                    <div class="tech-tag blue">Spring Boot</div>
                    <div class="tech-tag yellow">JavaFX</div>
                    <div class="tech-tag green">Unity</div>
                  </div>
                </div>
              </div>

              <div>
                <div class="tech-category">
                  <div class="tech-category-title">Databases / Stores</div>
                  <div class="tech-grid">
                    <div class="tech-tag accent">PostgreSQL</div>
                    <div class="tech-tag blue">MySQL</div>
                    <div class="tech-tag">MongoDB</div>
                    <div class="tech-tag primary">SQLite</div>
                    <div class="tech-tag yellow">Firebase</div>
                  </div>
                </div>
                <div class="tech-category">
                  <div class="tech-category-title">Tools &amp; Platforms</div>
                  <div class="tech-grid">
                    <div class="tech-tag yellow">Git</div>
                    <div class="tech-tag blue">GitHub</div>
                    <div class="tech-tag accent">Linux</div>
                    <div class="tech-tag primary">Android Studio</div>
                    <div class="tech-tag">Postman</div>
                    <div class="tech-tag green">Figma</div>
                    <div class="tech-tag">XAMPP</div>
                    <div class="tech-tag">Power Apps</div>
                    <div class="tech-tag">Excel</div>
                    <div class="tech-tag">Adobe Photoshop</div>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="content-block">
            <div class="section-header">
              <div class="section-dot" style="background-color: #f2c94c;"></div>
              <h2 class="section-title">Projects &amp; Education</h2>
            </div>
            
            <div class="grid-2-col">
              <div>
                <div class="sub-heading">Featured Projects</div>
                <div class="timeline-item">
                  <div class="timeline-title">🍦 Ice Cream Simulator</div>
                  <span class="timeline-date">.NET MAUI + Arduino</span>
                  <div class="timeline-desc">Cross-platform ice cream simulator with real-time temperature &amp; humidity monitoring via Arduino integration.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">🎯 Duo-Codeur</div>
                  <span class="timeline-date">React Native + Expo Go</span>
                  <div class="timeline-desc">Mobile learning app teaching coding through Duolingo-style gamified experience with external API integration.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">🏦 Stocks &amp; Commands</div>
                  <span class="timeline-date">Java + Spring Boot</span>
                  <div class="timeline-desc">Backend application for stock inventory &amp; customer order management with REST APIs and Maven.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">📚 Biblioplane</div>
                  <span class="timeline-date">Android + Firebase</span>
                  <div class="timeline-desc">Campus library locator with map integration, top books &amp; user ratings.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">🖼️ Collaborative Canvas</div>
                  <span class="timeline-date">Django + JavaScript</span>
                  <div class="timeline-desc">Real-time collaborative canvas web application with multi-user interaction.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">📄 Invoice System</div>
                  <span class="timeline-date">C# + .NET Framework</span>
                  <div class="timeline-desc">Billing and invoicing system with client management, article handling, and automated calculations.</div>
                </div>
              </div>

              <div>
                <div class="sub-heading">Academic &amp; Professional</div>
                <div class="timeline-item">
                  <div class="timeline-title">🎓 BSc in Information Technology</div>
                  <span class="timeline-date">HELB Ilya Prigogine (2022-2026)</span>
                  <div class="timeline-desc">Graduated with honors. Specialized in software architecture, data structures, and security protocols.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">📜 Upper Secondary Education</div>
                  <span class="timeline-date">Economics &amp; Sociology (2022)</span>
                  <div class="timeline-desc">Strong foundation in analytical thinking and problem-solving.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">💼 Internship @ MyGridEnergy</div>
                  <span class="timeline-date">2026</span>
                  <div class="timeline-desc">Hands-on software development experience in a professional environment.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">🎯 Currently Seeking</div>
                  <span class="timeline-date">Alternate Contract (Master's + Work)</span>
                  <div class="timeline-desc">Combining a Master's degree with hands-on work experience starting in the upcoming academic year.</div>
                </div>
                <div class="timeline-item">
                  <div class="timeline-title">🎮 Project Management</div>
                  <span class="timeline-date">Sinter des Planetes + ICT Knowledge Base</span>
                  <div class="timeline-desc">Led teams as Scrum Master, coordinating Agile ceremonies and sprint planning for augmented reality and ICT documentation projects.</div>
                </div>
              </div>
            </div>
          </div>

          <div class="footer-block">
            <div class="contact-info">
              <div class="contact-item">📧 <a href="mailto:johnayazbeck@hotmail.com">johnayazbeck@hotmail.com</a></div>
              <div class="contact-item">🔗 <a href="https://www.linkedin.com/in/yazbeckjohn">linkedin.com/in/yazbeckjohn</a></div>
              <div class="contact-item">📱 +32 470 54 86 41</div>
              <div class="contact-item">📍 Brussels, Belgium</div>
              <div class="contact-item">▶️ <a href="https://www.youtube.com/@JohnCoding">YouTube @JohnCoding</a></div>
            </div>
            <div class="quote">
              "Building systems that scale,<br/>breaking challenges that don't,<br/>and always pushing the limits."
            </div>
          </div>

        </div>
      </div>
    </div>
  </foreignObject>
</svg>
