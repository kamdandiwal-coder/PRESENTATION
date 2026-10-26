# PRESENTATION
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Claudia Sheinbaum: A Historic Leader - Presentation</title>
    <style>
        :root {
            --primary-color: #006643; /* Mexican Green vibe */
            --secondary-color: #bc002c; /* Mexican Red accent */
            --bg-color: #f4f7f6;
            --card-bg: #ffffff;
            --text-color: #333333;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
        }

        .presentation-container {
            width: 90%;
            max-width: 1000px;
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 8px 24px rgba(0,0,0,0.12);
            overflow: hidden;
            display: flex;
            flex-direction: column;
            position: relative;
        }

        .slide {
            display: none;
            padding: 40px 50px;
            box-sizing: border-box;
            min-height: 520px;
            animation: fadeIn 0.5s ease-in-out;
        }

        .slide.active {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(6px); }
            to { opacity: 1; transform: translateY(0); }
        }

        h2 {
            color: var(--primary-color);
            margin-top: 0;
            font-size: 2rem;
            border-bottom: 3px solid var(--secondary-color);
            padding-bottom: 10px;
            display: inline-block;
        }

        .content-body {
            display: flex;
            gap: 30px;
            align-items: center;
            margin: 20px 0;
            flex-grow: 1;
        }

        .text-content {
            flex: 1;
            font-size: 1.1rem;
            line-height: 1.6;
        }

        .image-container {
            flex: 1;
            text-align: center;
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .image-container img {
            max-width: 100%;
            max-height: 280px;
            border-radius: 8px;
            object-fit: cover;
            box-shadow: 0 4px 12px rgba(0,0,0,0.1);
        }

        .copyright-tag {
            font-size: 0.75rem;
            color: #666;
            margin-top: 6px;
            font-style: italic;
        }

        /* Intro slide special layout */
        .intro-slide {
            text-align: center;
            justify-content: center;
            background: linear-gradient(135deg, #006643 0%, #004d32 100%);
            color: white;
            padding: 50px;
        }
        .intro-slide h2 { color: white; border-bottom-color: #ffffff; }
        .intro-details {
            background: rgba(255, 255, 255, 0.1);
            padding: 20px;
            border-radius: 8px;
            display: inline-block;
            margin-top: 20px;
            text-align: left;
        }

        /* Navigation Controls */
        .nav-controls {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background: #eaeaea;
            border-top: 1px solid #ddd;
        }

        button {
            background-color: var(--primary-color);
            color: white;
            border: none;
            padding: 10px 22px;
            font-size: 1rem;
            border-radius: 6px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background-color: #004d32;
        }

        button:disabled {
            background-color: #ccc;
            cursor: not-allowed;
        }

        .slide-counter {
            font-weight: bold;
            color: #555;
        }

        ul { margin: 0; padding-left: 20px; }
        li { margin-bottom: 8px; }
    </style>
</head>
<body>

<div class="presentation-container">

    <!-- PAGE 1: STUDENT INTRODUCTION -->
    <div class="slide intro-slide active">
        <div>
            <h2>Communication Skills Presentation</h2>
            <h1 style="font-size: 2.5rem; margin: 15px 0;">Claudia Sheinbaum: A Visionary Leader</h1>
            <p style="font-size: 1.2rem; opacity: 0.9;">First Female President of Mexico</p>
        </div>
        <div style="display: flex; justify-content: center;">
            <div class="intro-details">
                <p><strong>Name:</strong> Kamalpreet Kaur</p>
                <p><strong>UID:</strong> 26BFI10148</p>
                <p><strong>Subject Name:</strong> Communication Skills</p>
                <p><strong>Submitted To:</strong> Ms. Parveen Sahota</p>
            </div>
        </div>
        <div></div>
    </div>

    <!-- PAGE 2: BRIEF INTRO -->
    <div class="slide">
        <h2>1. Brief Introduction</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Who is she?</strong> Claudia Sheinbaum Pardo is a prominent Mexican politician, scientist, and environmental engineer.</li>
                    <li><strong>Historic Milestone:</strong> She assumed office as the 66th President of Mexico, making history as the <strong>first female</strong> and first Jewish president in the nation's over 200 years of independence.</li>
                    <li><strong>Core Ethos:</strong> Marries rigorous data-driven scientific inquiry with progressive social welfare and sustainable development policies.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/Claudia_Sheinbaum_Pardo_%28cropped%29.jpg/800px-Claudia_Sheinbaum_Pardo_%28cropped%29.jpg" alt="Claudia Sheinbaum">
                <div class="copyright-tag">Photo: Eneas Mx / Wikimedia Commons (CC BY 4.0)</div>
            </div>
        </div>
    </div>

    <!-- PAGE 3: EARLY LIFE & BACKGROUND -->
    <div class="slide">
        <h2>2. Early Life & Background</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Family Roots:</strong> Born in Mexico City on June 24, 1962, into an intellectually active, left-leaning family. Her parents were scientists (a chemist father and a biologist mother).</li>
                    <li><strong>Academic Excellence:</strong> Pursued higher education at the prestigious National Autonomous University of Mexico (UNAM), earning a bachelor's degree in physics, a master's, and a Ph.D. in energy engineering.</li>
                    <li><strong>Global Research:</strong> Conducted vital doctoral research at the Lawrence Berkeley National Laboratory in California, analyzing transportation and energy trends.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/UNAM_Rectoria_Torre.jpg/800px-UNAM_Rectoria_Torre.jpg" alt="UNAM Campus">
                <div class="copyright-tag">Photo: Dr. Edgardo W. O. / Wikimedia Commons (CC BY-SA 3.0) - Represents UNAM Academic Background</div>
            </div>
        </div>
    </div>

    <!-- PAGE 4: MAJOR CONTRIBUTIONS & ACHIEVEMENTS -->
    <div class="slide">
        <h2>3. Major Contributions & Achievements</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Nobel Peace Prize Contribution:</strong> Served as a contributing author for the UN Intergovernmental Panel on Climate Change (IPCC), which shared the 2007 Nobel Peace Prize.</li>
                    <li><strong>Environmental Governance:</strong> As Mexico City's Environment Secretary (2000–2006), she spearheaded historic public transit initiatives like the Metrobús BRT system and massive green infrastructure projects.</li>
                    <li><strong>Mayoral Success:</strong> As Head of Government of Mexico City (2018–2023), she drastically reduced crime rates, expanded digital connectivity, and implemented extensive rainwater harvesting systems.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/87/Metrob%C3%BAs_CDMX_Indios_Verdes.jpg/800px-Metrob%C3%BAs_CDMX_Indios_Verdes.jpg" alt="Mexico City Metrobús">
                <div class="copyright-tag">Photo: ProtoplasmaKid / Wikimedia Commons (CC BY-SA 4.0) - Illustrating Urban Transit Innovation</div>
            </div>
        </div>
    </div>

    <!-- PAGE 5: LEADERSHIP QUALITIES & STYLE -->
    <div class="slide">
        <h2>4. Leadership Qualities & Style</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Data-Driven Pragmatism:</strong> Frequently states, <em>"I believe in science."</em> She formulates public policy based on analytics, statistical evidence, and logistical feasibility.</li>
                    <li><strong>Calm and Methodical:</strong> Known for a composed, analytical demeanor—remaining calm and collected under immense political and social pressure.</li>
                    <li><strong>Collaborative Reformer:</strong> Balances grassroots public engagement with rigorous administrative efficiency, prioritizing structured planning over reactive politics.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/d/d4/Claudia_Sheinbaum_-_2018_%28cropped%29.jpg/800px-Claudia_Sheinbaum_-_2018_%28cropped%29.jpg" alt="Sheinbaum speaking">
                <div class="copyright-tag">Photo: Gobierno de la Ciudad de México / Wikimedia Commons (Public Domain)</div>
            </div>
        </div>
    </div>

    <!-- PAGE 6: CHALLENGES & HOW THEY WERE OVERCOME -->
    <div class="slide">
        <h2>5. Challenges & How They Were Overcome</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Navigating the Pandemic:</strong> Faced immense friction during COVID-19 by balancing public health safety protocols (expanding testing, emphasizing mask-wearing) with economic realities in a mega-city of 9 million people.</li>
                    <li><strong>Overcoming Systemic Barriers:</strong> Broke through deep-rooted political glass ceilings in a historically male-dominated arena through tireless advocacy and grassroots mobilization.</li>
                    <li><strong>Addressing Security & Infrastructure:</strong> Tackled complex urban safety concerns by upgrading intelligence-led policing, community social programs, and expanding modern infrastructure.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/73/Zocalo_CDMX_2022.jpg/800px-Zocalo_CDMX_2022.jpg" alt="Mexico City Zocalo">
                <div class="copyright-tag">Photo: Christopher Alvarenga / Wikimedia Commons (CC BY-SA 4.0) - Central Mexico City Square</div>
            </div>
        </div>
    </div>

    <!-- PAGE 7: LASTING IMPACTS & LEGACY -->
    <div class="slide">
        <h2>6. Lasting Impacts & Legacy</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>Breaking Barriers for Women:</strong> Redefining political leadership paradigms globally, proving that technical expertise and gender inclusion can coexist powerfully at the highest level of state.</li>
                    <li><strong>Green Energy Transition:</strong> Shifted national conversations toward subsidized renewable energy sources, energy efficiency, and combating climate change.</li>
                    <li><strong>Institutional Trust:</strong> Left a framework of transparent governance and public accountability that serves as a blueprint for modern Latin American democracies.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b3/Solar_power_plants_%28cropped%29.jpg/800px-Solar_power_plants_%28cropped%29.jpg" alt="Solar Energy Panels">
                <div class="copyright-tag">Photo: US Department of Energy / Wikimedia Commons (Public Domain) - Representing Green Transition</div>
            </div>
        </div>
    </div>

    <!-- PAGE 8: PERSONAL REFLECTIONS & LESSONS LEARNED -->
    <div class="slide">
        <h2>7. Personal Reflections & Lessons Learned</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>The Power of Preparation:</strong> Excellence in education and deep subject matter competence provide a sturdy anchor during times of crisis.</li>
                    <li><strong>Resilience in Leadership:</strong> True leadership is not about avoiding obstacles, but about tackling them methodically with composure and empathy.</li>
                    <li><strong>Breaking Glass Ceilings:</strong> Demonstrates that representation matters deeply—opening doors and inspiring future generations of young girls globally to step into science, technology, and governance.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/89/Palacio_Nacional_Mexico_City.jpg/800px-Palacio_Nacional_Mexico_City.jpg" alt="Palacio Nacional Mexico">
                <div class="copyright-tag">Photo: Diego Delso / Wikimedia Commons (CC BY-SA 4.0) - National Palace, Mexico</div>
            </div>
        </div>
    </div>

    <!-- PAGE 9: CONCLUSION & SUMMARY -->
    <div class="slide">
        <h2>8. Conclusion</h2>
        <div class="content-body">
            <div class="text-content">
                <ul>
                    <li><strong>A Transformative Figure:</strong> Claudia Sheinbaum’s journey from a dedicated climate scientist and UNAM researcher to the President of Mexico is nothing short of inspirational.</li>
                    <li><strong>A Blend of Science and Humanity:</strong> Her career proves that analytical precision and compassionate public service can successfully merge to yield long-term societal benefits.</li>
                    <li><strong>Enduring Inspiration:</strong> Her legacy continues to shape the future of modern governance, equality, and environmental sustainability.</li>
                </ul>
            </div>
            <div class="image-container">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/c9/Bandera_de_M%C3%A9xico.svg/800px-Bandera_de_M%C3%A9xico.svg.png" alt="Flag of Mexico">
                <div class="copyright-tag">Image: Government of Mexico / Wikimedia Commons (Public Domain)</div>
            </div>
        </div>
    </div>

    <!-- PAGE 10: REFERENCES & THANK YOU -->
    <div class="slide">
        <h2>9. References & Thank You</h2>
        <div class="content-body" style="align-items: flex-start;">
            <div class="text-content" style="font-size: 0.95rem;">
                <p><strong>Key Sources & Further Reading:</strong></p>
                <ul>
                    <li>Encyclopædia Britannica - <em>"Claudia Sheinbaum: Biography & Policies"</em>.</li>
                    <li>Wikipedia - <em>"Claudia Sheinbaum"</em> and <em>"Cabinet of Claudia Sheinbaum"</em>.</li>
                    <li>PBS NewsHour - <em>"Who is Claudia Sheinbaum? Here's what to know about Mexico's leader"</em>.</li>
                    <li>Archives of Women's Political Communication - Iowa State University.</li>
                </ul>
                <p style="margin-top: 25px; text-align: center; font-size: 1.3rem; color: var(--primary-color);">
                    <strong>Thank You for Listening!</strong><br>
                    <span style="font-size: 1rem; color: #555;">Questions or Discussion?</span>
                </p>
            </div>
        </div>
    </div>

    <!-- NAVIGATION BAR -->
    <div class="nav-controls">
        <button id="prevBtn" onclick="changeSlide(-1)" disabled>Previous</button>
        <span class="slide-counter" id="slideCounter">Page 1 of 10</span>
        <button id="nextBtn" onclick="changeSlide(1)">Next</button>
    </div>

</div>

<script>
    let currentSlide = 0;
    const slides = document.querySelectorAll('.slide');
    const totalSlides = slides.length;

    function updateSlideDisplay() {
        slides.forEach((slide, index) => {
            slide.classList.toggle('active', index === currentSlide);
        });

        document.getElementById('slideCounter').innerText = `Page ${currentSlide + 1} of ${totalSlides}`;
        document.getElementById('prevBtn').disabled = currentSlide === 0;
        document.getElementById('nextBtn').disabled = currentSlide === totalSlides - 1;
    }

    function changeSlide(direction) {
        currentSlide += direction;
        if (currentSlide < 0) currentSlide = 0;
        if (currentSlide >= totalSlides) currentSlide = totalSlides - 1;
        updateSlideDisplay();
    }
</script>

</body>
</html>
