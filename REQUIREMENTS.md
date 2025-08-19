# Landing Page Requirements

This document outlines design and spacing requirements per section for desktop and mobile views, based on the provided spec.

---

## 1. Header

### Elements
- Logo image (resources/images/ic-logo.svg)
- Text logo: **COLMAR** (black) + **ACADEMY** (grey), 32px font-size, line-height 32px
- Navigation links: "On campus", "Online"
- Sign in link: text "Sign in"

### Desktop
- Header container: flex, `justify-content: space-between`, 
- Logo + text left
- Nav links (text): font-size 1.125rem (~18px), gap 16px, no list bullets
- Nav links:right-aligned (no auto margins on other items)
- Sign in: font-size 1rem, line-height 32px, margin-right 24px
- All items vertically centered at 32px height

### Mobile (≤768px)
- Header container: flex, wrap if needed, gap 16px
- Show only 4 icons in header (logo, on-campus, online, sign-in), each 24px height
- Icon list: flex with gap 16px, no text labels
- Horizontal padding: 16px por each side

---

## 2. Hero Section

    light GREY BACKGROUND need to be added
### Elements
- Large banner image (resources/images/banner.jpg)
- Heading: "Learn something new everyday"
- Paragraph: supporting copy
- Button: "Start learning"

### Desktop
- Layout: flex row, gap 16px
- Image: flex: 3 (approx 60%), content: flex: 2 (approx 40%)
- Margin-top: 16px
- Heading: font-size 2rem, margin-bottom 8px
- Paragraph: margin-bottom 16px, font-size 1rem
- Button: padding 12px 24px, background-primary

### Mobile (≤768px)
- Flex-direction: column, gap 16px
- Image and content full width
- Center-align button horizontally

---

## 3. Practice Feature Section

### Elements
- Large practice image (resources/images/information-main.jpg)
- Title: "It doesn’t hurt to keep practicing"
- Description paragraph
- List of 3 items: orientation (date), campus (link), guest lecture (link)

### Desktop
- Container: CSS Grid, `grid-template-columns: 2fr 1fr`, gap 16px
- Margin: 32px vertical
- Title: font-size 1.75rem, margin-bottom 8px
- Description: margin-bottom 16px
- List: flex column, gap 16px
- List-item: background-secondary, padding 8px, border-radius 4px, min-width 200px
- Item image: 60×60px, object-fit cover
- Text: h3 font-size 1rem, date/link font-size 0.875rem

### Mobile (≤768px)
- Grid → flex-direction column; gap 16px
- List: full-width items stacked

---

## 4. Courses Section

### Elements
- Section heading: "Start learning"
- Grid of 6 course cards (images + titles)

### Desktop
- Heading: font-size 1.75rem, margin-bottom 16px, center
- Grid: `grid-template-columns: repeat(auto-fit, minmax(200px, 1fr))`, gap 16px
- Card: background-secondary, border-radius 4px
- Card image: full width
- Title: font-size 1rem, padding 16px

### Mobile (≤768px)
- Grid collapses to one or two columns depending on viewport
- Ensure consistent gap 16px

---

## 5. Thesis Exhibit Section

### Elements
- Section heading: "Thesis exhibit"
- Video player (resources/videos/thesis.mp4)
- Two side cards (images + titles)

### Desktop
- Heading: font-size 1.75rem, margin-bottom 16px, center
- Container: flex row, gap 16px
- Video: flex 2, full width, border-radius 4px
- Aside: flex 1, flex-direction column, gap 16px
- Card: background-secondary, border-radius 4px; img full width; title padding 8px, font-size 1rem

### Mobile (≤768px)
- Flex-direction: column, gap 16px
- Video and cards full width

---

## 6. Footer

### Elements
- Text: "Colmar Academy © 2025. All rights reserved."
- Links: Privacy policy, Terms of service

### Desktop & Mobile
- Background-secondary, border-top 1px solid #ddd
- Padding: 16px top/bottom, 0 sides
- Container: flex, `justify-content: space-between`, `align-items: center`
- Text: font-size 0.875rem, color #777
- Links: list-style none, flex gap 16px, font-size 0.875rem, color-primary, no underlines
- Footer horizontal margins align with header (24px right on desktop, 16px padding on mobile)
