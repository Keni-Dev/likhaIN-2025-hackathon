# LikhaIN 2025 Hackathon - Base Template Prompt System

## 🎯 PART 1: PROJECT DISCOVERY & SPECIFICATION

**Instructions for Team Leader**: Copy and paste this entire section to Claude AI. The AI will ask clarifying questions, you answer them, and then it will generate detailed project specifications.

---

### PART 1 PROMPT (Copy everything below this line)

```
I am the team leader for a 4-person team competing in the LikhaIN 2025 Hackathon. We have 12 hours (8 PM - 8 AM) to build a Smart City solution. We are beginners and will use AI to help generate code.

TEAM COMPOSITION:
- Person 1: Frontend (Primary)
- Person 2: Frontend + Backend (Bridge role)
- Person 3: Backend (Primary)
- Person 4: Backend Support + Integration
- All 4 members will contribute to the pitch deck and presentation

TECH STACK PREFERENCE:
- Frontend: React + Tailwind CSS
- Backend: Node.js + Express
- Database: Firebase (for speed and ease)
- Deployment: Vercel (frontend) + Railway/Render (backend if needed)

PROBLEM AREA WE'RE INTERESTED IN:
[INSERT YOUR CHOSEN PROBLEM AREA - e.g., "Flood Management and Emergency Response"]

INITIAL SOLUTION IDEA:
[INSERT YOUR INITIAL IDEA - e.g., "A real-time flood monitoring and evacuation routing app with citizen reporting"]

TARGET USERS:
[INSERT WHO WILL USE THIS - e.g., "Residents in flood-prone areas, LGU disaster response teams"]

MUST-HAVE FEATURES (MVP):
[LIST 3-5 CORE FEATURES - e.g., 
1. Real-time flood level map with citizen reports
2. Smart evacuation route finder
3. Emergency alert system
4. LGU dashboard for monitoring]

NICE-TO-HAVE FEATURES (If time permits):
[LIST 2-3 ADDITIONAL FEATURES - e.g.,
1. Historical flood data visualization
2. Community forum
3. SMS integration]

AVAILABLE APIS/DATA SOURCES:
[LIST ANY APIS YOU PLAN TO USE - e.g., "Google Maps API, PAGASA weather data, Firebase for database"]

CONSTRAINTS & CONSIDERATIONS:
- We have exactly 12 hours to build this
- We are beginners, so code should be well-commented
- We need a working demo for judges
- Must be web-based (accessible on any device)
- Should work even with slow internet

Please ask me ANY clarifying questions you need to create a comprehensive technical specification for this project. Consider:
- Technical feasibility within 12 hours
- Feature prioritization
- Data structure and flow
- User experience flows
- Integration points
- Potential challenges
- What can realistically be built by beginners with AI assistance
```

---

## 🎯 PART 2: IMPLEMENTATION GUIDE GENERATOR

**Instructions for Team Leader**: After getting the detailed project specifications from Part 1, copy those specifications along with this Part 2 prompt. Claude AI will then generate a complete phase-by-phase implementation guide with ready-to-use prompts.

---

### PART 2 PROMPT (Copy everything below this line)

