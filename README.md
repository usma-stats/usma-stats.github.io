# MA206X: Probability and Statistics

Interactive lesson materials for MA206X at the United States Military Academy.

## About

This website contains interactive lesson materials following Devore's 9th Edition *Probability and Statistics for Engineering and the Sciences*. The site is designed to replace traditional lesson handouts, allowing cadets to:

- Follow along with boardwork during class
- Run and experiment with R code examples
- Review materials at their own pace
- Practice with embedded exercises

## Course Structure

### Block I: Data and Randomness (Lessons 1-16)
- Data types and sampling methods
- Exploratory data analysis
- Probability theory and counting
- Discrete and continuous distributions

### Block II: Inference (Lessons 17-27)
- Central Limit Theorem
- Confidence intervals
- Hypothesis testing
- One-sample and two-sample tests

### Block III: Regression Modeling (Lessons 28-40)
- Simple and multiple linear regression
- ANOVA
- Model diagnostics
- Course project

## Current Status

**Lessons 1-5 Complete:**

- ✅ Lesson 1: Types of Data, Sampling & Study Design
- ✅ Lesson 2: Sampling & Study Design
- ✅ Lesson 3: Measures of Location
- ✅ Lesson 4: Measures of Variability
- ✅ Lesson 5: Exploratory Data Analysis Lab

Additional lessons will be added throughout the semester.

## Technology

- **Quarto**: Website framework
- **R**: Statistical computing
- **Tidyverse**: Data manipulation and visualization
- **GitHub Pages**: Hosting

## Local Development

To build the website locally:

```bash
# Install Quarto (if not already installed)
# Download from https://quarto.org/docs/get-started/

# Clone the repository
git clone https://github.com/usma-stats/usma-stats.github.io.git
cd ma206x

# Render the website
quarto render

# Preview locally
quarto preview
```

The rendered site will be in the `docs/` directory.

## Deployment

This site is configured for GitHub Pages deployment:

1. Push changes to the repository
2. GitHub Pages serves from the `docs/` folder
3. Visit the site at https://usma-stats.github.io

## Structure

```
ma206x/
├── _quarto.yml           # Quarto configuration
├── index.qmd             # Home page
├── lesson_01.qmd         # Lesson 1
├── lesson_02.qmd         # Lesson 2
├── lesson_03.qmd         # Lesson 3
├── lesson_04.qmd         # Lesson 4
├── lesson_05.qmd         # Lesson 5
├── code_annex.qmd        # R code reference
├── syllabus.qmd          # Course syllabus
├── styles.css            # Custom styling
└── docs/                 # Rendered HTML (GitHub Pages)
```

## Contributing

This is a course website maintained by the MA206X instructor. For questions or issues, contact CPT Jonathan Day.

## License

Course materials are for educational use by USMA cadets.

---

**United States Military Academy**
Department of Mathematical Sciences
AY26-2
