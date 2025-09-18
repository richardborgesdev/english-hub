# GitHub Copilot Instructions for English Hub

## Project Overview
This is a comprehensive English learning repository designed to organize and track multiple English courses and resources. **The main goal is to create an AI-referenceable system for targeted learning feedback from Cambly sessions and structured study progression.**

## Repository Purpose
- **Primary Goal**: Organize English learning materials for AI-assisted feedback analysis from Cambly conversation sessions
- **Core Workflow**: Cambly provides real conversation feedback → AI analyzes errors → System recommends specific course sections to study
- **Target Use**: Integration with Cambly conversation sessions for personalized learning recommendations
- **Structure**: Numbered topic lists within chapters for easy AI reference and targeted review
- **Progress Tracking**: Checkboxes and completion status for systematic learning progression

## File Structure & Content Guidelines

### Core Learning Files
1. **THE_ENGLISH_MASTER_COURSE.md** - Comprehensive grammar course (152 sections)
   - Organized in 16 parts covering all grammar fundamentals
   - Checkbox tracking system for completed sections
   - Study priority recommendations included

2. **BUSUU.md** - Chapter-organized course topics with numbered lists
   - A1 level with 37 chapters
   - Each chapter has 1-N numbered topics for easy AI reference
   - Format: "Chapter X, topic Y" for precise feedback targeting

3. **PRONUNCIATION.md** - Detailed pronunciation course structure
   - 6 parts covering consonants, vowels, stress, and fluency
   - IPA symbols and technical pronunciation details

4. **CHEAT_SHEET.md** - Quick reference guide for essential English components
   - Comprehensive grammar rules and usage examples
   - Parts of speech with detailed explanations and examples
   - Verb system including all tenses, forms, and usage patterns
   - Practical communication topics (social, professional, everyday situations)
   - Word formation, collocations, and common idioms
   - Writing skills and punctuation guide
   - Serves as instant reference for grammar doubts and quick reviews

5. **CAMBLY.md** - Cambly session diary with AI feedback analysis (MOST IMPORTANT FILE)
   - Class-by-class conversation logs with timestamps
   - AI-generated feedback from Cambly platform analyzing grammar, vocabulary, coherence
   - Detailed vocabulary learned with pronunciation guides
   - Communication strengths and areas for improvement
   - Teacher assessments and next steps for each session
   - Real conversation highlights and cultural exchanges
   - Progress tracking across multiple classes

6. **README.md** - Project overview with goals, resources, and progress tracking
   - Task completion checklist
   - Resource links for various platforms (Duolingo, Busuu, TOEFL, IELTS, etc.)
   - Progress videos and milestones

### AI Integration Strategy
- **Chapter-Specific Numbering**: Topics numbered 1-N within each chapter (not continuous)
- **Easy Reference**: AI can specify "Chapter 12, topic 4" instead of "topic 60"
- **Targeted Feedback**: Enables precise recommendations based on Cambly session analysis
- **Progress Correlation**: Links specific topics to learning gaps identified in conversations

## Content Formatting Standards

### Markdown Structure
- Use clear headers with consistent hierarchy
- Implement checkbox systems for progress tracking
- Maintain numbered lists within chapters for AI reference
- Include course URLs and external resource links

### Chapter Organization
```markdown
### Chapter X: [Topic Name]
1. [Topic 1] - [Description]
2. [Topic 2] - [Description]
3. [Topic 3] - [Description]
```

### Progress Tracking
- Use `[X]` for completed items
- Use `[ ]` for pending items
- Include completion percentages where applicable
- Link to progress videos and external validation

## AI Assistant Guidelines

### When Working with This Repository:
1. **Maintain Numbering**: Always preserve chapter-specific numbering (1-N per chapter)
2. **Reference Format**: Use "Chapter X, topic Y" format for specific recommendations
3. **Progress Respect**: Don't modify completion checkboxes without explicit user instruction
4. **Structure Consistency**: Follow established markdown patterns and hierarchy
5. **Link Preservation**: Maintain all external resource links and course URLs

### Content Updates:
- **Adding New Topics**: Follow established numbering within chapters
- **Course Integration**: Maintain clear separation between different course materials
- **Resource Management**: Update README.md when adding new learning resources
- **Progress Updates**: Only modify completion status when explicitly requested

