# Netflix HCI Prototype - Interactive Wireframe

A fully interactive and clickable Netflix UI prototype developed as part of an HCI (Human-Computer Interaction) university project. This prototype demonstrates a complete user flow from profile selection through video playback, showcasing professional design standards and seamless navigation.

---

## 📋 Project Overview

**Project Type**: HCI Project
**Application**: Netflix Streaming Service
**Last Updated**: March 18, 2026

### Features
✅ Fully clickable and navigable prototype  
✅ Netflix-compliant dark theme design  
✅ Responsive layouts  
✅ Smooth transitions and hover effects  
✅ Complete user journey from login to playback  
✅ Professional typography and color system  

---

## 👥 Team Members & Contributions

| Name | Role | Screens Created | Contribution |
|------|------|-----------------|--------------|
| **Arpit** | UI Designer | index.html, playback.html | Profile selection & video player interface |
| **Varun** | UI Designer | home.html, title-details.html | Home discovery page & title detail page |
| **Darshil** | UI Designer | search.html, new-and-hot.html | Search functionality & trending content |
| **Shrimad** | Lead Developer | my-netflix.html, account.html | User profile & account management |

---

## 📱 Screen-by-Screen Breakdown

### 1. **index.html** - Profile Selection Screen
**Created by**: Arpit  
**Purpose**: Landing page where users select their viewing profile

**Key Features**:
- Display of available user profiles (Rohan, Priya, Ajay, Kids)
- Clickable profile avatars with hover effects
- "Who's watching?" branding
- Navigation to home.html upon profile selection

