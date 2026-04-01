# Netflix HCI Prototype - Interactive Wireframe

A fully interactive and clickable Netflix UI prototype developed as part of an HCI (Human-Computer Interaction) university project. This prototype demonstrates user flows from profile selection through discovery, playback, social/watch-party features, and account management, with a consistent dark theme and cross-page navigation.

---

## 📋 Project Overview

**Project Type**: HCI Project  
**Application**: Netflix Streaming Service  
**Last Updated**: April 1, 2026

### Features
✅ Fully clickable and navigable prototype  
✅ Netflix-compliant dark theme design (`#E50914` accent)  
✅ Responsive layouts (desktop + mobile-style screens)  
✅ Smooth transitions and hover effects on key surfaces  
✅ Flows: profiles → home → title → player → subtitles / watch party  
✅ Extended areas: Kids Mode, Continue Watching, Downloads, Fast Laughs, notifications, and more  

---

## 👥 Team Members & Contributions

| Name | Role | Screens Created | Contribution |
|------|------|-----------------|--------------|
| **Arpit** | UI Designer | index.html, playback.html | Profile selection & video player interface |
| **Varun** | UI Designer | home.html, title-details.html | Home discovery page & title detail page |
| **Darshil** | UI Designer | search.html, new-and-hot.html | Search functionality & trending content |
| **Shrimad** | Lead Developer | my-netflix.html, account.html | User profile & account management |

*Additional HTML screens (Kids Mode, Continue Watching, Downloads, Fast Laughs, Watch Party, notifications, subtitles, match stats, etc.) were added and linked across the prototype to support demos and evaluation.*

---

## 📱 Screen-by-Screen Breakdown

### 1. **index.html** - Profile Selection Screen
**Created by**: Arpit  
**Purpose**: Landing page where users select their viewing profile.

**Key Features**:
- Profiles (Rohan, Priya, Ajay, Kids) with hover effects and “Who’s watching?”
- **Kids** profile navigates to **kids-mode.html**; other profiles → **home.html**
- Manage Profiles / alerts (demo)

**User Flow**: Choose profile → Home (or Kids Mode for the Kids profile).

---

### 2. **home.html** - Home / Discover
**Created by**: Varun *(extended with global links)*  
**Purpose**: Main discovery hub with hero, rows, and sidebar.

**Key Features**:
- Sidebar: Home, Search, New & Hot, TV, add, **Kids Mode**, **Fast Laughs** (smiley icon)
- Hero → **title-details.html**; **Continue Watching** row includes **See all** → **continue-watching.html**
- Trending, Top Picks, footer links (Kids Mode, Downloads, Continue Watching, Fast Laughs, Match stats, Audio & subtitles, Watch Party, etc.)

**User Flow**: Browse → title details, search, new & hot, My Netflix, or extended pages via sidebar/footer.

---

### 3. **search.html** - Search & Explore
**Created by**: Darshil *(extended)*  
**Purpose**: Search UI, top searches, category grid.

**Key Features**:
- Nav: Home, Search, New & Hot, My List, Browse, Kids, **Continue**, **Laughs**
- Bell opens **notifications overlay** (same page); links to **playback** from results
- **Fast Laughs** → **fast-laughs.html**

---

### 4. **new-and-hot.html** - New & Hot / Coming Soon
**Created by**: Darshil *(extended)*  
**Purpose**: Tabs and coming-soon style content.

**Key Features**:
- Nav links including **Laughs** → **fast-laughs.html**, **Continue** → **continue-watching.html**
- Notification overlay pattern; links back to **home.html**

---

### 5. **title-details.html** - Title Details
**Created by**: Varun *(extended)*  
**Purpose**: Metadata, play, list, related titles.

**Key Features**:
- **Play** → **playback.html**; top bar: **Continue**, **Laughs**, **Kids**; bell notifications
- **Watch Party** CTA → **watch-party.html**

---

### 6. **playback.html** - Video Player
**Created by**: Arpit *(extended)*  
**Purpose**: Minimal player chrome and controls.

**Key Features**:
- Back → **title-details.html**; **Kids** shortcut; **💬** → **watch-party.html**; **⚙** → **subtitle.html** (Audio & Subtitles)
- Play/pause, skip, fullscreen (demo alerts)

---

### 7. **my-netflix.html** - My Netflix
**Created by**: Shrimad *(extended)*  
**Purpose**: Personal hub: notifications, downloads preview, My List.

**Key Features**:
- Header: **Kids** → **kids-mode.html**; profile → **account.html**
- **Downloads** header → **downloads.html**; notifications overlay
- Bottom nav: **Home**, **New & Hot**, **Fast Laughs** → **fast-laughs.html**, **Downloads** → **downloads.html**, **More** (active on this page)

---

### 8. **account.html** - Account Settings
**Created by**: Shrimad *(extended)*  
**Purpose**: Billing, profiles, app toggles.

**Key Features**:
- **Kids** profile row → **kids-mode.html**
- Bottom bar: **Home**, **Search**, **Downloads** → **downloads.html**, Account

---

## 📄 Additional Pages (linked across the prototype)

