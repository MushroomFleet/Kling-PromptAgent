# Text-to-Video Prompt Generation Module

## CORE STRUCTURE
```
Prompt = Subject (Subject Description) + Subject Movement + Scene (Scene Description) + (Camera Language + Lighting + Atmosphere)
```

## FORMAT SPECIFICATIONS
- Video Duration: 5-second or 10-second outputs
- Supported Aspect Ratios: 16:9, 9:16, 1:1

## COMPONENT REQUIREMENTS

### 1. SUBJECT & DESCRIPTION
- Main focus of the video
- Categories:
  - People
  - Animals
  - Plants
  - Objects
  - Environments

Required Details:
- Physical appearance
- Clothing/Accessories
- Facial features
- Body posture
- Distinctive characteristics

### 2. SUBJECT MOVEMENT
Critical for video generation. Must specify:
- Movement type (static/dynamic)
- Motion direction
- Speed/pace
- Interaction patterns
- Movement sequence
- Duration-appropriate actions (5-10 seconds)

### 3. SCENE & DESCRIPTION
Environment specifications:
- Foreground elements
- Background components
- Setting type:
  - Indoor scene
  - Outdoor setting
  - Natural environment
  - Urban environment
- Spatial relationships
- Scene scale

### 4. TECHNICAL ELEMENTS

#### Camera Language
- Shot types:
  - Ultra-wide angle
  - Close-up
  - Telephoto
  - Low-angle
  - High-angle
  - Aerial view
- Depth of field
- Camera movements:
  - Pan
  - Tilt
  - Dolly
  - Tracking
  - Zoom

#### Lighting
- Types:
  - Ambient lighting
  - Morning light
  - Sunset
  - Artificial lighting
- Effects:
  - Light interplay
  - Shadows
  - Tyndall effect

#### Atmosphere
- Mood elements
- Weather conditions
- Time of day
- Environmental effects
- Emotional tone

## TECHNICAL LIMITATIONS & TIPS

### Language and Structure
- Use simple words and sentence structures
- Avoid overly complex language
- Keep descriptions clear and straightforward

### Time and Content Constraints
- Aim for scenes completable within 5-10 seconds
- Keep visual content simple and focused
- Avoid complex sequences of events

### Model Capabilities

#### Current Limitations
- Numbers and counting are not reliably interpreted
  - Example: "10 puppies on the beach" may produce inconsistent results
- Complex physical movements are challenging
  - Avoid: Bouncing balls, high-altitude throws, complex trajectories
  - Stick to simpler, more static movements

#### Special Techniques
- For cultural styling:
  - Use terms like "Oriental mood," "China," or "Asia" for Chinese-style scenes
  - These keywords help generate culturally-specific aesthetics and characters

#### Multi-Scene Techniques
- Split-screen scenes can be specified:
  - Example: "4 camera angles, representing spring, summer, autumn, and winter"
- Use clear scene transitions
- Keep each scene component simple

## PROMPT PROGRESSION EXAMPLES

### Example: "Panda in Café" Scene
Let's examine how a prompt evolves through three levels of detail:

1. BASIC PROMPT
```
"A giant panda is reading a book in a café"
- Core elements only
- Lacks specific details
- Minimal scene context
```

2. INTERMEDIATE PROMPT
```
"A giant panda wearing black-framed glasses is reading a book in a café, with the book placed on the table. On the table, there is also a cup of coffee emitting steam, and next to it is the café's window."
- Added character details (glasses)
- Specified object placement
- Included environmental elements
- Added atmospheric details (steam)
```

3. CINEMATIC PROMPT
```
"In the shot, a medium shot with a blurred background and ambient lighting captures a scene where a giant panda, adorned with black-framed glasses, is reading a book in a café. The book rests on the table, accompanied by a cup of coffee that's steaming gently. Beside the cozy setting is the café's window, with a cinematic color grading applied to enhance the visual appeal."
- Added camera specifications
- Included lighting details
- Enhanced atmosphere description
- Specified visual style
- Professional finishing touches
```

## PROMPT ENHANCEMENT LADDER

### Level 1: Basic Structure
- Subject + Action + Location
- Clear but minimal detail
- Foundational elements only

### Level 2: Detailed Description
- Subject characteristics
- Object relationships
- Environmental context
- Atmospheric elements
- Spatial relationships

### Level 3: Technical Enhancement
- Camera angles and shots
- Lighting specifications
- Visual effects
- Color grading
- Professional finishing touches

## PRACTICAL USAGE TIPS

### Formula Application
- The formula serves as a guide, not a strict rule
- Feel free to communicate boldly and imaginatively
- Experimentation beyond the formula may yield surprising results

### Creative Freedom
1. Don't feel constrained by rigid structures
2. Balance formula guidance with creative expression
3. Allow for imaginative interpretation
4. Explore unique combinations of elements

### Best Practices for Reliability
1. Keep movements simple and natural
2. Avoid specific numerical quantities
3. Use clear cultural or style indicators
4. Break complex scenes into simple components
5. Focus on achievable visual effects

## VALIDATION CHECKLIST
Basic Level:
- [ ] Core subject identified
- [ ] Basic action described
- [ ] Location specified

Intermediate Level:
- [ ] Subject details added
- [ ] Object relationships defined
- [ ] Environmental context included
- [ ] Atmospheric elements present

Professional Level:
- [ ] Camera specifications included
- [ ] Lighting details defined
- [ ] Visual style specified
- [ ] Professional effects described

## COMMON PITFALLS TO AVOID
1. Over-complicated movement sequences
2. Too many scene changes
3. Conflicting camera movements
4. Unrealistic timing
5. Incompatible lighting scenarios
6. Overcrowded scenes
7. Complex physical movements
8. Specific numerical quantities
9. Overly detailed technical specifications

## OPTIMIZATION TIPS
1. Keep movements simple and clear
2. Ensure actions fit within time constraint
3. Make scene descriptions concise
4. Balance technical detail with clarity
5. Consider aspect ratio requirements
6. Maintain visual continuity
7. Use simple language structures
8. Focus on achievable effects
