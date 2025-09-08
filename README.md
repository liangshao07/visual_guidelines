# GitHub Open Source Project Visual Content Guidelines

This document summarizes the widely recognized visual content standards for GitHub open source projects, helping projects create professional and consistent visual presentations.

## 📋 Table of Contents

- [Core Principles](#core-principles)
- [Image Types and Usage](#image-types-and-usage)
- [Technical Specifications](#technical-specifications)
- [Design Standards](#design-standards)
- [File Management](#file-management)
- [Content Requirements](#content-requirements)
- [Platform Optimization](#platform-optimization)
- [Best Practices](#best-practices)

## 🎯 Core Principles

### 1. Professionalism
- High-quality visual effects
- Consistent design style
- Clear information communication
- Avoid amateur or casual appearance

### 2. Accessibility
- High contrast to ensure readability
- Color choices that support colorblind users
- Clear fonts and appropriate font sizes
- Clean and simple interface layout

### 3. Consistency
- Unified color schemes
- Same dimensions and formats
- Consistent screenshot styles
- Standardized naming conventions

### 4. Internationalization
- English interface priority (international audience)
- Avoid culture-specific elements
- Universal icons and symbols
- Simple visual language

## 📸 Image Types and Usage

### 1. README Display Images

#### Hero Image / Cover Image
```
- Purpose: README top display, first impression of project
- Size: 1200x630 (GitHub Social Preview standard)
- Format: PNG/JPG
- Content: Project Logo + Brief description + Core feature showcase
- Location: Top of README.md
```

#### Feature Showcase
```
- Purpose: Display main features and characteristics
- Size: 1280x720 (16:9 ratio)
- Format: PNG/WebP
- Content: Feature interface screenshots or feature diagrams
- Quantity: 3-5 images, covering core functions
```

#### Demo GIF / Demo Animation
```
- Purpose: Show interaction flow and usage methods
- Size: 800x600 (maximum)
- Format: GIF/WebP animation
- File size: <3MB
- Duration: 5-15 seconds
- Frame rate: 10-15 FPS
```

### 2. Documentation Images

#### Installation Screenshots
```
- Purpose: Show installation process and steps
- Size: Original interface size (maintain true proportions)
- Format: PNG
- Annotation: Clear step markers
```

#### Tutorial Images
```
- Purpose: Usage tutorials and documentation
- Size: Suitable for document display
- Format: PNG
- Requirements: Clear operation instructions
```

### 3. Release Assets

#### App Store Screenshots
```
- Purpose: Plugin/app store display
- Size: According to platform requirements (usually 1280x720+)
- Format: PNG/JPG
- Quality: Highest quality, no compression loss
```

## ⚙️ Technical Specifications

### Image Format Selection

| Purpose | Recommended Format | Alternative Format | Description |
|---------|-------------------|-------------------|-------------|
| Screenshots | PNG | WebP | Lossless quality, supports transparency |
| Photos | JPG | WebP | Suitable for complex colors, smaller file size |
| Icons | SVG | PNG | Vector format, scalable |
| Animation | GIF | WebP | Good compatibility, moderate file size |

### Size Standards

#### Responsive Size System
```
- Extra Large Screen: 1920x1080 (Desktop monitors)
- Large Screen: 1280x720 (Standard display)
- Medium Screen: 800x450 (Document embedding)
- Small Screen: 400x225 (Thumbnails)

Aspect ratio priority selection:
- 16:9 (Universal)
- 4:3 (Traditional)
- 1:1 (Avatar/Icons)
- Custom (Maintain original proportions)
```

#### File Size Limits
```
- Single image: <5MB (recommended <2MB)
- GIF animation: <3MB (recommended <1MB)
- README total images: <20MB
- Avatar/Logo: <500KB
```

### Resolution Requirements
```
- Minimum resolution: 72 DPI (Web display)
- Recommended resolution: 144 DPI (High definition display)
- Print quality: 300 DPI (If printing needed)
- Color space: sRGB (Web standard)
```

## 🎨 Design Standards

### 1. Color Specifications

#### GitHub Dark Theme Adaptation
```css
/* Primary colors */
--bg-primary: #0d1117;     /* GitHub dark background */
--bg-secondary: #161b22;   /* Secondary background */
--text-primary: #f0f6fc;   /* Primary text */
--text-secondary: #8b949e; /* Secondary text */
--accent: #238636;         /* Accent color (green) */
--border: #30363d;         /* Border color */
```

#### General Color Recommendations
```
- Use high contrast color schemes
- Avoid pure black (#000000) and pure white (#ffffff)
- No more than 3 main colors
- Maintain brand color consistency
- Consider colorblind-friendly color schemes
```

### 2. Typography Standards

#### Recommended Fonts
```
English: 
- Sans-serif: Inter, Roboto, Source Sans Pro
- Monospace: JetBrains Mono, Fira Code, Monaco

Chinese:
- Sans-serif: Source Han Sans, PingFang, Microsoft YaHei
- Monospace: Source Han Mono, Sarasa Gothic
```

#### Font Size Standards
```
- Headings: 24px+ (clearly readable)
- Body text: 16px+ (comfortable reading)
- Captions: 14px+ (minimum readable)
- Code: 14px+ (monospace font)
```

### 3. Layout Principles

#### Grid System
```
- Use 8px base grid
- Maintain element alignment
- Appropriate whitespace
- Clear information hierarchy
```

#### Composition Techniques
```
- Rule of thirds composition
- Golden ratio division
- Symmetrical or balanced layout
- Leading lines and focal point design
```

## 📁 File Management

### Directory Structure
```
project-root/
├── .github/
│   └── images/           # GitHub-specific images
│       ├── hero.png     # Social media preview image
│       └── logo.svg     # Project Logo
├── docs/
│   └── images/          # Documentation images
│       ├── installation/
│       ├── tutorials/
│       └── screenshots/
├── assets/              # General resources
│   ├── icons/          # Icon files
│   ├── screenshots/    # Application screenshots
│   └── demos/          # Demo files
└── README.md
```

### Naming Conventions

#### File Naming Patterns
```bash
# Feature-based naming
feature_[feature_name]_[status].[extension]
# Example: feature_stitching_result.png

# Sequential naming
[number]_[description].[extension]
# Example: 01_main_interface.png

# Semantic naming
[purpose]_[detailed_description].[extension]
# Example: hero_banner_dark_theme.png
```

#### Naming Best Practices
```
✅ Recommended:
- installation_step_1.png
- demo_video_editing.gif
- icon_app_logo.svg
- screenshot_main_ui.png

❌ Avoid:
- Screenshot2023.png
- IMG_001.jpg
- Image1.png
- Untitled.png
```

## 📝 Content Requirements

### 1. Privacy and Security

#### Sensitive Information Handling
```
Avoid or blur:
- Personal names and contact information
- Real email addresses
- API keys and tokens
- Private file paths
- Sensitive business data
```

#### Sample Data Usage
```
Recommended usage:
- Lorem ipsum text
- Example emails (example@example.com)
- Fictional company names
- Open source or free sample images
- Test usernames (testuser, demo, etc.)
```

### 2. Copyright Compliance

#### Image Usage Guidelines
```
✅ Safe to use:
- Original content you created
- CC0 licensed free images
- Official materials from open source projects
- Purchased commercial licensed images

❌ Avoid using:
- Randomly downloaded internet images
- Content with copyright disputes
- Screenshots from others' projects (unauthorized)
- Commercial software interfaces (unauthorized)
```

#### Recommended Material Sources
```
Free images:
- Unsplash (unsplash.com)
- Pexels (pexels.com)
- Pixabay (pixabay.com)

Icon resources:
- Feather Icons (feathericons.com)
- Heroicons (heroicons.com)
- Tabler Icons (tabler-icons.io)

Font resources:
- Google Fonts (fonts.google.com)
- Adobe Fonts (fonts.adobe.com)
```

### 3. Content Quality

#### Interface Screenshot Requirements
```
✅ High-quality screenshots:
- Complete functional interface
- Clear text and icons
- Realistic usage scenarios
- Reasonable data display
- Consistent interface state

❌ Low-quality screenshots:
- Blurry images
- Incomplete interface
- Blank or content-less interface
- Error state interface
- Developer tool traces
```

## 🌐 Platform Optimization

### 1. GitHub Platform Optimization

#### Social Preview Optimization
```
Size: 1200x630
Format: PNG/JPG
Requirements:
- Clear project title
- Concise feature description
- Attractive visual design
- Brand element display
```

#### README Display Optimization
```
- Use relative paths for image references
- Provide high-definition and standard versions if necessary
- Consider dark theme display effects
- Optimize mobile device display
```

### 2. Multi-Platform Considerations

#### Plugin/App Stores
```
VS Code Marketplace:
- Recommended: 1376x768
- Minimum: 1200x600
- Format: PNG
- Quality: High quality lossless

Apple App Store (iOS/macOS):
- iOS screenshots: 1290x2796 (iPhone 16 Pro)
- iPad screenshots: 2048x2732 (12.9" iPad Pro)
- macOS screenshots: 1280x800 (minimum)
- Format: PNG/JPG
- Requirements: Actual device screenshots, showing real usage scenarios

Google Play Store (Android):
- Phone screenshots: 1080x1920 (minimum)
- Tablet screenshots: 1200x1920 (7") / 1600x2560 (10")
- Format: PNG/JPG
- Quantity: Minimum 2, maximum 8

Microsoft Store (Windows):
- Screenshots: 1366x768 (minimum)
- Recommended: 1920x1080
- Format: PNG/JPG/JPEG
- Ratio: 16:9 recommended

Chrome Web Store:
- Screenshots: 1280x800 or 640x400
- Promotional images: 440x280
- Format: PNG/JPG
- Quality: High resolution

Firefox Add-ons:
- Screenshots: Maximum 1425x750
- Icons: 64x64, 32x32
- Format: PNG/JPG
- Requirements: Clear function display
```

#### Social Media Sharing
```
Twitter: 1200x675 (16:9)
LinkedIn: 1200x627
Facebook: 1200x630
Reddit: 1200x630
```

## 🏆 Best Practices

### 1. Screenshot Techniques

#### Preparation
```bash
# 1. Environment setup
- Use high-resolution monitors (2K/4K)
- Set 100% zoom level
- Close unrelated applications
- Clean desktop and taskbar

# 2. Browser settings
- Use incognito mode
- Disable extensions
- Set standard window size
- Hide developer tools
```

#### Recommended Screenshot Tools
```
macOS:
- Built-in screenshot (Cmd+Shift+4)
- CleanShot X (Professional tool)
- Skitch (With annotation features)

Windows:
- System screenshot tool (Win+Shift+S)
- Greenshot (Open source free)
- Snagit (Professional tool)

Cross-platform:
- LightShot
- Flameshot (Open source)
```

### 2. Image Optimization Techniques

#### Compression Optimization
```bash
# ImageOptim (macOS)
imageoptim *.png

# TinyPNG (Online)
# Visit tinypng.com

# Command line tools
# PNG optimization
pngquant --quality=65-80 input.png
optipng -o7 input.png

# JPG optimization
jpegoptim --max=85 input.jpg

# WebP conversion
cwebp -q 80 input.png -o output.webp
```

#### Batch Processing
```bash
# Batch resize
mogrify -resize 1280x720 *.png

# Batch format conversion
for file in *.png; do
    cwebp -q 80 "$file" -o "${file%.png}.webp"
done

# Batch rename
rename 's/Screenshot/screenshot/' *.png
```

### 3. Accessibility Optimization

#### Alt Text Writing
```markdown
<!-- ✅ Good Alt Text -->
![Main interface showing image stitching parameters with crop settings at 20% top and 15% bottom](screenshots/main_interface.png)

<!-- ❌ Poor Alt Text -->
![screenshot](screenshots/main_interface.png)
```

#### Responsive Display
```html
<!-- Provide multiple size versions -->
<picture>
  <source media="(max-width: 600px)" srcset="screenshot_mobile.png">
  <source media="(max-width: 1200px)" srcset="screenshot_tablet.png">
  <img src="screenshot_desktop.png" alt="Description">
</picture>
```

### 4. Version Control

#### Git LFS Usage
```bash
# Initialize LFS
git lfs install

# Track large files
git lfs track "*.png"
git lfs track "*.gif"
git lfs track "*.jpg"

# Commit LFS configuration
git add .gitattributes
git commit -m "Add LFS tracking for images"
```

#### .gitignore Configuration
```gitignore
# Ignore temporary image files
*.tmp
*_temp.*
*_backup.*

# Ignore original high-definition files (if compressed versions exist)
*_original.*
*_hd.*

# Ignore system-generated thumbnails
Thumbs.db
.DS_Store
```

## 📊 Quality Checklist

### Pre-Release Checklist
```markdown
## Technical Quality
- [ ] Correct image formats (PNG/JPG/WebP/SVG)
- [ ] Reasonable file sizes (<2MB regular images, <3MB animations)
- [ ] Sufficient resolution (minimum 800px width)
- [ ] Correct color space (sRGB)

## Visual Quality
- [ ] Clear images, no blur
- [ ] Saturated colors, moderate contrast
- [ ] Reasonable composition, highlighted focus
- [ ] Unified style, professional appearance

## Content Quality
- [ ] Complete interface, clear functionality
- [ ] Readable text, accurate information
- [ ] No sensitive information leakage
- [ ] Use compliant sample content

## Functional Completeness
- [ ] Cover main feature points
- [ ] Show core value proposition
- [ ] Include usage scenario demonstrations
- [ ] Provide operation flow guidance

## Internationalization Considerations
- [ ] Use English interface (if multilingual)
- [ ] Avoid culture-specific elements
- [ ] Universal and clear icon meanings
- [ ] Accurate Alt text descriptions
```

## 📚 References

### Design Inspiration
- [GitHub Explore](https://github.com/explore) - Excellent open source projects
- [Product Hunt](https://producthunt.com) - Product showcase cases
- [Dribbble](https://dribbble.com) - UI design works
- [Behance](https://behance.net) - Brand design cases

### Tool Recommendations
- **Design Tools**: Figma, Sketch, Adobe XD
- **Screenshot Tools**: CleanShot X, Greenshot, Flameshot
- **Optimization Tools**: ImageOptim, TinyPNG, Squoosh
- **Animation Creation**: LICEcap, GIPHY Capture, ScreenToGif

### Learning Resources
- [GitHub Docs - Social Preview](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview)
- [Material Design Guidelines](https://material.io/design)
- [Apple Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/)
