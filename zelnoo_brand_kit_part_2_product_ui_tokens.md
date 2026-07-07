# Zelnoo Brand Identity Kit — Part 2

## Product UI, Portals, UX, and Technical Tokens

**Version:** 1.0 Working Draft  
**Brand:** Zelnoo  
**Primary Brand Colour:** `#F08E04`

---

## 1. UI Component System

### 1.1 Buttons

#### Primary Button

Use for the main action on a screen.

| Property | Value |
|---|---|
| Background | `#F08E04` |
| Text | `#000000` |
| Font | DM Sans 600 |
| Radius | 12 px |
| Height Desktop | 48 px |
| Height Mobile | 48–52 px |
| Hover | `#D97704` |
| Disabled | `#E5E7EB` background, `#9CA3AF` text |

Examples:

- Book Test
- Confirm Pickup
- Upload Report
- Save Pricing
- Make Payment

#### Secondary Button

Use for important but non-primary actions.

| Property | Value |
|---|---|
| Background | `#000000` |
| Text | `#FFFFFF` |
| Hover | `#111111` |

#### Outline Button

Use for optional actions.

| Property | Value |
|---|---|
| Background | Transparent / White |
| Border | `#000000` or `#E5E7EB` |
| Text | `#000000` |

#### Ghost Button

Use for low-emphasis actions in dense UI.

| Property | Value |
|---|---|
| Background | Transparent |
| Text | `#1A1A1A` or `#6B7280` |
| Hover | `#F9FAFB` |

### 1.2 Button Copy Rules

Use action verbs. Keep buttons short.

| Good | Avoid |
|---|---|
| Book Test | Click Here |
| Confirm Pickup | Proceed With Completion of Sample Pickup |
| Upload Report | Upload the Final Diagnostic Report PDF |
| View Details | More |
| Pay Now | Payment Action |

### 1.3 Cards

Cards are central to Zelnoo because customers will compare labs, tests, prices, TAT, and quality indicators.

#### Diagnostic Center Card Must Include

- Center name.
- Distance or service area.
- Price or package price.
- TAT / report time.
- Accreditation / verification badge where applicable.
- Home pickup availability.
- Rating / quality score only if verified.
- Primary CTA: Book / View Details.

#### Card Style

| Property | Value |
|---|---|
| Background | White |
| Border | `1px solid #E5E7EB` |
| Radius | 16–20 px |
| Padding | 16–24 px |
| Shadow | `shadow-sm` default; `shadow-md` hover |
| Highlight | Use orange only for price, CTA, selected state, or recommended badge |

### 1.4 Inputs and Forms

| Property | Value |
|---|---|
| Height | 48–52 px |
| Border | `#E5E7EB` |
| Focus Border | `#F08E04` |
| Focus Ring | `rgba(240,142,4,0.16)` |
| Radius | 10 px |
| Label | DM Sans 600, 13–14 px |
| Helper Text | DM Sans 400, 12–13 px, muted grey |

### 1.5 Badges and Chips

| Badge Type | Background | Text | Usage |
|---|---|---|---|
| Verified | `#DCFCE7` | `#166534` | Verified lab, verified phlebotomist. |
| NABL | `#FFF3D6` | `#92400E` | Accreditation badge. |
| Fast Report | `#DBEAFE` | `#1D4ED8` | TAT highlight. |
| Home Pickup | `#F1F5F9` | `#334155` | Service feature. |
| Recommended | `#000000` | `#F08E04` | Platform ranking / highlighted result. |
| Delayed | `#FEF3C7` | `#92400E` | Operational warning. |
| Issue | `#FEE2E2` | `#991B1B` | Sample or dispute issue. |

### 1.6 Tables and Dashboards

Use tables for admin, lab, finance, catalog, pricing, and inventory workflows.

Rules:

- Header row: neutral grey background, 12 px uppercase labels.
- Row height: 48–56 px.
- Use zebra striping only when needed for dense data.
- Use status chips instead of coloured full rows.
- Use orange sparingly for selected row or primary action.
- Use DM Mono for IDs.

### 1.7 Status System

| Status | Colour | UI Treatment |
|---|---|---|
| Draft | Neutral | Grey chip. |
| Pending | Warning | Yellow/amber chip. |
| Confirmed | Info | Blue chip. |
| Assigned | Info | Blue or teal chip. |
| Collected | Teal / Success | Teal chip in phlebotomy flow. |
| Delivered to Lab | Success | Green chip. |
| Report Uploaded | Success | Green chip. |
| Completed | Success | Green chip. |
| Cancelled | Error | Red chip. |
| Disputed | Error / Warning | Red or amber chip depending on severity. |

### 1.8 Trust Badges

Trust badges are important but must be factual.

Approved badge categories:

- Verified Lab
- NABL Accredited
- Home Collection Available
- Digital Reports
- Fast TAT
- Trained Phlebotomist
- Secure Payment
- Report Vault
- Quality Monitored

Avoid badges unless the claim is operationally true.

---

## 2. Product Experience Guidelines

### 2.1 Consumer App

Consumer UI must be simple, reassuring, and fast.

| Screen | Brand Guidance |
|---|---|
| Splash / Onboarding | Use centered icon/lockup, orange gradient or white background. |
| Search | Large search bar, clear test/category suggestions. |
| Results | Compare price, TAT, distance, pickup, accreditation. |
| Booking | Reduce steps; show date, time, address, patient, payment. |
| Order Tracking | Use timeline style with clear operational status. |
| Reports Vault | Clean file cards, family filters, report metadata. |
| Profile / Family | Soft orange highlights, minimal form friction. |

#### Consumer Copy Style

| Context | Example |
|---|---|
| Search placeholder | “Search tests, packages, or diagnostic centers” |
| Booking CTA | “Book Test” |
| Home pickup note | “A trained collection partner will visit your selected address.” |
| Report vault | “Your reports will be saved securely for future access.” |
| Price transparency | “Prices may vary by lab, package, and location.” |

### 2.2 Phlebotomist / Partner App

The phlebotomist app is operational. It must prioritize clarity, speed, hygiene, chain-of-custody, and task completion.

Visual rules:

- Use high-contrast task cards.
- Use large CTAs for field use.
- Use clear pickup/delivery statuses.
- Use teal only for route/logistics context; primary actions remain orange.
- Use warning/error states clearly for sample issues.

| Screen | Required Information |
|---|---|
| Today’s Tasks | Pickup time, address, patient initials, test type, required vial/inventory. |
| Task Detail | Patient info, collection instructions, lab destination, QR/sample ID. |
| Collection Checklist | Vials, labels, consent, hygiene, packaging, biohazard bag. |
| Handover | Lab confirmation, timestamp, photo/QR scan if applicable. |
| Issue Reporting | Missed pickup, wrong address, insufficient sample, patient unavailable. |

### 2.3 Lab / Diagnostic Center Portal

The lab portal should feel professional, structured, and business-grade.

Key areas:

- Onboarding and verification.
- Catalog upload and mapping.
- Pricing and TAT management.
- Slot calendar.
- Order management.
- Report upload.
- Dispute and refund coordination.

Visual rules:

- Use tables and structured forms.
- Use orange for save/update actions.
- Use amber for pricing/TAT highlights.
- Use clear document upload states.
- Keep the interface utilitarian, not decorative.

### 2.4 Doctor Portal

Doctor-facing UI should feel clinically respectful and low-friction.

Visual rules:

- Use white background and blue accents for clinical workflow.
- Orange only for Zelnoo brand CTA.
- Avoid flashy marketing language.
- Focus on patient consent, prescriptions, report tracking, and recommendations.

### 2.5 Admin Console

The admin console is for internal control and governance.

Visual rules:

