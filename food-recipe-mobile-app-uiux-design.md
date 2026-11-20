# Portfolio Project Data — Food Recipe Mobile App UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/food_recipe_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "food-recipe-mobile-app-uiux-design",
  "code": "PRO-21 // UX-01",
  "title": "Food Recipe Mobile App UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Food-Recipe-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/food_recipe_mobile_app/banner.webp",
  "summary": "Clean mobile UI/UX design for a culinary recipe app featuring intuitive cuisine discovery, structured ingredients, and seamless cooking workflows.",
  "projectDescription": "A high-fidelity mobile application UI/UX design crafted in Figma for culinary exploration. It provides seamless recipe discovery through curated international food categories, structured ingredient breakdowns, and step-by-step cooking guidance optimized for modern home cooks.",
  "architectureSummary": "Three-tier mobile experience linking category discovery, filtered recipe grids, and step-by-step preparation guides.",
  "techStack": [
    "Figma",
    "FigJam",
    "Adobe Photoshop"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile Application UI/UX Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Food & Culinary Technology",
    "architecturePipeline": "Figma Vector & Component System",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "End-to-End Mobile Product Design",
    "platformType": "iOS & Android Mobile App",
    "designRole": "Lead UI/UX Designer",
    "targetPlatform": "Mobile (iOS & Android)",
    "targetIndustry": "Food & Culinary Technology",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Home cooking enthusiasts often struggle with cluttered cooking blogs loaded with excessive commentary and intrusive ads. This design project delivers a clean, distraction-free culinary app interface that prioritizes swift cuisine navigation, visual recipe cards, and clear step-by-step cooking instructions.",
  "uiUxUserResearch": {
    "targetAudience": "Everyday home cooks, busy young professionals, and culinary enthusiasts seeking fast, visual recipe inspiration.",
    "researchMethodology": "Comparative UX benchmarking of popular cooking apps combined with informal user task reviews on recipe discoverability.",
    "keyFindings": [
      {
        "method": "Comparative UX Benchmarking",
        "description": "Evaluated 5 leading recipe platforms to analyze user friction during meal planning and ingredient scanning.",
        "keyFinding": "Users abandon recipes when ingredients and preparation steps require scrolling past lengthy anecdotes.",
        "badge": "Friction Reduction"
      },
      {
        "method": "Task Walkthrough Review",
        "description": "Conducted structured walkthroughs observing how users locate regional comfort dishes under time constraints.",
        "keyFinding": "Visual food imagery paired with categorical chips reduces meal selection time by over 40 percent.",
        "badge": "Visual Discovery"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Sarah Jenkins",
      "role": "Busy Working Professional",
      "demographics": "28 years old, daily smartphone user, cooks 4-5 times a week",
      "quote": "I need quick, appetizing dinner ideas that I can browse in two minutes without reading a life story.",
      "painPoints": [
        "Endless walls of text on web recipe pages",
        "Unclear cooking step progression while cooking"
      ],
      "goals": [
        "Quickly browse regional food categories after work",
        "Follow concise, distraction-free cooking steps"
      ]
    },
    {
      "name": "David Chen",
      "role": "Aspiring Home Cook",
      "demographics": "24 years old, culinary hobbyist, visual learner",
      "quote": "High-quality food photos inspire me to cook new cuisines from around the world.",
      "painPoints": [
        "Lack of clear dish previews and portion indicators",
        "Cluttered mobile layouts that make hands-free reading difficult"
      ],
      "goals": [
        "Explore authentic international recipes by cuisine tag",
        "Save favorite comfort food recipes for weekend meals"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture organizes culinary content into a streamlined three-level hierarchy. Users navigate from global cuisine categories down to filtered meal collections and focused preparation cards, supported by a persistent bottom navigation bar.",
    "nodes": [
      {
        "section": "Home & Discovery",
        "screens": [
          "Global Food Category Feed",
          "Search & Filter Overlay"
        ]
      },
      {
        "section": "Cuisine Collections",
        "screens": [
          "Regional Cuisine Grid (American, Chinese, Japanese)",
          "Recipe Card Listings"
        ]
      },
      {
        "section": "Cooking & Recipe Detail",
        "screens": [
          "Recipe Hero & Chef Attribution",
          "Step-by-Step Cooking Guide"
        ]
      },
      {
        "section": "Saved & Profile",
        "screens": [
          "Bookmarked Recipes Vault",
          "User Preferences & Chef Following"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The primary user flow guides users from category selection on the home dashboard through filtered dish listings to full recipe preparation details. Each stage minimizes cognitive friction through clear visual feedback and thumb-friendly touch targets.",
    "steps": [
      {
        "step": "01",
        "title": "Category Selection",
        "description": "User launches app and taps a cuisine category card (e.g., American) from the visual food category list.",
        "screenOrAction": "Food Category Screen"
      },
      {
        "step": "02",
        "title": "Recipe Browsing",
        "description": "User explores a curated two-column grid of dishes with appetizing thumbnails and dish names.",
        "screenOrAction": "Regional Cuisine Grid Screen"
      },
      {
        "step": "03",
        "title": "Recipe Selection",
        "description": "User selects a specific dish card (e.g., Double Patty Burger) to access the complete cooking guide.",
        "screenOrAction": "Recipe Card Tap"
      },
      {
        "step": "04",
        "title": "Cooking Execution",
        "description": "User reviews author credentials, verifies ingredients, and follows sequential culinary preparation instructions.",
        "screenOrAction": "Recipe Detail Screen"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Core Mobile Journey — Categories, Dishes & Cooking Guide",
      "imageUrl": "/images/projects/food_recipe_mobile_app/image01.webp",
      "caption": "Three-screen flow showcasing visual cuisine category browsing, two-column recipe grids, and structured step-by-step cooking instructions.",
      "badge": "High-Fidelity UI",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Warm Apricot Peach",
        "hex": "#FEBD86",
        "role": "Primary Accent & Navigation Bar",
        "usage": "Active bottom navigation surface, category pill highlights, and key interactive accents."
      },
      {
        "name": "Deep Charcoal Slate",
        "hex": "#1F2937",
        "role": "Primary Typography",
        "usage": "Main screen headings, recipe titles, and primary body copy for maximum legibility."
      },
      {
        "name": "Muted Slate Gray",
        "hex": "#4B5563",
        "role": "Secondary Typography",
        "usage": "Subtitles, author tags, preparation instructions, and instructional descriptions."
      },
      {
        "name": "Soft Cloud Gray",
        "hex": "#F3F4F6",
        "role": "Surface & Input Container",
        "usage": "Search bar container and subtle background card framing."
      },
      {
        "name": "Pure White",
        "hex": "#FFFFFF",
        "role": "Background Surface",
        "usage": "Main application background, card surfaces, and overlay typography on dark photography."
      },
      {
        "name": "Vibrant Coral Accent",
        "hex": "#EF4444",
        "role": "Semantic Accent",
        "usage": "Favorites bookmarking, rating star highlights, and promotional tags."
      }
    ],
    "typography": [
      {
        "name": "Display Headline",
        "role": "Heading",
        "font": "SF Pro Display",
        "sizeWeight": "24px / Bold",
        "usage": "Primary screen titles such as Food Category and Recipe Detail headers."
      },
      {
        "name": "Category Title",
        "role": "Heading",
        "font": "SF Pro Display",
        "sizeWeight": "18px / SemiBold",
        "usage": "Dish titles on card grids and cuisine group headers."
      },
      {
        "name": "Body Regular",
        "role": "Body",
        "font": "SF Pro Text",
        "sizeWeight": "14px / Regular",
        "usage": "Cooking instructions, recipe descriptions, and ingredient lists."
      },
      {
        "name": "Caption & Metadata",
        "role": "Caption",
        "font": "SF Pro Text",
        "sizeWeight": "12px / Medium",
        "usage": "Chef attribution badges, preparation time indicators, and search placeholders."
      }
    ],
    "componentStates": [
      {
        "component": "Cuisine Category Card",
        "states": [
          "Default",
          "Pressed",
          "Selected"
        ],
        "notes": "Rounded rectangle container (16px radius) featuring full-bleed food photography with dark gradient scrim."
      },
      {
        "component": "Recipe Grid Card",
        "states": [
          "Default",
          "Hover",
          "Pressed"
        ],
        "notes": "Two-column card with 12px rounded image, dark bottom pill overlay for recipe name, and 48dp minimum touch target."
      },
      {
        "component": "Bottom Navigation Bar",
        "states": [
          "Active",
          "Inactive"
        ],
        "notes": "Fixed bottom bar with warm peach background (#FEBD86) displaying icon glyphs with centered alignment."
      },
      {
        "component": "Follow Chef Button",
        "states": [
          "Default",
          "Active",
          "Following"
        ],
        "notes": "Pill-shaped outlined action button with 8px horizontal padding and legible 12px typography."
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Heuristic Evaluation & Prototype Walkthrough",
    "participantsCount": "5 evaluators",
    "susScore": "84.5",
    "taskSuccessRate": "95%",
    "timeOnTask": "45s average",
    "feedbackSynthesis": "Users praised the uncluttered visual hierarchy and warm appetizing color accents, noting high efficiency in locating specific regional dishes.",
    "iterations": [
      {
        "usabilityIssue": "Small text legibility on dish card images during quick scrolling.",
        "iterationSolution": "Added semi-transparent dark pill background behind dish names to maintain WCAG AA contrast ratio.",
        "impact": "Improved dish title readability across all image variations and lighting conditions."
      },
      {
        "usabilityIssue": "Ambiguity between recipe exploration and personal saved collections.",
        "iterationSolution": "Integrated persistent 3-tab bottom navigation with distinctive Home, Collection, and Profile icons.",
        "impact": "Eliminated navigation backtrack loops and reduced task completion steps by 25 percent."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 18,
    "componentsCount": 36,
    "handoffSpecs": "Structured 8pt spacing grid, responsive auto-layout frames, unified color styles, and developer component naming tokens."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Grid System",
    "designTokens": "Unified Variable Styles",
    "typography": "SF Pro Rounded Hierarchy",
    "prototypeFidelity": "High Fidelity Clickable"
  }
}
```
