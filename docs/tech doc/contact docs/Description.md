# MaxAre --- UI/UX & Frontend Design System Description

## Overview

MaxAre is a modern digital platform for creating and sharing digital
invitations, destination events, celebration details, and personal
memory galleries.

The visual identity should feel **masculine, elegant, warm, premium,
modern, and travel-oriented**. The interface combines the sophistication
of a luxury travel journal with the emotional character of a beautifully
designed invitation.

The core visual principle is:

> **Elegant memories, designed with purpose.**

The design should avoid an overly romantic or feminine appearance.
Instead, it should use deep navy, warm terracotta, sand, sage, teal, and
muted gold to create a confident and sophisticated identity.

------------------------------------------------------------------------

## 1. Brand Color Palette

### Primary Brand Colors

-   **Deep Ocean --- `#1E2A38`**
    -   Main brand color.
    -   Use for primary buttons, navigation, footer, headings, active
        states, major UI elements, and strong visual sections.
-   **Warm Terracotta --- `#B45E4A`**
    -   Main emotional accent.
    -   Use for secondary buttons, event accents, hover states,
        invitation details, decorative elements, and warm highlights.
-   **Sage Green --- `#6E6D62`**
    -   Natural and organic supporting color.
    -   Use for travel categories, destination labels, nature-related
        elements, and subtle accents.
-   **Sand Beige --- `#DCC9B3`**
    -   Warm neutral accent.
    -   Use for invitation surfaces, secondary cards, decorative areas,
        and soft UI backgrounds.
-   **Slate Blue --- `#3F4C5A`**
    -   Supporting dark tone.
    -   Use for secondary dark areas, metadata, supporting text, and
        travel-oriented components.

### Accent Colors

-   **Muted Gold --- `#C9A66B`**
    -   Use sparingly for premium details, special badges, wedding
        accents, thin decorative lines, and small highlights.
-   **Deep Teal --- `#2F6A6D`**
    -   Use for travel, destination, and nature categories.
-   **Burnt Orange --- `#D47A4A`**
    -   Use for warm event highlights and special category accents.
-   **Lavender Gray --- `#7E8491`**
    -   Use for secondary metadata, disabled elements, and neutral
        supporting UI.

### Neutral Colors

-   **Warm Ivory --- `#F7F4F0`**
    -   Main page background.
-   **Light Gray --- `#E8E5E1`**
    -   Borders, dividers, secondary surfaces, and input backgrounds.
-   **Medium Gray --- `#B0B3B8`**
    -   Placeholder text and disabled UI.
-   **Dark Gray --- `#40464D`**
    -   Secondary text and descriptions.
-   **Charcoal --- `#1A1D21`**
    -   Main text and high-contrast headings.

### Semantic Colors

-   Success: `#4CAF7D`
-   Warning: `#E0A800`
-   Error: `#D9534F`
-   Info: `#3484E6`

Semantic colors must remain separate from the main brand palette.

------------------------------------------------------------------------

## 2. Typography

### Heading Font

Use **Playfair Display** for:

-   Hero headings
-   Event titles
-   Destination names
-   Invitation titles
-   Major section headings
-   Editorial brand moments

Recommended weights:

-   400 Regular
-   500 Medium
-   600 Semi-Bold
-   700 Bold

Playfair Display provides a sophisticated editorial appearance without
making the interface feel overly romantic.

### Body Font

Use **Inter** for:

-   Navigation
-   Buttons
-   Forms
-   Descriptions
-   Metadata
-   Filters
-   Dashboard interfaces
-   Labels
-   Utility text

Recommended weights:

-   400 Regular
-   500 Medium
-   600 Semi-Bold
-   700 Bold

### Type Scale

-   Hero Title: 56--64px desktop / 38--44px mobile
-   Page Title: 40px desktop / 32px mobile
-   Section Heading: 28px desktop / 24--28px mobile
-   Card Title: 20--24px desktop / 18--20px mobile
-   Body Large: 18px
-   Body: 16px
-   Small: 14px
-   Caption: 12px

Headings should use approximately 1.1--1.3 line-height. Body text should
use approximately 1.5--1.7 line-height.

------------------------------------------------------------------------

## 3. Layout System

Use a responsive **12-column grid** on desktop.

### Desktop

-   Maximum content width: 1200--1280px
-   Horizontal padding: 32--48px
-   12-column grid
-   24px column gap

### Tablet

-   Horizontal padding: 24px
-   6--8 column grid
-   20px gap

### Mobile

-   Horizontal padding: 16--20px
-   4-column grid
-   12--16px gap

The layout should feel spacious and breathable. Avoid excessive content
density.

------------------------------------------------------------------------

## 4. Spacing System

Use an 8px spacing system:

-   4px --- micro spacing
-   8px --- icon/text spacing
-   12px --- compact spacing
-   16px --- standard spacing
-   24px --- component spacing
-   32px --- section spacing
-   40px --- medium section spacing
-   48px --- large section spacing
-   64px --- major section spacing
-   80px --- hero spacing
-   96px --- large visual separation

Prioritize whitespace and hierarchy over fitting more content into a
small area.

