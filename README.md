# Sleep, CSF Flow & Delirium: A Glymphatic Perspective

An interactive research webpage synthesizing findings from three landmark neuroscience studies connecting sleep, cerebrospinal fluid dynamics, EEG oscillations, and delirium in critically ill patients.

## Featured Research Papers

1. **Fultz et al., Science 2019** - "Coupled electrophysiological, hemodynamic, and cerebrospinal fluid oscillations in human sleep"
2. **Liu et al., bioRxiv 2026** - "Mechanical Ventilation Suppresses Glymphatic Function in Parallel with Delirium-Like Symptoms in Mice"
3. **Boesen et al., Nature Reviews Neurology 2026** - "Glymphatic dysfunction as a unifying mechanism for delirium"

## Features

- **Interactive Charts**: 11+ Chart.js visualizations including line charts, bar charts, and radar charts
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Tabbed Content**: Deep-dive sections with tabbed navigation
- **Interactive Slider**: Explore the relationship between slow-wave activity and delirium risk
- **Professional Layout**: Modern, clean design with a harmonious color palette

## How to Deploy to GitHub Pages

### Step 1: Create a New Repository on GitHub

1. Go to [GitHub](https://github.com) and log in to your account
2. Click the **+** icon in the top-right corner and select **New repository**
3. Name your repository: `sleep-csf-delirium`
4. Choose **Public** (so anyone can access it)
5. Click **Create repository**

### Step 2: Upload Files

You have two options:

#### Option A: Upload via GitHub Web Interface (Easiest)

1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop the `index.html` file from this folder
3. Click **Commit changes**

#### Option B: Use Git Command Line

```bash
git clone https://github.com/YOUR_USERNAME/sleep-csf-delirium.git
cd sleep-csf-delirium
# Copy index.html to this directory
git add index.html
git commit -m "Add research webpage"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (gear icon)
3. Scroll down to **Pages** section on the left sidebar
4. Under "Source", select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

### Step 4: Access Your Webpage

Your webpage will be available at:
```
https://YOUR_USERNAME.github.io/sleep-csf-delirium/
```

GitHub will display the URL in the Pages section after a few moments.

## File Structure

```
sleep-csf-delirium/
├── index.html          # Main webpage (all-in-one file)
├── README.md           # This file
└── .gitignore          # (Optional) Git ignore file
```

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Responsive design with CSS variables
- **JavaScript**: Interactive functionality
- **Chart.js**: Data visualization library (loaded via CDN)
- **Font Awesome**: Icons (loaded via CDN)

## Browser Compatibility

This webpage works on all modern browsers:
- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Content Sections

1. **Overview** - Key statistics and the cascade from sleep to delirium
2. **EEG–CSF Coupling** - Fultz et al. findings with interactive charts
3. **Glymphatic System** - Brain waste clearance mechanism
4. **Mechanical Ventilation** - Liu et al. findings on ICU interventions
5. **Delirium Hypothesis** - Boesen et al. unifying framework
6. **Synthesis** - Integrated pathway connecting all three papers
7. **Clinical Implications** - Therapeutic avenues and future directions

## Key Findings Highlighted

- **Respiratory vs. Sleep-Driven CSF Flow**: During wakefulness, CSF pulsations are coupled to respiratory frequency (~0.25 Hz), while NREM sleep activates a 20-fold more efficient mechanism via EEG slow waves (0.05 Hz)
- **Glymphatic Suppression**: Mechanical ventilation acutely increases intracranial pressure and suppresses glymphatic transport by ~70%
- **Sleep Preservation**: Tui therapy may potentially be combined with other protocols to support natural sleep architecture and circadian rhythm integrity

## Interactive Features

- **Tabbed Navigation**: Switch between Methods, EEG-CSF Link, and Significance in the Fultz section
- **Interactive Slider**: Adjust slow-wave activity to see estimated glymphatic efficiency and delirium risk change in real-time
- **Responsive Charts**: Hover over charts to see detailed data points

## References

All references are cited within the webpage and linked to their respective DOI or source URLs.

## License

This webpage is provided for educational and research purposes.

## Questions or Issues?

If you encounter any issues deploying to GitHub Pages, please refer to the [GitHub Pages Documentation](https://docs.github.com/en/pages).
