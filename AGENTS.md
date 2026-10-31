# AGENTS.md — Sacred Community Slide Deck Guidelines

> **Project:** Systematic Study of HH Bhakti Tirtha Swami’s *Reflections on Sacred Teachings V: Śrīla Bhaktisiddhānta Sarasvatī’s Sixty-four Principles for Community*  
> **Speaker:** HH Bhakti Dhira Damodara Swami Maharaja  
> **Course:** Sacred Community Course  
> **Directory Convention:** In-progress decks in `slides/`, completed & finalized decks in `slides/ready/`.

---

## 1. Core Philosophy & Golden Rules

1. **Strict Content Loyalty (95%+ Verbatim Rule):**
   - When the user pastes or assigns text for a day's Principle or Q&A, **use only that specific text**.
   - **Never import outside text, distant Q&As, or other chapters from the EPUB** into the teaching slides unless the user explicitly provides or requests it.
   - Minor trimming, bulleting, and paragraph splitting for slide legibility are allowed, but do not paraphrase loosely, alter meaning, invert thoughts, or invent philosophical bridges.

2. **No Slide Overcrowding:**
   - Slides have limited physical space on a projector/screen.
   - Maximum **2 to 3 concise paragraphs** per slide.
   - If content for an answer or theme is long, either condense it while preserving verbatim phrases or split it logically across paired slides.

3. **Do Not Spoil Solutions in Diagnostic Slides:**
   - Slide 2 ("The Root of the Problem") must diagnose the conditioning, illusion, or ego trap.
   - Never reveal the spiritual solution or Principle on Slide 2; let the disease be diagnosed first so the Principle on Slide 3 shines as the antidote.

---

## 2. Standard Principle Deck Architecture (Days with Principles)

Standard length: **8 to 11 slides**.

```
Slide 1: Title Slide
Slide 2: The Root of the Problem (Diagnosing the Disease) - ONLY where possible
Slide 3: Core Principle & Vision (Śrīla Bhaktisiddhānta Sarasvatī's Injunction)
Slides 4–6/7: Unpacking the Philosophy
Slides 7–8 or only 8: Living Example(s) (Ācāryas & Sacred Narratives)
Slide 9: Vaishnava Sangha (Heart-to-Heart Reflection)
Slide 10: From Hearing to Living (Live Exercise + Kartik Sadhana)
```

### Detailed Slide Specifications:

#### Slide 1: Title Slide
```markdown
# Day XX Slide Deck: [Catchy Theme / Title] (Principle X / Principles X & Y)
---

## Slide 1: Title Slide
### **Sacred Community Course**

**Day XX: [Theme / Title]**  
Systematic Study of Principle X: *[Exact verbatim text of Śrīla Bhaktisiddhānta's Principle]*

**Speaker:** HH Bhakti Dhira Damodara Swami Maharaja  
**Course Text:** *Reflections on Sacred Teachings V* (Principle X)
```

#### Slide 2: The Root of the Problem
- **Purpose:** Diagnoses the underlying ego trap, material conditioning, or relational friction (e.g., why do we criticize? why do we get offended? why do we seek credit?).
- **Exception:** Do not force an artificial problem slide on purely visionary, ecstatic principles (e.g., Principle 1 *param vijayate śrī-kṛṣṇa-saṅkīrtanam* or Principle 8 *Spiritual Embassies*). Let those flow naturally.

#### Slide 3: Core Principle & Vision
- Prominently states Principle X in bold/quotes.
- Highlights Śrīla Bhaktisiddhānta Sarasvatī’s high transcendental standard.

#### Slides 4 to 6 (or 7): Deep Dive / Systematic Breakdown
- Extracts the core teachings from Bhakti Tirtha Swami’s commentary.
- Uses clear, thematic subtitles (e.g., `### **Internal Strength vs. Insecurity**`, `### **No Neutral Association**`).
- Formats quotes with quotation marks: `“...”`.