```
Based on the project specifications above, please create a COMPLETE PHASE-BY-PHASE IMPLEMENTATION GUIDE for our 4-person hackathon team.

TIMELINE: 12 hours (8 PM - 8 AM, November 12-13, 2025)

TEAM ROLES:
- **Person 1 (Frontend Lead)**: UI components, styling, responsive design
- **Person 2 (Full Stack Bridge)**: Frontend logic, API integration, some backend support
- **Person 3 (Backend Lead)**: Server setup, database design, API endpoints
- **Person 4 (Backend Support + Integration)**: Third-party APIs, deployment, testing

OUTPUT REQUIREMENTS:

Create a guide with the following structure:

## PHASE 0: SETUP & INITIALIZATION (8:00 PM - 9:00 PM)
### For Everyone:
- Repository setup instructions
- Project structure creation
- Environment configuration
- Initial dependencies installation

Provide a **COPY-PASTE READY PROMPT** for setting up:
1. Frontend boilerplate
2. Backend boilerplate
3. Git workflow setup

---

## PHASE 1: CORE FOUNDATION (9:00 PM - 12:00 AM)

### Section A: Person 1 - Frontend UI Foundation
**Time Allocation**: 3 hours

For each step, provide:
1. A clear description of what to build
2. A **COPY-PASTE READY PROMPT** to send to AI for code generation
3. List of expected file outputs
4. Testing checkpoints

**Step 1.1**: [Description]
**AI Prompt to Use**:

[Detailed prompt that Person 1 can copy-paste to Claude AI]

**Expected Output Files**: 
- `filename1.jsx`
- `filename2.css`

**How to Test**: [Simple testing instructions]

**Step 1.2**: [Continue pattern]

---

### Section B: Person 2 - Frontend Logic & State Management
**Time Allocation**: 3 hours

[Same detailed structure as Section A]

---

### Section C: Person 3 - Backend Core & Database
**Time Allocation**: 3 hours

[Same detailed structure as Section A]

---

### Section D: Person 4 - Third-Party Integrations Setup
**Time Allocation**: 3 hours

[Same detailed structure as Section A]

---

## PHASE 2: INTEGRATION & FEATURE COMPLETION (12:00 AM - 4:00 AM)

[Same structure, with integration steps for all 4 team members]

---

## PHASE 3: TESTING & POLISH (4:00 AM - 6:00 AM)

[Testing procedures, bug fixing guide, UI polish]

---

## PHASE 4: DEPLOYMENT & DEMO PREP (6:00 AM - 8:00 AM)

[Deployment steps, demo script creation, backup plans]

---

## GIT WORKFLOW GUIDE

Provide detailed Git commands for:
1. Initial clone and setup
2. Branch creation for each person
3. Commit frequency (every hour)
4. Pull request and merge process
5. Conflict resolution basics
6. Emergency rollback commands

---

## TROUBLESHOOTING GUIDE

For each phase, list:
- Common errors beginners might encounter
- Quick fixes
- Where to ask for help (which AI prompt to use)

---

## PROMPT OPTIMIZATION TIPS

For each AI code generation prompt you create, ensure:
1. It includes all necessary context (which libraries are available, coding style)
2. It specifies file names and structure
3. It requests code comments for beginners
4. It asks for error handling
5. It requests sample data/test cases
6. It reminds AI about mobile-first design (if frontend)
7. It asks for console.log statements for debugging

---

CRITICAL REQUIREMENTS:
- Every step must have a ready-to-use AI prompt
- Each prompt should generate complete, working code
- Include fallback solutions if something doesn't work
- Keep language simple for beginners
- Each phase should have clear "DONE" checkpoints
- Include hourly standup check-in prompts
- Provide backup plans if a feature is too complex

Begin creating the complete implementation guide now.
```

---

## 📋 HOW TO USE THIS TEMPLATE SYSTEM

### Step-by-Step Usage:

**1. BEFORE THE HACKATHON (November 2-11)**
   - Decide on your problem area and initial idea
   - Fill in your answers to Part 1 prompt
   - Test the system with Claude AI to see what questions come up

**2. DAY 1 - AFTER PROBLEM REVEAL (November 12, 5:00-7:00 PM)**
   - If your chosen problem aligns with what's revealed, great!
   - If not, quickly adapt Part 1 with the new problem
   - Leader sends Part 1 to Claude AI
   - Leader answers all clarifying questions
   - Save the detailed specifications

**3. DINNER BREAK (7:00-8:00 PM)**
   - Leader combines specifications + Part 2 prompt
   - Send to Claude AI
   - Receive complete implementation guide
   - Team reviews together during dinner
   - Each person saves their section

**4. DURING CODING SPRINT (8:00 PM - 8:00 AM)**
   - Each person follows their section step-by-step
   - Copy-paste AI prompts as provided
   - Commit code every hour
   - Check in as a team every 2 hours

**5. FINAL HOURS (6:00 AM - 8:00 AM)**
   - Follow deployment and demo prep section
   - All 4 work on pitch deck together
   - Practice presentation

---

## 🔧 EXAMPLE WALKTHROUGH

Here's a mini example to show you how it works:

### Example: Flood Monitoring App

**PART 1 FILLED OUT:**
```
PROBLEM AREA: Flood Management
SOLUTION: Real-time flood monitoring with citizen reporting
TARGET USERS: Residents and LGU officials
MUST-HAVE: Map, citizen reports, alerts, evacuation routes
APIS: Google Maps, Firebase
```

**AI ASKS CLARIFYING QUESTIONS:**
- "Should users need to create accounts or allow anonymous reporting?"
- "What data fields for each flood report?"
- "How should evacuation routes be calculated?"
[Leader answers these]

**AI GENERATES SPECIFICATIONS:**
- Complete data schema
- API endpoint structure  
- Component hierarchy
- Feature prioritization
- Time estimates

**PART 2 GENERATES THIS TYPE OF OUTPUT:**

