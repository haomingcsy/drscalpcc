# DrScalp Images Directory

This directory contains all image assets for the DrScalp landing pages.

## Image Categories

### Hero Images
- `hero-main.jpg` - Main hero background/banner image
- `hero-before-after.jpg` - Before/after comparison for hero section
- `ai-scan-demo.jpg` - AI scalp analysis visualization

### Treatment Process
- `treatment-process-*.jpg` - Step-by-step treatment images
- `zynstem-technology.jpg` - ZynStem technology illustration
- `nanojet-device.jpg` - NanoJet delivery system

### Before/After Gallery
- `before-after-male-*.jpg` - Male patient results
- `before-after-female-*.jpg` - Female patient results
- Format: `before-after-[gender]-[age]-[weeks].jpg`

### Icons & Graphics
- `scalp-analysis-icon.svg` - AI analysis icon
- `treatment-icons/` - Treatment type icons
- `check-icon.svg` - Checkmark for lists
- `logo.svg` - DrScalp logo

### Location Images
- `clinic-raffles.jpg` - Raffles City clinic
- `clinic-orchard.jpg` - Orchard Central clinic
- `clinic-jurong.jpg` - Jurong Point clinic

### Testimonials
- `testimonial-*.jpg` - Customer photos (if using real photos)
- `avatar-placeholder.svg` - Default avatar

### Badges & Certifications
- `certification-*.png` - Medical certifications
- `award-*.png` - Awards and recognitions
- `media-logos/` - Media mentions logos

## Image Specifications

### Recommended Sizes
- Hero images: 1920x1080px (desktop), 768x1024px (mobile)
- Before/After: 600x600px (square format)
- Testimonial photos: 200x200px (square)
- Icons: 64x64px or SVG format
- Location photos: 800x600px

### File Formats
- Photos: JPEG (optimized, 80-85% quality)
- Icons/Graphics: SVG (preferred) or PNG
- Logos: SVG or PNG with transparency

### Optimization Guidelines
1. Compress all images before uploading
2. Use WebP format for modern browsers (with JPEG fallback)
3. Implement lazy loading for below-fold images
4. Use responsive images with srcset for different screen sizes

## Placeholder Images Needed

Priority images to add:
1. [ ] Hero section background or main visual
2. [ ] AI scalp analysis demonstration
3. [ ] Before/after results (at least 4-6 pairs)
4. [ ] Clinic/treatment room photos
5. [ ] ZynStem technology illustration
6. [ ] Doctor/staff photos (optional)
7. [ ] Certification badges

## Usage Examples

```html
<!-- Hero Background -->
<div style="background-image: url('images/hero-main.jpg');">

<!-- Before/After Gallery -->
<img src="images/before-after-male-35-8weeks.jpg" alt="Male patient, 35, results after 8 weeks">

<!-- Treatment Icon -->
<img src="images/treatment-icons/zynstem.svg" alt="ZynStem Bio-Cell Therapy">

<!-- Responsive Image -->
<picture>
  <source media="(max-width: 768px)" srcset="images/hero-mobile.jpg">
  <img src="images/hero-main.jpg" alt="DrScalp Hair Treatment">
</picture>
```

## Notes
- All patient photos must have signed consent forms
- Blur or anonymize faces if required for privacy
- Ensure all before/after photos are authentic and unedited
- Medical claims in images must be verified and compliant