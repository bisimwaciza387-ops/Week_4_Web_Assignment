# SpendWise Dashboard

## About the Project

SpendWise is a modern financial dashboard designed to help users view and understand their spending categories.

This project was created using HTML and CSS. It focuses on building a responsive dashboard layout using CSS Grid, Flexbox, CSS custom properties, and simple card micro-interactions.

## What I Built

The dashboard contains:

- Sidebar navigation
- Dashboard header
- Financial summary cards
- Six spending category cards
- Responsive mobile layout
- Hover and keyboard focus effects
- Light and dark themes

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Custom Properties
- Media Queries

## Dashboard Sections

### Sidebar

The sidebar contains navigation links for:

- Dashboard
- Income
- Expenses
- Reports
- Settings

### Header

The header displays the dashboard title, a welcome message, the current month, and a user profile.

### Summary

The summary section displays:

- Total Budget
- Total Spent
- Remaining Balance

### Spending Categories

The dashboard contains six financial categories:

1. Food
2. Transport
3. Rent
4. Entertainment
5. Savings
6. Utilities

Each card contains realistic static financial information.

## Responsive Design

A media query is used at 768px to make the dashboard responsive.

On smaller screens:

- The sidebar changes to a single-column layout.
- Summary cards stack vertically.
- Category cards stack vertically.
- Header content adapts to smaller screens.

## Micro-interactions

The category cards include hover and keyboard focus effects.

The effects use:

- `transform`
- `box-shadow`
- `transition`

The animation duration is 200ms.

## Dark Theme

The project includes a dark theme using:

```css
@media (prefers-color-scheme: dark)
