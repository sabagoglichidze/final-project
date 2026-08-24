# MaxAre — UI/UX & Frontend Design System Specification

## 1. Design Direction

**Brand:** MaxAre
**Platform:** Digital invitations, destination events, celebration details, and memory galleries for tourists and event organizers.

MaxAre-ის ვიზუალური იდენტობა უნდა იყოს **უფრო მამაკაცური, დახვეწილი, თბილი და პრემიუმ**, ვიდრე წინა ვერსია. დიზაინი აღარ უნდა ეყრდნობოდეს ძირითადად ვარდისფერ/ბლუშ ფერებს. მთავარი ვიზუალური საყრდენი ხდება **Deep Ocean Navy**, რომელსაც აბალანსებს **Warm Terracotta, Sage Green, Sand Beige და Muted Gold**.

საერთო შეგრძნება:

* მამაკაცური და თავდაჯერებული
* პრემიუმ და თანამედროვე
* თბილი, მაგრამ არა ზედმეტად რომანტიკული
* სამოგზაურო და თავგადასავლების შთაგონებით
* ელეგანტური და editorial
* მარტივი და ფუნქციური
* საკმარისად ნეიტრალური, რომ მოერგოს როგორც ქორწილს, ისე მოგზაურობას, დაბადების დღეს, იუბილესა და სხვა ღონისძიებებს

მთავარი პრინციპია:

> **“Elegant memories, designed with purpose.”**

MaxAre უნდა გამოიყურებოდეს როგორც **premium travel journal + modern invitation platform + memory gallery**, და არა როგორც ჩვეულებრივი event-management dashboard.

---

# 2. Color Palette

ფერების სისტემა უნდა იყოს მიწიერი, ბუნებრივი და უფრო მამაკაცური. ძირითადი ფერი არის ღრმა ლურჯი/ნავური ტონი, ხოლო თბილი ტერაკოტა და ქვიშისფერი ქმნის MaxAre-ს ემოციურ მხარეს.

## 2.1 Primary Colors

### Deep Ocean — Primary Brand

**HEX:** `#1E2A38`
**RGB:** `30, 42, 56`

ეს არის MaxAre-ის მთავარი ბრენდული ფერი.

გამოიყენება:

* Primary buttons
* Header/navigation
* Footer
* მთავარი CTA
* აქტიური navigation state
* მნიშვნელოვანი UI ელემენტები
* ტექსტის ძლიერი აქცენტები
* dark sections

ეს ფერი უნდა იყოს MaxAre-ის მთავარი ვიზუალური იდენტიფიკატორი.

---

### Warm Terracotta

**HEX:** `#B45E4A`
**RGB:** `180, 94, 74`

გამოიყენება:

* Secondary CTA
* Hover states
* Event accents
* Invitation details
* ხაზები და decorative elements
* მნიშვნელოვანი სტატუსები
* ფოტოების თბილი overlay-ები

Terracotta არის MaxAre-ის ემოციური ფერი და Deep Ocean-ს აბალანსებს.

---

### Sage Green

**HEX:** `#6E6D62`
**RGB:** `110, 109, 98`

გამოიყენება:

* Nature/travel categories
* Secondary UI
* Destination tags
* subtle decorative elements
* organic visual accents

---

### Sand Beige

**HEX:** `#DCC9B3`
**RGB:** `220, 201, 179`

გამოიყენება:

* Card accents
* Invitation backgrounds
* Secondary surfaces
* decorative sections
* warm UI states

---

### Slate Blue

**HEX:** `#3F4C5A`
**RGB:** `63, 76, 90`

გამოიყენება:

* Secondary dark sections
* Supporting UI
* Metadata
* Alternative buttons
* Travel-oriented components

---

# 3. Accent Colors

### Muted Gold

**HEX:** `#C9A66B`
**RGB:** `201, 166, 107`

გამოიყენება ძალიან შეზღუდულად:

* Premium badge
* Decorative line
* Wedding/event accents
* Icons
* Small highlights
* Active special states

Gold არ უნდა გახდეს მთავარი ფერი.

---

### Deep Teal

**HEX:** `#2F6A6D`
**RGB:** `47, 106, 109`

გამოიყენება:

* Travel
* Nature
* Destination categories
* Secondary accents

---

### Burnt Orange

**HEX:** `#D47A4A`
**RGB:** `212, 122, 74`

გამოიყენება:

* Warm event accents
* Travel highlights
* Attention states
* Special category tags

---

