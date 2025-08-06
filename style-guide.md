# $KYLIE Style Guide - Updated

## Brand Overview
**$KYLIE** - The College Dog Memecoin on Solana
A heartwarming memecoin inspired by a real Shiba Inu who goes to college with her owner.

## Color Palette

### Primary Colors
- **Primary Orange**: `#FF6B35` (Main brand color)
- **Secondary Orange**: `#F7931E` (Gradient companion)
- **Dark Brown**: `#140d07` (Hero background)
- **Medium Brown**: `#2a1f15` (Gradient middle)
- **Cream/White**: `#FEFEFE` (Text on dark backgrounds)

### Background Gradients
- **Hero Background**: `linear-gradient(135deg, #140d07 0%, #2a1f15 50%, #140d07 100%)`
- **Footer Background**: `linear-gradient(135deg, #FF6B35 0%, #F7931E 100%)`
- **Button Gradient**: `linear-gradient(135deg, #FF6B35 0%, #F7931E 100%)`

### Text Colors
- **Primary Text**: `#140d07` (Dark brown for light backgrounds)
- **Light Text**: `#FEFEFE` (Cream for dark backgrounds)
- **Secondary Text**: `rgba(255, 255, 255, 0.8)` (Semi-transparent white)

## Typography

### Font Family
- **Primary**: 'Inter', sans-serif
- **Fallback**: system fonts

### Font Weights
- **Regular**: 400
- **Semi-Bold**: 600
- **Bold**: 700

### Font Sizes
- **Hero Title**: 3.5rem (The College Dog)
- **Section Titles**: 2.5rem
- **Subheadings**: 1.3rem
- **Body Text**: 1.1rem
- **Footer Text**: 1.1rem
- **Social Icons**: 1.8rem

## Layout & Spacing

### Container
- **Max Width**: 1200px
- **Padding**: 0 2rem
- **Section Padding**: 5rem 0

### Grid System
- **Hero Section**: 2-column grid (1fr 1fr)
- **Story Section**: 2-column grid
- **How to Buy**: Responsive grid (auto-fit, minmax(250px, 1fr))
- **Roadmap**: Single column with timeline

### Spacing
- **Gap Between Columns**: 4rem
- **Margin Bottom**: 1rem, 1.5rem, 2rem, 3rem
- **Padding**: 0.5rem, 1rem, 2rem, 2.5rem

## Components

### Navigation
- **Background**: Transparent
- **Logo**: $KYLIE in bold, fixed positioning
- **Logo Position**: Fixed at top-left (top: 2rem, left: 2rem)
- **Mobile Menu**: Hamburger icon
- **Height**: Minimal, clean design

### Hero Section
- **Background**: Dark brown gradient
- **Layout**: 2-column grid
- **Title**: "The College Dog" (3.5rem, bold)
- **Social Icons**: Fixed at top-right corner (top: 2rem, right: 2rem)
- **Button**: Orange gradient with pulse animation

### Story Section
- **Background**: White
- **Layout**: 2-column grid
- **Title Color**: Dark brown (#140d07)
- **Image**: No border or shadow, clean display

### Roadmap Section
- **Background**: White
- **Timeline**: Vertical line with brown color (#140d07)
- **Phase Boxes**: White background with soft shadow
- **Kylie Images**: Floating animation with 1.98 scale
- **Animation**: 3s ease-in-out float animation

### How to Buy Section
- **Background**: Dark brown gradient (same as hero)
- **Cards**: Glass morphism effect with backdrop blur
- **Step Numbers**: Orange gradient circles (70px)
- **Hover Effects**: Scale, lift, and shimmer animations
- **Steps**: 1) Create Wallet, 2) Get SOL, 3) Swap for $KYLIE, 4) Community
- **Final Step**: "Connect with fellow degens on X and telegram"

### Footer
- **Background**: Orange gradient
- **Layout**: Centered text only
- **Text**: "Wen moon? Wen treats? 🚀🐕"
- **Height**: Minimal (0.75rem padding)

## Interactive Elements

