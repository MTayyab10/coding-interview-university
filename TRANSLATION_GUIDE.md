# Translation System Documentation

## Overview

The Coding Interview University supports multiple languages through a comprehensive translation system. This documentation provides detailed information about available translations, their coverage, quality standards, and contribution processes.

## Available Translations

### Complete Translations

The following translations are currently complete and maintained by the community:

| Language | Code | File | Lines | Percentage | Last Updated | Maintainer Status |
|----------|------|------|-------|------------|--------------|-------------------|
| **English** | `en` | `README.md` | 1,990 | 100% (Reference) | Continuous | Primary Author |
| **Chinese (Simplified)** | `cn` | `translations/README-cn.md` | 1,651 | ~83% | Community | Active |
| **Chinese (Traditional)** | `tw` | `translations/README-tw.md` | 1,891 | ~95% | Community | Active |
| **Spanish** | `es` | `translations/README-es.md` | 1,918 | ~96% | Community | Active |
| **Portuguese (Brazilian)** | `ptbr` | `translations/README-ptbr.md` | 1,968 | ~99% | Community | Active |
| **Vietnamese** | `vi` | `translations/README-vi.md` | 1,956 | ~98% | Community | Active |
| **Polish** | `pl` | `translations/README-pl.md` | 1,971 | ~99% | Community | Active |
| **Korean** | `ko` | `translations/README-ko.md` | 2,089 | ~105% | Community | Active |
| **German** | `de` | `translations/README-de.md` | 2,095 | ~105% | Community | Active |
| **French** | `fr` | `translations/README-fr.md` | 2,014 | ~101% | Community | Active |
| **Arabic** | `ar` | `translations/README-ar.md` | 2,032 | ~102% | Community | Active |
| **Hebrew** | `he` | `translations/README-he.md` | 2,010 | ~101% | Community | Active |
| **Hindi** | `hi` | `translations/README-hi.md` | 1,730 | ~87% | Community | Active |
| **Bengali** | `bn` | `translations/README-bn.md` | 2,131 | ~107% | Community | Active |
| **Thai** | `th` | `translations/README-th.md` | 1,938 | ~97% | Community | Active |
| **Ukrainian** | `uk` | `translations/README-uk.md` | 1,939 | ~97% | Community | Active |
| **Indonesian** | `id` | `translations/README-id.md` | 1,984 | ~100% | Community | Active |

### Translations in Progress

The following translations are currently being developed:

