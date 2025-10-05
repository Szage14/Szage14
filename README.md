# Cristian Jay - Gamified Developer Portfolio

A futuristic, cyberpunk-inspired portfolio showcasing Cristian Jay's full-stack development journey through a gamified interface. Experience progression bars, achievement systems, and neon-lit UI elements that transform a traditional resume into an interactive character profile.

## Features

### Gaming Elements
- **Level & XP System**: Visual representation of experience with animated XP bar
- **Skill Progression Bars**: Tech stack displayed as leveling skills with percentage mastery
- **Quest System**: Projects presented as completed quests with rarity tiers (Legendary, Epic, Rare)
- **Achievement Badges**: Visual indicators for milestones and accomplishments
- **Character Stats Panel**: Quick overview of key metrics (projects, skills, achievements)

### Cyberpunk Aesthetics
- **Neon Color Scheme**: Electric cyan and magenta accents on dark backgrounds
- **Holographic Cards**: Glassmorphic effects with animated borders
- **Scan Line Effects**: Retro CRT monitor-inspired animations
- **Grid Background**: Animated perspective grid for depth
- **Glitch Animations**: Subtle text glitches and hover effects

### Interactive UI
- **Hover Animations**: Cards lift and glow on interaction
- **Smooth Transitions**: Polished animations throughout
- **Responsive Design**: Optimized for all screen sizes
- **Accessibility**: Semantic HTML and ARIA labels

## Tech Stack

- **Framework**: Next.js 15 (App Router)
- **Styling**: Tailwind CSS v4
- **UI Components**: shadcn/ui
- **Icons**: Lucide React
- **Fonts**: Orbitron (headings), Inter (body)
- **Language**: TypeScript

## Project Structure

\`\`\`
├── app/
│   ├── layout.tsx          # Root layout with font configuration
│   ├── page.tsx            # Main portfolio page
│   └── globals.css         # Global styles and design tokens
├── components/
│   └── ui/                 # shadcn/ui components
└── public/                 # Static assets
\`\`\`

## Design System

### Color Palette
- **Primary**: Cyan (#00f0ff) - Main accent color
- **Secondary**: Magenta (#ff00ff) - Secondary accent
- **Background**: Dark grays (#0a0a0a, #111111)
- **Foreground**: Light grays for text
- **Accents**: Neon variants for highlights

### Typography
- **Headings**: Orbitron (futuristic, geometric)
- **Body**: Inter (clean, readable)
- **Monospace**: Geist Mono (code snippets)

### Components

#### Hero Section
- Animated profile with level badge
- Real-time XP bar animation
- Character stats grid
- Glowing neon borders

#### Skills Section
- Categorized skill groups (Frontend, Backend, Tools)
- Animated progression bars
- Percentage indicators
- Hover effects with glow

#### Projects Section
- Quest-style cards with rarity colors
- Tech stack badges
- XP rewards
- GitHub and live demo links
- Holographic card effects

#### Experience Timeline
- Chronological work history
- Company logos and descriptions
- Duration indicators
- Animated connectors

#### Education Section
- Academic achievements
- Graduation details
- Relevant coursework

## Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository
\`\`\`bash
git clone <repository-url>
cd cjay-portfolio
\`\`\`

2. Install dependencies
\`\`\`bash
npm install
\`\`\`

3. Run the development server
\`\`\`bash
npm run dev
\`\`\`

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### Build for Production

\`\`\`bash
npm run build
npm start
\`\`\`

## Customization

### Update Personal Information
Edit the data in `app/page.tsx`:
- Profile information (name, title, bio)
- Skills array with categories
- Projects with descriptions and links
- Work experience timeline
- Education details

### Modify Design Tokens
Adjust colors and styles in `app/globals.css`:
- Color scheme variables
- Animation timings
- Border styles
- Glow effects

### Change Fonts
Update font imports in `app/layout.tsx` and reference in `globals.css`

## Performance

- **Optimized Images**: Use Next.js Image component for assets
- **Code Splitting**: Automatic with Next.js App Router
- **CSS-in-JS**: Tailwind for minimal runtime overhead
- **Animations**: GPU-accelerated transforms

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

MIT License - feel free to use this template for your own portfolio!

## Credits

Designed and developed with a focus on creating an immersive, game-like experience for showcasing developer skills and projects.

---

**Level Up Your Portfolio** 🎮✨