### Lavender Gray

**HEX:** `#7E8491`
**RGB:** `126, 132, 145`

გამოიყენება:

* Secondary metadata
* Disabled states
* Supporting UI
* Neutral decorative accents

---

# 4. Neutral Color System

### Warm Ivory

**HEX:** `#F7F4F0`

მთავარი გვერდის background.

ეს არის MaxAre-ის ძირითადი canvas — თბილი, სუფთა და ნაკლებად მკაცრი, ვიდრე pure white.

---

### Light Gray

**HEX:** `#E8E5E1`

გამოიყენება:

* Secondary background
* Dividers
* Input backgrounds
* subtle cards

---

### Medium Gray

**HEX:** `#B0B3B8`

გამოიყენება:

* Placeholder
* Disabled controls
* secondary metadata

---

### Dark Gray

**HEX:** `#40464D`

გამოიყენება:

* Secondary text
* descriptions
* metadata

---

### Charcoal

**HEX:** `#1A1D21`

გამოიყენება:

* Strongest text
* headings
* high-contrast sections

---

# 5. Recommended CSS Color Tokens

```css
:root {
  /* Brand */
  --color-primary: #1E2A38;
  --color-primary-light: #3F4C5A;

  /* Warm accents */
  --color-terracotta: #B45E4A;
  --color-sand: #DCC9B3;
  --color-gold: #C9A66B;

  /* Nature / travel */
  --color-sage: #6E6D62;
  --color-teal: #2F6A6D;
  --color-orange: #D47A4A;

  /* Supporting */
  --color-lavender-gray: #7E8491;

  /* Neutrals */
  --color-background: #F7F4F0;
  --color-surface: #FFFFFF;
  --color-surface-soft: #E8E5E1;

  --color-text: #1A1D21;
  --color-text-secondary: #40464D;
  --color-text-muted: #B0B3B8;

  /* System */
  --color-success: #4CAF7D;
  --color-warning: #E0A800;
  --color-error: #D9534F;
  --color-info: #3484E6;

  /* Radius */
  --radius-sm: 8px;
  --radius-md: 12px;
  --radius-lg: 20px;
  --radius-xl: 28px;
  --radius-pill: 999px;

  /* Shadows */
  --shadow-soft: 0 8px 24px rgba(0, 0, 0, 0.06);
  --shadow-card: 0 12px 30px rgba(0, 0, 0, 0.08);
  --shadow-hover: 0 20px 40px rgba(0, 0, 0, 0.12);
}
```

---

# 6. Typography

MaxAre-ის typography უნდა აერთიანებდეს **კლასიკურ editorial serif-ს** და **თანამედროვე sans-serif-ს**.

## 6.1 Heading Font

### Playfair Display

გამოიყენება:

* Hero headings
* Event titles
* Destination names
* Invitation titles
* Major section headings
* Brand/editorial moments

რეკომენდებული weights:

* Regular `400`
* Medium `500`
* Semi-Bold `600`
* Bold `700`

Playfair Display ქმნის პრემიუმ და დახვეწილ ხასიათს, თუმცა Deep Ocean ფერთან ერთად აღარ გამოიყურება ზედმეტად რომანტიკულად.

---

## 6.2 Body Font

### Inter

გამოიყენება:

* Navigation
* Buttons
* Forms
* Metadata
* Descriptions
* Dashboard
* Filters
* Labels
* Utility text

რეკომენდებული weights:

* `400`
* `500`
* `600`
* `700`

---

# 7. Typography Scale

| Element         | Desktop |  Mobile | Weight |
| --------------- | ------: | ------: | -----: |
| Hero Title      | 56–64px | 38–44px |    600 |
| Page Title      |    40px |    32px |    600 |
| Section Heading |    28px | 24–28px |    600 |
| Card Title      | 20–24px | 18–20px |    600 |
| Body Large      |    18px |    17px |    400 |
| Body            |    16px | 15–16px |    400 |
| Small           |    14px |    14px |    400 |
| Caption         |    12px |    12px |    500 |

Heading line-height უნდა იყოს დაახლოებით `1.1–1.3`, ხოლო body text-ისთვის `1.5–1.7`.

---

# 8. Layout System

MaxAre იყენებს **12-column responsive grid-ს**.

## Desktop

* Max width: `1200–1280px`
* Horizontal padding: `32–48px`
* Grid: 12 columns
* Column gap: `24px`

## Tablet

* Horizontal padding: `24px`
* Grid: 6–8 columns
* Gap: `20px`

