# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a Custom GPT Social Media Manager project for "Roma Caput Mundi Apartment" - a vacation rental business in Rome's Balduina district. The project focuses on creating an AI-powered system to automate social media content creation, particularly for Facebook marketing.

## Architecture & Core Components

### Business Context
- **Property**: 50m² vacation rental near Vatican (100m from Appiano FS station)
- **Target Market**: Italian and international tourists, couples and small families (1-6 night stays)
- **Current Performance**: 96 nights sold (5 months), €114.98 avg/night, 64% occupancy
- **Revenue Goal**: Increase bookings and reduce dependency on OTA platforms (currently 79.4% Booking.com, 20.6% Airbnb)

### Content Strategy Framework
The mega-prompt.md file contains the complete business analysis and requirements for:

1. **Content Types**:
   - Event-based posts (Roman holidays, festivals, religious events)
   - Educational content (Vatican Museum tips, local restaurant guides)
   - Last-minute offers for low season (Jan-Feb, Nov-Dec)
   - Social proof posts (guest testimonials, reviews)
   - Direct booking incentives (bypass OTA commissions)

2. **Target Audience**:
   - Primary: Ages 28-55, 70% Italian (North Italy), 30% international
   - Composition: 60% couples, 30% young families, 10% solo travelers
   - Psychographics: Value authenticity, cost-effectiveness, local experience

3. **Brand Voice**:
   - Friendly and welcoming ("tu" form in Italian)
   - Local expert with insider knowledge
   - Professional but warm and spontaneous
   - Enthusiastic about Rome without being pushy

## File Structure

```
custom-gpt-social-manager-rcmapt/
├── mega-prompt.md          # Complete business context and GPT instructions
└── CLAUDE.md              # This file
```

## Key Business Metrics & Goals

- **Current Revenue**: €2,208/month average
- **Pricing Optimization**: Currently 18-42% below market rates
- **Occupancy Target**: Increase from 64% to 72-77% (market average)
- **Direct Bookings**: Reduce OTA dependency (currently paying 18-20% commissions)
- **Seasonal Strategy**: Fill low-season gaps (winter months)

## Content Creation Guidelines

When working on social media content for this project:

1. **Tone**: Use the established brand voice (friendly local expert)
2. **Language**: Primarily Italian for domestic market, English for international
3. **Focus Areas**: Position + Services + Vatican proximity + Local authenticity
4. **CTAs**: Emphasize direct bookings with discount incentives
5. **Hashtags**: Use localized tags (#RomaVacanze #VaticanApartment #BalduinaRoma)

## Competitor Context

Key differentiators to emphasize:
- Strategic location (Vatican access without city center chaos)
- Complete apartment privacy vs hotel rooms
- Premium services (Netflix, Sky, fast WiFi) at accessible pricing
- Local residential experience in Balduina neighborhood

## Development Notes

This is primarily a content strategy and prompt engineering project rather than a traditional software development repository. The main deliverable is the mega-prompt.md file which serves as the comprehensive instruction set for the Custom GPT system.

When modifying content:
- Maintain the established business context and metrics
- Keep target audience psychographics consistent
- Preserve the brand voice guidelines
- Ensure social media strategies align with revenue goals (direct bookings, occupancy rate improvement)