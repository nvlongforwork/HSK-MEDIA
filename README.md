# HSK-MEDIA

Media and content files for the HSK Chinese Learning App.

## Structure

```
hsk-media/
├── audio/
│   └── hsk1/
│       ├── lesson-1/    (audio files for lesson 1)
│       ├── lesson-2/
│       └── ... lesson-15
├── images/
│   └── hsk1/
│       ├── lesson-1/    (images for lesson 1)
│       ├── lesson-2/
│       └── ... lesson-15
├── content/
│   └── hsk1/
│       ├── lesson-1/
│       │   ├── vocabulary.md
│       │   ├── grammar.md
│       │   └── exercises.md
│       ├── lesson-2/
│       └── ... lesson-15
└── README.md
```

## Content Format

### Vocabulary (vocabulary.md)
Markdown table with columns: #, 汉字, 拼音, English, Example

### Grammar (grammar.md)
Markdown with grammar point explanations, structures, and examples

### Exercises (exercises.md)
Markdown with Multiple Choice, Fill in the Blanks, and Flashcards sections

## Usage

Content is fetched by the HSK app via GitHub raw URLs:
```
https://raw.githubusercontent.com/nvlongforwork/hsk-media/main/content/hsk1/lesson-1/vocabulary.md
```

## Adding Media

- **Audio**: Place `.mp3` files in `audio/hsk{level}/lesson-{n}/`
- **Images**: Place `.png`/`.jpg` files in `images/hsk{level}/lesson-{n}/`
- **Content**: Edit `.md` files in `content/hsk{level}/lesson-{n}/`
