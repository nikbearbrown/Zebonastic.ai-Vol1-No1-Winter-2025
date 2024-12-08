# Prompt Templates for Midjourney

## Introduction
Creating effective prompts for Midjourney is both an art and a science. This chapter equips you with actionable strategies, practical templates, and exercises to help you approach prompt engineering systematically. With these techniques, you can achieve more consistent, creative, and high-quality results in your AI-assisted design journey.

---

## Basic Template Structure

Midjourney prompts have several core components that act as building blocks for generating specific outputs. Understanding and mastering these elements is key to building effective templates.

### Core Components:

1. **Subject**
   - **Main Focus**: The core object, character, or element in the image.
   - **Key Attributes**: Details like color, age, or defining features.
   - **Actions/Poses**: The behavior or posture of the subject.

2. **Environment**
   - **Setting**: The context or location where the subject exists.
   - **Lighting Conditions**: Natural light, studio setup, dramatic contrasts, etc.
   - **Atmosphere**: The mood or emotional tone of the scene.

3. **Style**
   - **Artistic Medium**: Photorealism, oil painting, digital art, etc.
   - **Technical Approach**: Level of abstraction, realism, or surrealism.
   - **Reference Artists**: Specific styles (e.g., Van Gogh, Moebius).

4. **Technical Parameters**
   - **Aspect Ratio**: Frame dimensions (e.g., --ar 16:9 for widescreen).
   - **Image Quality**: Defines rendering detail (--q 1 to --q 5).
   - **Style Weights**: Degree of influence (--s 0-1000).

---

## Practical Templates

Below are detailed templates for common use cases, along with examples inspired by fictional characters from literature, mythology, and fairy tales.

### Template 1: Character Portraits
```plaintext
/imagine "a [character] in [pose/action], [artistic style], [lighting], [mood], [camera angle]" --ar 2:3 --q 2
```
**Example**:
- "a contemplative King Arthur holding Excalibur, medieval illuminated manuscript style, soft golden light, regal and stoic mood, low angle shot" --ar 2:3 --q 2

---

### Template 2: Environmental Scenes
```plaintext
/imagine "[environment description], [time of day], [weather], [artistic style], [composition notes]" --ar 16:9
```
**Example**:
- "the Enchanted Forest from Snow White, dawn breaking, misty and glowing, classical storybook illustration style, wide panoramic view" --ar 16:9

---

### Template 3: Product Visualization
```plaintext
/imagine "[product] in [setting], [lighting setup], [style], [detail level], [perspective]" --ar 4:5 --q 2
```
**Example**:
- "Cinderella's glass slipper displayed on a royal cushion, spotlight in a lavish ballroom, hyperrealistic product photography style, intricate crystal reflections, close-up shot" --ar 4:5 --q 2

---

## Hands-On Exercises

### Exercise 1: Style Exploration
1. Choose a subject from mythology or fairy tales (e.g., "a golden apple from Greek mythology").
2. Create variations using different styles:
   - **Photorealistic**: "a golden apple with glowing aura, photorealistic style, soft shadows" --ar 4:5
   - **Illustrated**: "a golden apple with engraved patterns, whimsical storybook illustration style" --ar 4:5
   - **Abstract**: "a golden apple represented by shimmering geometric shapes, cubist art style" --ar 4:5

3. Analyze the differences in mood, tone, and detail.

---

### Exercise 2: Mood Development
Use the same subject and environment but experiment with different emotional tones.

**Template**:
```plaintext
"[subject] in [environment], [lighting], [mood]"
```

**Examples**:
1. **Peaceful**: "Sleeping Beauty resting in her enchanted castle, morning sunlight, tranquil mood, soft pastel colors"
2. **Dramatic**: "Hercules battling the Nemean Lion in a rocky gorge, stormy skies, intense mood, high-contrast lighting"
3. **Mysterious**: "a shadowy figure of the Pied Piper leading children through a misty forest, eerie atmosphere, muted tones"

---

### Exercise 3: Technical Parameter Testing
Experiment with different parameters to understand their impact.

1. **Quality Testing**:
   - "--q 1": Faster generation with basic details.
   - "--q 2": Higher detail for intricate images.

2. **Style Weights**:
   - "--s 50": Subtle stylistic influence.
   - "--s 750": Strong adherence to a specific style.

3. **Chaos Testing**:
   - "--c 0": Consistent, predictable outputs.
   - "--c 100": Highly varied and experimental results.

4. **Aspect Ratios**:
   - "--ar 16:9": Widescreen cinematic look.
   - "--ar 1:1": Balanced square compositions.

---

## Advanced Tips

### Combining Multiple Influences
Blend multiple artistic styles for unique results.
```plaintext
/imagine "[subject] in the style of [artist1] meets [artist2], [medium] with [influences]"
```
**Example**:
- "a depiction of Icarus soaring towards the sun in the style of Michelangelo meets Hayao Miyazaki, oil painting with anime influences"

---

### Emphasizing Specific Elements
Use weight modifiers (`::`) for emphasis.
```plaintext
/imagine "Medusa ::2, with her snake hair ::1, in the style of Art Nouveau" --ar 2:3
```

---

## Recommended AI Tools

1. **Primary Tools**:
   - **Midjourney**: Core platform for AI art.
   - **Discord**: Interface for running prompts.
   - **PromptHero**: Inspiration for prompt writing.

2. **Support Tools**:
   - **Canva**: Post-processing and graphic design.
   - **Pinterest**: Collect visual references.
   - **Adobe Color**: Plan color palettes.

3. **Automation**:
   - **Zapier**: Automate prompt submissions.
   - **Airtable**: Manage template libraries.
   - **GitHub**: Track revisions.

---

## Project: Building Your Template Library

### Week 1: Experimentation
- Create at least three templates (character, environment, product) inspired by literary or mythological figures.
- Test variations and document results.

### Week 2: Refinement
- Identify successful patterns.
- Add advanced techniques (e.g., combining influences, weight modifiers).

### Week 3: Workflow Optimization
- Automate prompt organization.
- Develop a personal style guide.
- Share templates with peers for feedback.

---

## Success Metrics
Evaluate your progress with the following criteria:
- **Consistency**: Generate repeatable results.
- **Efficiency**: Reduce iteration time.
- **Creativity**: Expand your artistic range.
- **Quality**: Improve technical detail.
- **Flexibility**: Adapt prompts to different scenarios.

---

## Conclusion
Prompt templates are the foundation for mastering AI-assisted art in Midjourney. By experimenting with structured approaches and drawing inspiration from literature, mythology, and fairy tales, you can unlock your creativity, streamline your workflow, and achieve professional-quality results. Let these exercises and examples inspire your next creative project!