| Language | GitHub Issue | Status | Contributors |
|----------|--------------|---------|--------------|
| **Italian** | [#170](https://github.com/jwasham/coding-interview-university/issues/170) | In Progress | Community |
| **Japanese** | [#257](https://github.com/jwasham/coding-interview-university/issues/257) | In Progress | Community |
| **Turkish** | [#90](https://github.com/jwasham/coding-interview-university/issues/90) | In Progress | Community |
| **Russian** | [#87](https://github.com/jwasham/coding-interview-university/issues/87) | In Progress | Community |
| **Telugu** | [#117](https://github.com/jwasham/coding-interview-university/issues/117) | In Progress | Community |
| **Urdu** | [#140](https://github.com/jwasham/coding-interview-university/issues/140) | In Progress | Community |
| **Greek** | [#166](https://github.com/jwasham/coding-interview-university/issues/166) | In Progress | Community |
| **Malayalam** | [#239](https://github.com/jwasham/coding-interview-university/issues/239) | In Progress | Community |

## Translation Standards and Guidelines

### File Naming Convention

All translation files follow the pattern:
```
translations/README-{language_code}.md
```

Where `{language_code}` follows these conventions:
- **Two-letter ISO codes**: `cn`, `es`, `fr`, `de`, `ko`, etc.
- **Regional variants**: `ptbr` (Portuguese Brazilian), `tw` (Traditional Chinese)
- **Special cases**: Use descriptive codes when ISO standards don't apply

### Content Structure Requirements

Each translation must maintain:

1. **Complete Table of Contents**
   - All section headers translated
   - Anchor links preserved with English slugs
   - Hierarchical structure maintained

2. **Resource Links**
   - Original URLs preserved (unless language-specific alternatives exist)
   - Link descriptions translated
   - Video resources with subtitles preferred when available

3. **Code Examples**
   - Code snippets remain in original language (usually English)
   - Comments may be translated
   - Variable names follow local conventions when appropriate

4. **Progress Checkboxes**
   - Checkbox format `- [ ]` preserved exactly
   - Allows for progress tracking in any language

### Quality Standards

#### Translation Accuracy
- **Technical Terms**: Maintain consistency with established technical vocabulary
- **Cultural Adaptation**: Adapt examples and references to local context when beneficial
- **Clarity**: Prioritize clear communication over literal translation

#### Formatting Requirements
- **Markdown Syntax**: Preserve all formatting elements
- **Link Integrity**: Ensure all internal and external links function correctly
- **Table Structure**: Maintain table formatting and alignment
- **Code Blocks**: Preserve syntax highlighting language tags

## How to Access Translations

### Direct File Access

```bash
# Pattern for accessing any translation
/translations/README-{language_code}.md

# Examples:
/translations/README-cn.md     # Chinese Simplified
/translations/README-tw.md     # Chinese Traditional
/translations/README-es.md     # Spanish
/translations/README-ptbr.md   # Portuguese Brazilian
/translations/README-vi.md     # Vietnamese
/translations/README-pl.md     # Polish
/translations/README-ko.md     # Korean
/translations/README-de.md     # German
/translations/README-fr.md     # French
/translations/README-ar.md     # Arabic
/translations/README-he.md     # Hebrew
/translations/README-hi.md     # Hindi
/translations/README-bn.md     # Bengali
/translations/README-th.md     # Thai
/translations/README-uk.md     # Ukrainian
/translations/README-id.md     # Indonesian
```

### GitHub Interface Access

From the main repository README, users can access translations via:
1. The translations dropdown in the main README
2. Direct navigation to the `translations/` directory
3. Language-specific links in the main document

## Contributing New Translations

### Process Overview

As outlined in `translations/how-to.md`, the contribution process involves:

1. **Create Coordination Issue**
   - Open a GitHub issue to coordinate with other potential translators
   - Include target language and estimated timeline
   - Tag with `translation` label

2. **Create Working Branch/Fork**
   - Fork the repository or create a branch for collaboration
   - Set up the translation file following naming conventions
   - Begin translation work

3. **Submit for Review**
   - Create a pull request when translation is substantially complete
   - Request review from native speakers and maintainers
   - Address feedback and iterate as needed

### Translation Workflow

#### Phase 1: Setup and Planning
```bash
# 1. Fork the repository
git fork https://github.com/jwasham/coding-interview-university

# 2. Create translation branch
git checkout -b translation-{language_code}

# 3. Create translation file
cp README.md translations/README-{language_code}.md
```

#### Phase 2: Translation Work
1. **Start with Structure**
   - Translate table of contents first
   - Establish terminology consistency
   - Set up section headers

2. **Content Translation**
   - Work section by section
   - Maintain technical accuracy
   - Preserve all links and formatting

3. **Review and Polish**
   - Proofread for grammar and clarity
   - Verify all links function correctly
   - Test markdown rendering

#### Phase 3: Community Review
1. **Initial Submit**
   - Create pull request with substantial completion
   - Request community feedback
   - Tag native speakers for review

2. **Iteration**
   - Address reviewer feedback
   - Make corrections and improvements
   - Finalize translation

3. **Merge**
   - Final approval from maintainers
   - Integration into main repository
   - Addition to translation index

### Best Practices for Translators

#### Technical Terminology
- **Consistency**: Create and maintain a glossary of technical terms
- **Standards**: Follow established conventions in your language's tech community
- **Clarity**: When in doubt, include the English term in parentheses

#### Cultural Adaptation
- **Examples**: Adapt company examples to include local tech companies when relevant
- **Educational Resources**: Include local university courses or resources when available
- **Community**: Reference local programming communities and forums

#### Collaboration
- **Communication**: Stay in touch with other contributors through GitHub issues
- **Coordination**: Avoid duplicate work by clearly claiming sections
- **Review**: Actively participate in reviewing other translations

## Translation Maintenance

### Keeping Translations Updated

#### Update Triggers
- New content added to main README
- Structural changes to the curriculum
- Link updates or corrections
- Community-requested improvements

#### Maintenance Process
1. **Change Detection**
   - Monitor main repository for updates
   - Track changes through Git commits
   - Identify sections requiring translation updates

2. **Update Translation**
   - Apply changes to translated version
   - Maintain consistency with new content
   - Update any changed links or resources

3. **Quality Assurance**
   - Review updated sections
   - Test all functionality
   - Submit updates via pull request

### Community Support

#### Translation Coordinators
Each major translation ideally has:
- **Primary Maintainer**: Responsible for major updates and quality oversight
- **Community Contributors**: Help with updates, corrections, and improvements
- **Technical Reviewers**: Verify technical accuracy of translations

#### Support Channels
- **GitHub Issues**: For reporting translation problems or suggestions
- **Pull Requests**: For submitting corrections and improvements
- **Community Discussion**: Language-specific discussion threads

## Technical Implementation

### File Structure Analysis

```
translations/
├── README-ar.md      # Arabic - RTL language support
├── README-bn.md      # Bengali - Indic script
├── README-cn.md      # Chinese Simplified - CJK
├── README-de.md      # German - Extended Latin
├── README-es.md      # Spanish - Latin script
├── README-fr.md      # French - Extended Latin
├── README-he.md      # Hebrew - RTL language
├── README-hi.md      # Hindi - Devanagari script
├── README-id.md      # Indonesian - Latin script
├── README-ko.md      # Korean - Hangul script
├── README-pl.md      # Polish - Extended Latin
├── README-ptbr.md    # Portuguese Brazilian
├── README-th.md      # Thai - Thai script
├── README-tw.md      # Chinese Traditional - CJK
├── README-uk.md      # Ukrainian - Cyrillic
├── README-vi.md      # Vietnamese - Extended Latin
└── how-to.md         # Translation guidelines
```

### Character Encoding
- **UTF-8 Support**: All files use UTF-8 encoding for full Unicode support
- **Script Variety**: Supports Latin, Cyrillic, CJK, Arabic, Indic, and Thai scripts
- **RTL Languages**: Right-to-left languages (Arabic, Hebrew) properly supported

### Markdown Compatibility
- **GitHub Flavored Markdown**: All translations use GFM for consistency
- **Checkbox Support**: Progress tracking checkboxes work in all languages
- **Link Preservation**: Internal anchor links function across all translations

## Future Translation Plans

### Expanding Language Coverage
Priority languages for future translation:
- **Major Regional Languages**: Russian, Japanese, Italian
- **Emerging Markets**: Portuguese (European), Indonesian variants
- **Underrepresented Languages**: African languages, additional Indian languages

### Automation and Tools
- **Translation Memory**: Developing shared translation glossaries
- **Update Automation**: Tools to identify when translations need updates
- **Quality Assurance**: Automated checks for link integrity and formatting

### Community Growth
- **Translation Teams**: Organizing language-specific contributor groups
- **Mentorship Programs**: Pairing experienced translators with newcomers
- **Recognition Systems**: Acknowledging major translation contributors

---

This comprehensive translation system ensures that the Coding Interview University curriculum is accessible to a global audience, with high-quality translations maintained by dedicated community members worldwide.