- Use neutral UI with strong information hierarchy.
- Use dark headers or sidebars where needed.
- Use orange for primary actions and active navigation.
- Use semantic colours for disputes, delays, refunds, and quality issues.

Admin must support:

- Partner verification.
- Catalog mapping review.
- Booking/order monitoring.
- Dispute and refund workflows.
- Quality scoring.
- Fraud/anomaly signals.
- Manual ranking overrides.

---

## 3. Website Brand Guidelines

### 3.1 Website Visual Direction

The website should be premium, conversion-focused, and trust-building.

Recommended homepage sections:

1. Hero: Diagnostics, democratized.
2. Search or booking CTA.
3. How Zelnoo works.
4. Compare diagnostic centers.
5. Doorstep collection.
6. Reports vault.
7. For labs / doctors / partners.
8. Trust, quality, and transparency.
9. FAQs.
10. Final CTA.

### 3.2 Website Hero Example

```text
Headline:
Diagnostics, democratized.

Subheadline:
Compare diagnostic centers, book tests from home, and access your reports in one secure place.

Primary CTA:
Book a Test

Secondary CTA:
Partner with Zelnoo
```

### 3.3 Website Header Rules

| Element | Rule |
|---|---|
| Logo | Top left, horizontal lockup. |
| Navigation | Simple: Book Tests, For Labs, For Doctors, Partner, About. |
| CTA | Orange button: Book Test / Get Started. |
| Background | White or transparent over dark hero. |
| Mobile | Use hamburger menu with logo and CTA retained. |

### 3.4 Website Footer Rules

Footer should use black background with orange highlights.

Include:

- Zelnoo logo.
- Tagline.
- Product links.
- Partner links.
- Company links.
- Legal links.
- Contact email / phone.
- Address where applicable.
- Disclaimer for healthcare interpretation.

---

## 4. Mobile App Brand Guidelines

### 4.1 App Icon

The app icon should use the Zelnoo icon only. Avoid small tagline or full wordmark in the app icon.

| Element | Rule |
|---|---|
| Icon | Circular Z mark. |
| Background | Orange gradient or black. |
| Safe Area | Keep icon away from rounded app icon corners. |
| Text | No text inside app icon. |

### 4.2 Splash Screen

| Option | Style |
|---|---|
| Premium Dark | Black background, centered full-colour icon, orange wordmark. |
| Clean White | White background, centered icon + wordmark. |
| Orange Gradient | Orange/gold gradient background, black/white logo. |

### 4.3 Bottom Navigation

| State | Style |
|---|---|
| Active | Orange icon + label. |
| Inactive | Muted grey icon + label. |
| Background | White with subtle top border. |
| Icon Size | 22–24 px. |
| Label | 11–12 px DM Sans. |

Suggested consumer app tabs:

1. Home
2. Search
3. Bookings
4. Reports
5. Profile

### 4.4 Mobile Card Rules

- Use large tappable cards.
- Avoid dense table-style layouts on mobile.
- Prioritize test name, lab name, price, TAT, and CTA.
- Use chips for key service features.
- Keep primary CTA visible without scrolling where possible.

---

## 5. Data, Privacy, and Consent UI Language

### 5.1 Consent Principles

| Principle | Rule |
|---|---|
| Specific | Say what data will be shared. |
| Purpose-led | Say why it is being shared. |
| Reversible | Explain whether access can be revoked. |
| Minimal | Do not ask for unnecessary permissions. |
| Plain language | Avoid legal-heavy UI copy. |

### 5.2 Consent Copy Examples

#### Doctor Report Access

```text
Allow Dr. {doctor_name} to view this report?
They will be able to access the selected report for consultation purposes. You can revoke access later from report sharing settings.
```

#### Family Profile

```text
Add this family member to manage bookings and reports from your account. Use this only if you are authorized to manage their health information.
```

#### Report Vault

```text
Your reports are stored for easy access. Do not share reports with others unless you trust them.
```

---