## Mobile

* Horizontal padding: `16–20px`
* Grid: 4 columns
* Gap: `12–16px`

Layout უნდა იყოს spacious და breathable.

---

# 9. Spacing System

საბაზისო სისტემა არის **8px spacing scale**.

```text
4px    Micro
8px    Icon/text
12px   Compact
16px   Standard
24px   Component
32px   Section
40px   Medium section
48px   Large section
64px   Major section
80px   Hero spacing
96px   Large visual separation
```

მთავარი პრინციპი:

**Content density უნდა იყოს დაბალი, ხოლო visual hierarchy — მკაფიო.**

---

# 10. Card Design

MaxAre-ის cards უნდა გამოიყურებოდეს უფრო როგორც **premium editorial content blocks**, ვიდრე ჩვეულებრივი SaaS cards.

## Card Structure

Destination/Event Card შეიძლება შეიცავდეს:

1. Large photograph
2. Category badge
3. Title
4. Location
5. Date
6. Description
7. Guest count
8. CTA

---

## Card Styling

```text
Background: #FFFFFF
Radius: 20px
Border: 1px solid #E8E5E1
Shadow: 0 12px 30px rgba(0,0,0,0.08)
Padding: 20–24px
```

ფოტო უნდა იყოს მთავარი ვიზუალური ელემენტი.

---

# 11. Destination Card

Destination card უნდა ასახავდეს MaxAre-ის travel-oriented მხარეს.

მაგალითად:

**Santorini Getaway**

* Destination image
* Location
* Date
* Guest count
* Short description
* View Details CTA

Badge შეიძლება იყოს:

`DESTINATION`

Badge-ის ფერი:

`#2F6A6D`

---

# 12. Invitation Preview Card

Invitation card უნდა გამოიყურებოდეს როგორც რეალური premium printed invitation.

გამოიყენოს:

* Warm Ivory background
* Sand Beige
* Deep Ocean typography
* subtle Terracotta
* ძალიან მცირე Gold accents
* elegant floral/botanical line art
* QR code

Invitation card-ის მთავარი ფერი უნდა იყოს **Warm Ivory**, ხოლო typography — **Deep Ocean**.

ეს ქმნის მამაკაცურ და თანამედროვე wedding/event aesthetic-ს.

---

# 13. Memory Gallery Card

Memory card-ისთვის ფოტო უნდა იკავებდეს თითქმის მთელ card-ს.

რეკომენდებული სტრუქტურა:

```text
┌─────────────────────────┐
│                         │
│        PHOTO            │
│                         │
│                         │
│  Our Santorini Memories │
│  May 2025 • 42 Photos   │
└─────────────────────────┘
```

ფოტოს ქვედა ნაწილში შეიძლება იყოს subtle dark gradient.

Text:

`#FFFFFF`

Overlay:

Deep Ocean / Charcoal translucent gradient.

---

# 14. Card Hover

Desktop-ზე:

```text
transform: translateY(-4px);
box-shadow: 0 20px 40px rgba(0,0,0,0.12);
```

Image:

```text
transform: scale(1.03);
```

Transition:

`250–300ms ease`

ინტერაქცია უნდა იყოს subtle.

---

# 15. Buttons

## Primary Button

```text
Background: #1E2A38
Text: #FFFFFF
Radius: 10–12px
Padding: 12px 20px
Weight: 600
```

მაგალითი:

**Create Invitation →**

Primary CTA ყოველთვის უნდა იყოს ყველაზე ძლიერი მოქმედება.

---

## Secondary Button

```text
Background: #B45E4A
Text: #FFFFFF
Radius: 10–12px
```

გამოიყენება:

* View Details
* Save
* Explore
* Secondary event actions

---

## Outline Button

```text
Background: transparent
Border: 1px solid #1E2A38
Color: #1E2A38
Radius: 10–12px
```

მაგალითად:

**Learn More →**

---

## Ghost Button

გამოიყენება დაბალი პრიორიტეტის მოქმედებებისთვის.

```text
Background: transparent
Border: none
Color: #1E2A38
```

---

# 16. Button States

### Default

Deep Ocean / Terracotta.

### Hover

* Slightly darker background
* `translateY(-1px)`
* Soft shadow

### Active

უფრო მუქი და კონტრასტული ფერი.

### Disabled

გამოიყენოს:

`#B0B3B8`

Opacity არ უნდა იყოს იმდენად დაბალი, რომ ტექსტი გაურკვეველი გახდეს.