### AI Feedback Integration:
- **Cambly Analysis**: Structure responses to reference specific chapters and topics
- **Learning Gaps**: Identify areas needing review using the established numbering system
- **Study Recommendations**: Provide targeted suggestions using chapter/topic format
- **Progress Correlation**: Link feedback to specific course sections for focused improvement

### CAMBLY.md Feedback Analysis Guidelines:
- **Error Pattern Recognition**: Analyze recurring grammar mistakes across multiple classes
- **Vocabulary Integration**: Cross-reference new vocabulary with relevant course chapters
- **Progress Tracking**: Monitor improvement trends in specific skill areas
- **Targeted Recommendations**: Link Cambly feedback to specific BUSUU chapters and grammar sections
- **Cultural Context**: Preserve teacher insights and conversation highlights
- **Assessment Continuity**: Maintain consistent tracking of strengths and weaknesses over time

## Cambly Feedback Processing

### Feedback Structure Format:
Each Cambly class entry should maintain this structure:
```markdown
## Class X | Date

### Cambly ai feedback:
#### Category (Grammar/Vocabulary/Coherence/Other):
1. You said: "[original phrase]"
   > Suggestion: "[corrected phrase]"
   > Explanation: [detailed explanation]

### Additional class insights:
#### Vocabulary learned:
1. **word**: pronunciation - definition/context

#### Areas for improvement:
1. **Category**: specific issues and corrections needed

#### Next steps:
1. Actionable items for focused study
```

### Cross-Reference Integration:
When analyzing Cambly feedback, always correlate errors with:
- **Grammar Course Sections**: THE_ENGLISH_MASTER_COURSE.md sections
- **Conversation Topics**: BUSUU.md chapters
- **Pronunciation Issues**: PRONUNCIATION.md relevant sections
- **Quick Grammar Reference**: CHEAT_SHEET.md for instant rule clarification
- **Recurring Patterns**: Track persistent issues across multiple classes

## Special Considerations

### Language Learning Context
- **Multi-Platform Integration**: Content spans Duolingo, Busuu, Udemy, and other platforms
- **Exam Preparation**: Includes TOEFL, IELTS, DET preparation materials
- **Skill Categories**: Grammar, pronunciation, speaking, writing, and exam-specific skills
- **Brazilian Learner**: Resources include Portuguese-specific English learning channels

### Technical Requirements
- **Markdown Compatibility**: All content must render properly in GitHub and VS Code
- **Link Functionality**: External links should be properly formatted and accessible
- **Checkbox Support**: Progress tracking must work across different markdown renderers
- **IPA Symbols**: Pronunciation content includes International Phonetic Alphabet characters

## Usage Examples

### Good AI Responses:
```
"Based on your Cambly feedback, I recommend reviewing:
- Chapter 12: At the table, topics 1-3 (polite communication)
- Chapter 25: At a café, topic 5 (polite requests)
This will help with your restaurant conversation skills."
```

### Cambly Feedback Analysis:
```
"From Class 7, I notice recurring preposition errors:
- 'depends of' → 'depends on' (review THE_ENGLISH_MASTER_COURSE.md Section 75-82)
- 'exit of' → 'exit from' (practice with BUSUU.md Chapter 29: Places around town)
Focus on preposition usage with specific verbs."
```

### Cross-Course Correlation:
```
"Your Cambly vocabulary from Class 6 (maintenance, VPN, ticket system)
relates to BUSUU.md Chapter 10: Jobs, topics 1-4.
Practice professional communication scenarios."
```

### Quick Grammar Reference:
```
"From your Cambly feedback, you're confusing 'depends of' vs 'depends on'.
Check CHEAT_SHEET.md → Prepositions → Verb + Preposition Collocations.
The rule: 'depend on' (not 'depend of') - see section on common collocation errors."
```### Course Progress Updates:
```markdown
- [X] **Section 45:** Articles and Demonstratives *(Overview)*
- [ ] **Section 46:** A, An, The
```

### New Topic Addition:
```markdown
### Chapter 38: New Topics
1. Topic description - Learning objective
2. Topic description - Learning objective
```

## Repository Goals
- **2500+ day Duolingo streak completion**
- **Complete Busuu main course and extras**
- **Achieve DET 120+, TOEFL 100+, IELTS 7.5+ scores**
- **Create personalized grammar review system**
- **Integrate AI feedback for targeted learning improvements**

This structure enables efficient, AI-assisted English learning with precise feedback targeting and systematic progress tracking.