#### Living Example Slide(s)
- Features authentic pastimes of Śrīla Prabhupāda, previous ācāryas, or Mahābhārata/Śrīmad-Bhāgavatam exemplars (*Black Lotus*, *My Glorious Master*, *Transcendental Diary*, *Śrī Bhaktisiddhānta Vaibhava*, etc.).
- If an example is not yet finalized, insert a clean placeholder:
  `> *[Living Example / Sādhaka Story Placeholder: Brief 1-line concept]*`
- **Contrast Tables:** If contrasting two characters (e.g. Duryodhana vs. Yudhiṣṭhira), use a clean Markdown table with enough narrative context for listeners to understand without prior knowledge, while remaining concise.

#### Penultimate Slide: Vaishnava Sangha
```markdown
## Slide X: Vaishnava Sangha
### **Heart-to-Heart Reflection**

1. **[Theme 1]:** [Profound, introspective question addressing personal ego, defense mechanisms, or leadership traps].

2. **[Theme 2]:** [Practical relationship question exploring real sangha dynamics, vulnerability, or compassion].
```

#### Final Slide: From Hearing to Living (Mandatory Ending Formula)
```markdown
## Slide X: From Hearing to Living
### **An Immediate Heart Offering**

Don’t just hear it — practice it.

"[Short grounding quote from the day's text]"

**The [60-Second / 2-Minute] Silent Mirror:**  
[Quiet individual introspection prompt: identifying where we have failed, held grudges, or protected false ego.]

**Live Zoom Chat Exercise: [Exercise Name]**  
In the chat, share your internal shift (without naming names):
- *“Dropping: [Specific ego defense / reaction] → Choosing: [Specific devotional response].”*
- *“[Example 2]”*
- *“[Example 3]”*

---

***Kartik Sadhana: The [Name] Rule — [Specific, tangible 24-hour or multi-day behavioral vow].***
```
*Note: Keep chat prompts dead-simple so devotees on Zoom don't get confused (e.g., `Dropping: ... → Choosing: ...`).*

---

## 3. Dedicated Q&A Clinic Deck Architecture (e.g., Days 12, 19, 20, 21, 28, 29)

For Days reviewing multiple Q&As from the text:
1. **1 Slide Per Question:** Merge paragraphs belonging to the same question onto a single slide.
2. **Immediate Living Example:** Place each question's Living Example (or placeholder) directly after that question's slide (e.g., Q1 $\rightarrow$ Q1 Example $\rightarrow$ Q2 $\rightarrow$ Q2 Example...).
3. **Slide Headings:** Clearly label the question:
   `## Slide X: Q[N]: [Question / Dilemma]`  
   `### **[Catchy Subtitle Describing the Prescription]**`
4. Conclude with **Vaishnava Sangha** reflection and **From Hearing to Living**.

---

## 4. Tone, Formatting & File Standards

- **File Naming & Path:**
  - In progress: `slides/day-XX (pX).md`
  - Completed: `slides/ready/day-XX (pX).md`
- **Slide Delimiters:** Use `---` with blank lines before and after between every single slide.
- **Header Levels:**
  - File title: `# Day XX Slide Deck: ...`
  - Slide numbers: `## Slide X: [Slide Title]`
  - Slide subtitles: `### **[Subtitle]**`
- **Punctuation & Diacritics:** Maintain authentic Vaishnava Sanskrit transliteration (e.g., *Śrīla Prabhupāda*, *kāruṇikā*, *ahaṅkāra*, *titikṣā*).

---

## 5. Completed Reference Exemplars

When formatting upcoming decks, refer to these completed and user-approved files in `slides/ready/` as gold standards:
- **`slides/ready/day-04 (p2).md`**: Prototype for Slide 2 "Root of the Problem" diagnosis.
- **`slides/ready/day-07 (p5).md`**: Exemplary flow from leadership distinction to transparent medium.
- **`slides/ready/day-09 (p8).md`**: Visionary principle flow (embassy metaphor without artificial problem slide).
- **`slides/ready/day-11 (p10).md`**: Self-rectification & love-finding model.
- **`slides/ready/day-12 (QnA).md`**: Clinic structure (Q&A + paired Living Examples + Zoom chat exercise).
