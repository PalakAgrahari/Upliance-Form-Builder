# React + Redux Form Builder

A modern form builder application built with React 19, TypeScript, Redux Toolkit, and Material-UI. Create custom forms with advanced validation, derived fields, and real-time preview.

## 🚀 Live Demo

**[(https://uplianceai-form-builder.vercel.app/)](https://uplianceai-form-builder.vercel.app/)**

## ✨ Features

- **7 Field Types**: Text, Number, Textarea, Select, Radio, Checkbox, Date
- **Advanced Validation**: Required fields, length constraints, email format
- **Derived Fields**: Auto-calculating fields (age from birth date, sum of numbers)
- **Drag & Drop**: Animated field reordering
- **Dual Themes**: Light/Dark mode toggle
- **Auto-Save**: Draft recovery system
- **localStorage**: No backend required

## 🛠️ Tech Stack

- React 19 + TypeScript
- Redux Toolkit
- Material-UI (MUI) v7
- Framer Motion
- Vite

## 🚀 Quick Start

```
# Clone and install
git clone https://github.com/PalakAgrahari/Upliance-Form-Builder.git
cd Upliance-Form-Builder
npm install

# Start development
npm run dev

# Build for production
npm run build
```

## 📱 Usage

### Creating Forms
1. Navigate to `/create`
2. Add fields with validation rules
3. Configure derived fields for calculations
4. Drag to reorder, save with custom name

### Derived Fields Example
```
// Age calculation
Field Type: Number
✅ Derived Field
Formula: "Age from Birth Date"
Parent Field: "Birth Date"
```

## 🌐 Deployment

Ready for Vercel deployment with included `vercel.json`:
1. Push to GitHub
2. Import in Vercel
3. Auto-deploy on git push

## 🔧 Key Capabilities

- **Real-time Preview**: Live form rendering with validation
- **Form Dashboard**: Grid view of saved forms
- **Custom Formulas**: JavaScript expressions for complex calculations
- **Responsive Design**: Works on all devices
- **Performance**: Code splitting and optimized bundles

## 🏗️ Project Structure

```
src/
├── components/FormBuilder/    # Form creation
├── components/FormRenderer/   # Form preview
├── pages/                    # Routes
├── store/                    # Redux state
└── utils/                    # Helpers
```

