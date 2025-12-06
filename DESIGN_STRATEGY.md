# Cryzese Website Design Strategy

## Design Philosophy: Hyper-Futuristic Cinematic Tech

### Core Principles
1. **Premium Minimalism**: Clean, spacious layouts with intentional negative space
2. **Animated Immersion**: Every section reveals with smooth, purposeful motion
3. **Cryptographic Elegance**: Neural mesh patterns and flowing data lines as visual metaphors
4. **Cinematic Depth**: Layered elements with parallax, glow, and 3D effects

### Color Palette (OKLCH Format)
- **Dark Futuristic Base**: `oklch(0.08 0.01 280)` (#02050A)
- **Deep Blue Gradient**: `oklch(0.25 0.15 240)` → `oklch(0.50 0.20 250)` (#003C90 → #007BFF)
- **Silver Metallic**: `oklch(0.80 0.05 280)` (#C9CED7)
- **Neon Cyan Glow**: `oklch(0.65 0.25 200)` (#00E8FF)
- **Accent Blue**: `oklch(0.60 0.20 250)` (#0099FF)

### Typography System
- **Display Font**: Orbitron (bold, geometric, futuristic)
- **Heading Font**: Poppins (clean, modern, professional)
- **Body Font**: Inter (readable, neutral, technical)

### Animation Guidelines
- **Parallax**: Subtle depth on scroll (2-5% offset)
- **Floating Particles**: Slow, organic drift (8-12s duration)
- **Glow Pulse**: Soft radiance on interactive elements (1.5-2s cycle)
- **Section Reveals**: Staggered fade-in + slide-up (0.6-0.8s)
- **3D Mesh**: Scroll-reactive neural network animation

### Signature Visual Elements
1. **Neural Mesh Patterns**: SVG-based animated network nodes
2. **Glowing Halos**: Soft blur + shadow effects on logos and CTAs
3. **Data Flow Lines**: Animated gradient strokes suggesting information flow
4. **Circuit Paths**: Geometric patterns in background sections

### Interaction Philosophy
- **Hover States**: Glow intensification, subtle scale increase
- **Button Feedback**: Pulse animation on hover, smooth state transitions
- **Scroll Triggers**: Reveal animations tied to viewport intersection
- **Responsive Depth**: 3D effects scale down gracefully on mobile

---

## Implementation Notes
- All animations use Framer Motion for smooth performance
- Three.js for 3D neural mesh background (hero section)
- Recharts for tokenomics donut chart
- SVG dividers with animated gradients between sections
- CSS Grid for responsive card layouts
- Tailwind CSS for utility-based styling with custom theme colors
