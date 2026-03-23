# Pressure Tested — Layer 1: Positioning Engine

**Live URL:** https://pressuretested.co

## What This Is

Layer 1 of the Pressure Tested professional survival system. A question-driven intake form that derives a YouTube niche from who someone already is — not from keyword databases or algorithm data.

## What It Does

- Six extraction questions: background, passion, authority, audience, teaching hour, channel status
- - Derives niche and lane density (Underserved / Moderate / Crowded) from answers
  - - Outputs a branded PDF Positioning Report (name, niche, lane density, 5 video ideas, next step CTA)
    - - Outputs an Excel file (3 sheets: Positioning Summary, Video Ideas, Coach Tracker)
      - - Captures email to Kit (ConvertKit) form ID 9137267
        - - Redirects to Layer 2 (Signal Diagnostic) with niche context in URL params
         
          - ## The Three-Layer System
         
          - | Layer | Repo | Live URL | Purpose |
          - |---|---|---|---|
          - | Layer 1 | pressuretested-co | pressuretested.co | Positioning Engine — find your lane before you build |
          - | Layer 2 | pressuretested-diagnostic | dswann101164.github.io/pressuretested-diagnostic | Signal Diagnostic — score your channel against real data |
          - | Layer 3 | — | david@pressuretested.co | Coaching Calls — interpret both layers, build the roadmap |
         
          - ## Tech Stack
         
          - - Pure HTML/CSS/JS — no framework
            - - jsPDF 2.5.1 (CDN) — PDF generation
              - - SheetJS 0.18.5 (CDN) — Excel generation
                - - GitHub Pages — hosting
                  - - CNAME — pressuretested.co
                   
                    - ## Files
                   
                    - - `index.html` — the full positioning engine (single file)
                      - - `CNAME` — domain mapping to pressuretested.co
                       
                        - ## Brand
                       
                        - - Navy: #0D1B2A
                          - - Gold: #C9A84C
                            - - Font: Montserrat + IBM Plex Mono
                              - - Tagline: Real Stats. No Hype. Late-Start Wins.