### Buttons
- **Primary**: Orange gradient, rounded corners (50px)
- **Hover**: Lift animation (-2px), enhanced shadow
- **Pulse Animation**: For call-to-action buttons

### Social Icons
- **Size**: 1.8rem (desktop), 1.5rem (mobile)
- **Color**: White (#FEFEFE)
- **Hover**: Opacity change and lift animation
- **Positioning**: Fixed positioning at top-right corner
- **Icons**: X (𝕏) and Telegram (Font Awesome icon)
- **Gap**: 1.5rem (desktop), 1rem (mobile)

### Cards & Hover Effects
- **How to Buy Cards**: Scale (1.02), lift (-8px), enhanced shadow
- **Roadmap Cards**: Lift (-5px), shadow enhancement
- **Shimmer Effect**: Gradient overlay animation

## Animations

### Keyframe Animations
- **Float**: Gentle up-down movement for Kylie images
- **FadeInUp**: Entry animation for content
- **Pulse**: Call-to-action button animation
- **Shimmer**: Card hover effect

### Transition Timing
- **Standard**: 0.3s ease
- **Smooth**: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275)
- **Float**: 3s ease-in-out

## Responsive Design

### Breakpoints
- **Mobile**: max-width: 768px
- **Tablet**: max-width: 1024px
- **Desktop**: 1200px+

### Mobile Adaptations
- **Hero**: Single column layout
- **Story**: Single column layout
- **Timeline**: Left-aligned with padding
- **Navigation**: Hidden links, mobile menu button
- **Logo**: Smaller size (1.5rem), positioned at top-left (1rem, 1rem)
- **Social Icons**: Smaller size (1.5rem), positioned at top-right (1rem, 1rem)

## Content Guidelines

### Tone & Voice
- **Playful**: Use degen community language
- **Memey**: Include emojis and crypto slang
- **Authentic**: College-themed with genuine community spirit
- **Fun**: Lighthearted and engaging

### Key Phrases
- "Wen moon? Wen treats? 🚀🐕"
- "The College Dog"
- "The Original Campus Degen"
- "Freshman Frenzy", "Sophomore Slump", "Junior Jitters", "Senior Send-Off"

### Emojis & Icons
- **Social**: 𝕏 (X/Twitter), Telegram icon
- **Theme**: 🚀🐕 (rocket and dog)
- **Navigation**: Hamburger menu icon

## File Structure

### Images
- `assets/CLAY-KYLIE.png` - Hero image
- `assets/travle-kylie.png` - Story image
- `assets/kylie-head.png` - Roadmap Phase 1
- `assets/kylie-wink.png` - Roadmap Phase 2
- `assets/kylie-thumbs-up.png` - Roadmap Phase 3

### CSS Organization
- **Variables**: CSS custom properties for colors
- **Components**: Modular CSS for each section
- **Animations**: Keyframe definitions
- **Responsive**: Media queries for mobile

## Accessibility

### Color Contrast
- **Dark text on light backgrounds**: High contrast
- **Light text on dark backgrounds**: High contrast
- **Orange buttons**: Sufficient contrast for readability

### Focus States
- **Links**: Visible focus indicators
- **Buttons**: Enhanced focus states
- **Interactive elements**: Clear hover and focus states

## Recent Updates (Latest Session)

### Fixed Positioning Elements
- **Logo**: Changed to fixed positioning (top-left corner)
- **Social Icons**: Changed to fixed positioning (top-right corner)
- **Responsive Spacing**: Added responsive breakpoints for better display consistency

### Content Updates
- **Hero Title**: Simplified to "The College Dog" (removed "Kylie")
- **How to Buy Step 4**: Updated to "Community - Connect with fellow degens on X and telegram"
- **Image Fixes**: Fixed case sensitivity issues (CLAY-KYLIE.png → clay-kylie.png)

### Layout Improvements
- **Symmetrical Positioning**: Logo on left mirrors social icons on right
- **Consistent Spacing**: Both elements use same positioning values across breakpoints
- **Mobile Optimization**: Responsive adjustments for tablet and mobile devices

---

*This style guide reflects the current state of the $KYLIE website as of the latest updates, including fixed positioning elements, responsive improvements, and content refinements.* 