---

# 17. Badges

Badge-ები უნდა იყოს pill-shaped.

```text
Radius: 999px
Padding: 6px 10px
Font: Inter
Size: 12–13px
Weight: 600
```

მაგალითები:

* Wedding
* Birthday
* Travel
* Anniversary
* Featured
* Destination

ფერების გამოყენება:

```text
Wedding      → Terracotta
Birthday     → Sand Beige
Travel       → Deep Teal
Anniversary  → Sage
Featured     → Muted Gold
```

---

# 18. Forms

Inputs უნდა იყოს მარტივი და premium.

```text
Height: 48–52px
Radius: 10–12px
Background: #FFFFFF
Border: #E8E5E1
Padding: 0 16px
```

Placeholder:

`#7E8491`

Focus:

```text
Border: #1E2A38
Box-shadow: 0 0 0 3px rgba(30,42,56,0.10);
```

---

# 19. Navigation

Desktop navigation:

```text
MaxAre     Discover     Events     Memories     About        Create Invitation
```

Header:

* Height: `72–80px`
* Background: `#F7F4F0`
* Logo: Deep Ocean
* Primary CTA: Deep Ocean
* Secondary accents: Terracotta

Navigation არ უნდა იყოს ზედმეტად მძიმე.

---

# 20. Hero Section

Hero უნდა იყოს უფრო cinematic და masculine.

### Background

`#F7F4F0`

### Left side

* Small eyebrow
* Large Playfair Display heading
* Supporting Inter paragraph
* Deep Ocean CTA
* Terracotta secondary action

### Right side

* Destination photograph
* Invitation preview
* Memory card
* Subtle decorative linework

შესაძლებელია გამოყენებული იყოს Deep Ocean decorative block ან image overlay, რათა hero-ს ჰქონდეს მეტი depth.

---

# 21. Decorative Style

დეკორაცია უნდა იყოს:

* Minimal botanical line art
* Travel-inspired line icons
* Thin gold rules
* Subtle geometric shapes
* Paper-inspired surfaces
* Minimal floral elements

არ გამოიყენოთ:

* ბევრი pink
* neon colors
* excessive gradients
* heavy glassmorphism
* cartoon-style decoration
* ზედმეტად glossy UI

---

# 22. Photography Direction

Photography არის MaxAre-ის ერთ-ერთი მთავარი ემოციური ნაწილი.

სასურველია:

* ბუნებრივი განათება
* cinematic travel photography
* architecture
* landscapes
* destination weddings
* authentic people
* warm sunlight
* Mediterranean / European locations
* muted earth tones

ფოტოები უნდა იყოს რეალისტური და premium.

---

# 23. Shadows

Shadow სისტემა უნდა იყოს მსუბუქი და თანამედროვე.

### Soft Shadow

```text
0 8px 24px rgba(0,0,0,0.06)
```

### Card Shadow

```text
0 12px 30px rgba(0,0,0,0.08)
```

### Hover Shadow

```text
0 20px 40px rgba(0,0,0,0.12)
```

არ გამოიყენოთ მძიმე შავი ჩრდილები.

---

# 24. Border Radius

```text
Small controls: 8px
Inputs: 10–12px
Buttons: 10–12px
Cards: 20px
Large cards: 28px
Modal: 20px
Pills: 999px
```

კუთხეები უნდა იყოს რბილი, მაგრამ არა ზედმეტად bubble-like.

---

# 25. Iconography

Icons უნდა იყოს:

* Thin/medium line style
* Rounded geometry
* Deep Ocean ან Charcoal
* ზომიერად მინიმალისტური

ძირითადი icons:

* Heart
* Calendar
* Location
* Gift
* Camera
* Users
* Send
* Share
* Envelope
* Bell

Icons არ უნდა იყოს ძალიან სქელი ან cartoonish.

---

# 26. Semantic Colors

სისტემური შეტყობინებები უნდა დარჩეს სტანდარტული და მკაფიო.

### Success

`#4CAF7D`

### Warning

`#E0A800`

### Error

`#D9534F`

### Info

`#3484E6`

Semantic colors არ უნდა შეერიოს მთავარ ბრენდულ პალიტრას.

---

# 27. Responsive Design

## Mobile

პრიორიტეტი:

1. Main content
2. Image
3. Title
4. Essential metadata
5. Primary CTA

Cards უნდა გადავიდეს single-column layout-ზე.

## Tablet