**Design Elements**:
- Radial gradient background (#141414 to #000)
- Profile cards with 130x130px avatars
- Hover scale effect (1.1x transformation)
- Lock icons for profile protection
- Smooth transitions and animations

**User Flow**: User selects profile → Navigates to home.html

---

### 2. **home.html** - Home/Discover Page
**Created by**: Varun  
**Purpose**: Main discovery interface with featured content and recommendations

**Key Features**:
- Sidebar navigation with icon-based menu
- Hero section with featured movie ("The Midnight Sky")
- "Play Now" call-to-action button
- "Continue Watching" section with progress bars
- "Trending Now" horizontal scrollable carousel
- Netflix branding and navigation

**Navigation Links**:
- Search icon → search.html
- New & Hot icon → new-and-hot.html
- Profile icon → my-netflix.html
- Featured movie thumbnail → title-details.html

**Design Elements**:
- Dark theme (#0f0f0f background)
- Inter font for modern typography
- Netflix red (#E50914) for CTAs
- Smooth hover animations on posters
- 20px sidebar with vertical icon navigation

**User Flow**: 
- Browse content recommendations
- Select movie/show thumbnail
- Access search, trending, or account features

---

### 3. **search.html** - Search & Explore Page
**Created by**: Darshil  
**Purpose**: Content search and discovery interface

**Key Features**:
- Search input with filter capabilities
- Top 5 searches section with rankings
- Search result cards with play buttons
- Filter chips (All, Movies, TV Shows, Documentaries, Anime, Kids, Stand-Up)
- Category cards for browsing (Action, Sci-Fi, Nature, Mystery, Comedy, Romance, etc.)
- Back/home navigation

**Navigation**:
- Play button on each search result → playback.html
- Home link in navigation → home.html
- Category cards support browsing by genre

**Design Elements**:
- Netflix red (#E50914) for branding
- Dark background (#141414 primary, #242424 surface)
- CSS custom properties for consistent theming
- Ranking numbers in large bold font
- Hover effects on cards and buttons

**User Flow**: 
- Enter search query
- View search results with play options
- Click play to start video → playback.html

---

### 4. **new-and-hot.html** - New & Hot / Coming Soon
**Created by**: Darshil  
**Purpose**: Display trending, new, and upcoming content

**Key Features**:
- Tab switcher (Now Trending, Coming Soon, Everyone's Watching, Top 10)
- Coming soon content cards with release dates
- Countdown timers for upcoming releases
- Action buttons (Remind Me, Add to List, Share, Play)
- Genre and metadata tags
- Professional card layouts with hover effects

**Navigation**:
- Home link → home.html
- Search link → search.html
- Play button → playback.html (implied)

**Design Elements**:
- Netflix red (#E50914) for accents
- Gold (#f5c518) for special annotations
- Dark theme with layered backgrounds
- Card-based layout with image backgrounds
- Tab underline indicator for active state

**User Flow**: 
- Browse upcoming releases
- View release countdown
- Add to list or set reminders
- Prepare for release date

---

### 5. **title-details.html** - Title Details/Movie Info Page
**Created by**: Varun  
**Purpose**: Detailed movie/show information and metadata

**Key Features**:
- Large title heading ("THE MIDNIGHT SKY")
- Match percentage (98% Match)
- Movie metadata (year, rating, runtime, quality)
- Detailed description
- Call-to-action buttons (Play, My List, Like)
- Cast and crew information
- Genres and categorization
- "More Like This" recommendations section
- Back/home navigation

**Navigation**:
- Play button → playback.html
- Home/logo → home.html
- Related content recommendations

**Design Elements**:
- Hero gradient overlay for readability
- Large 5xl+ heading typography
- Netflix standard colors (#e5e5e5 text, #808080 secondary)
- Roboto font with Helvetica Neue fallback
- Responsive two-column layout
- Image backgrounds with gradient overlays

**User Flow**: 
- View complete movie information
- Watch trailer or synopsis
- Click play to start watching
- Explore related titles

---

### 6. **playback.html** - Video Playback Interface
**Created by**: Arpit  
**Purpose**: Video player with playback controls

**Key Features**:
- Full-screen video player
- Top bar with back button and info icon
- Bottom controls:
  - Play/Pause button
  - Skip backward/forward (10 seconds)
  - Volume control
  - Current time display
  - Settings menu
  - Fullscreen toggle
- Progress bar with timeline scrubbing
- Hoverable controls for clean interface

**Navigation**:
- Back arrow (⬅) → title-details.html
- Responsive controls that appear on hover

**Design Elements**:
- Pure black background (#000)
- Red progress bar (#ff0000)
- White controls with 22px font size
- Minimalist UI - hides when not hovering
- Professional player layout

**User Flow**: 
- Watch video content
- Control playback
- Adjust volume or quality
- Return to title details

---

### 7. **my-netflix.html** - My Netflix / Personal Profile
**Created by**: Shrimad  
**Purpose**: User's personal content library and profile management

**Key Features**:
- Notifications section with preview
- Downloads management with storage indicator
- My List (user's watchlist)
- Horizontal scrollable content cards
- Bottom navigation (Home, Games, New & Hot, My Netflix)
- Profile avatar for account access
- Mobile-optimized layout

**Navigation**:
- Home button (bottom) → home.html
- Profile avatar → account.html
- Games icon → (placeholder for games feature)
- New & Hot icon → new-and-hot.html

**Design Elements**:
- Custom Netflix colors (netflixRed: #E50914)
- System fonts for modern look
- Bottom navigation bar with active states
- Sticky header for easy navigation
- Card-based content display
- Clean mobile-first design

**User Flow**: 
- View personal watchlist
- Check notifications
- Manage downloads
- Access account settings

---

### 8. **account.html** - Account Settings
**Created by**: Shrimad  
**Purpose**: User account management and preferences

**Key Features**:
- Sticky header with back navigation
- Account ID display
- Membership & Billing section:
  - Current plan display
  - Billing date
  - Update payment method button
  - Change plan button
- Profile & Parental Controls section:
  - List of user profiles
  - Admin/parental lock status
  - Profile unlock status
- Dark mode support with Tailwind CSS

**Navigation**:
- Back arrow → my-netflix.html
- Responsive header layout

**Design Elements**:
- Public Sans font for typography
- Netflix red (#E50914) for primary actions
- Material Icons for visual consistency
- Card-based layout with borders
- Dark mode with `dark:` Tailwind classes
- Professional settings page structure

**User Flow**: 
- View account information
- Manage billing and subscription
- Update payment methods
- Adjust parental controls

---

## 🗺️ Navigation Flow Diagram

```
index.html (Profile Selection)
    ↓
    └─→ home.html (Home/Discover)
         ├─→ search.html (Search)
         │   └─→ playback.html (Video Player)
         │       └─→ title-details.html
         │           └─→ playback.html
         │
         ├─→ new-and-hot.html (Trending)
         │   └─→ home.html
         │
         ├─→ title-details.html (Title Details)
         │   ├─→ playback.html (Video Player)
         │   └─→ home.html
         │
         └─→ my-netflix.html (My Profile)
             ├─→ home.html
             ├─→ account.html (Account Settings)
             │   └─→ my-netflix.html
             └─→ home.html
```

---

## 🎨 Design System

### Color Palette (Netflix Brand)
```css
/* Primary Colors */
--netflix-red: #E50914          /* Main brand color for CTAs */
--netflix-red-dark: #d30108     /* Hover/active state */

/* Background Colors */
--bg-primary: #141414           /* Main background */
--bg-secondary: #1a1a1a         /* Card/surface background */
--bg-tertiary: #242424          /* Elevated surfaces */

/* Text Colors */
--text-primary: #ffffff         /* Main text */
--text-secondary: #e5e5e5       /* Secondary text */
--text-muted: #808080           /* Tertiary/disabled text */

/* Utility */
--dark: #0f0f0f                 /* Darkest background variant */
--pure-black: #000000           /* Pure black for video player */
```

### Typography
- **Primary Font**: Inter, Roboto, Helvetica Neue
- **Fallback**: System fonts (-apple-system, BlinkMacSystemFont)
- **Font Weights**: 300 (light), 400 (regular), 600 (semibold), 700 (bold)

### Components
- **Buttons**: White background with black text for primary, Netflix red for secondary
- **Cards**: Dark backgrounds with subtle borders and hover scales
- **Navigation**: Icon-based with hover text indicators
- **Progress Bars**: Red (#E50914) for content progress

---

## 🚀 How to Use the Prototype

### Getting Started
1. Open `index.html` in a web browser
2. Select a user profile (Rohan, Priya, Ajay, or Kids)
3. Navigate through the application using clickable elements

### Navigation Tips
- **Sidebars**: Click icons to navigate between main sections
- **Cards**: Hover to see additional options, click to navigate
- **Buttons**: All buttons with underlines are clickable
- **Text Links**: Blue underlined text navigates to new pages
---

## 📊 Technical Stack

### Frontend Technologies
- **HTML5**: Semantic markup
- **CSS3**: Custom properties, flexbox, grid, animations
- **Tailwind CSS**: Utility-first CSS framework (home.html, title-details.html, my-netflix.html, account.html)
- **Vanilla JavaScript**: Interactive features
- **Google Fonts**: Inter, Roboto, Public Sans typefaces
- **Font Awesome**: Icon library for UI elements
- **Material Icons**: Icon set (account.html)

### Framework/Libraries Used
- **Tailwind CSS v3**: Utility-first styling
- **CDN-hosted**: All assets loaded via CDN for portability

### File Structure
```
HCI Project/
├── README.md                    (This file)
├── index.html                  (Profile Selection)
├── home.html                   (Home/Discover)
├── search.html                 (Search & Explore)
├── new-and-hot.html            (New & Hot)
├── title-details.html          (Title Details)
├── playback.html               (Video Playback)
├── my-netflix.html             (My Netflix)
└── account.html                (Account Settings)
```

---

## ✨ Key Features & Highlights

### 1. **Fully Clickable Prototype**
- Every navigation element is functional
- Smooth transitions between pages
- No placeholder buttons or broken links

### 2. **Netflix Design Compliance**
- Dark theme implementation
- Official Netflix color scheme
- Professional typography
- Industry-standard spacing and layout

### 3. **Responsive Design**
- Mobile-first approach
- Adapts to various screen sizes
- Touch-friendly interface

### 4. **Interactive Elements**
- Hover effects on cards and buttons
- Smooth scale transformations
- Active state indicators
- Visual feedback for user actions

### 5. **Accessibility**
- WCAG AA contrast compliance
- Semantic HTML structure
- Keyboard-navigable (standard browser functionality)
- Material Design icons for universal understanding

---

## 🎯 User Flows Supported

### Flow 1: Discovery to Playback
1. Select profile (index.html)
2. Browse home page recommendations (home.html)
3. View title details (title-details.html)
4. Start playback (playback.html)

### Flow 2: Search to Playback
1. Navigate to search (home.html → search.html)
2. View search results
3. Click play on desired title (search.html → playback.html)
4. Watch video content

### Flow 3: Profile Management
1. Navigate to My Netflix (home.html → my-netflix.html)
2. View watchlist and downloads
3. Access account settings (my-netflix.html → account.html)
4. Manage subscription and preferences

### Flow 4: Content Browsing
1. View trending content (home.html → new-and-hot.html)
2. Check upcoming releases
3. Set reminders for titles
4. Return to home (new-and-hot.html → home.html)

---

## 🔍 Quality Checklist

✅ All pages load without errors  
✅ All navigation links functional  
✅ Consistent branding across pages  
✅ Netflix red (#E50914) used correctly  
✅ Dark theme implemented properly  
✅ Text contrast meets WCAG AA standards  
✅ Responsive layouts work on mobile  
✅ Smooth hover effects and transitions  
✅ Professional typography hierarchy  
✅ Clean, maintainable code  

---