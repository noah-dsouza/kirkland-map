An online, mobile-oriented indoor navigation web app for self-storage facilities to help customers find the quickest route from the loading dock directly to their storage unit.

Overview

Navigating large, multi-level self-storage facilities while pushing heavy carts or carrying boxes can be confusing. This tool eliminates the hassle by providing a mobile-first, turn-by-turn indoor routing interface that calculates the fastest path through hallways, elevators, and corridors.

Key Features

Mobile-First Interface: Optimized for quick, single-handed use on smartphones while walking through corridors.

Loading Dock to Unit Routing: Select your starting dock/bay and get precise directional guidance right to your locker.

Indoor Navigation Logic: Map routing engineered specifically to handle interior hallways, floor changes, and elevator links.

Fast & Responsive: Lightweight structure designed to load quickly on mobile web browsers, even inside shielded facility interiors.

🛠️ Tech Stack

Frontend: HTML5, CSS3, JavaScript (ES6+)

Styling: Mobile-first Responsive CSS / Web Components

Routing & Mapping: Custom pathfinding using djikistra and A* & SVG visual mapping

🏁 Quick Start

Prerequisites

Node.js (v18.0 or higher)

npm or yarn

Installation

Clone the repository:
git clone https://github.com/noah-dsouza/kirkland-map.git
cd kirkland-map

Install dependencies:
npm install

Start the development server:
npm run dev

Open your mobile browser or emulator at http://localhost:3000.

Facility Map Configuration

To configure or update floor plans, hallway nodes, and unit locations:

Floor plans and vector maps are stored in the assets directory.

Routing nodes (docks, elevators, intersections, unit doors) and facility coordinates can be updated directly within the configuration files.

Contributing

Fork the repository

Create your feature branch (git checkout -b feature/AmazingFeature)

Commit your changes (git commit -m 'Add some AmazingFeature')

Push to the branch (git push origin feature/AmazingFeature)

Open a Pull Request
