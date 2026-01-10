# Replit Prompt: FRNDSAPP Landing Page

Build a stunning, modern landing page for **FRNDSAPP** - a revolutionary messaging app where ANYONE can create AI-powered matching Spaces.

**Note:** The app name is "FRNDSAPP" (all one word with APP, like WhatsApp).

---

## ⚠️ IMPORTANT RULES - READ CAREFULLY

1. **DO NOT miss any feature** - Every section in this document is CRITICAL
2. **Privacy Page is MANDATORY** - Create a full /privacy.html page with ALL details
3. **Hero Animation is CRITICAL** - Animated phone showing the complete flow (see below)
4. **One-Way Matching** - NOT like Tinder! Swipe right = instant conversation (no mutual match)
5. **All security features must be highlighted** - 3D liveness, OTS, E2EE, contact hashing
6. **Make it distinctive** - NO generic Bootstrap/Tailwind look
7. **Mobile-first** - Must work perfectly on mobile
8. **Include ALL pages**: index.html, privacy.html, terms.html

---

## ⚠️ CRITICAL: THE EXACT USER FLOW (Must be shown correctly!)

**This is NOT about people "connecting inside channels". Here's the EXACT flow:**

```
┌─────────────────────────────────────────────────────────────────────┐
│                    THE FRNDSAPP FLOW                                │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  STEP 1: CREATOR CREATES A SPACE                                    │
│  ────────────────────────────────                                   │
│  • Creator chats with AI to define the Space                        │
│  • AI asks: "What should people match on?"                          │
│  • AI asks: "What are the two roles?" (if complement mode)          │
│  • AI builds the schema (fields, filters, options)                  │
│  • Space is created and published!                                  │
│                                                                     │
│  STEP 2: USERS JOIN EXISTING SPACES                                 │
│  ──────────────────────────────────                                 │
│  • User browses/searches for Spaces                                 │
│  • User taps "Join" on a Space (e.g., "Flight Assist")              │
│  • AI asks questions based on Space schema:                         │
│    → "Are you a Helper or Traveler?"                                │
│    → "What's your flight destination?"                              │
│    → "What help do you need?"                                       │
│  • User's profile is created in that Space                          │
│                                                                     │
│  STEP 3: USER SEES MATCHING RESULTS                                 │
│  ──────────────────────────────────                                 │
│  • AI finds matches based on user's profile                         │
│  • Results shown as cards (like dating apps)                        │
│  • Cards show: Name, Photo, Distance, Match info                    │
│  • Sorted by: Relevance + Distance                                  │
│                                                                     │
│  STEP 4: SWIPE RIGHT = SEND MESSAGE (No mutual match!)              │
│  ─────────────────────────────────────────────────────              │
│  • User swipes right on a match                                     │
│  • Chat screen opens IMMEDIATELY                                    │
│  • User types and sends message (E2EE encrypted)                    │
│  • This is like a normal messaging app!                             │
│  • NO "It's a Match!" popup                                         │
│  • NO waiting for other person to swipe                             │
│                                                                     │
│  STEP 5: OTHER USER RECEIVES IN "NEW MATCHES"                       │
│  ────────────────────────────────────────────                       │
│  • Other user sees notification in "New Matches" tab                │
│  • They see: Your profile + Your message                            │
│  • They have 2 options:                                             │
│    → REPLY = Conversation moves to "Frnds" (main chat)              │
│    → BLOCK = You disappear, they never see you again                │
│  • If blocked, you never know (no awkwardness!)                     │
│                                                                     │
│  STEP 6: ONGOING CHAT (Like WhatsApp!)                              │
│  ─────────────────────────────────────                              │
│  • Once they reply, you're "Frnds"                                  │
│  • Chat appears in main "Frnds" section                             │
│  • Normal messaging: E2EE text, photos, calls                       │
│  • Can use OTS for sensitive content                                │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

**KEY POINTS TO SHOW:**
- Spaces are PRE-CREATED by someone (creator)
- Users JOIN existing Spaces and fill their profile via AI
- Matching happens WITHIN a Space
- Swiping is ONE-WAY (no mutual match needed)
- It's a MESSAGING APP at its core (like WhatsApp with smart matching)

---

## App Overview

FRNDSAPP is NOT another boring dating app or blackbox matching service. It's a platform where:

### 🎯 The Big Innovation: User-Created Matching Spaces
Unlike Tinder, Bumble, or LinkedIn where YOU are stuck with THEIR matching rules:
- **Anyone can create a Space** - Imagine any matching use case and build it!
- **AI Schema Builder** - Our AI helps you define matching rules conversationally
- **No coding required** - Any curious user can create their own Space in minutes
- **Infinite possibilities** - Travel buddies, EV charger sharing, band members, study partners, anything!

### 🎯 NOT Like Dating Apps - One-Way Matching!
**THIS IS CRITICAL - DIFFERENT FROM TINDER:**
- **Swipe right = Start conversation immediately** - No waiting for mutual match!
- **Other person sees you in "New Matches" section** - They can reply or block
- **If they reply** → Conversation moves to main "Frnds" chat section
- **If they block** → You never know, no awkwardness
- **No "It's a Match!" popup** - Just smooth, natural conversations

### 🔐 Uncompromising Security
- **3D Face Liveness Required** - NO user can register without passing real-time 3D liveness detection
- **Profile Picture Verification** - Every profile pic is compared against the verified live face
- **End-to-End Encrypted** - Not even FRNDSAPP can read your messages
- **OTS (One-Time Secure) Messages** - The most secure messaging feature ever built
- **E2EE File & Location Sharing** - Photos, videos, files, locations - ALL encrypted
- **E2EE Audio/Video Calls** - WebRTC with encryption by default

### 🔓 Open Source & Transparent
- **Frontend code is open source** - Check our GitHub!
- **Bug bashers welcome** - Security researchers can audit our code
- **Privacy you can verify** - Don't trust us, verify yourself

### 📱 Contact Privacy
- **Your contacts are HASHED** before sending to our servers
- **We never see your contact list** - Only hashed values
- **We only return matches** - Users already on FRNDSAPP
- **No data mining** - We don't store or sell your contacts

### 📍 Location-Based Matching
- **Nearby Feature** - Find people near you in any Space
- **Distance-sorted results** - See closest matches first (e.g., "3.2 km away")
- **Geolocation filtering** - Match within your preferred radius
- **Privacy preserved** - We only show distance, NEVER exact location

**Main Tagline:** "Connect in Space. Securely." 👨‍🚀🔑👩‍🚀

**App Category:** "💬 Messaging & Connecting, Redefined"

**Subheadline:** "Space has no boundaries. Neither do possibilities. Join Spaces for dating, business, travel — anything."

**Secondary tagline (for creators):** "Space is infinite. So are possibilities."

**Alt Taglines:**
- "Real People. Smart Matching. True Privacy."
- "Connect in Space. Create in Space."
- "No boundaries. Infinite possibilities."
- "Messaging, reimagined."
- "Not just another app. A new way to connect."

---

## Design Requirements

### Style & Aesthetic
- **Modern, premium feel** - think Stripe, Linear, or Notion landing pages
- **Dark mode primary** with gradient accents (deep purple → electric blue → cyan)
- **Glassmorphism effects** for cards and sections
- **Smooth scroll animations** and micro-interactions
- **Typography**: Use distinctive fonts like "Space Grotesk", "Outfit", "Satoshi", or "General Sans"
- **Hero section** with animated gradient background or particles
- **Avoid generic Bootstrap/Tailwind look** - make it distinctive!

### Color Palette
```
Primary: #6366F1 (Indigo)
Secondary: #8B5CF6 (Purple)
Accent: #06B6D4 (Cyan)
Dark BG: #0F0F1A
Card BG: rgba(255,255,255,0.05) with blur
Text: #FFFFFF / #A0A0B0
```

---

## Page Structure

### 1. Navigation (Sticky)
- Logo: "FRNDSAPP" with icon
- Links: Features | How It Works | Security | Open Source | Download
- CTA Button: "Get the App" (with both iOS and Android options)

### 2. Hero Section
```
Badge: "💬 Messaging & Connecting, Redefined"