```
## PHASE 1, STEP 1.1: Create Map Component

**Person 1 - Frontend Lead**

**What to Build**: A full-screen map component using React and Google Maps that displays the user's current location.

**AI Prompt to Copy-Paste**:
---
I'm building a React component for a flood monitoring app. I need:

1. A MapComponent.jsx file that:
   - Uses @react-google-maps/api library
   - Shows a full-screen Google Map
   - Centers on user's current location (use geolocation API)
   - Has zoom level 13
   - Includes error handling if location access denied
   - Uses Tailwind CSS for styling
   - Has a loading spinner while map loads
   - Is mobile-responsive

2. Environment variable setup for Google Maps API key

3. Add detailed comments explaining each part (I'm a beginner)

4. Include console.log statements for debugging

Please provide:
- Complete MapComponent.jsx code
- .env.example file showing required variables
- Instructions on where to place this component

Use functional components with hooks. Style with Tailwind CSS classes only.
---

**Expected Output Files**:
- `src/components/MapComponent.jsx`
- `.env.example`
- Instructions document

**How to Test**:
1. Run `npm start`
2. Open browser to localhost:3000
3. Should see map centered on your location
4. Check browser console for any errors

**Git Commands**:
```bash
git add src/components/MapComponent.jsx .env.example
git commit -m "Add map component with geolocation"
git push origin person1-frontend
```

**If It Doesn't Work**:
- Check if Google Maps API key is valid
- Look in console for error messages
- Try this backup prompt: [simpler version provided]
```

---

## ⚡ QUICK TIPS FOR SUCCESS

1. **Don't Skip Part 1**: The clarifying questions are crucial. The better your specifications, the better your implementation guide.

2. **Print Your Section**: Each person should print or have their section open on a second screen.

3. **One Prompt at a Time**: Don't rush. Complete one step fully before moving to the next.

4. **Commit Often**: After each working piece of code, commit immediately.

5. **Test Before Integrating**: Make sure your individual pieces work before combining.

6. **Ask for Simpler Versions**: If generated code is too complex, ask AI: "Can you simplify this for a beginner?"

7. **Keep Backups**: Save all AI-generated code in a separate folder as backup.

8. **Don't Be Perfectionist**: Working > Perfect. Ship features that work.

---

## 🆘 EMERGENCY FALLBACK PROMPTS

If something isn't working and you're stuck:

### For Frontend Issues:
```
I'm getting this error: [paste error]
My code is: [paste code]
I'm a beginner working on a hackathon project with 12 hours left.
Please provide a simple fix with explanation.
```

### For Backend Issues:
```
My API endpoint isn't working. 
Error: [paste error]
Expected behavior: [describe]
Current code: [paste]
Please provide debugging steps and a fix.
```

### For Integration Issues:
```
I'm trying to connect my frontend to backend.
Frontend code: [paste]
Backend endpoint: [describe]
Error: [paste]
Please show me exactly what to change and where.
```

---

## 📊 SUCCESS CHECKLIST

Before moving to next phase, verify:

**Phase 0 Complete:**
- [ ] All 4 team members can push/pull from Git
- [ ] Frontend runs on localhost
- [ ] Backend server starts without errors
- [ ] Firebase connection works
- [ ] All APIs have keys and are tested

**Phase 1 Complete:**
- [ ] Basic UI components render
- [ ] Database schema is set up
- [ ] At least 1 API endpoint works
- [ ] Team can see each other's progress

**Phase 2 Complete:**
- [ ] Frontend connects to backend successfully
- [ ] Core features work end-to-end
- [ ] Data saves and retrieves correctly
- [ ] No critical bugs

**Phase 3 Complete:**
- [ ] App works on mobile browser
- [ ] All MVP features functional
- [ ] Demo script ready
- [ ] Screenshots/video backup created

**Phase 4 Complete:**
- [ ] App is deployed and accessible
- [ ] Pitch deck finished
- [ ] Presentation practiced 3+ times
- [ ] Q&A responses prepared

---

## 🎤 PITCH DECK COLLABORATIVE PROMPT

After coding is done, use this for all 4 members:

```
We just finished building [app name] for a Smart City hackathon. We need to create a 10-slide pitch deck.

PROJECT DETAILS:
- Problem: [brief description]
- Solution: [our app]
- Key Features: [list]
- Tech Used: [stack]
- Target Users: [who]

JUDGING CRITERIA:
- Innovation & Creativity (30%)
- Relevance & Impact (25%)
- Feasibility (20%)
- Clarity & Organization (15%)
- Scalability (10%)

Please create:
1. Slide-by-slide outline with content suggestions
2. Design tips for each slide
3. Speaking notes for presentation
4. Anticipated Q&A with suggested answers

Team roles:
- Person 1: Presents problem & solution
- Person 2: Demonstrates app
- Person 3: Explains technical architecture
- Person 4: Discusses impact & scalability

Make it compelling but authentic. We're beginners, so keep language accessible.
```

---

## 🎯 FINAL MOTIVATION

Remember:
- This template is your guide, not a rigid script
- Adapt as needed during the hackathon
- Communication is more important than perfect code
- A working simple solution beats a broken complex one
- You've prepared more than most teams
- Trust the process, trust your team

**Good luck! You've got this! 🚀**
