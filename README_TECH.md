# 🚀 Caldas Detail Garage - AI Pitch Presentation

## 📋 Project Overview

**Bilingual presentation** for pitching MecanoIA's SofIA AI assistant to Caldas Detail Garage, a premium automotive detailing business with multi-million EUR revenue.

## 🏗️ Technical Stack

```yaml
Frontend: Pure HTML5/CSS3/JavaScript
Design: Premium black/gold luxury aesthetic  
Internationalization: Data attributes (data-pt, data-en)
Navigation: Arrow controls + keyboard support
Responsive: Mobile/tablet/desktop optimized
Deployment: Netlify (static hosting)
```

## 📁 Project Structure

```
pitch_cdg/
├── presentation/
│   └── index.html          # Main bilingual presentation
├── netlify.toml           # Deployment configuration
├── RESUMO_EXECUTIVO.md    # Executive summary (dev/AGI readable)
├── README.md             # Technical documentation
└── strategy.md           # Business strategy notes
```

## 🎯 Features

### **Core Functionality**
- ✅ 10-slide bilingual presentation (PT/EN)
- ✅ Real-time language toggle (🌐 button)
- ✅ Arrow navigation with slide counter
- ✅ Keyboard controls (←/→ arrow keys)
- ✅ Premium design matching client aesthetic
- ✅ Responsive design for all devices

### **Content Focus**
- 🏢 Premium automotive business transformation
- 🤖 AI assistant (SofIA) integration
- 🏄‍♂️ Street/surf lifestyle brand support
- 📈 ROI-focused value proposition
- ⚡ Realistic implementation timeline

## 🚀 Deployment

### **Netlify Setup**
```bash
# 1. Push to GitHub
git add .
git commit -m "Production ready presentation"
git push origin main

# 2. Connect to Netlify
# - Import from GitHub: groovaloo/pitch_cdg
# - Build settings: Auto-configured via netlify.toml
# - Domain: caldas-pitch.netlify.app (suggested)
```

### **Local Development**
```bash
# Serve locally
cd presentation/
python3 -m http.server 8000
# Or
npx serve .
```

## 🔧 Configuration

### **Language System**
```html
<!-- Bilingual elements use data attributes -->
<h2 data-pt="Título em Português" data-en="English Title">
  Default Text (Portuguese)
</h2>
```

### **Navigation Controls**
```javascript
// Keyboard support
document.addEventListener('keydown', (e) => {
    if (e.key === 'ArrowLeft') previousSlide();
    if (e.key === 'ArrowRight') nextSlide();
});
```

## 📊 Business Context

### **Client Profile**
```yaml
Company: Caldas Detail Garage
Revenue: Multi-million EUR annually
Services: Premium automotive detailing (€500-€3,000)
Pain Points: 
  - No 24/7 customer support
  - New brand launch management needed
  - VIP client expectations
```

### **Pitch Strategy**
- **Value Prop**: Enterprise AI for luxury automotive business
- **ROI Logic**: Single lost €3k client = 8+ months of AI investment
- **Integration**: CRM compatibility analysis required
- **Expansion**: Street/surf lifestyle brand support

## 🎨 Design System

### **Color Palette**
```css
:root {
    --primary-black: #000000;
    --luxury-gold: #FFD700;
    --text-white: #FFFFFF;
    --accent-gray: #333333;
    --gradient-gold: linear-gradient(135deg, #FFD700, #FFA500);
}
```

### **Typography**
```css
font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
/* Luxury aesthetic with clean, modern typography */
```

## 🔒 Security & Performance

### **Netlify Configuration**
- Security headers configured
- Asset caching optimized  
- XSS protection enabled
- Content type validation

### **Performance**
- Static HTML (no build process needed)
- Optimized images
- Efficient CSS/JS
- CDN delivery via Netlify

## 📝 Development Notes

### **Recent Updates**
- ✅ Fixed language toggle functionality
- ✅ Added street/surf emoji (🏄‍♂️) for new brand
- ✅ Removed unrealistic 48h promises
- ✅ Corrected broken emoji displays
- ✅ Updated executive summary for dev/AGI compatibility

### **Known Issues**
- None currently reported

## 🎯 Usage Instructions

### **For MEC Meeting**
1. Open presentation in Chrome/Safari (recommended)
2. Use arrow buttons or keyboard (←/→) for navigation
3. Click 🌐 to toggle PT/EN languages
4. Slides progress: Business problem → Solution → Integration → ROI

### **For Developers**
- All code is self-contained in `index.html`
- No build process or dependencies required
- Easy to modify content via data attributes
- Responsive design works on any device

## 🤝 Contributing

This is a client-specific presentation. For updates:
1. Test locally before deployment
2. Maintain bilingual content consistency
3. Preserve luxury design aesthetic
4. Keep business context accurate

---

**Ready for MEC presentation! 🎯**