Headline: "Connect in Space. 🔒"

Subheadline: "Space has no boundaries. Neither do possibilities.
Join Spaces for dating, business, travel — anything."

Create Line: "Can't find the right Space? Create your own with your rules! ✨"

CTAs (App Store Style Buttons):
[🍎 Download on App Store]  [▶️ Get it on Google Play]

Below CTAs - smaller text:
"No fake profiles. Real connections. True privacy."
"Every user 3D verified. Every message E2EE."
```

### 2a. ⭐ HERO ANIMATION - CRITICAL (Animated Phone Mockup)

**This is the MAIN visual element. Create an animated phone showing the COMPLETE flow:**

**IMPORTANT: The animation shows the REAL user journey:**
1. First, users BROWSE existing spaces and JOIN one
2. THEN, if they can't find what they need, they CREATE a new space
3. SoulMate is NOT in the initial list - it gets CREATED later!

```
ANIMATION SEQUENCE (Loop every ~33 seconds, 11 steps):

═══════════════════════════════════════════════════════════════════════
       HERO SECTION: TWO FLOATING OVERLAPPING SPACE BUBBLES
═══════════════════════════════════════════════════════════════════════

Two playful, overlapping circular bubbles floating independently!
More appealing and interactive than a single big bubble:

┌─────────────────────────────────────────────────────────────────────┐
│                                                                     │
│   ╭──────────────────────╮                                         │
│   │  🚀  ⭐   ✨         │  ← BUBBLE 1 (larger, behind)            │
│   │    ⭐      🚀        │    - Purple/blue gradient               │
│   │       ╭────────────────────╮                                   │
│   │       │  ⭐   🛸    ⭐     │  ← BUBBLE 2 (smaller, front)      │
│   │       │     ✨   ⭐        │    - Cyan/purple gradient          │
│   │       ╰────────────────────╯    - Overlapping bubble 1         │
│   ╰──────────────────────╯                                         │
│                                                                     │
│ 👨‍🚀                                                        👩‍🚀      │
│ (left)      🚀 🔐 E2EE  ─────────────────→            (right)     │
│            (rocket flies diagonal path)                            │
│                                                                     │
│         ╭─────────────────────────────────────╮                    │
│         │  💬 Next-Gen Messaging App          │                    │
│         │                                     │                    │
│         │    "Connect in Space."              │                    │
│         │         Securely.                   │                    │
│         │                                     │                    │
│         │  Space has no boundaries.           │                    │
│         │  Neither do possibilities.          │                    │
│         │  Join Spaces for dating, business,  │                    │
│         │  travel — anything.                 │                    │
│         │                                     │                    │
│         │  Can't find the right Space?        │                    │
│         │  Create your own with AI! ✨        │                    │
│         │                                     │                    │
│         │  [🍎 App Store] [▶️ Google Play]    │                    │
│         │                                     │                    │
│         │  No fake profiles. Real connections.│                    │
│         ╰─────────────────────────────────────╯                    │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘

**TWO BUBBLE DESIGN:**
- Bubble 1: Larger (w-72/h-72), positioned top-left, floats with 8s animation
- Bubble 2: Smaller (w-56/h-56), positioned top-right, overlaps bubble 1, floats with 6s animation
- Both bubbles have independent floating animations (different speeds/patterns)
- Each bubble contains floating stars, rockets, UFOs, sparkles
- Bubbles are perfectly circular (rounded-full)
- Very transparent (bg-gradient with 8-15% opacity)

**VISUAL ELEMENTS:**
- Stars twinkling inside each bubble (different timings)
- Mini rockets and UFOs floating (🚀 🛸)
- Sparkles (✨ ⭐)
- Astronauts positioned at diagonal - left upper, right lower
- Rocket flies diagonal path between astronauts

**INTERACTIONS (bubbles BULGE, GLOW, and FUSION on hover!):**
- Hover ANYWHERE in the bubble area triggers FULL effect on BOTH bubbles:
  - 5 layers of box shadows (30px, 60px, 100px, 150px, 200px)
  - Border brightens to 70% opacity
  - Background gradient intensifies significantly
  - BULGE: Scale up to 1.08x (elastic easing)
  - Inner ring glows brighter
  - Pulsing brightness animation (1.5s loop)
  - **FUSION DOTS**: 10 colorful dots appear and merge/fly toward each other
    - Different colors (primary, accent, secondary, cyan, purple, white)
    - Different trajectories and speeds (1.8s to 2.4s)
    - Scale up then shrink to 0 as they "merge"
    - Creates magical particle fusion effect
- Click anywhere: Triple ripple effect + ROCKET flies diagonally
- Rocket arcs from one astronaut to the other
- Sending astronaut waves, receiving astronaut celebrates
- Alternates direction each click

**CONTENT PLACEMENT:**
- "Can't find the right Space? Create your own with AI!" is INSIDE the bubble area
- All text content is positioned between/below the floating bubbles
- Headline and CTAs remain centered and visible

Headline: "Connect in Space. 🔒"

