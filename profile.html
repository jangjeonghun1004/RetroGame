<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>장정훈 - Full Stack Developer</title>
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Reset & Base */
        * { box-sizing: border-box; }
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            user-select: none;
            -webkit-font-smoothing: none;
        }

        /* Variables for Windows 95/98 Theme */
        :root {
            --bg-teal: #008080;
            --win-gray: #c0c0c0;
            --win-blue-dark: #000080;
            --win-blue-light: #1084d0;
            --win-gray-dark: #808080;
            --win-gray-light: #a0a0a0;
            --win-text: #000000;
            --border-white: #ffffff;
            --border-gray: #808080;
            --border-black: #000000;
        }

        /* Desktop */
        #desktop {
            background-color: var(--bg-teal);
            width: 100%;
            height: calc(100% - 40px);
            position: relative;
            padding: 10px;
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            align-content: flex-start;
            gap: 20px;
        }

        /* Icons */
        .desktop-icon {
            width: 80px;
            display: flex;
            flex-direction: column;
            align-items: center;
            cursor: pointer;
            color: white;
            text-align: center;
            font-size: 12px;
            text-shadow: 1px 1px 0px rgba(0,0,0,0.5);
            border: 1px solid transparent;
        }
        .desktop-icon:hover {
            border: 1px dotted rgba(255, 255, 255, 0.3);
        }
        .desktop-icon:hover .icon-img {
            filter: brightness(1.2);
        }
        .desktop-icon:active .icon-label {
            background-color: var(--win-blue-dark);
            border: 1px dotted white;
        }
        .icon-img {
            width: 48px;
            height: 48px;
            margin-bottom: 5px;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .icon-label {
            padding: 2px 4px;
        }

        /* Window Styling */
        .window {
            position: absolute;
            background-color: var(--win-gray);
            border-top: 2px solid var(--border-white);
            border-left: 2px solid var(--border-white);
            border-right: 2px solid var(--border-black);
            border-bottom: 2px solid var(--border-black);
            box-shadow: 1px 1px 0px black;
            display: flex;
            flex-direction: column;
            min-width: 300px;
            min-height: 200px;
            max-width: 90vw;
            max-height: 80vh;
            display: none; /* Hidden by default */
        }

        /* Active Window Title Bar Color */
        .window.active .title-bar {
            background: linear-gradient(90deg, var(--win-blue-dark), var(--win-blue-light));
        }

        /* Inactive Window Title Bar Color */
        .window .title-bar {
            background: linear-gradient(90deg, var(--win-gray-dark), var(--win-gray-light));
            color: #ccc;
        }
        
        .window.active .title-bar-text {
            color: white;
        }

        .title-bar {
            padding: 3px 4px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            cursor: default;
        }

        .title-bar-text {
            font-weight: bold;
            font-size: 14px;
            display: flex;
            align-items: center;
            gap: 5px;
        }

        .title-bar-controls {
            display: flex;
            gap: 2px;
        }

        .win-btn {
            width: 16px;
            height: 14px;
            background-color: var(--win-gray);
            border-top: 1px solid var(--border-white);
            border-left: 1px solid var(--border-white);
            border-right: 1px solid var(--border-black);
            border-bottom: 1px solid var(--border-black);
            font-size: 10px;
            display: flex;
            justify-content: center;
            align-items: center;
            cursor: pointer;
            font-weight: bold;
            line-height: 1;
            color: black;
        }
        .win-btn:active {
            border-top: 1px solid var(--border-black);
            border-left: 1px solid var(--border-black);
            border-right: 1px solid var(--border-white);
            border-bottom: 1px solid var(--border-white);
        }

        .window-body {
            padding: 10px;
            flex: 1;
            overflow: auto;
            font-size: 14px;
            line-height: 1.5;
        }

        /* Content Styling inside Windows */
        .content-section {
            background: white;
            border: 2px inset var(--win-gray);
            padding: 15px;
            height: 100%;
            overflow-y: auto;
            color: black;
            user-select: text;
        }

        h2, h3, h4 { margin-top: 0; }
        .skill-tag {
            display: inline-block;
            background: #eee;
            border: 1px solid #999;
            padding: 2px 6px;
            margin: 2px;
            font-size: 12px;
            border-radius: 2px;
        }
        .exp-item {
            margin-bottom: 15px;
            border-bottom: 1px dashed #ccc;
            padding-bottom: 10px;
        }
        .exp-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            flex-wrap: wrap;
        }
        .exp-title { font-weight: bold; color: var(--win-blue-dark); }
        .exp-date { font-size: 12px; color: #666; }
        
        a { color: blue; }

        /* Taskbar */
        #taskbar {
            height: 40px;
            background-color: var(--win-gray);
            border-top: 2px solid var(--border-white);
            position: fixed;
            bottom: 0;
            width: 100%;
            display: flex;
            align-items: center;
            padding: 2px;
            z-index: 1000;
        }

        #start-btn {
            height: 32px;
            padding: 0 10px;
            display: flex;
            align-items: center;
            gap: 5px;
            font-weight: bold;
            font-style: italic;
            background-color: var(--win-gray);
            border-top: 2px solid var(--border-white);
            border-left: 2px solid var(--border-white);
            border-right: 2px solid var(--border-black);
            border-bottom: 2px solid var(--border-black);
            box-shadow: 1px 1px 0px black;
            cursor: pointer;
            margin-right: 10px;
        }
        #start-btn:active, #start-btn.active {
            border-top: 2px solid var(--border-black);
            border-left: 2px solid var(--border-black);
            border-right: 2px solid var(--border-white);
            border-bottom: 2px solid var(--border-white);
            background-color: #dcdcdc;
        }

        .taskbar-divider {
            width: 2px;
            height: 28px;
            background: var(--border-gray);
            border-right: 1px solid white;
            margin: 0 5px;
        }

        #task-list {
            flex: 1;
            display: flex;
            gap: 4px;
            overflow-x: auto;
        }

        .task-item {
            width: 150px;
            height: 32px;
            background-color: var(--win-gray);
            border-top: 2px solid var(--border-white);
            border-left: 2px solid var(--border-white);
            border-right: 2px solid var(--border-black);
            border-bottom: 2px solid var(--border-black);
            display: flex;
            align-items: center;
            padding: 0 8px;
            font-size: 12px;
            cursor: pointer;
            text-overflow: ellipsis;
            white-space: nowrap;
            overflow: hidden;
        }
        .task-item.active {
            background-color: #eee;
            border-top: 2px solid var(--border-black);
            border-left: 2px solid var(--border-black);
            border-right: 2px solid var(--border-white);
            border-bottom: 2px solid var(--border-white);
            font-weight: bold;
        }

        #clock-tray {
            width: 80px;
            height: 32px;
            background-color: var(--win-gray);
            border: 2px inset var(--win-gray);
            border-bottom: 1px solid white; 
            border-right: 1px solid white;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 12px;
            margin-left: 5px;
        }

        /* Start Menu */
        #start-menu {
            position: absolute;
            bottom: 42px;
            left: 2px;
            width: 250px;
            background-color: var(--win-gray);
            border-top: 2px solid var(--border-white);
            border-left: 2px solid var(--border-white);
            border-right: 2px solid var(--border-black);
            border-bottom: 2px solid var(--border-black);
            box-shadow: 2px 2px 5px rgba(0,0,0,0.5);
            display: flex;
            display: none; /* Hidden */
            z-index: 2000;
        }
        
        .start-side-bar {
            width: 30px;
            background: linear-gradient(180deg, var(--win-blue-dark), var(--win-blue-light));
            display: flex;
            align-items: flex-end;
            padding-bottom: 10px;
        }
        .start-side-text {
            transform: rotate(-90deg);
            color: white;
            font-weight: bold;
            font-size: 20px;
            white-space: nowrap;
            margin-bottom: 10px;
        }
        
        .start-items {
            flex: 1;
            padding: 5px;
        }
        
        .start-item {
            padding: 8px 10px;
            display: flex;
            align-items: center;
            gap: 10px;
            cursor: pointer;
            font-size: 14px;
        }
        .start-item:hover {
            background-color: var(--win-blue-dark);
            color: white;
        }
        .start-divider {
            height: 2px;
            border-top: 1px solid var(--border-gray);
            border-bottom: 1px solid white;
            margin: 5px 0;
        }

    </style>
