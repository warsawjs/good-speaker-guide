# Typography on Slides

## Font Selection and Sizing

### Minimum Size Requirements

* **Body text: 24pt minimum** — anything smaller is difficult to read from the
    back of the room
* **Headings: 36pt minimum** — ensures clear hierarchy and readability
* **Code: 18-20pt minimum** — monospace fonts appear smaller, may need to be
    larger

!> **CRITICAL:** A font that is readable on your computer monitor will likely
be too small on a projector screen. Always test on a projector or assume you
need larger sizes.

### Accessible Font Choices

**Sans-serif fonts are more accessible** — they're easier to read on screens
and for people with dyslexia:

* **Highly recommended:**
    + `Arial` — universally available, excellent readability
    + `Verdana` — designed for screen readability
    + `Calibri` — clean, modern, and clear
    + `Helvetica` — classic, professional choice
    + `Open Sans` — free, widely used, very readable
    + `Lato` — modern, friendly, professional
* **For headings/accent:**
    + `Raleway` — elegant, pairs well with Lato
    + `Montserrat` — bold, attention-grabbing
* **Avoid:**
    + Decorative or script fonts (difficult to read)
    + Very thin or very bold fonts (hard to read at distance)
    + Fonts with similar-looking characters (l, I, 1)

!> **ACCESSIBILITY NOTE:** Some fonts are specifically designed to be
dyslexia-friendly (like OpenDyslexic) but may look unusual. Stick with clean
sans-serif fonts that are proven to be accessible.

## Color and Contrast

### Contrast Requirements (WCAG Standards)

Slides are displayed via projector, which often has weaker color reproduction
than monitors. **High contrast is essential for accessibility.**

* **Minimum contrast ratios:**
    + Normal text (< 24pt): **4.5:1** contrast ratio minimum
    + Large text (≥ 24pt): **3.1** contrast ratio minimum
    + **Aim for 7:1 or higher** for best accessibility
* **Tools to verify contrast:**
    + <https://contrast-ratio.com/>
    + <https://webaim.org/resources/contrastchecker/>
    + Built-in checkers in design tools

### Recommended Color Combinations

**High contrast combinations that work well:**

* **Black text on white background** — 21:1 ratio, maximum contrast
* **White text on black background** — 21:1 ratio, excellent for dark themes
* **Dark blue (#000080) on white** — 12.6:1 ratio, professional
* **White on dark blue (#000080)** — 12.6:1 ratio, classic
* **Black on light yellow (#FFFFE0)** — 19.6:1 ratio, highlighting

**Problematic combinations to avoid:**

* **Yellow on white** — insufficient contrast
* **Light gray on white** — difficult to read
* **Red on black** — hard for colorblind users
* **Green on red** — invisible to many colorblind people
* **Blue on purple** — poor contrast, hard to distinguish
* **Pastel colors on white** — generally too light

### Color Accessibility

* **Never rely on color alone** — always combine color with text, icons,
    patterns, or labels
* **Consider colorblindness** — 8% of men and 0.5% of women have some form of
    color vision deficiency
* **Test with colorblind simulators:**
    + <https://www.color-blindness.com/coblis-color-blindness-simulator/>
    + Browser extensions like "Colorblind Web Page Filter"
* **Use patterns and textures** — in charts and graphs, combine colors with
    patterns
* **Label directly** — instead of "the red line shows X", say "the revenue line
    (in red) shows X"

## Source Code Presentation

### Readability and Accessibility

* **Enable syntax highlighting** — makes code structure clear
* **No line numbers** — they add clutter and are rarely necessary in
    presentations
* **Use full screen for code** — expand code to fill available space
* **Increase default size** — most slide frameworks show code too small by
    default
* **Light theme preferred** — code on light background (light theme) is much
    more visible from the audience than dark theme

!> **IMPORTANT:** Dark themes look great on monitors but often have insufficient
contrast on projectors. If you must use dark theme, test it on a projector
first and use higher contrast colors.

### Syntax Highlighting Color Schemes

**For light backgrounds:**

* Use dark colors for text
* Ensure keywords, strings, and comments are distinguishable
* Test that highlighting works for colorblind viewers

**For dark backgrounds:**

* Use bright, saturated colors that stand out
* Ensure very high contrast (text should be nearly white)
* Test on actual projector, not just your monitor

### ⚠️ Risky Code Presentation Formats

**These platforms have accessibility issues for presentations:**

* **GitHub.com** — low contrast, small fonts, designed for monitors not
    projectors
* **Gist.github.com** — same issues as GitHub, not optimized for projection
* **Carbon.now.sh** — pretty but often insufficient contrast, decorative rather
    than accessible

**When to use them:**

* Only in optimal conditions: strong projector lamp, large screen, dark room
* Always have a backup with higher contrast
* Consider taking a screenshot and increasing contrast in an image editor

## Animation and Motion

### Accessibility Considerations

* **Animations can trigger issues:**
    + Motion sickness or vertigo in some people
    + Distraction for people with ADHD or cognitive disabilities
    + Poor performance on weak computers causes jarring effects
* **If you must use animations:**
    + Keep them very short (< 200ms)
    + Use simple fades or slides, not complex motion
    + Never animate continuously or loop animations
    + Provide a way to skip or disable animations if possible

### Flashing and Blinking

!> **CRITICAL ACCESSIBILITY ISSUE:** Content that flashes more than 3 times per
second can cause seizures in people with photosensitive epilepsy.

* **Never use:**
    + Rapidly flashing text or images
    + Strobe effects
    + Quickly alternating colors
    + Auto-playing videos with flashing content
* **General guideline:** If something flashes or blinks, it's probably not
    necessary

## Typography Best Practices

### Line Length and Spacing

* **Line length:** 50-75 characters maximum per line for readability
* **Line spacing:** 1.5x to 2x the font size for body text
* **Paragraph spacing:** Clear separation between paragraphs
* **Bullet point spacing:** Don't crowd bullets; use whitespace

### Text Alignment

* **Left-aligned** — most readable for body text, especially for dyslexic
    readers
* **Centered** — good for headings and short phrases
* **Right-aligned** — rarely appropriate, hard to read
* **Justified** — avoid, creates uneven spacing and is harder to read

### Emphasis and Hierarchy

* **Use bold for emphasis** — more accessible than italic, color, or size alone
* **Create clear hierarchy** — heading sizes should be visibly different from
    body text
* **Limit font variations** — use 2-3 fonts maximum in a presentation
* **Consistent styling** — keep styling consistent throughout all slides

## Multilingual and International Considerations

* **Choose fonts with international character support** — ensure accents,
    diacritics, and non-Latin characters display correctly
* **Test with actual content** — if presenting in multiple languages, verify
    all characters display
* **Consider reading direction** — some audiences may read right-to-left;
    design accordingly
* **Avoid culturally specific references** — ensure imagery and examples work
    across cultures