═══════════════════════════════════════════════════════════════════════
              PART 1: JOIN EXISTING SPACE (Flight Assist)
═══════════════════════════════════════════════════════════════════════

┌─────────────────────────────────────────────────────────────────────┐
│ STEP 1: BROWSE SPACES with catchy CREATE banner (3 seconds)         │
├─────────────────────────────────────────────────────────────────────┤
│ Phone shows: Catchy "Create Your Own Space" banner at TOP           │
│                                                                     │
│ ┌─────────────────────────────────────────────────────────────────┐ │
│ │ 🌌 Can't find your Space?                                       │ │
│ │ CREATE YOUR OWN! ✨                            [+]              │ │
│ │ Space is infinite. So are possibilities.                        │ │
│ └─────────────────────────────────────────────────────────────────┘ │
│                                                                     │
│ Search bar: "Search spaces..."                                      │
│                                                                     │
│ Space List (NO SoulMate yet - it's created later!):                 │
│ ✈️ Flight Assist - 1.2k members (highlighted, user will tap this)  │
│ 💼 Deal Room - 3.8k members                                         │
│ ⚡ Charge Share - 890 members                                       │
│ 📚 Study Squad - 2.1k members                                       │
│                                                                     │
│ ══════════════════ FOOTER TABS ══════════════════                   │
│ 💬 Chats  |  📍 Nearby  |  🌌 Space*  |  📞 Calls                   │
│ (* = selected tab)                                                  │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 2: JOIN FLIGHT ASSIST - AI ASKS QUESTIONS (3 seconds)          │
├─────────────────────────────────────────────────────────────────────┤
│ Header: ✈️ Flight Assist - "Joining..."                             │
│                                                                     │
│ AI: "Welcome! Are you a Traveler or Helper?" 🤖                     │
│ User: "Traveler"                                                    │
│ AI: "What's your flight route?"                                     │
│ User: "DEL → JFK, Dec 25"                                           │
│ AI: "What help do you need?"                                        │
│ User: "Customs help, first time"                                    │
│ AI: "✓ Profile created! 3 helpers found"                            │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 3: MATCH 1 - SWIPE LEFT (Skip) (3 seconds)                     │
├─────────────────────────────────────────────────────────────────────┤
│ Header: ✈️ Matches (1 of 3)                                         │
│                                                                     │
│ Card: Mike, 45                                                      │
│ - ✈️ DEL→JFK                                                        │
│ - 📍 2.3 km away                                                    │
│ - Languages: English only                                           │
│ - Helped: 5 travelers                                               │
│                                                                     │
│ [✕ SWIPE LEFT HIGHLIGHTED] [💚 dim]                                 │
│ Text: "← Swipe left to skip"                                        │
│                                                                     │
│ (Show the card sliding LEFT and disappearing)                       │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 4: MATCH 2 - SWIPE RIGHT on Raj! (3 seconds)                   │
├─────────────────────────────────────────────────────────────────────┤
│ Header: ✈️ Matches (2 of 3)                                         │
│                                                                     │
│ Card: Raj, 32 (HIGHLIGHTED with green border)                       │
│ - ✈️ SAME FLIGHT! DEL→JFK ⭐                                        │
│ - 📍 0.5 km • At gate now!                                          │
│ - Languages: Hindi, English ✓                                       │
│ - Helped: 50+ travelers ⭐                                          │
│                                                                     │
│ [✕ dim] [💚 SWIPE RIGHT HIGHLIGHTED + pulsing]                      │
│ Text: "Perfect match! Swipe right →"                                │
│                                                                     │
│ (Show the card sliding RIGHT)                                       │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 5: E2EE CHAT WITH RAJ (3 seconds)                              │
├─────────────────────────────────────────────────────────────────────┤
│ Header: 👨 Raj ✓ | 🔒 E2EE Chat | [📞] [📹]                          │
│                                                                     │
│ 🔐 End-to-end encrypted                                             │
│                                                                     │
│ You: "Hi Raj! I'm nervous about customs 😅"                         │
│ Raj: "No worries! I've helped 50+ first-timers. Meet at Gate 42?"   │
│ You: "Perfect! Thanks so much 🙏"                                   │
│ Raj: "See you in 20 mins! Blue jacket ✈️"                           │
│                                                                     │
│ [Type a message...] [Send]                                          │
└─────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════
              PART 2: CREATE NEW SPACE (SoulMate)
═══════════════════════════════════════════════════════════════════════
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 6: SAME AS STEP 1 - WITH + BUTTON HIGHLIGHTED (3 seconds)      │
├─────────────────────────────────────────────────────────────────────┤
│ ⚠️ SAME SCREEN AS STEP 1 but with CREATE banner PULSING!           │
│                                                                     │
│ ┌─────────────────────────────────────────────────────────────────┐ │
│ │ 🌌 Can't find your Space?                    ⚡ PULSING ⚡      │ │
│ │ CREATE YOUR OWN! ✨                     [+] ← GREEN PING        │ │
│ │ Space is infinite. So are possibilities.                        │ │
│ └─────────────────────────────────────────────────────────────────┘ │
│                                                                     │
│ Search bar: (dimmed)                                                │
│ Space List: (very dimmed - focus on create button)                  │
│                                                                     │
│ ══════════════════ FOOTER TABS ══════════════════                   │
│ 💬 Chats  |  📍 Nearby  |  🌌 Space*  |  📞 Calls                   │
│                                                                     │
│ (User taps the pulsing + button with green ping indicator)          │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 7: CREATE SOULMATE SPACE FORM (3 seconds)                      │
├─────────────────────────────────────────────────────────────────────┤
│ Header: "Create New Space"                                          │
│                                                                     │
│ Space Name: 💍 SoulMate|                                            │
│ Description: "Serious dating for marriage-minded"                   │
│ Image: [💍 icon uploaded ✓]                                         │
│                                                                     │
│ [✨ Create with AI]                                                 │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 8: AI BUILDS SOULMATE SCHEMA (3 seconds)                       │
├─────────────────────────────────────────────────────────────────────┤
│ AI: "What should people match on?" 🤖                               │
│ User: "Age, Religion, Family values"                                │
│ AI: "Questions to ask users?"                                       │
│ User: "Marriage timeline, location pref"                            │
│                                                                     │
│ ┌─────────────────────────────────────┐                             │
│ │ ✨ "SoulMate" is LIVE!             │                             │
│ │ Now chatting with Priya...          │                             │
│ └─────────────────────────────────────┘                             │
└─────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════
              PART 3: OTS MESSAGE - SCREENSHOT DETECTION ⭐
═══════════════════════════════════════════════════════════════════════
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 9: OTS MESSAGE IN SOULMATE CHAT (3 seconds)                    │
├─────────────────────────────────────────────────────────────────────┤
│ Header: 👩 Priya | 🔒 E2EE                                          │
│                                                                     │
│ Priya: "Great video call yesterday! 💕"                             │
│ You: "Here's a personal pic from the wedding 😊"                    │
│                                                                     │
│ ┌─────────────────────────────────────┐                             │
│ │ 🔒 OTS Message                      │                             │
│ │ 📷 Private photo                    │                             │
│ │ View once only                      │                             │
│ └─────────────────────────────────────┘                             │
│                                                                     │
│ Priya: "Opening OTS... 👀"                                          │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 10: ⚠️ SCREENSHOT ATTEMPT DETECTED! (3 seconds)                │
├─────────────────────────────────────────────────────────────────────┤
│ [Camera Active 🔴]                                                  │
│                                                                     │
│ ┌─────────────────────────────────────┐                             │
│ │ (Image with gray anti-screenshot    │                             │
│ │  lines overlaid)                    │                             │
│ │                                     │                             │
│ │ ┌─────────────────────────────────┐ │                             │
│ │ │ 📱⚠️ EXTERNAL CAMERA DETECTED! │ │                             │
│ │ │ Another phone trying to capture │ │                             │
│ │ └─────────────────────────────────┘ │                             │
│ └─────────────────────────────────────┘                             │
│                                                                     │
│ 🚫 Screenshot attempt blocked!                                      │
│ Message deleted • Sender notified                                   │
│                                                                     │
│ (Label turns RED for this step)                                     │
└─────────────────────────────────────────────────────────────────────┘
                              ↓
┌─────────────────────────────────────────────────────────────────────┐
│ STEP 11: BACK TO CHAT - OTS DELETED (3 seconds)                     │
├─────────────────────────────────────────────────────────────────────┤
│ Header: 👩 Priya | 🔒 E2EE                                          │
│                                                                     │
│ Priya: "Great video call yesterday! 💕"                             │
│ You: "Here's a personal pic from the wedding 😊"                    │
│                                                                     │
│ ┌─────────────────────────────────────┐                             │
│ │ 💨 OTS message deleted              │                             │
│ │ ⚠️ Screenshot attempt detected     │                             │
│ └─────────────────────────────────────┘                             │
│                                                                     │
│ Priya: "Oops! Someone tried to capture. Message gone! 🔐"           │
│ You: "That's why I love OTS! Our privacy protected 💕"              │
│                                                                     │
│ 🔐 Private moments stay private!                                    │
└─────────────────────────────────────────────────────────────────────┘

═══════════════════════════════════════════════════════════════════════
                         LOOP BACK TO STEP 1
═══════════════════════════════════════════════════════════════════════
```

**Animation Notes:**

**CRITICAL FLOW ORDER:**
1. FIRST show browsing/joining EXISTING spaces
2. THEN show "Can't find? Create!" flow
3. SoulMate is NOT in initial list - it gets CREATED by user

**11 Steps with Labels:**
| Step | Label | Duration | What Happens |
|------|-------|----------|--------------|
| 1 | Browse Spaces | 3s | Space list with + banner, footer tabs (Space selected) |
| 2 | Join Flight Assist | 3s | AI asks questions, profile created |
| 3 | Match 1: Skip | 3s | Show Mike, user swipes LEFT |
| 4 | Match 2: Perfect! | 3s | Show Raj (perfect match), swipe RIGHT |
| 5 | E2EE Chat | 3s | Chat with Raj |
| 6 | Create New Space | 3s | SAME as Step 1, + button pulsing, footer tabs |
| 7 | Building SoulMate | 3s | Create form with name/description |
| 8 | AI Schema | 3s | AI builds schema, Space published |
| 9 | OTS Message | 3s | Send private pic in SoulMate chat |
| 10 | ⚠️ Snap Detected! | 3s | Screenshot attempt blocked (RED label) |
| 11 | Privacy Protected | 3s | Back to chat, OTS deleted message |

**Key Visual Elements:**
- **Astronaut Animation:** Two astronauts floating with bubbles, connected by a moon-bubble with rotating key
- **Footer Tabs:** Chats | Nearby | Space* | Calls (shown on space list screens)
- **+ Create Button:** Always visible at top of Spaces list in catchy banner
- **Swipe LEFT/RIGHT:** Show both in matches (skip first, accept second)
- **OTS Detection:** Show camera active, gray lines, red alert overlay
- **Progress Dots:** 11 clickable dots at bottom (users can click to jump to any step)
- **Navigation Arrows:** < > buttons for manual prev/next navigation
- **Step Counter:** Shows "1 / 11" current position
- **Step Label:** Changes each step, turns RED on step 10 (detection)
- **Auto-play:** Pauses when user interacts, resumes after 8 seconds

**Features Highlighted:**
| Flow | Features Shown |
|------|---------------|
| Hero Section | INTERACTIVE transparent bubble - click to send E2EE messages between astronauts |
| Flight Assist | AI onboarding, multiple matches, swipe left/right, E2EE chat |
| SoulMate | Space creation from scratch, AI schema builder |
| OTS Demo | Private photos, camera detection, screenshot blocking, auto-delete |
| App Structure | Footer tabs showing full messaging app (Chats, Nearby, Space, Calls) |

- **Important:** Show that ALL chats are E2EE by default (🔒 indicator)
- **Important:** Video call shows E2EE indicator (📹🔒)
- **Important:** Footer tabs show this is a full messaging app, not just matching
- Phone frame should be modern (iPhone-style)
- Chat bubbles type out character by character
- Swipe gestures must be clear (left = skip, right = connect)
- Total cycle: ~33 seconds (11 steps × 3 seconds), then loop

### 2b. "Why FRNDSAPP is Different" - Quick comparison strip
```
┌──────────────────────┬────────────────────────────────────────┐
│ Other Apps           │ FRNDSAPP                               │
├──────────────────────┼────────────────────────────────────────┤
│ Their matching rules │ You create rules for your Space        │
│ Fake profiles        │ 3D face verified only                  │
│ Can read messages    │ Even FRNDSAPP can't read your messages │
│ Basic security       │ OTS: No one can snap, ever!            │
└──────────────────────┴────────────────────────────────────────┘
```

### 3. Trust Badges
Row of badges/icons:
- 🔒 E2EE Everything (Messages, Calls, Files, Location)
- ✅ 3D Face Verified Users Only
- ✨ Create Your Own Matching Spaces
- 📍 Location-Based Matching
- 👁️ OTS Ultra-Secure Messages
- 💻 Open Source Frontend
- 📱 Contact Hashing (We Never See Your Contacts)

### 4. Features Section (Cards with icons)

**Feature 1: CREATE YOUR OWN MATCHING SPACE** ⭐ (Hero Feature)
```
Icon: ✨ or 🚀
Title: "Imagine Any Matching Space. Build It."
Description: "Tired of boring, one-size-fits-all dating apps? With FRNDSAPP, 
YOU decide what to match on. Our AI Schema Builder helps you create 
custom matching Spaces in minutes - no coding needed. 

Flight buddies? EV charger sharing? Band members? Study partners? 
If you can imagine it, you can create it. Any curious user or developer 
can build their own matching Space easily."

Highlight: "This is NOT a blackbox like Tinder. YOU control the matching rules."
```

**Feature 2: 3D Face Verification - No Fakes Allowed**
```
Icon: 🛡️ or 👤
Title: "Real Humans Only. Guaranteed."
Description: "No user can even REGISTER without passing 3D liveness detection. 
We check for real depth, movement, and anti-spoofing - no photos of photos, 
no masks, no screens.

PLUS: Every profile picture you upload is compared against your verified 
live face. Only pictures of YOU are allowed. Zero catfishing. Zero fake profiles."
```

**Feature 3: True Privacy - Even WE Can't See**
```
Icon: 🔐
Title: "We Can't See ANYTHING. Nobody Can."
Description: "End-to-end encryption using Signal Protocol means:

• Text messages - encrypted
• Photos & videos - encrypted  
• File sharing - encrypted
• Location sharing - encrypted
• Audio calls - encrypted (WebRTC)
• Video calls - encrypted (WebRTC)

Not even FRNDSAPP servers can decrypt your content. 
We literally cannot see what you share. Period."
```

**Feature 4: OTS Messages - Ultra Secure** ⭐ (Unique Feature)
```
Icon: 🔒 or 👁️
Title: "One-Time Secure Messages: Beyond Encryption"
Description: "For your most sensitive messages, OTS takes security to another level:

• Camera activates INSTANTLY when reading starts
• no one can even take snap from another phone
• Message BLOCKS and DELETES if you look away or move
• Detects if ANYONE else appears in frame
• Anti-screenshot protection with gray line patterns
• If a sneaky photo is detected, sender is immediately notified
• Works only on your primary device

The recipient must be alone, looking at the screen, with their verified 
face confirmed in real-time. Anything suspicious = message gone."
```

**Feature 5: One-Swipe Conversations** ⭐ (Key Differentiator)
```
Icon: 💬 or ➡️
Title: "Swipe Right. Start Talking. No Waiting."
Description: "Forget the dating app dance of mutual matching!

On FRNDSAPP:
• Swipe right on someone you like
• Chat opens IMMEDIATELY
• Start typing your message
• No 'It's a Match!' popup
• No waiting to see if they swipe back

The other person sees you in their 'New Matches' section.
They reply → You're Frnds. They block → You disappear quietly.

Simple. Natural. The way conversations should start."
```

**Feature 6: Nearby Matching**
```
Icon: 📍
Title: "Find People Near You"
Description: "Every Space supports location-based matching. Find travel 
buddies at your airport, study partners on your campus, or chargers 
in your neighborhood. 

• See distance on every card: '3.2 km away'
• Results sorted by proximity
• Your exact location is NEVER shared
• We only show distance, not coordinates"
```

**Feature 7: AI That Gets You**
```
Icon: 🧠
Title: "Smart Matching, Not Just Keywords"
Description: "Our AI understands meaning, not just words. It relaxes 
filters intelligently when needed and prioritizes the best matches 
based on semantic similarity. The more you describe, the better it matches."
```

**Feature 8: Open Source Frontend** ⭐
```
Icon: 💻 or </>
Title: "Open Source. Verify Yourself."
Description: "Don't just trust us - verify our code yourself! 
Our frontend is fully open source on GitHub.

• Security researchers can audit our code
• Bug bashers are welcome
• Developers can contribute
• Transparency you can trust

GitHub: github.com/[your-repo-link]"
```

**Feature 9: Contact Privacy Done Right**
```
Icon: 📱 or 🔒
Title: "Your Contacts Stay Yours"
Description: "When you sync contacts, we NEVER see your actual contact list:

1. Your contacts are HASHED on your device
2. Only hashed values are sent to us
3. We compare hashes and return matches
4. We only tell you who's already on FRNDSAPP

No contact mining. No data selling. We literally can't see names or numbers."
```

### 5. How It Works Section (6 Steps - The Complete Flow)

**IMPORTANT: Show this as a clear journey, not vague "connections"**

```
Step 1: "Prove You're Real" 🛡️
- One-time 3D face liveness scan
- Anti-spoofing checks (no photos, no masks)
- Takes 30 seconds, verified forever
- "This is your identity anchor"
- Every profile pic verified against this face

Step 2: "Browse or Create Spaces" ✨
- Browse existing Spaces (Deal Room, SoulMate, Flight Assist...)
- OR create your OWN Space!
- To create: Chat with AI
  → AI: "What should people match on?"
  → AI: "What are the two roles?"
  → AI: "Space created! ✨"
- YOU define the schema. YOU control the matching rules.

Step 3: "Join a Space & Build Your Profile" 📝
- Tap "Join" on any Space
- AI asks YOU questions (based on Space schema):
  → "Are you a Helper or Traveler?"
  → "What's your destination?"
  → "What type of help?"
- Your profile is created in THAT Space
- You can join multiple Spaces!

Step 4: "See Your Matches" 🎯
- AI finds people who match YOUR profile
- Results shown as swipeable cards
- Each card shows: Photo, Name, Distance, Match details
- Sorted by: AI relevance + distance
- Example: "Priya - 4.2 km away • Same destination • Speaks Hindi"

Step 5: "Swipe Right = Send Message!" 💬 ⭐ THIS IS KEY!
- Swipe right on someone
- Chat screen opens IMMEDIATELY
- Type your message and send (E2EE encrypted)
- NO waiting for mutual match!
- NO "It's a Match!" popup!
- It's like sending a message on WhatsApp!

Step 6: "They Reply or Block" 🤝
- Other person sees your message in "New Matches" tab
- They see: Your profile + Your message
- They can: [Reply] or [Block]
- REPLY → You become "Frnds", chat in main section
- BLOCK → You disappear (you never know!)
- Now chat like normal: text, photos, calls (all E2EE)
- Use OTS for extra-sensitive content
```

**Visual: Show the key difference:**
```
┌────────────────────────────────────────────────────────────────────┐
│                    FRNDSAPP vs DATING APPS                         │
├─────────────────────────────┬──────────────────────────────────────┤
│   TINDER / BUMBLE           │   FRNDSAPP                           │
├─────────────────────────────┼──────────────────────────────────────┤
│ Swipe right...              │ Swipe right...                       │
│ Wait and hope...            │ 💬 Chat opens IMMEDIATELY!           │
│ Maybe they swipe back...    │ Type your message, send it           │
│ "It's a Match!" popup       │ No popup. No waiting.                │
│ THEN you can finally chat   │ Like sending a WhatsApp message      │
│                             │                                      │
│ Awkward if no match         │ They reply or block (you never know) │
│ Both must swipe             │ Only YOU need to swipe               │
└─────────────────────────────┴──────────────────────────────────────┘
```

**Another visual: The "New Matches" flow:**
```
┌─────────────────────────────────────────────────────────────────────┐
│ WHAT THE OTHER PERSON SEES:                                         │
├─────────────────────────────────────────────────────────────────────┤
│                                                                     │
│  📱 "New Matches" Tab (badge: 1 new)                                │
│                                                                     │
│  ┌───────────────────────────────────────────────────────────────┐  │
│  │ 👤 Raj wants to connect                                       │  │
│  │ "Hi! I'm on the same flight - can help with customs!"         │  │
│  │                                                               │  │
│  │ [View Profile]  [Reply ✓]  [Block ✗]                          │  │
│  └───────────────────────────────────────────────────────────────┘  │
│                                                                     │
│  If Reply → Chat moves to "Frnds" section (main chat)              │
│  If Block → Raj disappears, never knows                            │
│                                                                     │
└─────────────────────────────────────────────────────────────────────┘
```

### 6. Use Cases Section (Show versatility)

```
Title: "What Will YOU Create?"
Subheadline: "Here are some Spaces our users have built. 
Your imagination is the only limit."
```

**FEATURED SPACES (3 larger cards showing variety):**

💼 **Deal Room** ⭐
```
"Exclusive B2B deals & partnerships
- Sellers share confidential term sheets via OTS
- Buyers view pricing once - can't screenshot or forward!
- Perfect for: Software licensing, bulk inventory, partnerships
- Your exclusive pricing stays exclusive 🔐"
```

💍 **SoulMate** ⭐  
```
"Serious dating for people ready for marriage
- 3D face verified - NO catfishing possible!
- Find matches NEAR you (4.2 km away!)
- E2EE video calls - get to know each other privately
- Share private moments via OTS - auto-deletes, can't be leaked!
- All chats encrypted - even we can't read them 🔐💕"
```

✈️ **Flight Assist** ⭐
```
"Connect travelers with airport helpers
- Match by destination, flight time, help type
- Find helpers on YOUR flight, at YOUR airport!
- Language help, navigation, first-time flyer support
- 0.5 km away - meet at the gate! 🛫"
```

**More Space Ideas (smaller cards):**
- ⚡ **Charge Share** - "Share your EV charger with drivers nearby. Set your rate, availability."
- 📚 **Study Squad** - "Find study partners by subject, university, exam date."
- 🎯 **Career Mentor** - "Mentors find mentees. Match by industry, experience level."
- 🎸 **Band Finder** - "Musicians finding musicians. Match by instruments, genre."
- 🐕 **Pet Sitter** - "Find trusted pet sitters nearby. Verified humans only!"
- 🏠 **Roommate Match** - "Find compatible roommates by location, budget, lifestyle."

**Bottom text:**
"These are just examples. Create a Space for ANYTHING. 
Our AI Schema Builder makes it easy - just describe what you want to match on.

Each Space uses different features:
💼 Deal Room → OTS for confidential docs
💍 SoulMate → Nearby + E2EE calls + OTS private pics
✈️ Flight → Time + Location + E2EE chat

Remember: ALL chats are E2EE encrypted. ALL video calls are E2EE. 
OTS is for extra-sensitive content that auto-deletes after viewing!"

### 7. Security Deep Dive Section

```
Title: "Security That Goes Beyond Anything You've Seen"

Subheadline: "We built FRNDSAPP for people who take privacy seriously."

Cards:

1. True End-to-End Encryption - EVERYTHING
   "Signal Protocol encryption. Your messages are encrypted on YOUR device 
   and only decrypted on the recipient's device. Our servers only see 
   encrypted blobs. We literally CANNOT read your messages - even if 
   we wanted to, even if compelled by law.
   
   This applies to EVERYTHING:
   ✓ Text messages
   ✓ Photos & videos you share
   ✓ Files & documents
   ✓ Location sharing
   ✓ Audio calls (WebRTC E2EE)
   ✓ Video calls (WebRTC E2EE)"

2. 3D Face Liveness - Registration Gate
   "You can't even CREATE an account without passing real-time 3D liveness 
   detection. We check depth, movement, blink detection, and anti-spoofing. 
   No photos of photos. No masks. No screens. Real humans only."

3. Profile Picture Verification
   "Every profile picture you upload is compared against your verified 
   live face using facial recognition. If it's not you, it's rejected. 
   No catfishing. No fake photos. No exceptions."

4. OTS Messages - The Ultimate Protection
   Detailed breakdown:
   ┌─────────────────────────────────────────────────────────────┐
   │ HOW OTS (ONE-TIME SECURE) MESSAGES WORK                    │
   ├─────────────────────────────────────────────────────────────┤
   │ 📷 Camera activates INSTANTLY when you start reading       │
   │ 👤 Must be YOUR verified face - checked in real-time       │
   │ 🚫 Message BLOCKS if you look away or move                 │
   │ 🚫 Message DELETES if anyone else appears in frame         │
   │ 📱 Works ONLY on your primary registered device            │
   │ 📸 Gray line patterns blur any sneaky screenshot attempts  │
   │ ⚠️ Photo attempt detected? Sender is notified immediately  │
   │ 💨 After reading, message is permanently deleted           │
   └─────────────────────────────────────────────────────────────┘
   "The most secure way to share sensitive information. Ever."

5. Nearby Without Tracking
   "Location matching uses geohash technology - we know your 
   approximate area for matching, not your exact location. 
   And location data is never shared with other users directly."

6. Contact Sync - Hash Only
   "When you sync contacts to find friends on FRNDSAPP:
   ┌─────────────────────────────────────────────────────────────┐
   │ 1. Contacts are HASHED on YOUR device                      │
   │ 2. Only hash values sent to our servers                    │
   │ 3. We compare hashes with existing user hashes             │
   │ 4. We return: 'These contacts are on FRNDSAPP'             │
   │ 5. We NEVER see actual names or phone numbers              │
   └─────────────────────────────────────────────────────────────┘
   No contact mining. No selling data. We literally can't."

7. Open Source - Verify Our Claims
   "Our frontend code is fully open source. Don't trust us - 
   VERIFY us. Security researchers and developers can audit 
   our encryption implementation, privacy practices, and more.
   
   GitHub: github.com/[your-repo-link]
   
   Bug bounty? We welcome responsible disclosure."
```

### 8. Testimonials/Social Proof (Optional placeholder)
```
"Finally, an app where I know everyone is real." - User
"The AI matching is scary good at finding the right people." - User
```

### 9. Download CTA Section (Large, prominent)

```
Headline: "Ready to Find Your People?"

Subheadline: "Join thousands of verified users who are done with 
fake profiles and endless swiping with no replies.

Join a Space. Find your match. Start chatting instantly."

[🍎 Download on App Store]    [▶️ Get it on Google Play]

Small text: "Free to download. Join unlimited Spaces. Premium features available."

Secondary text: "Can't find the right Space? Create your own with AI →"

Trust reminder below:
"🔒 3D face verified | 🔐 E2EE messages, calls, files | 👁️ OTS ultra-secure | 💻 Open source | 📱 Hashed contacts"
```

### 10. Open Source / Developers Section (Before Footer)
```
Title: "Built for Developers. Verified by Community."

Content:
"We believe in transparency. That's why our frontend code is fully 
open source. Audit our encryption. Find bugs. Contribute improvements.

[🔗 View on GitHub]    [📖 Documentation]    [🐛 Report a Bug]

GitHub: github.com/[your-repo-link]

'We have nothing to hide because we literally can't see your data anyway.'"
```

### 11. Footer
- Logo: FRNDSAPP
- Links: Privacy Policy | Terms | Contact | About | GitHub
- Social icons (placeholder)
- Open Source badge/icon
- Copyright: © 2024 FRNDSAPP. All rights reserved.

---

## ⭐ MANDATORY: Privacy Policy Page (privacy.html)

**Create a separate privacy.html page with ALL these details. This is CRITICAL.**

### Page Structure:

```
# FRNDSAPP Privacy Policy

Last Updated: [Current Date]

At FRNDSAPP, privacy isn't just a feature - it's our foundation. 
We've built the most privacy-respecting social app in existence.

---

## Our Privacy Promise

"We literally CANNOT see your data. This is by design, not policy."

Unlike other apps that promise privacy but hold your data, 
FRNDSAPP is architecturally designed so that we CANNOT access 
your private information - even if we wanted to, even if compelled.

---

## 1. What We Collect (Minimal)

### Account Information
- Email or phone number (for authentication only)
- Your chosen display name
- Profile pictures (verified against your face)

### Verification Data
- 3D face liveness scan (stored securely, used ONLY for verification)
- This ensures no fake accounts and validates your profile pictures

### Space Participation
- Which Spaces you join
- Your public profile in those Spaces
- Your matching preferences (used for AI matching)

### Location (Optional, Privacy-Preserved)
- Approximate area for nearby matching (geohash, not exact coordinates)
- We show "3.2 km away" - NEVER your exact location
- You control when to share location

---

## 2. What We CANNOT See (By Design)

### End-to-End Encrypted Content
ALL of the following are encrypted on YOUR device and can ONLY be 
decrypted by the intended recipient:

✓ Text messages - We see encrypted blobs only
✓ Photos you share - Encrypted before upload
✓ Videos you share - Encrypted before upload
✓ Files & documents - Encrypted before upload
✓ Voice messages - Encrypted before upload
✓ Location sharing - Encrypted coordinates
✓ Audio calls - WebRTC E2EE, we never hear
✓ Video calls - WebRTC E2EE, we never see

We use the Signal Protocol - the same encryption trusted by 
journalists, activists, and security professionals worldwide.

### OTS (One-Time Secure) Messages
These are EXTRA secure:
- Encrypted end-to-end
- Camera verifies recipient in real-time
- Auto-delete after viewing
- We have ZERO access to content

---

## 3. Contact Sync - Hash Only

When you sync contacts to find friends:

┌─────────────────────────────────────────────────────────────┐
│ HOW CONTACT SYNC WORKS                                      │
├─────────────────────────────────────────────────────────────┤
│ 1. Your phone hashes each contact (one-way encryption)      │
│ 2. Only hash values are sent to our servers                 │
│ 3. We compare hashes with registered user hashes            │
│ 4. We return: "These hashes match existing users"           │
│ 5. Your app shows: "These contacts are on FRNDSAPP"         │
├─────────────────────────────────────────────────────────────┤
│ RESULT: We NEVER see names, numbers, or any contact info    │
│ We literally cannot extract your contact list from hashes   │
└─────────────────────────────────────────────────────────────┘

---

## 4. 3D Face Verification

### Why We Do It
- Ensures every user is a real human
- Prevents fake profiles and catfishing
- Validates that profile pictures are actually YOU

### How It Works
- One-time 3D liveness scan at registration
- Checks: depth, movement, blink, anti-spoofing
- No photos of photos, no masks, no screens
- Stored securely, used ONLY for verification

### Profile Picture Verification
- Every profile pic is compared to your verified face
- If the face doesn't match, the picture is rejected
- This prevents catfishing and fake photos

---

## 5. Location Privacy

### What We Know
- Approximate area (geohash) for nearby matching
- Example: "Downtown Seattle area" - NOT your address

### What We Show Others
- Distance only: "3.2 km away"
- NEVER your exact coordinates
- NEVER your address or precise location

### You Control It
- Location sharing is optional
- You can disable it anytime
- Spaces work without location too

---

## 6. Data Storage & Security

### Where Data Lives
- Encrypted messages: On your device + encrypted backup
- Account data: Secure cloud infrastructure (AWS)
- Face verification: Encrypted, isolated storage

### Security Measures
- All data encrypted at rest
- TLS encryption in transit
- Regular security audits
- No third-party analytics that track you

---

## 7. What We DON'T Do

❌ We don't sell your data - We have nothing to sell
❌ We don't show targeted ads - We can't, we don't have your data
❌ We don't read your messages - We literally cannot
❌ We don't share with third parties - Nothing to share
❌ We don't mine your contacts - We only see hashes
❌ We don't track your location history - Only current for matching
❌ We don't store message content - It's E2EE, we only see blobs

---

## 8. Your Rights

### Access Your Data
- Export your account information anytime
- See which Spaces you're in
- View your profile data

### Delete Your Data
- Delete your account completely
- All your data is removed
- Messages you sent remain encrypted (others keep their copy)

### Control Your Privacy
- Adjust location sharing
- Control who can message you
- Block users instantly

---

## 9. Open Source Transparency

Our frontend code is fully open source:
- GitHub: github.com/[your-repo-link]
- Audit our encryption implementation
- Verify our privacy claims
- Report security issues

"Don't trust us - VERIFY us."

---

## 10. OTS Messages - Extra Privacy

One-Time Secure messages have additional protections:

┌─────────────────────────────────────────────────────────────┐
│ OTS MESSAGE PRIVACY                                         │
├─────────────────────────────────────────────────────────────┤
│ 📷 Camera activates to verify recipient                     │
│ 👤 Only YOUR verified face can unlock                       │
│ 🚫 Blocks if you look away or move                         │
│ 🚫 Deletes if anyone else appears                          │
│ 📱 Works only on primary device                            │
│ 📸 Gray patterns blur screenshot attempts                   │
│ ⚠️ Sender notified if screenshot detected                  │
│ 💨 Auto-deletes after viewing                              │
├─────────────────────────────────────────────────────────────┤
│ RESULT: The most private way to share sensitive info        │
└─────────────────────────────────────────────────────────────┘

---

## 11. Children's Privacy

FRNDSAPP is not intended for users under 18.
3D face verification helps ensure age-appropriate usage.

---

## 12. Changes to This Policy

We'll notify you of significant changes via:
- In-app notification
- Email (if provided)

---

## 13. Contact Us

Questions about privacy?
- Email: privacy@frndsapp.com
- GitHub Issues: For security researchers

---

## Summary: The FRNDSAPP Privacy Difference

| What Others Do          | What FRNDSAPP Does           |
|-------------------------|------------------------------|
| Store your messages     | Can't read them (E2EE)       |
| See your contacts       | Only see hashes              |
| Track exact location    | Only approximate area        |
| Allow fake profiles     | 3D face verified only        |
| Sell your data          | Have nothing to sell         |
| Promise privacy         | Prove it with open source    |

"Privacy isn't our policy. It's our architecture."
```

---

## Technical Requirements

### Stack
- **HTML/CSS/JavaScript** (static site)
- **Modern CSS**: CSS Grid, Flexbox, CSS Variables, animations
- **Optional**: Use GSAP or AOS for scroll animations
- **Responsive**: Mobile-first, works on all devices
- **Performance**: Optimize images, lazy load, fast loading

### Animations
- Smooth scroll behavior
- Fade-in on scroll for sections
- Subtle hover effects on cards
- Gradient animation in hero background
- Optional: Particle or mesh gradient background

### Mobile Responsiveness
- Hamburger menu on mobile
- Stack cards vertically
- Adjust font sizes
- Touch-friendly CTAs

---

## Assets Needed

### Placeholder Images
- Phone mockups showing app interface
- App icon/logo (can create simple one with "F" or use text)
- Feature icons (use emoji or create SVGs)

### Store Badges
Use official Apple App Store and Google Play badges
(Replace with actual links when available)

---

## Sample Copy

### Meta Tags
```html
<title>FRNDSAPP - Find Your People. Verified. | 3D Face Verified | E2EE Everything</title>
<meta name="description" content="Join Spaces for dating, business, travel, hobbies - anything. 
Every user 3D face verified. Every message encrypted. Swipe right, start chatting instantly - 
no waiting for mutual matches. No fake profiles. Real connections.">
```

### Hero Copy Options
Option 1 (Recommended): "Find Your People. Verified."
Option 2: "Real People. Smart Matching. True Privacy."
Option 3: "Verified Humans. Real Connections."

### Key Messaging Points (emphasize throughout)

**THE CORE FLOW (Most Important!):**
1. "Join a Space → Fill profile via AI → See matches → Swipe → Chat!"
2. "Swipe right = Send message immediately. No mutual match needed!"
3. "Other person gets your message in 'New Matches' → Reply or Block"
4. "Reply = You're Frnds. Block = You disappear (no awkwardness!)"
5. "It's a messaging app with smart matching, not a dating app with chat"

**Space Creation:**
6. "Anyone can CREATE a Space - AI helps you build the schema"
7. "YOU define what questions to ask users who join"
8. "No coding needed - just chat with AI"

**Security & Privacy:**
9. "3D face verified - no fakes possible"  
10. "We literally cannot see ANYTHING - messages, calls, files"
11. "OTS: Camera ON while reading, auto-deletes"
12. "Profile pics verified against your real face"
13. "Contacts are HASHED - we never see your actual contacts"
14. "All chats & calls E2EE by default"
15. "Open source frontend - verify our code"

**Matching:**
16. "See distance on matches: '4.2 km away'"
17. "AI matches by meaning, not just keywords"

---

## Output

Create a complete, deployable static website with:

### Required Files:
1. `index.html` - Main landing page with hero animation
2. `privacy.html` - FULL privacy policy page (see section above - MANDATORY!)
3. `terms.html` - Terms of service page
4. `styles.css` - All styles (or use Tailwind if preferred)
5. `script.js` - Animations and interactions (especially hero phone animation!)
6. `/assets/` folder for images

### CRITICAL Requirements:
- ⭐ **Hero phone animation** showing the complete flow (create → AI builds → join → match → swipe → chat)
- ⭐ **Privacy page** with ALL details from section above
- ⭐ **One-way matching** messaging throughout (not like dating apps)
- ⭐ **All security features** prominently displayed
- ⭐ **Distance display** shown in examples ("3.2 km away")
- ⭐ **"New Matches" → "Frnds"** flow explained clearly

### Animation Requirements (script.js):
- Hero phone animation cycling through **3 Spaces** (Deal Room → Wedding → Flight)
- Each Space shows: Create → AI builds → Match → Chat/OTS
- Typing effect for chat messages
- Swipe gesture animation
- Smooth transitions between Spaces (fade or slide)
- Progress indicators (3 dots for 3 Spaces)
- **OTS-specific animations:**
  - Camera overlay appearing
  - Face verification checkmark
  - Gray line patterns (anti-screenshot)
  - "Deleted forever" poof/fade effect
- Total cycle: ~30-40 seconds, then loop
- Scroll-triggered animations for other sections

Make it beautiful, modern, and distinctive. Avoid generic templates!

---

## Inspiration Sites
- stripe.com
- linear.app
- notion.so
- raycast.com
- vercel.com

Create something that stands out and makes people want to download the app!

