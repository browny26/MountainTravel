# Travel The Mountains - Design Replication Documentation

## Overview
This project replicates a visually compelling design inspired by an image found on Pinterest. The webpage uses modern web technologies and libraries to achieve smooth animations, clean layout designs, and a responsive user interface. It features a mountain travel guide concept with prominent typography, image sections, and a parallax-like scrolling experience.

## Technologies Used

- **HTML5**: Markup structure.
- **CSS3 & Tailwind CSS**: Styling and layout.
- **GSAP (GreenSock Animation Platform)**: Smooth animations and scroll-based effects.
- **Bootstrap Icons**: For iconography.

## Design
https://pin.it/2Ty03R1QN

## Structure Breakdown

### 1. Header Section

#### Features:
- A full-page hero section with navigation.
- Brand name `MNT` displayed on the left.
- A navigation menu with options: "Equipment," "About Us," and "Blog."
- A call-to-action button styled with a person-circle icon for "Account."

#### Animated Elements:
- "Follow Us" links on the left, rotated vertically with Instagram and Twitter icons.
- A centered headline: "Be Prepared For The Mountains And Beyond!"
- A scroll-down link with an arrow pointing down.

#### Design Enhancements:
- Overlay gradient from transparent to the primary theme color.
- Absolute positioning for layering effects.

### 2. Main Content Section

#### First Subsection:
- Headline: "What level of hiker are you?"
- Supporting paragraph: A descriptive block of placeholder text.
- Button-like text element with "read more" linking to additional content.
- Large typographic "01" element with a semi-transparent effect.

#### Second Subsection:
- Headline: "Picking the right Hiking Gear!"
- Similar structure to the first subsection, with different content and typography "02."

### Customization with Tailwind Configuration

Tailwind’s extended configuration includes:
- Custom font families: `Source Serif 4` and `Roboto`.
- Theme colors: `primary` (dark blue) and `secondary` (golden yellow).

### JavaScript and GSAP Integration

GSAP ScrollTrigger and Lenis handles scroll animations:
- Smooth, scroll-triggered effects for dynamic content transitions.
- Scroll behavior linked to anchor navigation (`#main`).

### Improvements Made
- Responsive design using Tailwind utilities.
- Hover and focus states for interactive elements.
- Visual depth using gradient overlays and layering techniques.

## Conclusion
This project showcases a detailed and functional replica of a design found on Pinterest. The use of Tailwind and GSAP provides flexibility and performance, delivering a modern web experience suitable for travel-themed websites.

