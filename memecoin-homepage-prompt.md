# Next.js Memecoin Homepage Generation Prompt

## Project Overview
Create a modern, engaging Next.js homepage for a memecoin website that captures the fun, viral nature of memecoins while maintaining professional credibility. The site should be mobile-responsive, fast-loading, and optimized for conversion.

## Technical Requirements
- **Framework**: Next.js 14+ with App Router
- **Styling**: Tailwind CSS with custom animations
- **Icons**: Lucide React or Heroicons
- **Fonts**: Modern web fonts (Inter, Poppins, or similar)
- **Deployment**: Vercel-ready configuration

## Design Requirements

### Visual Style
- **Color Scheme**: Vibrant, meme-inspired colors with dark/light mode support
- **Typography**: Bold, attention-grabbing headlines with clean body text
- **Animations**: Smooth hover effects, loading animations, and micro-interactions
- **Layout**: Hero section, features, tokenomics, roadmap, community links

### Key Sections

#### 1. Hero Section
- Large, bold headline with the coin name and tagline
- Animated background (gradient or particle effect)
- Call-to-action buttons (Buy Now, Join Community, View Chart)
- Live price ticker or market cap display
- Meme-inspired visual elements

#### 2. About Section
- Brief, engaging description of the memecoin
- Key features and benefits
- Meme culture integration
- Community-driven narrative

#### 3. Tokenomics
- Visual representation of token distribution
- Key metrics (total supply, burn mechanism, etc.)
- Animated charts or progress bars

#### 4. Roadmap
- Timeline of past and future milestones
- Interactive timeline component
- Achievement badges or progress indicators

#### 5. Community & Social
- Social media links with hover effects
- Discord/Telegram integration
- Community stats (holders, social followers)
- Newsletter signup

#### 6. Footer
- Links to whitepaper, audit reports
- Legal disclaimers
- Additional resources

## Interactive Features
- **Price Ticker**: Real-time or simulated price updates
- **Countdown Timer**: For upcoming events or launches
- **Social Proof**: Live holder count or transaction feed
- **Mobile Menu**: Hamburger menu with smooth animations
- **Loading States**: Skeleton screens and loading spinners

## Performance Requirements
- **Lighthouse Score**: 90+ for all metrics
- **Image Optimization**: Next.js Image component with proper sizing
- **Font Loading**: Optimized font loading strategy
- **Bundle Size**: Minimal JavaScript bundle
- **SEO**: Proper meta tags, structured data, and Open Graph

## Content Guidelines
- **Tone**: Fun, engaging, but not overly childish
- **Language**: Accessible to both crypto veterans and newcomers
- **Call-to-Actions**: Clear, prominent, and action-oriented
- **Trust Signals**: Security badges, audit reports, team info

## Accessibility
- WCAG 2.1 AA compliance
- Keyboard navigation support
- Screen reader compatibility
- High contrast mode support
- Focus indicators

## SEO & Marketing
- Meta tags for social sharing
- Structured data for rich snippets
- Analytics integration (Google Analytics, etc.)
- Social media preview cards
- Open Graph and Twitter Card meta tags

## File Structure
```
src/
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── globals.css
├── components/
│   ├── ui/
│   ├── sections/
│   └── layout/
├── lib/
│   ├── utils.ts
│   └── constants.ts
└── public/
    ├── images/
    └── icons/
```

## Additional Considerations
- **Dark/Light Mode**: Toggle with system preference detection
- **Internationalization**: Ready for multiple languages
- **Analytics**: Conversion tracking and user behavior
- **Security**: CSP headers, security best practices
- **Testing**: Component testing setup

## Success Metrics
- Fast loading times (<3 seconds)
- High engagement (time on page, scroll depth)
- Mobile-friendly design
- Clear conversion paths
- Professional appearance that builds trust

Generate a complete Next.js homepage that meets these requirements, with clean, maintainable code and modern development practices. 