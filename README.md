# Science-Exhibition
SChool Science Exhibition.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>S.R.E.F's Seth Nandalal Dhoot English Medium School - Science Exhibition 2025-2026</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f9fc;
            color: #333;
            line-height: 1.6;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header {
            background: linear-gradient(135deg, #1a5fb4 0%, #3584e4 100%);
            color: white;
            padding: 30px 0;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }

        .logo-container {
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 15px;
        }

        .logo {
            font-size: 2.5rem;
            margin-right: 15px;
        }

        .school-name {
            font-size: 1.8rem;
            font-weight: 700;
        }

        .exhibition-title {
            font-size: 2.2rem;
            margin: 10px 0;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.2);
        }

        .exhibition-subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            margin-bottom: 10px;
        }

        .date-badge {
            display: inline-block;
            background: #f15b28;
            padding: 8px 20px;
            border-radius: 30px;
            font-weight: bold;
            margin-top: 10px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        .intro-section {
            padding: 40px 0;
            text-align: center;
            background-color: white;
            margin: 20px 0;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .intro-section h2 {
            color: #1a5fb4;
            margin-bottom: 20px;
            font-size: 1.8rem;
        }

        .intro-section p {
            max-width: 800px;
            margin: 0 auto 20px;
            font-size: 1.1rem;
        }

        .topics-section {
            padding: 30px 0;
        }

        .section-title {
            text-align: center;
            margin-bottom: 30px;
            color: #1a5fb4;
            font-size: 2rem;
            position: relative;
        }

        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: #f15b28;
            margin: 10px auto;
            border-radius: 2px;
        }

        .category {
            margin-bottom: 40px;
            background: white;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .category-header {
            background: #1a5fb4;
            color: white;
            padding: 15px 20px;
            display: flex;
            align-items: center;
        }

        .category-icon {
            font-size: 1.5rem;
            margin-right: 10px;
        }

        .category-title {
            font-size: 1.4rem;
            font-weight: 600;
        }

        .topics-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(350px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .topic-card {
            background: #f8fafc;
            border-radius: 8px;
            padding: 20px;
            transition: transform 0.3s, box-shadow 0.3s;
            border-left: 4px solid #3584e4;
            height: 100%;
            display: flex;
            flex-direction: column;
        }

        .topic-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 15px rgba(0, 0, 0, 0.1);
        }

        .topic-number {
            display: inline-block;
            background: #3584e4;
            color: white;
            width: 30px;
            height: 30px;
            border-radius: 50%;
            text-align: center;
            line-height: 30px;
            font-weight: bold;
            margin-bottom: 10px;
        }

        .topic-name {
            font-size: 1.2rem;
            font-weight: 600;
            margin-bottom: 10px;
            color: #1a5fb4;
        }

        .topic-summary {
            flex-grow: 1;
            color: #555;
        }

        footer {
            background: #1a2b4c;
            color: white;
            padding: 30px 0;
            margin-top: 40px;
        }

        .footer-content {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
        }

        .footer-section {
            flex: 1;
            min-width: 300px;
            margin-bottom: 20px;
        }

        .footer-section h3 {
            font-size: 1.3rem;
            margin-bottom: 15px;
            color: #f15b28;
        }

        .contact-info {
            list-style: none;
        }

        .contact-info li {
            margin-bottom: 10px;
            display: flex;
            align-items: center;
        }

        .contact-info i {
            margin-right: 10px;
            color: #f15b28;
        }

        .copyright {
            text-align: center;
            padding-top: 20px;
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            margin-top: 20px;
        }

        .inspiration-note {
            background: #e6f2ff;
            padding: 15px;
            border-radius: 8px;
            margin-top: 15px;
            border-left: 4px solid #f15b28;
        }

        @media (max-width: 768px) {
            .topics-grid {
                grid-template-columns: 1fr;
            }
            
            .school-name {
                font-size: 1.4rem;
            }
            
            .exhibition-title {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo-container">
                <div class="logo">
                    <i class="fas fa-atom"></i>
                </div>
                <div>
                    <div class="school-name">S.R.E.F's SETH NANDALAL DHOOT ENGLISH MEDIUM SCHOOL</div>
                    <div class="exhibition-title">SCIENCE EXHIBITION 2025-2026</div>
                    <div class="exhibition-subtitle">Exploring the Universe: From Our Planet to Outer Space</div>
                    <div class="date-badge">November 2025</div>
                </div>
            </div>
        </div>
    </header>

    <div class="container">
        <section class="intro-section">
            <h2>Welcome to Our Annual Science Exhibition</h2>
            <p>This year, our students from standards 6 to 9 will showcase innovative projects that connect classroom learning with real-world scientific exploration.</p>
            <p>All projects are designed to align with the Maharashtra State Board syllabus while encouraging creativity and problem-solving skills.</p>
        </section>

        <section class="topics-section">
            <h2 class="section-title">Exhibition Topics</h2>
            
            <!-- Category 1 -->
            <div class="category">
                <div class="category-header">
                    <div class="category-icon"><i class="fas fa-globe-asia"></i></div>
                    <div class="category-title">Our Planet & Environment</div>
                </div>
                <div class="topics-grid">
                    <div class="topic-card">
                        <div class="topic-number">1</div>
                        <div class="topic-name">The Greenhouse Effect in a Jar</div>
                        <div class="topic-summary">Create a small-scale model to demonstrate how greenhouse gases trap heat from a lamp (the Sun) and increase temperature inside a sealed jar compared to a control jar. This visually explains global warming.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">2</div>
                        <div class="topic-name">Watershed Management and Pollution</div>
                        <div class="topic-summary">Build a model of a watershed using a tray, soil, and clay. Use food coloring as "pollutant" to show how runoff carries pollution into rivers and lakes.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">3</div>
                        <div class="topic-name">Solar Still for Water Purification</div>
                        <div class="topic-summary">Construct a device using a plastic bowl and cling film to show how sunlight evaporates dirty water, which then condenses as clean water, demonstrating distillation.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">4</div>
                        <div class="topic-name">Working Model of a Dam & Hydroelectric Power</div>
                        <div class="topic-summary">Build a small dam across a stream in a tray. Use a water wheel connected to a motor to generate voltage, lighting an LED. Demonstrates energy conversion.</div>
                    </div>
                </div>
            </div>
            
            <!-- Category 2 -->
            <div class="category">
                <div class="category-header">
                    <div class="category-icon"><i class="fas fa-rocket"></i></div>
                    <div class="category-title">Space & Astronomy</div>
                </div>
                <div class="topics-grid">
                    <div class="topic-card">
                        <div class="topic-number">5</div>
                        <div class="topic-name">Phases of the Moon Model</div>
                        <div class="topic-summary">Create a physical model using a white ball (Moon) and a light bulb (Sun) to show and explain the different phases of the moon.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">6</div>
                        <div class="topic-name">Solar System Orrery</div>
                        <div class="topic-summary">Build a mechanical model of the solar system using different sized balls for planets, demonstrating the relative orbits around the Sun.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">7</div>
                        <div class="topic-name">Designing a Mars Lander</div>
                        <div class="topic-summary">Build a lander using straws, cups, and balloons that can protect a raw egg ("astronaut") when dropped. Teaches principles of impact and engineering.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">8</div>
                        <div class="topic-name">Sundial and the Earth's Rotation</div>
                        <div class="topic-summary">Construct a functional sundial using cardboard to show local time based on the shadow cast by the sun. Demonstrates Earth's rotation.</div>
                    </div>
                </div>
            </div>
            
            <!-- Category 3 -->
            <div class="category">
                <div class="category-header">
                    <div class="category-icon"><i class="fas fa-robot"></i></div>
                    <div class="category-title">Technology & Robotics</div>
                </div>
                <div class="topics-grid">
                    <div class="topic-card">
                        <div class="topic-number">9</div>
                        <div class="topic-name">Simple Robotic Arm</div>
                        <div class="topic-summary">Build a robotic arm using cardboard, syringes, and plastic tubes. Using hydraulics, the arm can pick up and move small objects.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">10</div>
                        <div class="topic-name">Smart Waste Segregator</div>
                        <div class="topic-summary">Create a model that uses a simple tilt mechanism or color sensor to separate different colored objects into bins representing waste types.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">11</div>
                        <div class="topic-name">Water Level Indicator</div>
                        <div class="topic-summary">Using wires, batteries, and LEDs, create a circuit that lights up sequentially as water level rises in a tank.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">12</div>
                        <div class="topic-name">Automatic Street Light Controller</div>
                        <div class="topic-summary">Build a circuit using an LDR that automatically turns an LED on when ambient light falls and off during the day, saving energy.</div>
                    </div>
                </div>
            </div>
            
            <!-- Category 4 -->
            <div class="category">
                <div class="category-header">
                    <div class="category-icon"><i class="fas fa-dna"></i></div>
                    <div class="category-title">Biology & Human Health</div>
                </div>
                <div class="topics-grid">
                    <div class="topic-card">
                        <div class="topic-number">13</div>
                        <div class="topic-name">Working Model of the Human Lungs</div>
                        <div class="topic-summary">Use a plastic bottle as the ribcage, balloons as lungs, and a rubber sheet as the diaphragm to demonstrate inhalation and exhalation.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">14</div>
                        <div class="topic-name">DNA Double Helix Model</div>
                        <div class="topic-summary">Create a 3D model of the DNA structure using colored beads or pipe cleaners to visualize the double helix and base pairing.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">15</div>
                        <div class="topic-name">Hydroponics - Growing Plants Without Soil</div>
                        <div class="topic-summary">Set up a small hydroponic system using plastic bottles and nutrient solution to demonstrate alternative farming techniques.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">16</div>
                        <div class="topic-name">The Solar Cooker</div>
                        <div class="topic-summary">Design and build a solar cooker using a cardboard box and aluminum foil to demonstrate use of solar energy for cooking.</div>
                    </div>
                </div>
            </div>
            
            <!-- Category 5 -->
            <div class="category">
                <div class="category-header">
                    <div class="category-icon"><i class="fas fa-flask"></i></div>
                    <div class="category-title">Physics & Chemistry in Action</div>
                </div>
                <div class="topics-grid">
                    <div class="topic-card">
                        <div class="topic-number">17</div>
                        <div class="topic-name">Newton's Cradle</div>
                        <div class="topic-summary">Build the classic physics toy using metal balls suspended with strings to demonstrate conservation of energy and momentum.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">18</div>
                        <div class="topic-name">Electromagnetic Train</div>
                        <div class="topic-summary">Create a simple "train" using a battery and magnets that propels itself inside a coiled copper wire, demonstrating electromagnetism.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">19</div>
                        <div class="topic-name">Volcano Eruption (Chemical Reaction)</div>
                        <div class="topic-summary">Build a volcano structure and cause an eruption using a chemical reaction between baking soda and vinegar, producing carbon dioxide gas.</div>
                    </div>
                    <div class="topic-card">
                        <div class="topic-number">20</div>
                        <div class="topic-name">Lemon Battery and Potato Clock</div>
                        <div class="topic-summary">Demonstrate how chemical energy can be converted into electrical energy using lemons or potatoes to power a small clock or LED.</div>
                    </div>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <div class="container">
            <div class="footer-content">
                <div class="footer-section">
                    <h3>Contact Information</h3>
                    <ul class="contact-info">
                        <li><i class="fas fa-map-marker-alt"></i> Bhavani Nagar, Near ITI College, Ahilyanagar, Maharashtra</li>
                        <li><i class="fas fa-phone"></i> 9762375647</li>
                        <li><i class="fas fa-envelope"></i> sref1@yahoo.com</li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Exhibition Details</h3>
                    <ul class="contact-info">
                        <li><i class="fas fa-calendar-alt"></i> November 2025</li>
                        <li><i class="fas fa-clock"></i> 9:00 AM - 4:00 PM</li>
                        <li><i class="fas fa-users"></i> Open to Students, Parents & Guests</li>
                    </ul>
                </div>
                <div class="footer-section">
                    <h3>Organized By</h3>
                    <p>Science Department<br>S.R.E.F's Seth Nandalal Dhoot English Medium School</p>
                </div>
            </div>
            <div class="copyright">
                <p>&copy; 2025 S.R.E.F's Seth Nandalal Dhoot English Medium School. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
