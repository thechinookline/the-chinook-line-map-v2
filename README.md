# The Chinook Line

An interactive visualization of a proposed Alberta skytrain network connecting Calgary to Edmonton. The system includes 21 stations serving airports, colleges, downtown centers, and communities along the route, with both straight and curved rail segments displayed on a 3D map.

## Getting Started

First, run the development server:

```bash
npm run dev
```

```bash
 npx next dev --turbo
```

Leaflet Map:

https://leafletjs.com/reference.html

# Alberta Regional Map - Interactive Location Visualizer

An interactive web application showcasing key locations across Alberta with route visualization between major points of interest.


## 📍 About This Project V2 2025

This interactive map displays various important locations across Alberta (Calgary to Edmonton), including educational institutions, airports, downtown centers, and community hubs. The application features route visualization connecting these locations with both straight and curved path lines.

### Key Features

- **Interactive Leaflet Map** - Smooth zoom and pan navigation
- **Location Markers** - Detailed popups with location information
- **Route Visualization** - Color-coded paths between locations
- **Mixed Route Types** - Both straight lines and curved arcs
- **Responsive Design** - Works on desktop and mobile devices
- **TypeScript** - Fully typed for better development experience

## 🗺️ Locations Displayed

### Educational Institutions
- **Bow Valley College** - Downtown Calgary campus
- **Red Deer Polytechnic** - Main campus
- **University of Alberta** - Main Edmonton campus

### Airports
- **Calgary International Airport (YYC)**
- **Red Deer Regional Airport (YQF)**

### Major Centers
- **Airdrie Downtown** - City centre
- **Crossfield Downtown** - Town centre
- **Lacombe** - City centre
- **Wetaskiwin** - City centre
- **Leduc** - City centre

### Communities & Towns
- Carstairs, Didsbury, Olds, Bowden, Innisfail, Penhold, Blackfalds, Ponoka, Maskwacis, Millet

### Landmarks
- **West Edmonton Mall** - World's largest shopping mall

## 🛣️ Route Network

The map displays a comprehensive route system connecting:

1. **Calgary to Edmonton Corridor**
   - Calgary Downtown (BowValley College) → Calgary Airport → Airdrie → Crossfield → Carstairs → Didsbury → Olds → Bowden → Innisfail → Penhold → Red Deer Airport → Red Deer Polytechnic → Blackfalds → Lacombe → Ponoka → Maskwacis → Wetaskiwin → Millet → Leduc → University of Alberta → West Edmonton Mall

2. **Special Routes**
   - **Curved Routes**: 
     - Bow Valley College to Calgary Airport
     - University of Alberta to West Edmonton Mall
     - Leduc to University of Alberta
   - **Straight Routes**: All other connections

## 🛠️ Technical Stack

- **Framework**: Next.js 14 with TypeScript
- **Mapping**: Leaflet.js with OpenStreetMap tiles
- **Styling**: CSS3 with responsive design
- **Deployment**: Netlify
- **Icons**: Leaflet default markers

## 📁 Project Structure
```
skytrain-2025-v1/
├── app/
│ ├── components/
│ │ └── Map.tsx # Main map component
│ ├── utils/
│ │ ├── coordinates.ts # Location data and routes
│ │ └── createArcCurve.ts # Curved route generator
│ ├── favicon.ico 
│ ├── globals.css 
│ ├── layout.tsx 
│ └── page.tsx # Main page
├── public/ # Static assets
├── package.json # Dependencies and scripts
├── next.config.js # Next.js configuration
├── netlify.toml # Netlify deployment config
└── README.md # This file
```

## Acknowledgments
OpenStreetMap for base map tiles

Leaflet.js for interactive mapping capabilities

Next.js team for the excellent React framework

Netlify for seamless deployment


## Important Disclaimers
### Legal & Government Relations Disclaimer
This project is a conceptual visualization created by independent developers and does not represent any official government plans, proposals, or endorsements.

I am not affiliated with any government agency, transportation authority, or official planning body in Alberta or Canada. This skytrain concept is purely speculative and created for demonstration purposes only.

### Startup Status & Intentions
This project represents a startup vision and entrepreneurial exploration of potential transit solutions. As a startup initiative:

1. No Official Authority: This concept has not been reviewed, approved, or endorsed by any government entity
2. Future Collaboration Needed: Actual implementation would require extensive consultation, approval, and partnership with:

- Municipal governments (Calgary, Edmonton, and all towns along the route)
- Provincial Government of Alberta
- Federal transportation authorities
- Indigenous communities and First Nations
- Environmental regulatory bodies

3. Conceptual Stage Only: This visualization exists to stimulate discussion and explore possibilities

Required Next Steps for Realization
For this concept to move beyond visualization, the following would be necessary:

- Government Consultation: Formal discussions with municipal, provincial, and federal officials
- Feasibility Studies: Comprehensive technical, environmental, and economic analysis
- Community Engagement: Public consultations with all affected communities
- Regulatory Approvals: Compliance with all transportation, land use, and environmental regulations
- Funding Partnerships: Collaboration with public and private funding sources

### Contact & Collaboration
I welcome dialogue with:

- Government officials and transportation planners
- Urban development experts
- Community representatives
- Potential partners and investors

This project should be viewed as a conversation starter and conceptual exploration, not as an imminent or approved infrastructure project.

> Note: All coordinates, station locations, and route designs are approximate and conceptual. Real-world implementation would require significant adjustments based on engineering studies, land availability, and community input.