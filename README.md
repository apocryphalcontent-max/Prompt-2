# Prompt-2: Outline Evaluation & Concept Integration Prompt

A prompt template designed to evaluate project outlines and determine optimal placement for integrating new concepts.

## Purpose

This prompt helps you:
- Evaluate the structure and completeness of existing project outlines
- Identify where new concepts should be integrated within the current structure
- Determine when concepts warrant their own dedicated sections
- Suggest optimal placement for new sections when needed

---

## Outline Evaluation & Concept Integration Prompt

Use this prompt with your preferred AI assistant to analyze your outline and integrate new concepts:

```
I need your help evaluating a project outline and determining where to integrate new concepts.

## Project Outline

[PASTE YOUR OUTLINE HERE]

## Concepts to Integrate

[LIST THE CONCEPTS YOU WANT TO ADD]

---

## Analysis Instructions

Please analyze the outline and concepts above, then provide:

### 1. Outline Evaluation
- Assess the current structure for logical flow and completeness
- Identify any gaps or areas that could be strengthened
- Note sections that are well-developed vs. those needing expansion

### 2. Concept Integration Analysis

For each concept to integrate, determine:

**A. If the concept fits within an existing section:**
- Specify the exact section where it belongs
- Explain why this placement is optimal
- Suggest the specific location within that section (beginning, middle, end, or after a specific subsection)
- Provide a brief integration note on how to weave it into existing content

**B. If the concept warrants its own section:**
- Recommend this as a new section
- Specify where in the outline the new section should be placed (before/after which existing section)
- Explain why a dedicated section is necessary (scope, complexity, thematic independence)
- Suggest subsections or key points the new section should cover

### 3. Integration Priority

Rank the concepts by integration priority:
- **Essential**: Core to the project's purpose, must be integrated
- **Important**: Significantly enhances the outline, should be integrated
- **Optional**: Nice to have, can be integrated if space/scope allows

### 4. Output Format

Present your analysis as:

| Concept | Integration Type | Location | Rationale |
|---------|------------------|----------|-----------|
| [Name]  | Existing Section / New Section | [Specific placement] | [Why here] |

### 5. Updated Outline Preview

Provide a revised outline showing where each concept has been integrated, with new additions marked with [NEW] tags.
```

---

## Decision Criteria for New Sections

A concept warrants its own section when:

1. **Scope**: It has enough depth to support multiple subsections or detailed discussion
2. **Independence**: It stands as a distinct theme not adequately covered by existing sections
3. **Cross-cutting**: It relates to multiple existing sections but doesn't belong exclusively to any
4. **Foundational**: It provides essential background needed before understanding other sections
5. **Complexity**: It requires dedicated explanation that would disrupt flow if embedded elsewhere

---

## Example Usage

### Input Outline:
```
1. Introduction
2. Background
3. Methodology
4. Results
5. Conclusion
```

### Concepts to Integrate:
- Data validation procedures
- Ethical considerations
- Future research directions

### Expected Analysis Output:
| Concept | Integration Type | Location | Rationale |
|---------|------------------|----------|-----------|
| Data validation procedures | Existing Section | Section 3: Methodology (after data collection) | Directly relates to methods; enhances credibility |
| Ethical considerations | New Section | New Section 2.5 (between Background and Methodology) | Cross-cutting concern requiring dedicated treatment |
| Future research directions | Existing Section | Section 5: Conclusion (final subsection) | Natural extension of conclusions |

---

## Tips for Best Results

1. **Be specific with your outline**: Include section numbers, subsections, and brief descriptions
2. **Describe concepts clearly**: Provide context on what each concept covers
3. **Note dependencies**: If concepts depend on each other, mention this
4. **Indicate constraints**: Share any page limits, scope boundaries, or structural requirements

---

## License

Licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for details.