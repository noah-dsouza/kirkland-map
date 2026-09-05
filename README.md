<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KirklandMap - Facility Indoor Navigation</title>
</head>
<body>

    <!-- README Content Section -->
    <main style="max-width: 800px; margin: 0 auto; padding: 20px; font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Helvetica, Arial, sans-serif; line-height: 1.6; color: #24292e;">

        <h1>KirklandMap (StorageNav) 📱📦</h1>
        <p>An online, mobile-oriented indoor navigation web app for self-storage facilities to help customers find the quickest route from the loading dock directly to their storage unit.</p>

        <hr>

        <h2>🚀 Overview</h2>
        <p>Navigating large, multi-level self-storage facilities while pushing heavy carts or carrying boxes can be confusing. <strong>KirklandMap</strong> eliminates the hassle by providing a mobile-first, turn-by-turn indoor routing interface that calculates the fastest path through hallways, elevators, and corridors.</p>

        <h2>✨ Key Features</h2>
        <ul>
            <li><strong>Mobile-First Interface:</strong> Optimized for quick, single-handed use on smartphones while walking through corridors.</li>
            <li><strong>Loading Dock to Unit Routing:</strong> Select your starting dock/bay and get precise directional guidance right to your locker.</li>
            <li><strong>Indoor Navigation Logic:</strong> Map routing engineered specifically to handle interior hallways, floor changes, and elevator links.</li>
            <li><strong>Fast & Responsive:</strong> Lightweight structure designed to load quickly on mobile web browsers, even inside shielded facility interiors.</li>
        </ul>

        <h2>🛠️ Tech Stack</h2>
        <ul>
            <li><strong>Frontend:</strong> HTML5, CSS3, JavaScript (ES6+)</li>
            <li><strong>Styling:</strong> Mobile-first Responsive CSS</li>
            <li><strong>Routing & Mapping:</strong> Custom pathfinding & SVG/Canvas visual mapping</li>
        </ul>

        <h2>🏁 Quick Start</h2>

        <h3>Prerequisites</h3>
        <ul>
            <li>Node.js (v18.0 or higher)</li>
            <li>npm or yarn</li>
        </ul>

        <h3>Installation</h3>
        <p>1. Clone the repository:</p>
        <pre style="background: #f6f8fa; padding: 12px; border-radius: 6px; overflow-x: auto;"><code>git clone https://github.com/noah-dsouza/kirkland-map.git
cd kirkland-map</code></pre>

        <p>2. Install dependencies:</p>
        <pre style="background: #f6f8fa; padding: 12px; border-radius: 6px; overflow-x: auto;"><code>npm install</code></pre>

        <p>3. Start the development server:</p>
        <pre style="background: #f6f8fa; padding: 12px; border-radius: 6px; overflow-x: auto;"><code>npm run dev</code></pre>

        <p>4. Open your mobile browser or dev tools emulator at <code>http://localhost:3000</code>.</p>

        <h2>📐 Facility Map Configuration</h2>
        <p>To configure or update floor plans, hallway nodes, and unit locations:</p>
        <ul>
            <li>Floor plans and vector maps are stored in the assets directory.</li>
            <li>Routing nodes (docks, elevators, intersections, unit doors) and facility coordinates can be updated directly within the configuration files.</li>
        </ul>

        <h2>🤝 Contributing</h2>
        <ol>
            <li>Fork the repository</li>
            <li>Create your feature branch (<code>git checkout -b feature/AmazingFeature</code>)</li>
            <li>Commit your changes (<code>git commit -m 'Add some AmazingFeature'</code>)</li>
            <li>Push to the branch (<code>git push origin feature/AmazingFeature</code>)</li>
            <li>Open a Pull Request</li>
        </ol>

        <h2>📄 License</h2>
        <p>Distributed under the MIT License. See <code>LICENSE</code> for details.</p>

    </main>

</body>
</html>
