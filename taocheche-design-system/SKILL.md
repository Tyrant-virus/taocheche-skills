---
name: "taocheche-design-system"
description: "Editorial Mobility Guidelines for high-end automotive experiences. Invoke when designing UI, styling components, or applying brand identity for Taocheche/automotive projects."
---

# Taocheche Design System: Editorial Mobility Guidelines

This skill provides the creative and technical foundation for transforming functional marketplaces into high-end editorial experiences.

## 1. Creative North Star: "The Curated Engine"
- **Focus**: Precision Typography & Tonal Depth.
- **Style**: Luxury automotive journal feel, intentional asymmetry, overlapping glass containers.
- **Visuals**: Reject traditional borders; use background color shifts or tonal transitions.

## 2. Colors: Tonal Architecture
### Brand Colors
- **Brand Blue (Main)**: `#285AF0` (Use for highlights and buttons only).
- **Blue Tints**: `#547FFF`, `#7B9AFB`, `#A4BFFF`, `#C4D2FF`, `#CEDAFF`, `#D8E1FF`, `#F3F5FF`.
- **Brand Yellow**: `#FFE900` (Urgent CTAs/Flash sales only), `#FFEF99`, `#FFFBD1`.

### Grey Colors (Text & Surfaces)
- **Grey-1 (Main Text)**: `#1A1F29`
- **Grey-2**: `#2F363E` | **Grey-3**: `#666A75` | **Grey-4**: `#8C8F99`
- **Grey-5 (Borders/Secondary)**: `#C4C6CC` | **Grey-6**: `#DADADD` | **Grey-7 (Base Surface)**: `#F3F4F9`

### Auxiliary Colors
- **Orange**: `#F48C00`, `#FFB53D`, `#FFE0AA`, `#FFF8E8`
- **Red**: `#E22222`, `#F06565`, `#FFB6B6`, `#FCDADA`, `#FCE9E9`
- **Green**: `#01A45D`, `#68CFA2`, `#B4EED5`

### Surface Hierarchy
- **Surface (Base)**: `#F3F4F9`.
- **Surface-Container-Low**: `#F8F9FB`.
- **Surface-Container-Highest**: `#EDF2FF`.
- **Glassmorphism**: Backdrop-blur 12px–20px, semi-transparent surfaces.

## 3. Typography: Editorial Authority
- **Primary Typeface**: System native (PingFang SC for iOS, Roboto for Android).
- **Numerical/Price Authority**: **Avenir Black** (Regular and Oblique) for all high-value vehicle prices.

### Type Scale
| Token | Size | Weight | Usage |
|-------|------|--------|-------|
| T1 Detail Price | 27px | Avenir Black | Vehicle price in detail pages. |
| T2 Large Title | 20px | Semibold (600) | Root titles, Entry titles. |
| T3 Medium Title| 17px | Medium (500) | Tab titles, Module headers. |
| T4 Small Title | 14px | Regular (400) | List titles, Product titles. |
| T5 Body | 12px | Regular (400) | Standard UI text. |
| T6 Small Body | 11px | Regular (400) | Secondary metadata. |
| T7 Note | 10px | Regular (400) | Footnotes, Micro-copy. |

## 4. Corner Radius: Precision Geometry
- **2PX**: Tags, Smallest buttons.
- **4PX**: **Standard** (Cards, Buttons, Search bars, Product images).
- **10PX**: Modals and Popups.
- **14PX**: Large featured cards in detail pages.
- **Full (Pill)**: Special action buttons.

## 5. Grid: Layout Structure
- **12-Column Layout**.
- **Gutter (水槽)**: 7px.
- **Page Margin (页面安全距离)**: 12px.
- **Card Horizontal Spacing (卡片横向间距)**: 10px.

## 6. Elevation & Depth: Layering
- **Tonal Layering**: Stack `surface_container_lowest` cards on `surface_container_low` backgrounds.
- **The Ghost Border**: Use 10% opacity `outline_variant` if definition is needed. Solid 1px borders are forbidden for sectioning.

## 7. Components
### Buttons
| Type | Height | Font Size | Corner Radius |
|------|--------|-----------|---------------|
| Large | 44px | 16px | 4px |
| Medium | 38px | 15px | 4px |
| Small | 28px | 12px | 4px |
| Extra Small| 24px | 12px | 4px |
- **Sticky Bottom**: 12px safe distance from page bottom.

## 8. Do's and Don'ts
### Do:
- Always pair vehicle prices (**Avenir Black**) with descriptive labels (**PingFang SC**).
- Use **12px page margins** for mobile layouts.
- Apply **10px horizontal spacing** between cards.
- Apply **Brand Blue (#285AF0)** to primary call-to-action buttons.
- Separate car listings using the **4px spacing scale** instead of divider lines.

### Don't:
- **Never use 1px solid dividers** to separate list items. Use whitespace or tonal shifts.
- Don't use standard grey shadows; tint shadows with a hint of brand blue.
- Don't use Brand Blue for large background blocks.
- Don't mix font weights within a single numerical price.
