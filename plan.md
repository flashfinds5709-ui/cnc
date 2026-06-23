# C&C Property Cleaning Implementation Plan

## Problem Statement
Build a one-page landing page for C&C Property Cleaning, a Long Island New York power washing company. The page should be simple and not bulky, using green, blue, and white. It should include top tabs for Services and About Me, strong instant CTAs, many high-quality stock power-washing photos including before/after style pictures, call button for 631-401-7026, placeholder Google Form consultation button, and placeholder Gmail compose email button.

## Required Content
- Company name: C&C Property Cleaning
- Services: Garbage cans, fences, driveways, wooden decks, custom inquiries
- Garbage cans text: first time customers get $10 per garbage can, after its $15 per garbage can
- About text: Carlo and Collin, cousins from Holtsville, wanting to make your property as clean as theirs.
- Why choose us dropdown text: young and ready to earn your business however necessary. we've helped maintain our parents property since we were young, and are ready to put the same effort into your property as if it were our own
- Service area: only Long Island, New York
- Notice: **Customer must provide access to water supply if required

## User Choices / Clarifications
- Google Form: use placeholder link for now
- Email: use placeholder email for now
- Photos: use high-quality stock power-washing photos
- Tone: simple and not too bulky

## Phase 1: Core POC
Skipped. This is a static one-page marketing site with placeholder outbound links and no external API integration requiring isolated validation.

## Phase 2: Main Landing Page Development
User stories:
1. As a visitor, I can immediately understand C&C Property Cleaning offers power washing on Long Island.
2. As a visitor, I can call 631-401-7026 from a prominent CTA.
3. As a visitor, I can click Book a Consultation and be routed to a placeholder Google Form link.
4. As a visitor, I can click Email and open Gmail compose with a placeholder email prefilled.
5. As a visitor, I can navigate using Services and About Me tabs.
6. As a visitor, I can expand dropdowns for garbage cans, fences, driveways, wooden decks, and custom inquiries, each with relevant imagery.
7. As a visitor, I can see before/after style images and a clean simple layout.
8. As a visitor, I can read the About Me section and Why choose us dropdown.
9. As a visitor, I can see the Long Island only operating area and bold asterisk water supply notice.

## Testing Plan
- Lint/build frontend.
- Testing Agent should verify nav tabs, CTAs, dropdowns, required text, images, responsive visible layout, and no console/runtime errors.

## Current Status
- Phase 1: Skipped intentionally; no complex core integration.
- Phase 2: Main landing page implemented in React/CSS; lint/build and Testing Agent validation pending.