| File | Purpose |
|------|---------|
| **kids-mode.html** | Kids-safe browsing UI; **Exit Kids** / branding → **home.html** |
| **notification.html** | Standalone notifications panel (also linked from bell icons where wired) |
| **downloads.html** | Mobile-style **Downloads**: Smart Downloads, storage, list, **Find More to Download** → search; bottom tabs aligned with My Netflix |
| **continue-watching.html** | Full **Continue Watching** list with sort controls and stats |
| **fast-laughs.html** | Vertical **Laughs** rail UI; sidebar links to Home, Search, My List, Alerts |
| **watch-party.html** | **Party lobby**: participants, invite link, **Live Chat** / **Settings** tabs; from player **💬** or title **Watch Party** |
| **subtitle.html** | **Audio & Subtitles** two-column picker; **Back to player** → **playback.html** |
| **match-score.html** | Sports-style **match stats** demo (shot map + bars); nav back → **home.html** |

---

## 🗺️ Navigation Flow Diagram (simplified)

```
index.html (profiles)
    └─→ home.html
         ├─→ search.html · new-and-hot.html · title-details.html
         ├─→ continue-watching.html · fast-laughs.html · kids-mode.html (sidebar/footer)
         ├─→ my-netflix.html → account.html · downloads.html
         └─→ footer → downloads · continue-watching · fast-laughs · match-score · subtitle · watch-party …

title-details.html → playback.html → subtitle.html | watch-party.html
playback.html → title-details.html (back)
```

---

## 🎨 Design System

### Color Palette (Netflix Brand)
```css
--netflix-red: #E50914          /* CTAs, accents */
--netflix-red-dark: #d30108     /* Hover/active */
--bg-primary: #141414           /* Main background */
--bg-secondary: #1a1a1a         /* Cards */
--text-primary: #ffffff
--text-secondary: #e5e5e5
--text-muted: #808080 / #b3b3b3
--pure-black: #000000           /* Player */
```

### Typography
- **Fonts**: Inter, Roboto, Public Sans, Helvetica Neue, system UI (varies by page)
- **Icons**: Font Awesome, Material Icons, inline SVGs, emoji where used for demo clarity

### Components
- Buttons, cards, carousels, progress bars, mobile tab bars, overlays (notifications), glass panels (Watch Party)

---

## 🚀 How to Use the Prototype

1. Open **`index.html`** in a modern browser (network useful for CDN images/fonts).
2. Pick a profile and use **sidebar**, **nav**, **footers**, and **in-page CTAs** to move between screens.
3. **Player**: use **⚙** for subtitles/audio; **💬** for Watch Party.

### Navigation Tips
- **Home** sidebar and **My Netflix** bottom bar expose **Fast Laughs**, **Downloads**, and **More**.
- **See all** on Continue Watching opens the dedicated **continue-watching** page.
- Some screens rely on **CDN** assets; allow network access for full visuals.

---

## 📊 Technical Stack

- **HTML5**, **CSS3** (custom properties, flexbox, grid, animations)
- **Tailwind CSS** (CDN) on selected pages: home, title-details, my-netflix, account, kids-mode, downloads, watch-party-related consumers
- **Vanilla JavaScript**: toggles (notifications, Smart Downloads, tabs, watch party invite copy)
- **External**: Google Fonts, Font Awesome, Material Icons, hosted images (e.g. Google user content URLs)

### Repository layout (HTML)
```
├── index.html
├── home.html
├── search.html
├── new-and-hot.html
├── title-details.html
├── playback.html
├── subtitle.html
├── watch-party.html
├── my-netflix.html
├── account.html
├── downloads.html
├── continue-watching.html
├── fast-laughs.html
├── kids-mode.html
├── notification.html
├── match-score.html
└── README.md
```

---

## 🎯 User Flows Supported

1. **Discovery → Playback**: Profile → Home → Title → Play → Player  
2. **Search → Playback**: Home → Search → result → **playback.html**  
3. **Profile & account**: Home → My Netflix → Account / Downloads  
4. **Kids**: Profile Kids / Kids link → **kids-mode.html** → Exit → Home  
5. **Continue Watching**: Home **See all** or nav → **continue-watching.html**  
6. **Fast Laughs**: Bottom bar or **Laughs** links → **fast-laughs.html**  
7. **Watch Party**: Title or Player chat → **watch-party.html** → back to player  
8. **Subtitles / audio**: Player **⚙** → **subtitle.html**  
9. **Downloads**: My Netflix / Account / footer → **downloads.html**  

---

## ✨ Highlights

- Cohesive **Netflix-style** dark UI with red accent  
- **Cross-linked** extended features (not a single isolated page)  
- **Mobile-style** patterns on My Netflix and Downloads  
- **Watch Party** and **subtitle** flows tied to the **player**  

---

## 🔍 Quality Checklist

✅ Static pages load without build step  
✅ Primary navigation paths wired between HTML files  
✅ Shared branding (dark UI, Netflix red)  
✅ Mix of responsive and fixed demo viewports  
✅ Hover/active states on interactive controls  
✅ README reflects current file set and flows  

---

*For course submission, start from `index.html` and follow any evaluator script; optional pages are reachable via Home footer and player/title actions.*