2-column layouts ძირითადად.

## Desktop

3–4 card columns, ფართო hero და multi-column content.

---

# 28. Accessibility

MaxAre უნდა იყოს accessible by default.

აუცილებელია:

* Semantic HTML
* Keyboard navigation
* Visible focus states
* Minimum `44px` touch target
* Alt text
* საკმარისი color contrast
* Color alone არ უნდა იყოს ინფორმაციის ერთადერთი მატარებელი
* `prefers-reduced-motion` მხარდაჭერა

---

# 29. Motion Design

Animation უნდა იყოს მშვიდი და პროფესიონალური.

გამოიყენე:

```text
200ms — small interactions
250–300ms — hover
300–500ms — modal/large transition
```

სასურველი ეფექტები:

* subtle lift
* image zoom
* opacity fade
* slide-up
* underline transition

არ გამოიყენოთ:

* bounce
* aggressive scale
* rotation
* flashing
* მუდმივი მოძრაობა

---

# 30. MaxAre Visual Hierarchy

ყველა გვერდზე პრიორიტეტი უნდა იყოს:

### 1. Deep Ocean

ქმნის ბრენდის იდენტობას და სერიოზულობას.

### 2. Photography

ქმნის ემოციას და destination/event context-ს.

### 3. Terracotta

ამატებს სითბოს და human touch-ს.

### 4. Sand / Ivory

ქმნის სივრცეს და premium editorial feeling-ს.

### 5. Gold

გამოიყენება მხოლოდ მცირე დეტალებში.

---

# 31. Overall Visual Formula

MaxAre-ის საბოლოო ვიზუალური ფორმულა:

**Deep Ocean + Warm Ivory + Terracotta + Sand Beige + Sage + Muted Gold**

ამ კომბინაციამ უნდა შექმნას:

**Masculine + Elegant + Warm + Premium + Travel + Celebration**

დიზაინი უნდა იყოს საკმარისად მამაკაცური და ნეიტრალური ყოველდღიური გამოყენებისთვის, მაგრამ ამავე დროს საკმარისად ელეგანტური ქორწილების, იუბილეების და განსაკუთრებული ღონისძიებებისთვის.

---

# 32. UI Image Generation Direction

MaxAre-ის UI mockup-ის ან დიზაინის ვიზუალის გენერირებისას გამოიყენე შემდეგი art direction:

> A sophisticated masculine-modern digital platform called MaxAre for digital invitations, destination events, celebrations, and memory galleries. Use a warm ivory background (#F7F4F0), deep ocean navy (#1E2A38) as the dominant brand color, warm terracotta (#B45E4A) as the emotional accent, sand beige (#DCC9B3), sage green (#6E6D62), slate blue (#3F4C5A), muted gold (#C9A66B), deep teal (#2F6A6D), burnt orange (#D47A4A), and lavender gray (#7E8491). Use Playfair Display for elegant editorial headings and Inter for clean interface text. Cards should have 20px rounded corners, subtle borders, soft shadows, premium travel photography, invitation previews, destination cards, and memory gallery cards. Buttons should be compact, confident, and minimal, with Deep Ocean primary CTAs and Terracotta secondary actions. The interface should combine the sophistication of a luxury travel journal with the functionality of a modern invitation platform. Avoid excessive pink, overly romantic styling, neon colors, heavy gradients, glassmorphism, and cartoon-like UI. The final appearance should feel masculine, premium, warm, cinematic, editorial, modern, and trustworthy.

---

# 33. Final Design Principle

MaxAre-ის მთავარი იდეა უნდა იყოს:

> **“Memories worth sharing, beautifully designed.”**

ეს დიზაინი უნდა აერთიანებდეს **მამაკაცურ თავდაჯერებულობას და თბილ ადამიანურ ემოციას**.

Deep Ocean ქმნის სტაბილურობასა და პრემიუმ ხასიათს.
Terracotta ამატებს სითბოს.
Sand Beige და Warm Ivory ქმნის სივრცეს.
Sage და Teal უკავშირებს ბრენდს ბუნებასა და მოგზაურობას.
Gold გამოიყენება როგორც მცირე პრემიუმ დეტალი.

შედეგად MaxAre უნდა აღიქმებოდეს არა როგორც უბრალოდ invitation website, არამედ როგორც **თანამედროვე ციფრული სივრცე, სადაც ადამიანები ქმნიან, აზიარებენ და ინახავენ მნიშვნელოვან მოგონებებს.**
