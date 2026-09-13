# Reusable Form Components — React + TypeScript

A component-driven job application form built with React, TypeScript, and CSS Modules. Each form element is a self-contained, reusable component with typed props, scoped styles, and native HTML attribute forwarding for maximum composability.
Built as a design challenge for optilyz.


# Components
* InputField:	Text input with label, extending native InputHTMLAttributes via prop spread for full HTML compatibility
* Upload:	File upload field with drag-and-drop styling and label
* Checkbox:	Labelled checkbox with required-field indicator
* Button:	Submit button extending native ButtonHTMLAttributes for composability
* Banner:	Job listing header displaying title, position type, location, and country
* Header:	Top navigation bar with logo
* Form:	Composed layout assembling all field components into a complete application form

# Stack
* React 17 with TypeScript (strict mode)
* CSS Modules for scoped, collision-free styling
* Create React App
* GitHub Actions for auto-deploy to GitHub Pages

# Project Structure
src/
├── Components/
│   ├── BannerComponent/      Banner.tsx + Banner.module.css
│   ├── ButtonComponent/      Button.tsx + Button.module.css
│   ├── CheckboxComponent/    Checkbox.tsx + Checkbox.module.css
│   ├── FormComponent/        Form.tsx + Form.module.css
│   ├── HeaderComponent/      Header.tsx + Header.module.css
│   ├── InputfieldComponent/  InputField.tsx + InputField.module.css
│   └── UploadComponent/      Upload.tsx + Upload.module.css
├── Assets/
├── App.tsx
├── ApplicationForm.tsx
└── index.tsx
Each component lives in its own folder with a co-located CSS Module, keeping styles scoped and the codebase easy to navigate.
