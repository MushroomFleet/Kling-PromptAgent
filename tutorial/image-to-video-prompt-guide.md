# Image-to-Video Prompt Generation Guide

## CORE FORMULA
```
Prompt = Subject + Movement, Background + Movement
```

## PRIMARY PRINCIPLES
1. Focus on subjects and their movements
2. Scene is pre-provided by the image
3. List multiple subjects and movements sequentially
4. Describe actions explicitly and clearly

## CRITICAL LIMITATIONS & TIPS

### Language Requirements
- Use simple words and sentence structures
- Avoid complex or elaborate language
- Keep descriptions straightforward and clear

### Physics & Movement Constraints
1. Movements must comply with physics laws
2. Describe movements likely to occur in the image context
3. Avoid complex physical movements such as:
   - Bouncing balls
   - High-altitude throws
   - Complex trajectories
   - Physics-heavy interactions

### Scene Continuity
1. Stay within image context
2. Major deviations may trigger:
   - Unwanted camera cuts
   - Unexpected transitions
   - Scene disruptions
3. Maintain visual consistency with original image

## ANALYSIS PROTOCOL

### 1. IMAGE ASSESSMENT
EXECUTE:
1. Identify all subjects in the image
2. Note their current positions/states
3. Determine scene/background context
4. Recognize existing visual elements

### 2. SUBJECT IDENTIFICATION
ANALYZE:
- Main subjects
- Secondary subjects
- Their relationships
- Current state/pose

CATEGORIES:
- People
- Animals
- Plants
- Objects
- Artworks
- Natural elements

### 3. MOVEMENT SPECIFICATION
RULES:
1. Describe movements explicitly
2. Connect actions to specific subjects
3. Use clear, direct language
4. Maintain logical movement flow

STRUCTURE:
```
[Subject] [Action Verb] [Movement Description] with [Additional Detail]
```

## SPECIAL CONSIDERATIONS

### Artwork Animation
When working with paintings/artworks:
1. Specify subject-action relationships clearly
2. Describe movements in relation to the artwork context
3. Account for artistic medium constraints
4. Consider visual style continuity

Example:
- INCORRECT: "wear sunglasses"
- CORRECT: "Mona Lisa puts on sunglasses with her hand"

### Multiple Subject Handling
For scenes with multiple subjects:
1. List actions sequentially
2. Maintain clear subject-action pairs
3. Consider interaction patterns
4. Preserve scene coherence

Example:
```
"Mona Lisa puts on sunglasses with her hand, and a ray of light appears in the background"
```

## TECHNICAL GUIDELINES

### Movement Types
1. Direct Physical Actions
   - Clear subject movement
   - Specific motion paths
   - Defined interactions

2. Environmental Changes
   - Background movements
   - Lighting shifts
   - Atmospheric effects

3. Camera Movements
   - Pan across scene
   - Focus changes
   - Perspective shifts

### Movement Feasibility
VERIFY:
1. Physical plausibility
2. Contextual appropriateness
3. Technical limitations
4. Scene consistency

AVOID:
1. Complex physics interactions
2. Unrealistic movements
3. Actions beyond current capabilities
4. Scene-breaking transitions

### Common Pitfalls
AVOID:
1. Vague movement instructions
2. Disconnected subject-action pairs
3. Overly complex sequences
4. Ambiguous subject references
5. Static descriptions

## VALIDATION CHECKLIST
- [ ] All subjects clearly identified
- [ ] Movements explicitly described
- [ ] Actions logically connected
- [ ] Sequence properly ordered
- [ ] Background elements considered
- [ ] Physics requirements met
- [ ] Language simplicity maintained
- [ ] Scene continuity preserved

## PROMPT CONSTRUCTION METHOD

### Step 1: Subject Analysis
```
Identify: [Main Subject], [Secondary Subjects]
State: Current position/state
Note: Visual characteristics
```

### Step 2: Movement Planning
```
Define: [Subject] + [Movement]
Sequence: Primary action → Secondary actions
Connect: Subject-movement relationships
```

### Step 3: Integration
```
Combine: Subject + Movement pairs
Add: Background elements if needed
Verify: Logical flow and coherence
```

## EXAMPLE PATTERNS

### Single Subject:
```
"[Subject] [performs action] with [movement detail]"
```

### Multiple Subjects:
```
"[Subject1] [action1], while [Subject2] [action2]"
```

### Complex Scene:
```
"[Subject1] [action1] with [detail], and [Subject2] [action2] in [location]"
```

## ERROR PREVENTION
1. Always connect subjects to specific actions
2. Maintain visual context from original image
3. Keep movement descriptions clear and achievable
4. Consider spatial relationships
5. Respect artistic medium constraints
6. Verify action feasibility
7. Use simple language
8. Stay within physics constraints
9. Avoid scene-breaking transitions
