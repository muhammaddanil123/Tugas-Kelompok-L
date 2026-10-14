# Design Tokens & System Specification

## 1. Color Palette

### Primary Colors (Brand)
- `primary-50`: `#F0F6FF`
- `primary-100`: `#E0EDFF`
- `primary-300`: `#82B4FF`
- `primary-500`: `#2563EB` (Base Primary)
- `primary-700`: `#1D4ED8`
- `primary-900`: `#1E3A8A`

### Neutral Colors
- `neutral-0`: `#FFFFFF` (Surface / Card Background)
- `neutral-100`: `#F3F4F6` (App Background)
- `neutral-300`: `#D1D5DB` (Border / Divider)
- `neutral-500`: `#6B7280` (Secondary Text / Placeholder)
- `neutral-900`: `#111827` (Primary Text / Headings)

### Semantic Colors
- `success`: `#10B981` (Feedback Sukses / Success Screen)
- `warning`: `#F59E0B` (Peringatan / Alert)
- `error`: `#EF4444` (Validation / Error State)
- `info`: `#3B82F6` (Informasi / Badges)

---

## 2. Typography (6 Levels)

| Level Token | Font Family | Size / Line Height | Weight | Usage |
| :--- | :--- | :--- | :--- | :--- |
| `heading-xl` | Inter / Poppins | 32px / 40px | Bold (700) | Main Title / Hero |
| `heading-lg` | Inter / Poppins | 24px / 32px | Bold (700) | Screen Header / Page Title |
| `heading-md` | Inter / Poppins | 20px / 28px | SemiBold (600) | Card Title / Section Header |
| `body-lg` | Inter / Poppins | 16px / 24px | Regular (400) | Body Text / Main Content |
| `body-sm` | Inter / Poppins | 14px / 20px | Regular (400) | Secondary Text / Form Label |
| `caption` | Inter / Poppins | 12px / 16px | Medium (500) | Helper Text / Badge / Timestamp |

---

## 3. Spacing Scale (Base 8 system)

- `space-4`: `4px` (Micro spacing / icon gap)
- `space-8`: `8px` (In-component padding / button gap)
- `space-16`: `16px` (Default container padding / input gap)
- `space-24`: `24px` (Section spacing / card padding)
- `space-32`: `32px` (Large gap between blocks)
- `space-48`: `48px` (Screen margin / header offset)

---

## 4. Reusable Figma Components (Min. 6)

1. **Button**: Primary, Secondary, Disabled states (with variants)
2. **Text Input**: Default, Active/Focus, Error, Success states
3. **Card Component**: AI Workflow / Task Card container
4. **Navigation Bar / Header**: Top app navigation
5. **Badge / Chip**: Status indicator (Active, Pending, Completed)
6. **Modal / Toast**: Notification / Alert popup
