
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Tarekegn Dejen Mengistu | Hydrology × Machine Learning Researcher</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
</head>

<body>
<header class="header">
    <div class="container nav">
        <div class="logo">TDM</div>
        <nav>
            <a href="#about">About</a>
            <a href="#research">Research</a>
            <a href="#skills">Skills</a>
            <a href="#publications">Publications</a>
            <a href="#awards">Awards</a>
            <a href="#contact">Contact</a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container hero-grid">
        <div>
            <p class="tagline">Hydrology × Machine Learning × Uncertainty Modeling</p>
            <h1>I'm <span class="accent">Tarekegn Dejen Mengistu</span></h1>
            <p class="desc">
                Hydrologist and ML researcher integrating physics-guided hydrological models
                with probabilistic deep learning, Bayesian inference, and large-scale
                climate data analytics to build resilient predictive systems.
            </p>
            <div class="actions">
                <a class="btn primary" href="#research">View Research</a>
                <a class="btn secondary" href="#contact">Contact</a>
            </div>
        </div>

        <div class="panel">
            <h2>Core Focus</h2>
            <ul>
                <li>Physics-guided ML frameworks</li>
                <li>SWAT / SWAT-MODFLOW modeling</li>
                <li>Probabilistic deep learning & uncertainty</li>
                <li>Climate-resilient water resources analytics</li>
            </ul>
        </div>
    </div>
</section>

<section id="about" class="section">
    <div class="container">
        <h2>About Me</h2>
        <p>
            I am a PhD researcher at the University of Science and Technology (UST), Korea,
            specializing in large-scale hydrology, ML-based predictive analytics, and
            uncertainty-aware modeling for sustainable water management.
        </p>
    </div>
</section>

<section id="research" class="section alt">
    <div class="container">
        <h2>Research Areas</h2>
        <ul>
            <li>Large-scale hydrological predictive analytics</li>
            <li>Probabilistic deep learning & Bayesian neural networks</li>
            <li>Uncertainty quantification & explainable ML</li>
            <li>Climate change impact modeling</li>
            <li>Geospatial environmental data analytics</li>
        </ul>
    </div>
</section>

<section id="skills" class="section">
    <div class="container">
        <h2>Technical Skills</h2>
        <div class="grid">
            <div class="card">
                <h3>Machine Learning & AI</h3>
                <ul>
                    <li>TensorFlow, TensorFlow Probability</li>
                    <li>Scikit-learn, NumPy, SciPy</li>
                    <li>Bayesian NN, uncertainty modeling</li>
                    <li>CNN, RNN/LSTM, ensemble ML</li>
                    <li>XAI (SHAP)</li>
                </ul>
            </div>

            <div class="card">
                <h3>Hydrological Modeling</h3>
                <ul>
                    <li>SWAT, SWAT+, SWAT-MODFLOW</li>
                    <li>Hydro-climatic data analytics</li>
                    <li>River–aquifer interaction modeling</li>
                </ul>
            </div>

            <div class="card">
                <h3>Data & Geospatial</h3>
                <ul>
                    <li>GeoPandas, GIS & Remote Sensing</li>
                    <li>Raster/Vector processing</li>
                    <li>Large-scale ETL workflows</li>
                </ul>
            </div>
        </div>
    </div>
</section>

<section id="publications" class="section alt">
    <div class="container">
        <h2>Selected Publications</h2>
        <ul>
            <li>Coupled SWAT–MODFLOW ensemble model for groundwater sustainability (2025)</li>
            <li>Climate change impacts on water resources vulnerability (2025)</li>
            <li>Land cover dynamics & groundwater recharge (Water, 2022)</li>
            <li>Aquifer recharge zone mapping (Water, 2022)</li>
            <li>Regional flood frequency analysis (Water, 2022)</li>
        </ul>
    </div>
</section>

<section id="awards" class="section">
    <div class="container">
        <h2>Awards & Honors</h2>
        <ul>
            <li>Research Excellence Award, UST (2025)</li>
            <li>KICT Travel Award, EGU Conference (2025)</li>
            <li>Best Poster Presentation — SWAT Conference (2024)</li>
            <li>UST Doctoral Research Scholarship (2021–2026)</li>
        </ul>
    </div>
</section>

<section id="contact" class="section alt">
    <div class="container">
        <h2>Contact</h2>
        <p>Email: <a href="mailto:taredejum6@gmail.com">taredejum6@gmail.com</a></p>
        <p>GitHub: <a href="https://github.com/tdmengistu">github.com/tdmengistu</a></p>
        <p>Location: Korea</p>
    </div>
</section>

<footer class="footer">
    <p>© 2025 Tarekegn Dejen Mengistu — Hydrology × ML Research</p>
</footer>

</body>
</html>
"""

style_css = """
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #0f172a;
    color: #e5e7eb;
}

.header {
    background: #1e293b;
    border-bottom: 1px solid #334155;
    padding: 15px 0;
    position: sticky;
    top: 0;
}

.container {
    width: 90%;
    max-width: 1100px;
    margin: auto;
}

.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.nav a { margin-left: 20px; color: #93c5fd; }

.hero {
    padding: 60px 0;
}

.hero-grid {
    display: grid;
    grid-template-columns: 1.6fr 1fr;
    gap: 40px;
}

h1 .accent { color: #facc15; }

.btn {
    padding: 10px 20px;
    border-radius: 50px;
    border: 1px solid #38bdf8;
    display: inline-block;
}

.btn.primary { background: #38bdf8; color: #0f172a; }

.section { padding: 50px 0; }
.section.alt { background: #020617; }

.grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(260px,1fr)); gap: 20px; }

.card {
    background: #0b1120;
    padding: 20px;
    border-radius: 10px;
    border: 1px solid #334155;
}

.footer {
    text-align: center;
    padding: 20px;
    border-top: 1px solid #334155;
}
"""

# Write output files
with open("index.html", "w", encoding="utf-8") as f:
    f.write(index_html)

with open("style.css", "w", encoding="utf-8") as f:
    f.write(style_css)

print("Portfolio website files created successfully!")