## 6. Charts, Data Visualization, and Dashboards

### 6.1 Chart Colour Rules

| Data Type | Colour |
|---|---|
| Primary metric | Zelnoo Orange `#F08E04`. |
| Secondary metric | Slate `#334155`. |
| Positive trend | Success `#16A34A`. |
| Warning trend | Warning `#F59E0B`. |
| Negative trend | Error `#DC2626`. |
| Neutral comparison | Grey `#94A3B8`. |

### 6.2 Chart Rules

Do:

- Label charts clearly.
- Use simple bar, line, area, and donut charts.
- Use orange only for the key metric.
- Include date range and data source.
- Use readable legends.

Avoid:

- 3D charts.
- Too many colours.
- Unlabeled axes.
- Decorative charts without decision value.
- Using red/green only without labels.

### 6.3 Dashboard Metric Cards

Metric cards should include:

- Metric title.
- Current value.
- Change indicator.
- Time period.
- Optional supporting note.

Example:

```text
Bookings Today
124
+18% vs yesterday
Updated 10:30 AM
```

---

## 7. Design Tokens

### 7.1 CSS Variables

```css
:root {
  /* Brand */
  --zelnoo-primary: #F08E04;
  --zelnoo-primary-light: #FABA0A;
  --zelnoo-primary-dark: #D97704;
  --zelnoo-primary-soft: #FFF3D6;

  /* Neutrals */
  --zelnoo-black: #000000;
  --zelnoo-dark: #111111;
  --zelnoo-text: #1A1A1A;
  --zelnoo-muted: #6B7280;
  --zelnoo-border: #E5E7EB;
  --zelnoo-off-white: #FAFAF9;
  --zelnoo-white: #FFFFFF;

  /* Semantic */
  --success: #16A34A;
  --success-soft: #DCFCE7;
  --warning: #F59E0B;
  --warning-soft: #FEF3C7;
  --error: #DC2626;
  --error-soft: #FEE2E2;
  --info: #2563EB;
  --info-soft: #DBEAFE;

  /* Fonts */
  --font-display: 'Syne', sans-serif;
  --font-body: 'DM Sans', sans-serif;
  --font-mono: 'DM Mono', monospace;

  /* Radius */
  --radius-sm: 6px;
  --radius-md: 10px;
  --radius-lg: 12px;
  --radius-xl: 16px;
  --radius-2xl: 20px;
  --radius-full: 999px;

  /* Shadows */
  --shadow-sm: 0 1px 2px rgba(0,0,0,0.06);
  --shadow-md: 0 4px 12px rgba(0,0,0,0.08);
  --shadow-lg: 0 12px 32px rgba(0,0,0,0.12);
  --shadow-orange: 0 8px 24px rgba(240,142,4,0.22);
}
```

### 7.2 Tailwind Token Mapping

```js
const zelnooTheme = {
  colors: {
    zelnoo: {
      primary: '#F08E04',
      light: '#FABA0A',
      dark: '#D97704',
      soft: '#FFF3D6',
      black: '#000000',
      darkText: '#1A1A1A',
      muted: '#6B7280',
      border: '#E5E7EB',
      offWhite: '#FAFAF9',
      white: '#FFFFFF',
    },
    success: '#16A34A',
    warning: '#F59E0B',
    error: '#DC2626',
    info: '#2563EB',
  },
  fontFamily: {
    display: ['Syne', 'sans-serif'],
    body: ['DM Sans', 'sans-serif'],
    mono: ['DM Mono', 'monospace'],
  },
  borderRadius: {
    sm: '6px',
    md: '10px',
    lg: '12px',
    xl: '16px',
    '2xl': '20px',
  },
};
```

### 7.3 React Native Theme

