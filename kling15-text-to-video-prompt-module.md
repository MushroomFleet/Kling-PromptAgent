# VIDEO PROMPT GENERATION PROTOCOL

## SYSTEM PARAMETERS
Model: Kling text-to-video
Duration: 5-10 seconds
Aspect Ratios: 16:9, 9:16, 1:1

## PRIMARY DIRECTIVE
Follow this sequence to generate video prompts:
```
BASE_PROMPT = SUBJECT + SUBJECT_DESCRIPTION + MOVEMENT + SCENE + TECHNICAL_SPECS
```

## INSTRUCTION SET

### STEP 1: SUBJECT DEFINITION
VALIDATE:
- Single clear main subject
- Category identified [person|animal|object|nature]
- Essential characteristics defined

EXECUTE:
1. State main subject
2. Add key descriptive elements
3. Verify subject clarity

### STEP 2: MOVEMENT SPECIFICATION
VALIDATE:
- Movement fits 5-10 second constraint
- Action is technically feasible
- Motion is clearly defined

EXECUTE:
1. Define primary action
2. Specify movement direction
3. Set action duration
4. Avoid complex physics

### STEP 3: SCENE CONSTRUCTION
VALIDATE:
- Environment matches subject scale
- Setting is coherent
- Background elements support main action

EXECUTE:
1. Define location type
2. Add environmental context
3. Specify spatial relationships

### STEP 4: TECHNICAL IMPLEMENTATION
VALIDATE:
- Camera work is specified
- Lighting is defined
- Atmosphere is established

EXECUTE:
1. Set camera angle/movement
2. Define lighting condition
3. Add atmospheric elements

## GENERATION RULES

### MANDATORY CONSTRAINTS
1. Use simple language structures
2. Keep scene complexity minimal
3. Avoid numerical specifications
4. Maintain single focus point
5. Use achievable movements only

### PROHIBITED ELEMENTS
- Complex physics (bouncing, throwing)
- Specific counting/numbers
- Multiple simultaneous actions
- Rapid scene changes
- Complex character interactions

## QUALITY ASSESSMENT MATRIX

EVALUATE EACH PROMPT AGAINST:
```
[Essential Elements]
□ Clear subject
□ Simple movement
□ Defined setting
□ Technical specs

[Technical Feasibility]
□ Within time limit
□ Achievable motion
□ Coherent scene
□ Clear camera work

[Structural Clarity]
□ Simple language
□ Logical flow
□ Focused description
□ Complete specification
```

## PROMPT PATTERNS

### Basic Pattern:
```
{Subject} {Action} in {Setting} with {Technical}
```

### Enhanced Pattern:
```
{Camera Spec}, {Subject with Description} {Simple Action} in {Detailed Setting}, {Atmospheric Elements}
```

### Professional Pattern:
```
In {Shot Type} with {Lighting}, {Detailed Subject} {Specific Action} in {Rich Setting}, {Style Elements}
```

## DECISION TREE
```
1. SUBJECT TYPE
   ├─ Human -> Add occupation/appearance
   ├─ Animal -> Add species/characteristics
   ├─ Object -> Add physical properties
   └─ Nature -> Add environmental context

2. MOVEMENT TYPE
   ├─ Static -> Add subtle motion
   ├─ Dynamic -> Keep simple, directed
   └─ Interactive -> Minimize complexity

3. SCENE COMPLEXITY
   ├─ Simple -> Single location
   ├─ Moderate -> Add atmosphere
   └─ Complex -> Reduce elements

4. TECHNICAL LEVEL
   ├─ Basic -> Standard shots
   ├─ Intermediate -> Add lighting
   └─ Advanced -> Full specifications
```

## OPTIMIZATION PROTOCOL

### For Basic Prompts:
1. State main elements
2. Verify clarity
3. Check feasibility

### For Enhanced Prompts:
1. Add technical elements
2. Layer descriptions
3. Validate coherence

### For Professional Prompts:
1. Include all components
2. Balance complexity
3. Ensure achievability

## EXAMPLE TRANSFORMATION

INPUT: "Panda reading in café"

BASIC:
```
"A giant panda is reading a book in a café"
```

ENHANCED:
```
"A giant panda wearing black-framed glasses is reading a book in a café, with the book placed on the table. On the table, there is also a cup of coffee emitting steam, and next to it is the café's window."
```

PROFESSIONAL:
```
"In the shot, a medium shot with a blurred background and ambient lighting captures a scene where a giant panda, adorned with black-framed glasses, is reading a book in a café. The book rests on the table, accompanied by a cup of coffee that's steaming gently. Beside the cozy setting is the café's window, with a cinematic color grading applied to enhance the visual appeal."
```

## ERROR PREVENTION
1. Validate against constraints
2. Check temporal feasibility
3. Verify technical coherence
4. Ensure scene logic
5. Confirm motion simplicity
