# Health Facility Locator — User Stories

## Overview

This document defines the key user stories for the Health Facility Locator feature.

The user stories describe what users should be able to do and why the functionality is important.

---

## Epic 1: Location Access

### US-001 — Detect Current Location

**As a** user,  
**I want to** allow the application to access my current location,  
**so that** I can find health facilities near me.

### US-002 — Search for a Location

**As a** user,  
**I want to** search for a location manually,  
**so that** I can find health facilities in another area even when I am not physically there.

### US-003 — Handle Location Permission Denial

**As a** user,  
**I want to** continue using the locator when I deny location permission,  
**so that** I can still search for health facilities manually.

---

## Epic 2: Map and Facility Discovery

### US-004 — View Facilities on a Map

**As a** user,  
**I want to** see health facilities displayed on an interactive map,  
**so that** I can understand where they are located.

### US-005 — View Facility Markers

**As a** user,  
**I want to** see individual facility markers on the map,  
**so that** I can identify facilities within my selected area.

### US-006 — Explore the Map

**As a** user,  
**I want to** zoom, move and explore the map,  
**so that** I can understand the surrounding geographical area.

---

## Epic 3: Facility Search and Filtering

### US-007 — Search for Health Facilities

**As a** user,  
**I want to** search for health facilities based on a location,  
**so that** I can find relevant facilities in that area.

### US-008 — Filter by Facility Type

**As a** user,  
**I want to** filter facilities by type,  
**so that** I can find the type of healthcare facility I need.

**Facility types include:**

- Hospitals
- Clinics
- Laboratories
- Pharmacies

### US-009 — Filter by Health Service

**As a** user,  
**I want to** filter facilities by available health services,  
**so that** I can find facilities that provide the specific service I need.

**Initial services include:**

- Immunization
- Maternal and reproductive health
- Child health
- Laboratory services
- Radiology
- Emergency care
- Pharmacy services

### US-010 — Combine Filters

**As a** user,  
**I want to** combine facility-type and service filters,  
**so that** I can narrow my search to the most relevant facilities.

---

## Epic 4: Facility Information

### US-011 — View Facility Details

**As a** user,  
**I want to** select a facility and view its information,  
**so that** I can determine whether it meets my needs.

### US-012 — View Facility Distance

**As a** user,  
**I want to** see the approximate distance from my current or selected location,  
**so that** I can identify conveniently located facilities.

### US-013 — View Available Services

**As a** user,  
**I want to** see the services available at a selected facility,  
**so that** I can determine whether the facility provides the care I need.

### US-014 — View Contact and Operating Information

**As a** user,  
**I want to** view available contact details and operating hours,  
**so that** I can decide when and how to contact or visit the facility.

---

## Epic 5: Directions and Navigation

### US-015 — Get Directions

**As a** user,  
**I want to** get directions to a selected health facility,  
**so that** I can navigate to the facility.

---

## Epic 6: Error and Empty States

### US-016 — Handle No Search Results

**As a** user,  
**I want to** receive a clear message when no facilities are found,  
**so that** I understand what happened and can change my search.

### US-017 — Handle Location Errors

**As a** user,  
**I want to** receive a clear message when my location cannot be detected,  
**so that** I know I can search for a location manually.

### US-018 — Handle Map or API Errors

**As a** user,  
**I want to** receive a clear error message when the map or required service is unavailable,  
**so that** I understand that the problem is temporary and can try again later.

---

## Epic 7: Responsive Experience

### US-019 — Use the Locator on Mobile

**As a** mobile user,  
**I want to** use the Health Facility Locator comfortably on my phone,  
**so that** I can find healthcare facilities while travelling or away from home.

### US-020 — Use the Locator on Desktop

**As a** desktop user,  
**I want to** use the locator on a larger screen,  
**so that** I can easily search, filter and explore health facilities.

---

## Future User Stories

The following stories are outside the initial implementation but may be considered in future iterations:

- User reviews and ratings
- Facility verification
- Appointment booking
- Emergency facility identification
- Operating-hours filtering
- Facility availability
- Saved facilities
- Advanced search
- Health facility administration portal