------------------------------------------------------------------------

## 5. Cards

MaxAre cards should look like **premium editorial content blocks**, not
generic SaaS cards.

### General Card Style

-   Background: `#FFFFFF`
-   Border: `1px solid #E8E5E1`
-   Border radius: `20px`
-   Padding: `20–24px`
-   Shadow: `0 12px 30px rgba(0,0,0,0.08)`

Cards should use high-quality photography and clear information
hierarchy.

### Destination/Event Card

Typical content:

1.  Large destination/event photograph
2.  Category badge
3.  Event or destination title
4.  Location
5.  Date
6.  Description
7.  Guest count
8.  Primary action

The card should feel similar to a premium travel magazine feature.

### Invitation Preview Card

The invitation card should resemble a physical premium printed
invitation.

Use:

-   Warm Ivory background
-   Deep Ocean typography
-   Sand Beige details
-   Terracotta accents
-   Minimal Muted Gold
-   Elegant botanical line art
-   QR code where appropriate

The overall result should be sophisticated and neutral rather than
overly romantic.

### Memory Gallery Card

Photography should dominate the component.

Use:

-   Large image
-   Subtle dark gradient at the bottom
-   White title
-   Date and photo count
-   Minimal action icon

Example:

`Our Santorini Memories` `May 2025 • 42 Photos`

------------------------------------------------------------------------

## 6. Card Interaction

Desktop cards should have subtle hover interactions.

Default:

-   `transform: translateY(0)`
-   Soft shadow

Hover:

-   `transform: translateY(-4px)`
-   Stronger shadow
-   Image scale around `1.03`

Use a `250–300ms ease` transition.

Animations should feel refined and premium, never playful or aggressive.

------------------------------------------------------------------------

## 7. Buttons

### Primary Button

-   Background: `#1E2A38`
-   Text: `#FFFFFF`
-   Border radius: `10–12px`
-   Padding: `12px 20px`
-   Font weight: 600

Example:

**Create Invitation →**

The primary CTA should always be the strongest action on the page.

### Secondary Button

-   Background: `#B45E4A`
-   Text: `#FFFFFF`
-   Border radius: `10–12px`

Use for:

-   View Details
-   Explore
-   Save
-   Secondary event actions

### Outline Button

-   Transparent background
-   `1px solid #1E2A38`
-   Text: `#1E2A38`
-   Radius: `10–12px`

Example:

**Learn More →**

### Ghost Button

Use for low-priority actions:

-   Transparent background
-   No border
-   Deep Ocean text

------------------------------------------------------------------------

## 8. Navigation

Desktop navigation should be minimal:

**MaxAre \| Discover \| Events \| Memories \| About \| Create
Invitation**

Recommended:

-   Height: 72--80px
-   Background: `#F7F4F0`
-   Logo: Deep Ocean
-   Primary CTA: Deep Ocean
-   Secondary accent: Terracotta

The navigation should feel lightweight and premium.

On mobile, use a clean menu button and a simple responsive navigation
panel.

------------------------------------------------------------------------

## 9. Hero Section

The hero should feel cinematic and premium.

### Background

Use `#F7F4F0`.

### Left Side

Include:

-   Small eyebrow text
-   Large Playfair Display heading
-   Supporting Inter paragraph
-   Deep Ocean primary CTA
-   Terracotta secondary CTA

### Right Side

Show:

-   Large destination photograph
-   Invitation preview
-   Memory card
-   Subtle botanical or geometric decoration

The hero should communicate travel, celebration, and memory without
looking overly romantic.

------------------------------------------------------------------------

## 10. Decorative Language

Use restrained decorative elements:

-   Minimal botanical line art
-   Thin gold rules
-   Travel-inspired line icons
-   Subtle geometric shapes
-   Paper-inspired surfaces
-   Minimal floral details

Avoid:

-   Excessive pink
-   Neon colors
-   Heavy gradients
-   Excessive glassmorphism
-   Cartoon graphics
-   Overly glossy UI
-   Heavy shadows

------------------------------------------------------------------------

## 11. Photography Direction

Photography is a major emotional component of MaxAre.

Recommended imagery:

-   Natural lighting
-   Cinematic travel photography
-   Mediterranean and European destinations
-   Architecture
-   Landscapes
-   Destination weddings
-   Authentic people
-   Warm sunlight
-   Muted earth tones

Photography should feel realistic, premium, editorial, and authentic.

------------------------------------------------------------------------

## 12. Forms

Inputs should be clean and premium.

Recommended:

-   Height: 48--52px
-   Radius: 10--12px
-   Background: `#FFFFFF`
-   Border: `#E8E5E1`
-   Horizontal padding: 16px

Placeholder color:

`#7E8491`

Focus state:

-   Border: `#1E2A38`
-   Soft navy focus ring

Forms should remain minimal and easy to scan.

------------------------------------------------------------------------

## 13. Badges

Use pill-shaped badges:

-   Radius: `999px`
-   Padding: `6px 10px`
-   Font: Inter
-   Size: 12--13px
-   Weight: 600

Suggested semantic category colors:

-   Wedding → Terracotta
-   Birthday → Sand Beige
-   Travel → Deep Teal
-   Anniversary → Sage
-   Featured → Muted Gold

------------------------------------------------------------------------

## 14. Iconography

Use clean line-style icons with rounded geometry.

Core icons:

-   Heart
-   Calendar
-   Location
-   Gift
-   Camera
-   Users
-   Send
-   Share
-   Envelope
-   Bell

Default icon color:

`#1E2A38`

Icons should be minimal, consistent, and medium-weight.

------------------------------------------------------------------------

## 15. Border Radius

Use a clear radius hierarchy:

-   Small controls: 8px
-   Inputs: 10--12px
-   Buttons: 10--12px
-   Cards: 20px
-   Large cards: 28px
-   Modals: 20px
-   Pills: 999px

Avoid extremely rounded, bubble-like interfaces.

------------------------------------------------------------------------

## 16. Shadow System

### Soft Shadow

`0 8px 24px rgba(0,0,0,0.06)`

### Card Shadow

`0 12px 30px rgba(0,0,0,0.08)`

### Hover Shadow

`0 20px 40px rgba(0,0,0,0.12)`

Shadows should be subtle, diffused, and modern.

------------------------------------------------------------------------

## 17. Responsive Design

### Mobile

Prioritize:

1.  Main content
2.  Image
3.  Title
4.  Essential metadata
5.  Primary CTA

Cards should generally become single-column.

### Tablet

Use two-column layouts where appropriate.

### Desktop

Use three-to-four-column card grids, wide hero compositions, and
multi-column sections.

Never make cards excessively narrow just to preserve a grid.

------------------------------------------------------------------------

## 18. Accessibility

MaxAre should be accessible by default.

Requirements:

-   Semantic HTML
-   Keyboard navigation
-   Visible focus states
-   Minimum 44px touch targets
-   Descriptive image alt text
-   Sufficient color contrast
-   Never rely on color alone to communicate information
-   Support `prefers-reduced-motion`

------------------------------------------------------------------------

## 19. Motion

Motion should be subtle and purposeful.

Recommended durations:

-   Small interactions: 200ms
-   Hover: 250--300ms
-   Modals and larger transitions: 300--500ms

Use:

-   Subtle card lift
-   Image zoom
-   Fade
-   Slide-up
-   Underline transitions

Avoid bouncing, flashing, aggressive scaling, and constant motion.

------------------------------------------------------------------------

## 20. Overall Visual Hierarchy

The visual hierarchy should follow this order:

### 1. Deep Ocean

Creates confidence, masculinity, stability, and brand recognition.

### 2. Photography

Creates emotion and communicates destination/event context.

### 3. Terracotta

Adds warmth and personality.

### 4. Warm Ivory / Sand

Creates breathing room and premium editorial atmosphere.

### 5. Gold

Adds restrained premium detail.

------------------------------------------------------------------------

## 21. Core Visual Formula

**Deep Ocean + Warm Ivory + Terracotta + Sand Beige + Sage + Deep Teal +
Muted Gold**

The result should communicate:

**Masculine + Elegant + Warm + Premium + Travel + Celebration**

The interface must be neutral enough for everyday use while remaining
sophisticated enough for weddings, anniversaries, birthdays, destination
events, and special celebrations.

------------------------------------------------------------------------

## 22. UI Generation Prompt

When generating UI mockups or visual concepts for MaxAre, use this
description:

> A sophisticated masculine-modern digital platform called MaxAre for
> digital invitations, destination events, celebrations, and memory
> galleries. Use a warm ivory background (#F7F4F0), deep ocean navy
> (#1E2A38) as the dominant brand color, warm terracotta (#B45E4A) as
> the emotional accent, sand beige (#DCC9B3), sage green (#6E6D62),
> slate blue (#3F4C5A), muted gold (#C9A66B), deep teal (#2F6A6D), burnt
> orange (#D47A4A), and lavender gray (#7E8491). Use Playfair Display
> for elegant editorial headings and Inter for clean interface text.
> Cards should have 20px rounded corners, subtle borders, soft shadows,
> premium travel photography, invitation previews, destination cards,
> and memory gallery cards. Buttons should be compact, confident, and
> minimal, with Deep Ocean primary CTAs and Terracotta secondary
> actions. The interface should combine the sophistication of a luxury
> travel journal with the functionality of a modern invitation platform.
> Avoid excessive pink, overly romantic styling, neon colors, heavy
> gradients, glassmorphism, and cartoon-like UI. The final appearance
> should feel masculine, premium, warm, cinematic, editorial, modern,
> and trustworthy.

------------------------------------------------------------------------

## 23. Final Brand Principle

**MaxAre --- Memories worth sharing, beautifully designed.**

MaxAre should combine masculine confidence with human warmth.

Deep Ocean provides stability and premium character.\
Terracotta provides warmth and emotion.\
Sand Beige and Warm Ivory provide space and elegance.\
Sage and Teal connect the brand with nature and travel.\
Muted Gold provides restrained premium detailing.

The final product should feel like a **modern digital space where people
create, share, and preserve meaningful memories**.