```ts
export const zelnooTheme = {
  colors: {
    primary: '#F08E04',
    primaryLight: '#FABA0A',
    primaryDark: '#D97704',
    primarySoft: '#FFF3D6',
    black: '#000000',
    dark: '#111111',
    text: '#1A1A1A',
    muted: '#6B7280',
    border: '#E5E7EB',
    background: '#FAFAF9',
    surface: '#FFFFFF',
    success: '#16A34A',
    warning: '#F59E0B',
    error: '#DC2626',
    info: '#2563EB',
  },
  radius: {
    sm: 6,
    md: 10,
    lg: 12,
    xl: 16,
    xxl: 20,
    full: 999,
  },
  spacing: {
    1: 4,
    2: 8,
    3: 12,
    4: 16,
    5: 20,
    6: 24,
    8: 32,
    10: 40,
    12: 48,
    16: 64,
  },
};
```

---

## 8. Figma / Design File Guidelines

### 8.1 Figma Page Structure

```text
Zelnoo Brand System
  00_Cover
  01_Logos
  02_Colours
  03_Typography
  04_Grid_And_Spacing
  05_Components_Web
  06_Components_Mobile
  07_Admin_Components
  08_Marketing_Templates
  09_Print_Templates
  10_Operations_Assets
  11_Archived_Old_Brand
```

### 8.2 Figma Naming Rules

```text
Logo/Primary/Horizontal/FullColour
Logo/Icon/FullColour
Logo/Icon/Black
Logo/Icon/White
Button/Primary/Default
Button/Primary/Hover
Button/Primary/Disabled
Card/DiagnosticCentre/Default
Badge/VerifiedLab
Badge/NABL
Input/Text/Default
Input/Text/Focus
Status/Booking/Confirmed
Status/Booking/Completed
```

### 8.3 Component Variant Rules

| Component | Required Variants |
|---|---|
| Button | Primary, secondary, outline, ghost, disabled, loading. |
| Input | Default, focus, filled, error, disabled. |
| Badge | Verified, NABL, home pickup, recommended, delayed, issue. |
| Card | Default, hover, selected, disabled, loading. |
| Modal | Small, medium, large, confirmation, warning. |
| Table Row | Default, hover, selected, error, delayed. |
| Navigation | Default, active, collapsed, mobile. |

### 8.4 Auto Layout Rules

- Use auto layout for all cards, forms, navigation, and buttons.
- Use 8 px spacing increments.
- Do not manually place text over images without a defined overlay.
- Keep reusable components detached only when final artwork is exported for print.
- Use design tokens as Figma variables wherever possible.

---

## 9. Developer Rules by Platform

### 9.1 Web Development

- Use the shared design token file.
- Use reusable components for buttons, cards, inputs, badges, modals, tables, and status chips.
- Do not hardcode colours except where the token file is unavailable.
- Use the same component rules for consumer web, lab portal, doctor portal, and admin console.
- Maintain responsive behaviour for mobile, tablet, and desktop.

### 9.2 Mobile Development

- Use the same colour tokens as web.
- Keep primary actions orange.
- Keep bottom navigation simple.
- Use large tap areas for field users.
- Avoid overloading phlebotomist screens with marketing visuals.

---

## 10. First Product Release Checklist

### 10.1 Product Tokens

| Item | Status |
|---|---|
| CSS tokens | Pending / Done |
| Tailwind theme | Pending / Done |
| React Native theme | Pending / Done |
| Figma variables | Pending / Done |
| Button components | Pending / Done |
| Card components | Pending / Done |
| Input components | Pending / Done |
| Badge/status components | Pending / Done |
| Dashboard/table components | Pending / Done |

### 10.2 Product Screens

| Area | Status |
|---|---|
| Website hero | Pending / Done |
| Consumer app splash | Pending / Done |
| Consumer search/results | Pending / Done |
| Booking flow | Pending / Done |
| Reports vault | Pending / Done |
| Phlebotomist task flow | Pending / Done |
| Lab portal dashboard | Pending / Done |
| Doctor portal dashboard | Pending / Done |
| Admin console dashboard | Pending / Done |

