# Yurakin.github.io
chernobyl nhd project
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Chernobyl Disaster: Reaction and Reform</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; background-color: #f7f7f7; color: #333; }
header { background-color: #2c3e50; color: white; padding: 10px 0; position: sticky; top: 0; z-index: 100; }
header nav { display: flex; justify-content: center; gap: 15px; }
header nav a { color: white; text-decoration: none; font-weight: bold; }
header nav a:hover { text-decoration: underline; }
h1, h2, h3 { color: #2c3e50; }
.section { background: #fff; padding: 20px; margin: 20px; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
img { max-width: 100%; height: auto; margin: 10px 0; }
iframe { border: 0; margin: 10px 0; width: 100%; height: 400px; }
canvas { margin: 10px 0; }
ul { margin: 10px 0 10px 20px; }
footer { font-size: 0.8em; text-align: center; margin-top: 30px; color: #555; }
</style>
</head>
<body>

<header>
<nav>
<a href="#intro">Home</a>
<a href="#history">History</a>
<a href="#safety">Safety</a>
<a href="#nuclear-power">Nuclear Power</a>
<a href="#political">Political Impact</a>
<a href="#cartoons">Cartoons</a>
<a href="#sources">Sources</a>
</nav>
</header>

<div class="section" id="intro">
<h1>Chernobyl Disaster: Reaction and Reform</h1>
<p>On April 26, 1986, Reactor 4 at the <strong>Chernobyl Nuclear Power Plant</strong> exploded in Ukraine. The RBMK Soviet reactor design had serious safety flaws. Radiation spread across Europe, forcing the evacuation of nearby Pripyat. The Soviet Union initially hid the disaster, demonstrating the dangers of secrecy and political control (“Report on the Accident at the Chernobyl Nuclear Power Station”).</p>
<p><strong>Thesis:</strong> The Chernobyl disaster caused worldwide fear, prompted immediate reactions, and led to reforms in nuclear safety, international policy, and reactor design, showing how disasters can drive global change.</p>
</div>

<div class="section" id="history">
<h2>History and Cover-Up</h2>
<p>The explosion occurred during a safety test gone wrong. Human error and flawed reactor design caused overheating. Radiation was detected in Sweden before the Soviet Union admitted the accident. The event exposed flaws in Soviet internal politics and sparked international concern (“Chernobyl Explosion”).</p>
<p>Earlier, the 1979 <strong>Three Mile Island</strong> accident in the U.S. had already shown the need for better training and emergency planning, but Chernobyl forced a worldwide reaction (“Report on the Accident at the Chernobyl Nuclear Power Station”).</p>
<img src="images/chernobyl_shelter.png" alt="Chernobyl Shelter">
</div>

<div class="section" id="safety">
<h2>Safety Improvements Over Time</h2>
<h3>After Chernobyl</h3>
<ul>
<li>RBMK reactors were redesigned to prevent overheating (“RBMK Reactors – Appendix”).</li>
<li>International Atomic Energy Agency (IAEA) strengthened safety rules (“How Chernobyl Jump-Started the Global Nuclear Safety Regime”).</li>
</ul>
<h3>After Fukushima (Japan, 2011)</h3>
<ul>
<li>Backup cooling systems were improved.</li>
<li>Stronger sea walls and flood protections were added.</li>
<li>Automatic shutdown systems became mandatory.</li>
</ul>
<h3>Modern Designs</h3>
<p><strong>China:</strong> Uses Hualong One reactors with double containment walls and passive cooling (“Plans For New Reactors Worldwide”).</p>
<p><strong>France:</strong> Uses European Pressurized Reactors (Generation III+) with automatic shutdown systems. Modern reactors are safer and more efficient than older designs.</p>
</div>

<div class="section" id="nuclear-power">
<h2>Nuclear Power Around the World</h2>
<p>Countries like France, China, and the U.S. rely on nuclear power for electricity. Nuclear energy grew in the 1970s and 1980s, slowed after Chernobyl, and increased again after 2000. Charts and maps help illustrate these changes.</p>
<h3>World Map of Nuclear Plants</h3>
<iframe src="https://www.world-nuclear.org/information-library/current-and-future-generation/plans-for-new-reactors-worldwide.aspx"></iframe>

<h3>Global Nuclear Energy Use Over Time</h3>
<canvas id="nuclearChart"></canvas>
<script>
const ctx = document.getElementById('nuclearChart').getContext('2d');
new Chart(ctx, {
 type: 'line',
 data: {
   labels: ['1970','1980','1990','2000','2010','2020'],
   datasets: [{
     label: 'Global Nuclear Electricity (%)',
     data: [2,8,17,16,13,10],
     borderColor: 'rgb(54,162,235)',
     backgroundColor: 'rgba(54,162,235,0.2)',
     tension: 0.1,
     fill: false
   }]
 }
});
</script>
</div>

<div class="section" id="political">
<h2>Political Impact</h2>
<p>Chernobyl led to major reforms in international nuclear policy. IAEA agreements set stricter safety rules. Governments revised legislation, emergency protocols, and operator training. Ecological movements in Eastern Europe increased pressure for environmental reforms. The cover-up highlighted how secrecy and politics can worsen disasters (“Chernobyl Disaster Spurs Ecological Movements in Eastern Europe”).</p>
</div>

<div class="section" id="cartoons">
<h2>Political Cartoon Ideas</h2>
<ul>
<li>A cracked 1986 RBMK reactor next to a modern 2026 reactor with shields and safety features.</li>
<li>The Earth wearing a radiation symbol in 1986, then wearing a safety helmet in 2026.</li>
</ul>
</div>

<div class="section" id="sources">
<h2>Sources</h2>
<ul>
<li>"Alps Still Contaminated by Radiation from Chernobyl." Medicine, Health, and Bioethics, 2006. Gale in Context.</li>
<li>Chernobyl Disaster Spurs Ecological Movements in Eastern Europe. 2006. Gale in Context.</li>
<li>"Chernobyl Explosion." Gale World History Online, 2023.</li>
<li>"Chernobyl Shelter." gao.gov, images/chernobyl_shelter.png.</li>
<li>"Frequently asked questions about Chernobyl." iaea.org.</li>
<li>"How Chernobyl Jump-Started the Global Nuclear Safety Regime." goa.gov, 2019.</li>
<li>"RBMK Reactors – Appendix to Nuclear Power Reactors." world-nuclear.org, 2026.</li>
<li>"Plans For New Reactors Worldwide." world-nuclear.org, 2026.</li>
<li>"Report on the Accident at the Chernobyl Nuclear Power Station." nrc.gov, 1987.</li>
<li>"Scientists can't agree about Chernobyl's impact on wildlife." KnowableMagazine, 2022.</li>
</ul>
</div>

<footer>
<p>&copy; 2026 Chernobyl NHD Website</p>
</footer>

</body>
</html>
