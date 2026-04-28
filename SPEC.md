# Imobiliária - Website Specification

## 1. Project Overview

- **Project Name**: Imobiliária Carlos
- **Type**: Traditional HTML/CSS/JS Website
- **Core Functionality**: Real estate agency website for showcasing properties, allowing users to browse listings, view property details, and contact the agency.
- **Target Users**: Home buyers, renters, and property investors

## 2. UI/UX Specification

### Layout Structure

- **Header**: Logo, navigation menu (Home, Imóveis, Sobre, Contato)
- **Hero Section**: Large banner with search form
- **Featured Properties**: Grid of property cards
- **Services Section**: What the agency offers
- **Footer**: Contact info, social links

### Responsive Breakpoints
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

### Visual Design

**Color Palette**:
- Primary: #1e3a5f (Deep Navy)
- Secondary: #c9a959 (Gold)
- Accent: #e74c3c (Coral Red)
- Background: #f5f5f5 (Light Gray)
- White: #ffffff

**Typography**:
- Headings: 'Playfair Display', serif
- Body: 'Lato', sans-serif

**Spacing System**:
- Base unit: 8px
- Section padding: 80px vertical

**Visual Effects**:
- Card hover: translateY(-5px) with shadow
- Smooth transitions: 0.3s ease

### Components

**Property Card**:
- Image (16:10 ratio)
- Property type badge
- Title, address
- Price
- Features (beds, baths, area)
- "Ver Detalhes" button

**Search Form**:
- Property type dropdown
- Location input
- Price range dropdown
- Search button

**Navigation**:
- Fixed header on scroll
- Mobile hamburger menu

## 3. Functionality Specification

### Core Features
1. Property listing display (6 sample properties)
2. Search/filter properties by type
3. Property detail modal
4. Contact form
5. Responsive navigation

### User Interactions
- Click property card → Open detail modal
- Click search → Filter properties
- Click nav item → Smooth scroll to section (for single page)

### Data
- 6 static properties with: id, title, address, type, price, beds, baths, area, image, description

## 4. Acceptance Criteria

- [ ] Page loads without errors
- [ ] All 6 properties display correctly
- [ ] Property cards show hover effect
- [ ] Search filters properties by type
- [ ] Detail modal opens with full property info
- [ ] Responsive on mobile/tablet/desktop
- [ ] Navigation works correctly
- [ ] Dark mode toggle works and persists in localStorage
- [ ] Login modal works with demo credentials
- [ ] Login/logout functionality works