</head>
<body>

    <!-- Desktop Area -->
    <div id="desktop">
        <!-- Icons Generated via JS -->
    </div>

    <!-- Start Menu -->
    <div id="start-menu">
        <div class="start-side-bar">
            <div class="start-side-text">JangOS 25</div>
        </div>
        <div class="start-items">
            <div class="start-item" onclick="openWindow('profile')">
                <i data-lucide="user"></i> <span>프로필 정보</span>
            </div>
            <div class="start-item" onclick="openWindow('resume')">
                <i data-lucide="file-text"></i> <span>경력 기술서</span>
            </div>
            <div class="start-item" onclick="openWindow('portfolio')">
                <i data-lucide="folder-open"></i> <span>포트폴리오</span>
            </div>
            <div class="start-divider"></div>
            <div class="start-item" onclick="openWindow('contact')">
                <i data-lucide="mail"></i> <span>이메일 보내기</span>
            </div>
            <div class="start-divider"></div>
            <div class="start-item" onclick="location.reload()">
                <i data-lucide="power"></i> <span>시스템 종료</span>
            </div>
        </div>
    </div>

    <!-- Taskbar -->
    <div id="taskbar">
        <div id="start-btn" onclick="toggleStartMenu()">
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Windows_logo_and_wordmark_-_1995-2001.svg/512px-Windows_logo_and_wordmark_-_1995-2001.svg.png" width="18" alt="win">
            Start
        </div>
        <div class="taskbar-divider"></div>
        <div id="task-list">
            <!-- Active Windows Tasks -->
        </div>
        <div class="taskbar-divider"></div>
        <div id="clock-tray">12:00 PM</div>
    </div>

    <script>
        // Init Lucide Icons
        
        // Data derived from resume
        const resumeData = {
            profile: {
                name: "장정훈",
                title: "풀스택 웹 개발자 (18년차)",
                birth: "1982년 (만 43세)",
                education: "서울디지털대 소프트웨어공학과 졸업 (2014.08)",
                intro: `소프트웨어공학전공과 다양한 실무 경험을 보유한 웹개발 인재입니다.<br>
                ASP.NET MVC, Spring Boot, React, Next.js 등 폭넓은 기술 스택을 보유하고 있습니다.<br>
                팀 내에서 긍정적인 협업 분위기를 만들고, 프로젝트의 성공적인 완수를 이끌어냅니다.`
            },
            skills: [
                { cat: "Backend", items: ["Java", "ASP.NET MVC", "ASP.NET Core", "Spring Boot", "Node.js"] },
                { cat: "Frontend", items: ["React", "Next.js", "JavaScript", "jQuery", "XPLATFORM"] },
                { cat: "Database", items: ["Oracle", "MS-SQL", "MySQL"] },
                { cat: "Tools", items: ["Git", "Restful API"] }
            ],
            experience: [
                {
                    company: "한국방송통신대학교출판문화원",
                    period: "2025.08 ~ 현재",
                    role: "전산팀 프리랜서",
                    desc: "Java, XPLATFORM, Oracle 기반 시스템 개발 및 유지보수"
                },
                {
                    company: "큐익스프레스",
                    period: "2018.04 ~ 2024.08 (6년 5개월)",
                    role: "개발실 차장",
                    desc: "WMS(물류 관리 시스템) 신규 개발 및 유지보수. ASP.NET MVC/Core, MS-SQL 환경. 반입/반출, 재고관리, 픽킹/팩킹 시스템 구축."
                },
                {
                    company: "한국방송통신대학교출판문화원",
                    period: "2016.08 ~ 2017.01",
                    role: "Mobile 시스템 리뉴얼",
                    desc: "Java JSP 활용 Front-end 개발 담당"
                },
                {
                    company: "토토로사",
                    period: "2013.07 ~ 2016.07",
                    role: "개발1팀 / SM",
                    desc: "ASP.NET MVC, jQuery 활용 웹 서비스 유지보수"
                },
                {
                    company: "텐디알",
                    period: "2006.12 ~ 2013.06",
                    role: "웹서비스 파트장",
                    desc: "ASP.NET, Linux/Windows Server 관리, 웹 개발"
                }
            ],
            contact: {
                phone: "010-2750-1476",
                email: "jangjeonghun1004@gmail.com",
                blog: "https://jangjeonghun.tistory.com/",
                address: "인천 부평구 부평4동"
            },
            portfolio: [
                { title: "GitHub 프로필", url: "https://jangjeonghun1004.github.io/profile" },
                { title: "Next.js 프로젝트", url: "https://next-pairing-book.vercel.app/" },
                { title: "React 프로젝트", url: "https://jangjeonghun1004.github.io/React-Project1/" },
                { title: "일정 관리 앱", url: "https://schedule-note.vercel.app/" }
            ]
        };

        // Window Management
        let zIndexCounter = 100;
        const openWindows = [];

        function renderDesktopIcons() {
            const icons = [
                { id: 'profile', icon: 'computer', label: '내 컴퓨터<br>(내 정보)', color: '#000080' },
                { id: 'resume', icon: 'file-text', label: '이력서.txt', color: '#fff' },
                { id: 'portfolio', icon: 'globe', label: '인터넷<br>(포트폴리오)', color: '#1084d0' },
                { id: 'contact', icon: 'mail', label: '아웃룩<br>(연락처)', color: '#ffd700' },
                { id: 'skills', icon: 'layers', label: '기술 스택', color: '#ff00ff' }
            ];

            const desktop = document.getElementById('desktop');
            desktop.innerHTML = ''; // Clear existing icons to prevent duplication on re-render

            icons.forEach(ic => {
                const el = document.createElement('div');
                el.className = 'desktop-icon';
                el.innerHTML = `
                    <div class="icon-img" style="color:${ic.color}"><i data-lucide="${ic.icon}" width="32" height="32"></i></div>
                    <div class="icon-label">${ic.label}</div>
                `;
                
                // Changed from ondblclick to onclick for better usability across all devices
                el.onclick = () => openWindow(ic.id); 
                
                desktop.appendChild(el);
            });
            
            // Safety check for Lucide
            if (typeof lucide !== 'undefined') {
                lucide.createIcons();
            }
        }

        function getContent(id) {
            if (id === 'profile') {
                return `
                    <div class="content-section" style="text-align:center;">
                        <i data-lucide="user-circle" width="64" height="64" style="margin: 10px auto; color: #000080;"></i>
                        <h2>${resumeData.profile.name}</h2>
                        <p><strong>${resumeData.profile.title}</strong></p>
                        <hr>
                        <p style="text-align:left; font-size:13px; line-height:1.6;">
                            <b>생년월일:</b> ${resumeData.profile.birth}<br>
                            <b>학력:</b> ${resumeData.profile.education}<br>
                            <b>주소:</b> ${resumeData.contact.address}<br>
                        </p>
                        <div style="background:#ffffe0; padding:10px; border:1px solid #999; text-align:left; margin-top:10px;">
                            ${resumeData.profile.intro}
                        </div>
                    </div>
                `;
            } else if (id === 'resume') {
                let html = `<div class="content-section" style="font-family: 'Courier New', monospace;">`;
                html += `<h3>[ 경력 기술서 ]</h3><br>`;
                resumeData.experience.forEach(exp => {
                    html += `
                        <div class="exp-item">
                            <div class="exp-header">
                                <span class="exp-title">■ ${exp.company}</span>
                                <span class="exp-date">${exp.period}</span>
                            </div>
                            <div style="margin-top:5px; color:#444;"><b>Role:</b> ${exp.role}</div>
                            <div style="margin-top:5px; padding-left:10px; border-left: 2px solid #ddd;">${exp.desc}</div>
                        </div>
                    `;
                });
                html += `</div>`;
                return html;
            } else if (id === 'portfolio') {
                let html = `<div class="content-section"><h3>즐겨찾기 (Links)</h3><ul>`;
                resumeData.portfolio.forEach(p => {
                    html += `<li><a href="${p.url}" target="_blank">🔗 ${p.title}</a> <br><small style="color:#666">${p.url}</small></li><br>`;
                });
                html += `<li><a href="${resumeData.contact.blog}" target="_blank">📝 기술 블로그 (Tistory)</a></li>`;
                html += `</ul>
                <div style="text-align:center; margin-top:20px; border:1px solid gray; padding:10px; background:#eee;">
                    <p>외부 링크는 새 탭에서 열립니다.</p>
                </div>
                </div>`;
                return html;
            } else if (id === 'contact') {
                return `
                    <div class="content-section">
                        <h3>Contact Info</h3>
                        <div style="display:flex; flex-direction:column; gap:10px;">
                            <div>
                                <label>Phone:</label>
                                <input type="text" value="${resumeData.contact.phone}" readonly style="width:100%">
                            </div>
                            <div>
                                <label>Email:</label>
                                <input type="text" value="${resumeData.contact.email}" readonly style="width:100%">
                            </div>
                            <div style="margin-top:20px; border-top:1px solid #ccc; padding-top:10px;">
                                <p>장정훈님에게 메일을 보내시겠습니까?</p>
                                <a href="mailto:${resumeData.contact.email}">
                                    <button style="padding:5px 15px; cursor:pointer;">Outlook 열기 (Mailto)</button>
                                </a>
                            </div>
                        </div>
                    </div>
                `;
            } else if (id === 'skills') {
                let html = `<div class="content-section">`;
                resumeData.skills.forEach(cat => {
                    html += `<h4>📂 ${cat.cat}</h4><div style="margin-bottom:15px;">`;
                    cat.items.forEach(skill => {
                        html += `<span class="skill-tag">${skill}</span>`;
                    });
                    html += `</div>`;
                });
                html += `</div>`;
                return html;
            }
        }

        function getTitle(id) {
            const titles = {
                profile: '시스템 정보 - 장정훈',
                resume: '이력서.txt - 메모장',
                portfolio: 'Microsoft Internet Explorer',
                contact: '새 메시지',
                skills: 'C:\\Skills'
            };
            return titles[id] || '새 창';
        }

        function openWindow(id) {
            // Close start menu
            document.getElementById('start-menu').style.display = 'none';
            document.getElementById('start-btn').classList.remove('active');

            // Bring to front if already open
            const existingWin = document.getElementById(`win-${id}`);
            if (existingWin) {
                if(existingWin.style.display === 'none') {
                    existingWin.style.display = 'flex';
                    updateTaskbar(id, true);
                }
                bringToFront(existingWin);
                return;
            }

            // Create new window
            const win = document.createElement('div');
            win.className = 'window active';
            win.id = `win-${id}`;
            win.style.display = 'flex'; // Explicitly show the window
            
            // --- Center Calculation Logic Changed ---
            const desktop = document.getElementById('desktop');
            const viewportWidth = desktop.offsetWidth;
            const viewportHeight = desktop.offsetHeight;
            
            // Estimate window size (based on min-width/height in CSS + buffer)
            const estWidth = 350; 
            const estHeight = 300;

            // Calculate center position
            // Add a small offset based on how many windows are open to create a stacking effect
            const stackOffset = (openWindows.length * 25) % 150; 
            
            let leftPos = (viewportWidth / 2) - (estWidth / 2) + stackOffset;
            let topPos = (viewportHeight / 2) - (estHeight / 2) + stackOffset;

            // Prevent off-screen placement on very small screens
            if (leftPos < 0) leftPos = 10;
            if (topPos < 0) topPos = 10;
            
            win.style.left = leftPos + 'px';
            win.style.top = topPos + 'px';
            win.style.zIndex = ++zIndexCounter;
            // ----------------------------------------

            win.innerHTML = `
                <div class="title-bar" onmousedown="startDrag(event, '${win.id}')">
                    <div class="title-bar-text">
                        <i data-lucide="${getIconForId(id)}" width="14" style="margin-right:5px"></i>
                        ${getTitle(id)}
                    </div>
                    <div class="title-bar-controls">
                        <div class="win-btn" onclick="minimizeWindow('${id}')">_</div>
                        <div class="win-btn" onclick="closeWindow('${id}')">X</div>
                    </div>
                </div>
                <div class="window-body">
                    ${getContent(id)}
                </div>
            `;
            
            // Add interaction
            win.onmousedown = () => bringToFront(win);

            document.body.appendChild(win);
            openWindows.push(id);
            
            if (typeof lucide !== 'undefined') {
                lucide.createIcons();
            }
            
            // Deactivate other windows visually
            document.querySelectorAll('.window').forEach(w => w.classList.remove('active'));
            win.classList.add('active');

            // Add to taskbar
            addTaskbarItem(id);
        }

        function getIconForId(id) {
            if(id === 'profile') return 'user';
            if(id === 'resume') return 'file-text';
            if(id === 'portfolio') return 'globe';
            if(id === 'contact') return 'mail';
            return 'folder';
        }

        function closeWindow(id) {
            const win = document.getElementById(`win-${id}`);
            if (win) win.remove();
            
            const index = openWindows.indexOf(id);
            if (index > -1) openWindows.splice(index, 1);
            
            removeTaskbarItem(id);
        }

        function minimizeWindow(id) {
            const win = document.getElementById(`win-${id}`);
            if (win) win.style.display = 'none';
            updateTaskbar(id, false);
        }

        function bringToFront(win) {
            win.style.zIndex = ++zIndexCounter;
            
            // Update active visual state
            document.querySelectorAll('.window').forEach(w => w.classList.remove('active'));
            win.classList.add('active');
            
            // Update active state visuals in taskbar
            const id = win.id.replace('win-', '');
            updateTaskbar(id, true);
        }

        // Taskbar Logic
        function addTaskbarItem(id) {
            const list = document.getElementById('task-list');
            const item = document.createElement('div');
            item.className = 'task-item active';
            item.id = `task-${id}`;
            item.innerText = getTitle(id);
            item.onclick = () => {
                const win = document.getElementById(`win-${id}`);
                if (win.style.display === 'none') {
                    win.style.display = 'flex';
                    bringToFront(win);
                } else {
                    // Check if it's top most
                    if(parseInt(win.style.zIndex) === zIndexCounter && win.classList.contains('active')) {
                        minimizeWindow(id);
                    } else {
                        bringToFront(win);
                    }
                }
            };
            list.appendChild(item);
            updateTaskbar(id, true);
        }

        function removeTaskbarItem(id) {
            const item = document.getElementById(`task-${id}`);
            if (item) item.remove();
        }

        function updateTaskbar(activeId, isOpen) {
            document.querySelectorAll('.task-item').forEach(el => {
                el.classList.remove('active');
            });
            if (isOpen) {
                const activeItem = document.getElementById(`task-${activeId}`);
                if (activeItem) activeItem.classList.add('active');
            }
        }

        // Drag Logic
        let isDragging = false;
        let currentDragWin = null;
        let dragOffsetX = 0;
        let dragOffsetY = 0;

        function startDrag(e, winId) {
            if(e.target.classList.contains('win-btn')) return; // Don't drag if clicking buttons
            
            isDragging = true;
            currentDragWin = document.getElementById(winId);
            const rect = currentDragWin.getBoundingClientRect();
            dragOffsetX = e.clientX - rect.left;
            dragOffsetY = e.clientY - rect.top;
            
            bringToFront(currentDragWin);
        }

        document.addEventListener('mousemove', (e) => {
            if (!isDragging || !currentDragWin) return;
            e.preventDefault();
            
            let newX = e.clientX - dragOffsetX;
            let newY = e.clientY - dragOffsetY;
            
            // Boundaries (Rough)
            newY = Math.max(0, newY); // Don't go above top
            newY = Math.min(window.innerHeight - 40 - 30, newY); // Don't go below taskbar

            currentDragWin.style.left = newX + 'px';
            currentDragWin.style.top = newY + 'px';
        });

        document.addEventListener('mouseup', () => {
            isDragging = false;
            currentDragWin = null;
        });

        // Start Menu Logic
        function toggleStartMenu() {
            const menu = document.getElementById('start-menu');
            const btn = document.getElementById('start-btn');
            
            if (menu.style.display === 'flex') {
                menu.style.display = 'none';
                btn.classList.remove('active');
            } else {
                menu.style.display = 'flex';
                btn.classList.add('active');
                if (typeof lucide !== 'undefined') {
                    lucide.createIcons();
                }
            }
        }

        // Clock
        function updateClock() {
            const now = new Date();
            let hours = now.getHours();
            const ampm = hours >= 12 ? 'PM' : 'AM';
            hours = hours % 12;
            hours = hours ? hours : 12; 
            const minutes = now.getMinutes().toString().padStart(2, '0');
            document.getElementById('clock-tray').innerText = `${hours}:${minutes} ${ampm}`;
        }
        setInterval(updateClock, 1000);
        updateClock();

        // Close start menu when clicking desktop
        document.getElementById('desktop').addEventListener('mousedown', (e) => {
             if(e.target === document.getElementById('desktop')) {
                 document.getElementById('start-menu').style.display = 'none';
                 document.getElementById('start-btn').classList.remove('active');
             }
        });

        // Initialize
        // Wait slightly to ensure lucide script is ready
        window.onload = function() {
            renderDesktopIcons();
            // Auto open profile on load after 500ms for effect
            setTimeout(() => openWindow('profile'), 500);
        };

    </script>
</body>
</html>
