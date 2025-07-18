<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name - QA Automation Engineer</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <!-- Google Fonts - Inter -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    <!-- Mermaid JS for diagrams -->
    <script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #1a202c; /* Dark background */
        }
        .typing-effect {
            animation: blink-caret .75s step-end infinite;
        }
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #60a5fa; } /* blue-400 */
        }
        .animate-fade-in {
            animation: fadeIn 1.5s ease-out forwards;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        /* Custom styles for hover effects on badges/cards */
        .hover-scale-105:hover {
            transform: scale(1.05);
        }
        .hover-shadow-xl:hover {
            box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.3), 0 10px 10px -5px rgba(0, 0, 0, 0.1);
        }
    </style>
</head>
<body class="bg-gradient-to-br from-gray-900 to-gray-800 text-gray-100 min-h-screen p-4 sm:p-8 rounded-lg shadow-xl">

    <!-- Hero Section -->
    <section class="text-center mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h1 class="text-4xl sm:text-5xl font-extrabold text-transparent bg-clip-text bg-gradient-to-r from-blue-400 to-purple-500 mb-4 animate-fade-in">
            Hello, I'm a <span id="typed-title" class="typing-effect border-r-4 border-blue-400 pr-1"></span>
        </h1>
        <p class="text-lg sm:text-xl text-gray-300 mb-6">
            A dedicated QA Automation Engineer with a passion for building robust, high-quality software. I leverage strong analytical skills and a collaborative mindset to deliver efficient and reliable automation solutions.
        </p>

        <!-- Dynamic Badges (placeholders for real-time data) -->
        <div class="flex flex-wrap justify-center gap-4 mb-8">
            <img src="https://komarev.com/ghpvc/?username=your-github-username&color=blue" alt="Profile views" class="rounded-md" />
            <img src="https://img.shields.io/github/followers/your-github-username?style=for-the-badge&color=green" alt="GitHub followers" class="rounded-md" />
            <img src="https://img.shields.io/github/stars/your-github-username?style=for-the-badge&color=yellow" alt="GitHub stars" class="rounded-md" />
            <img src="https://img.shields.io/github/commit-activity/y/your-github-username?style=for-the-badge&color=orange" alt="Commit activity" class="rounded-md" />
        </div>

        <a
            href="https://linkedin.com/in/your-linkedin-profile" target="_blank" rel="noopener noreferrer"
            class="inline-block bg-gradient-to-r from-blue-500 to-purple-600 hover:from-blue-600 hover:to-purple-700 text-white font-bold py-3 px-8 rounded-full shadow-lg transform transition-transform duration-300 hover:scale-105"
        >
            <i class="fab fa-linkedin mr-2"></i> Connect on LinkedIn
        </a>
    </section>

    <!-- About Me Section -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-green-400 to-teal-500 mb-6">
            <i class="fas fa-user-circle mr-3"></i> About Me
        </h2>
        <p class="text-lg text-gray-300 leading-relaxed">
            I am a results-driven QA Automation Engineer passionate about elevating software quality through intelligent and efficient testing strategies. My journey is marked by a relentless pursuit of robust solutions, leveraging a strong analytical foundation to dissect complex systems and build scalable automation frameworks. I thrive on the challenge of identifying and mitigating risks early in the development lifecycle, ensuring seamless user experiences and accelerating product delivery. With a collaborative spirit and a commitment to continuous learning, I am dedicated to fostering a culture of excellence and contributing impactful solutions to dynamic engineering teams.
        </p>
    </section>

    <!-- Tech Arsenal Section -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-pink-400 to-red-500 mb-6">
            <i class="fas fa-tools mr-3"></i> My Tech Arsenal
        </h2>
        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-5 gap-4">
            <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" class="rounded-md" />
            <img src="https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white" alt="Selenium" class="rounded-md" />
            <img src="https://img.shields.io/badge/Cucumber-2B6B3F?style=for-the-badge&logo=cucumber&logoColor=white" alt="Cucumber" class="rounded-md" />
            <img src="https://img.shields.io/badge/Rest%20Assured-orange?style=for-the-badge" alt="Rest Assured" class="rounded-md" />
            <img src="https://img.shields.io/badge/JMeter-59B258?style=for-the-badge&logo=apache-jmeter&logoColor=white" alt="JMeter" class="rounded-md" />
            <img src="https://img.shields.io/badge/TestNG-F26232?style=for-the-badge&logo=testng&logoColor=white" alt="TestNG" class="rounded-md" />
            <img src="https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white" alt="Maven" class="rounded-md" />
            <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" class="rounded-md" />
            <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" class="rounded-md" />
            <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" class="rounded-md" />
            <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring&logoColor=white" alt="Spring Boot" class="rounded-md" />
            <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" class="rounded-md" />
            <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript" class="rounded-md" />
            <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" class="rounded-md" />
            <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" class="rounded-md" />
            <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" class="rounded-md" />
            <img src="https://img.shields.io/badge/Confluence-172B4D?style=for-the-badge&logo=confluence&logoColor=white" alt="Confluence" class="rounded-md" />
            <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" class="rounded-md" />
            <img src="https://img.shields.io/badge/Jenkins-2C526F?style=for-the-badge&logo=jenkins&logoColor=white" alt="Jenkins" class="rounded-md" />
            <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" class="rounded-md" />
        </div>
    </section>

    <!-- GitHub Analytics -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-yellow-400 to-orange-500 mb-6">
            <i class="fas fa-chart-line mr-3"></i> GitHub Analytics
        </h2>
        <p class="text-gray-300 mb-4">
            Visualizing my coding journey and contributions.
            <br />
            <span class="text-sm text-gray-400">
                (Note: These are placeholder images. In a real GitHub profile, these would be dynamic charts generated by tools like `github-readme-stats` or `metrics`.)
            </span>
        </p>
        <div class="flex flex-wrap justify-center gap-6">
            <!-- GitHub Stats Card -->
            <img
                src="https://placehold.co/400x150/1a202c/e2e8f0?text=GitHub+Stats+Card"
                alt="GitHub Stats"
                class="rounded-lg shadow-md border border-gray-600 w-full md:w-auto"
            />
            <!-- Top Languages Card -->
            <img
                src="https://placehold.co/300x150/1a202c/e2e8f0?text=Top+Languages+Card"
                alt="Top Languages"
                class="rounded-lg shadow-md border border-gray-600 w-full md:w-auto"
            />
            <!-- Streak Stats Card -->
            <img
                src="https://placehold.co/400x150/1a202c/e2e8f0?text=GitHub+Streak+Stats"
                alt="GitHub Streak Stats"
                class="rounded-lg shadow-md border border-gray-600 w-full md:w-auto"
            />
        </div>
    </section>

    <!-- Featured Projects -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-purple-400 to-indigo-500 mb-6">
            <i class="fas fa-project-diagram mr-3"></i> Featured Projects
        </h2>
        <p class="text-gray-300 mb-6">
            A selection of my most impactful and relevant projects, showcasing my skills in QA automation and full-stack development.
        </p>
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
            <!-- Project Card 1: E-commerce Spring Boot & React App -->
            <div class="bg-gray-800 p-5 rounded-lg shadow-md border border-gray-600 transform transition-transform duration-300 hover:scale-105 hover:shadow-xl">
                <h3 class="text-xl font-semibold text-blue-300 mb-2">E-commerce Spring Boot & React App</h3>
                <p class="text-gray-400 text-sm mb-3">
                    A full-stack e-commerce platform demonstrating robust backend APIs (Spring Boot) and a dynamic frontend (React).
                </p>
                <div class="flex flex-wrap gap-2 mb-3">
                    <span class="bg-blue-600 text-white text-xs px-2 py-1 rounded-full">#FullStack</span>
                    <span class="bg-green-600 text-white text-xs px-2 py-1 rounded-full">#SpringBoot</span>
                    <span class="bg-purple-600 text-white text-xs px-2 py-1 rounded-full">#ReactJS</span>
                </div>
                <a href="https://github.com/your-username/ecommerce-springboot-react-app" target="_blank" rel="noopener noreferrer" class="text-blue-400 hover:underline">
                    View Project <i class="fas fa-external-link-alt ml-1"></i>
                </a>
            </div>

            <!-- Project Card 2: Rest Assured Microservices API Automation -->
            <div class="bg-gray-800 p-5 rounded-lg shadow-md border border-gray-600 transform transition-transform duration-300 hover:scale-105 hover:shadow-xl">
                <h3 class="text-xl font-semibold text-blue-300 mb-2">Rest Assured Microservices API Automation</h3>
                <p class="text-gray-400 text-sm mb-3">
                    A comprehensive API test automation framework for microservices, ensuring robust API quality.
                </p>
                <div class="flex flex-wrap gap-2 mb-3">
                    <span class="bg-orange-600 text-white text-xs px-2 py-1 rounded-full">#APITesting</span>
                    <span class="bg-red-600 text-white text-xs px-2 py-1 rounded-full">#RestAssured</span>
                    <span class="bg-teal-600 text-white text-xs px-2 py-1 rounded-full">#Microservices</span>
                </div>
                <a href="https://github.com/your-username/rest-assured-microservices-api-automation" target="_blank" rel="noopener noreferrer" class="text-blue-400 hover:underline">
                    View Project <i class="fas fa-external-link-alt ml-1"></i>
                </a>
            </div>

            <!-- Project Card 3: Cucumber Banking BDD Test Suite -->
            <div class="bg-gray-800 p-5 rounded-lg shadow-md border border-gray-600 transform transition-transform duration-300 hover:scale-105 hover:shadow-xl">
                <h3 class="text-xl font-semibold text-blue-300 mb-2">Cucumber Banking BDD Test Suite</h3>
                <p class="text-gray-400 text-sm mb-3">
                    BDD-driven test suite for a banking portal, emphasizing collaboration and clear scenario definitions.
                </p>
                <div class="flex flex-wrap gap-2 mb-3">
                    <span class="bg-green-700 text-white text-xs px-2 py-1 rounded-full">#BDD</span>
                    <span class="bg-purple-700 text-white text-xs px-2 py-1 rounded-full">#Cucumber</span>
                    <span class="bg-blue-700 text-white text-xs px-2 py-1 rounded-full">#BankingQA</span>
                </div>
                <a href="https://github.com/your-username/cucumber-banking-bdd-test-suite" target="_blank" rel="noopener noreferrer" class="text-blue-400 hover:underline">
                    View Project <i class="fas fa-external-link-alt ml-1"></i>
                </a>
            </div>

            <!-- Project Card 4: OrangeHRM Automation Project -->
            <div class="bg-gray-800 p-5 rounded-lg shadow-md border border-gray-600 transform transition-transform duration-300 hover:scale-105 hover:shadow-xl">
                <h3 class="text-xl font-semibold text-blue-300 mb-2">OrangeHRM Automation Project</h3>
                <p class="text-gray-400 text-sm mb-3">
                    An automated test suite for the OrangeHRM web application, showcasing robust web automation practices.
                </p>
                <div class="flex flex-wrap gap-2 mb-3">
                    <span class="bg-yellow-600 text-white text-xs px-2 py-1 rounded-full">#Selenium</span>
                    <span class="bg-cyan-600 text-white text-xs px-2 py-1 rounded-full">#WebAutomation</span>
                    <span class="bg-pink-600 text-white text-xs px-2 py-1 rounded-full">#QA</span>
                </div>
                <a href="https://github.com/your-username/selenium-orangehrm-automation" target="_blank" rel="noopener noreferrer" class="text-blue-400 hover:underline">
                    View Project <i class="fas fa-external-link-alt ml-1"></i>
                </a>
            </div>
        </div>
    </section>

    <!-- Current Focus -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-cyan-400 to-blue-500 mb-6">
            <i class="fas fa-compass mr-3"></i> My Strategic Roadmap: Building Expertise Step-by-Step
        </h2>
        <p class="text-lg text-gray-300 mb-6 leading-relaxed">
            My journey in software quality began with foundational programming concepts and has progressively evolved into specialized areas of QA automation. This roadmap illustrates my structured approach to acquiring and deepening expertise, ensuring a comprehensive skill set for delivering high-impact solutions. Each milestone represents a deliberate step in mastering modern testing methodologies and tools.
        </p>

        <h3 class="text-2xl font-semibold text-transparent bg-clip-text bg-gradient-to-r from-purple-300 to-pink-400 mb-4">
            <i class="fas fa-map-marker-alt mr-2"></i> Key Milestones & Learning Path
        </h3>
        <ul class="list-disc list-inside text-gray-300 mb-6 space-y-2">
            <li>**Foundational Programming:** Solidifying core Java, OOP, and data structures.</li>
            <li>**Desktop Application Development:** Gaining experience with JavaFX and database integration.</li>
            <li>**Web UI Automation:** Mastering Selenium for robust web application testing.</li>
            <li>**API Test Automation:** Building comprehensive test suites for RESTful APIs.</li>
            <li>**Behavior-Driven Development (BDD):** Implementing Cucumber for collaborative test scenario definition.</li>
            <li>**Performance Testing:** Utilizing JMeter to assess application scalability and responsiveness.</li>
            <li>**Full-Stack & AI Integration:** Exploring modern web frameworks (Spring Boot, React) and AI concepts.</li>
            <li>**Continuous Improvement:** Ongoing learning in CI/CD, cloud testing, and advanced automation patterns.</li>
        </ul>

        <div id="mermaid-diagram" class="mermaid bg-gray-800 p-4 rounded-lg overflow-x-auto border border-gray-600">
            graph TD
                A[Start: Java & Core Programming] --> B(Foundational Projects);
                B --> C{Mastering Test Automation};
                C --> D[Web UI Automation (Selenium)];
                C --> E[API Automation (Rest Assured)];
                C --> F[BDD & Performance Testing];
                D & E & F --> G{Advanced Concepts & Integration};
                G --> H[Full-Stack & AI Exposure];
                H --> I[Achieve: QA Automation Engineer];
                style A fill:#f9f,stroke:#333,stroke-width:2px;
                style I fill:#9f9,stroke:#333,stroke-width:2px;
        </div>
    </section>

    <!-- QA Passion Quote -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-fuchsia-400 to-violet-500 mb-6">
            <i class="fas fa-heart mr-3"></i> My QA Automation Passion
        </h2>
        <div class="text-center">
            <blockquote class="text-xl italic text-gray-200 mb-6 px-4 py-3 bg-gray-800 rounded-lg shadow-inner">
                "For me, QA Automation isn't just a job; it's the art of building confidence into every line of code, ensuring flawless user experiences."
            </blockquote>
        </div>
    </section>

    <!-- Achievements Dashboard -->
    <section class="mb-12 bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-red-400 to-pink-500 mb-6">
            <i class="fas fa-trophy mr-3"></i> Achievements & Metrics
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6 text-center">
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-rocket text-4xl text-blue-400 mb-3"></i>
                <p class="text-xl font-bold text-white">18+</p>
                <p class="text-gray-400 text-sm">Projects Completed</p>
            </div>
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-flask text-4xl text-green-400 mb-3"></i>
                <p class="text-xl font-bold text-white">5+</p>
                <p class="text-gray-400 text-sm">Test Frameworks Built</p>
            </div>
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-code text-4xl text-yellow-400 mb-3"></i>
                <p class="text-xl font-bold text-white">3+</p>
                <p class="text-gray-400 text-sm">Languages Mastered (Java, JS, SQL)</p>
            </div>
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-cogs text-4xl text-purple-400 mb-3"></i>
                <p class="text-xl font-bold text-white">Key Skills</p>
                <p class="text-gray-400 text-sm">Automation, BDD, API, Performance, CI/CD</p>
            </div>
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-users text-4xl text-teal-400 mb-3"></i>
                <p class="text-xl font-bold text-white">Leadership</p>
                <p class="text-gray-400 text-sm">Proven ability to guide & collaborate</p>
            </div>
            <div class="bg-gray-800 p-6 rounded-lg shadow-md border border-gray-600 flex flex-col items-center justify-center transform transition-transform duration-300 hover:scale-105">
                <i class="fas fa-chart-line text-4xl text-orange-400 mb-3"></i>
                <p class="text-xl font-bold text-white">Continuous Growth</p>
                <p class="text-gray-400 text-sm">Always learning & adapting</p>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="text-center bg-gray-700 p-6 rounded-xl shadow-lg border border-gray-600">
        <h2 class="text-3xl font-bold text-transparent bg-clip-text bg-gradient-to-r from-green-400 to-blue-500 mb-6">
            <i class="fas fa-handshake mr-3"></i> Let's Connect!
        </h2>
        <p class="text-lg text-gray-300 mb-4">
            I'm always open to discussing new opportunities, collaborations, or just sharing insights on quality assurance.
        </p>
        <div class="flex flex-wrap justify-center gap-6">
            <a
                href="mailto:your.email@example.com"
                class="flex items-center bg-gray-800 hover:bg-gray-900 text-white py-3 px-6 rounded-full shadow-md transition-colors duration-300"
            >
                <i class="fas fa-envelope mr-2"></i> Email Me
            </a>
            <a
                href="https://linkedin.com/in/your-linkedin-profile"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center bg-blue-700 hover:bg-blue-800 text-white py-3 px-6 rounded-full shadow-md transition-colors duration-300"
            >
                <i class="fab fa-linkedin mr-2"></i> LinkedIn
            </a>
            <a
                href="https://your-personal-website.com"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center bg-teal-700 hover:bg-teal-800 text-white py-3 px-6 rounded-full shadow-md transition-colors duration-300"
            >
                <i class="fas fa-globe mr-2"></i> My Website
            </a>
            <a
                href="https://github.com/your-github-username"
                target="_blank"
                rel="noopener noreferrer"
                class="flex items-center bg-gray-900 hover:bg-gray-700 text-white py-3 px-6 rounded-full shadow-md transition-colors duration-300"
            >
                <i class="fab fa-github mr-2"></i> GitHub
            </a>
        </div>
    </section>

    <script>
        // Typing Effect for Title
        document.addEventListener('DOMContentLoaded', () => {
            const titleText = "QA Automation Engineer";
            const typingSpeed = 100; // milliseconds per character
            const typingDelay = 1000; // delay before typing starts
            const typedTitleElement = document.getElementById('typed-title');
            let i = 0;

            setTimeout(() => {
                const typingInterval = setInterval(() => {
                    if (i < titleText.length) {
                        typedTitleElement.textContent += titleText.charAt(i);
                        i++;
                    } else {
                        clearInterval(typingInterval);
                    }
                }, typingSpeed);
            }, typingDelay);
        });

        // Initialize Mermaid Diagrams
        document.addEventListener('DOMContentLoaded', () => {
            if (window.mermaid) {
                // Ensure Mermaid is initialized only once
                window.mermaid.initialize({ startOnLoad: true });
                // Trigger content loaded to render diagrams that are already in the DOM
                window.mermaid.contentLoaded();
            } else {
                console.error("Mermaid.js not loaded. Diagrams will not render.");
            }
        });
    </script>
</body>
</html>
