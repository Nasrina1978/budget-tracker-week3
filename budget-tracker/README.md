# Budget Tracker - Week 3 Visual Design

A clean, responsive budget tracker built with HTML and CSS.

## 1. Color Palette (25%)
I used a professional fintech palette for consistency and contrast:
- **Background: #F8FAFC** - light slate for page background, reduces eye strain
- **Primary Navy: #0F172A** - for headings and table header, creates strong hierarchy
- **Accent Teal: #14B8A6** - for primary button (Add Expense) and balance highlight, indicates action
- **Accent Coral: #F43F5E** - for delete buttons
- **Badges:** Housing #D1FAE5/#065F46, Food #FEF3C7/#92400E, Transport #DBEAFE/#1E40AF

Applied consistently across header, buttons, badges, and table header.

## 2. Typography (20%)
- **Headings: Poppins (600, 700)** - from Google Fonts, bold and modern for Budget Tracker titles
- **Body: Inter (400, 500, 600)** - from Google Fonts, highly readable for forms and tables
- Hierarchy: h1 2.2rem, h2 1.25rem with bottom border, table headers uppercase 0.85rem

## 3. Table and Form Styling (30%)
- **Form:** Inputs have padding 12px 14px, border-radius 10px, border 1.5px solid #E2E8F0, background #F8FAFC. Focus state changes border to teal #14B8A6 with soft shadow. Form rows use flex with gap 20px.
- **Table:** Wrapped in .table-wrapper with border-radius 12px and border. Header dark navy #0F172A with white text, uppercase. Cells have padding 14px 16px. Rows alternate white and #F8FAFC, hover #F0FDFA. Badges styled with rounded pill shape.

## 4. Box Model (25%)
Every major section is a card using Box Model principles:
- **margin-bottom: 28px** - separates cards vertically
- **padding: 32px** - internal spacing
- **border: 1px solid #E2E8F0** - subtle definition
- **border-radius: 16px** - modern rounded corners
- **box-shadow: 0 4px 12px rgba(15,23,42,0.05)** - depth

Cards: header-card (with gradient), form-card, table-card. All responsive with media query for mobile.

## How to Run
Open index.html with Live Server (VS Code) at 127.0.0.1:5500