# Portfolio Project Data — Food Recipe Mobile App UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/food_recipe_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "food-recipe-mobile-app-uiux-design",
  "code": "PRO-01 // UX-01",
  "title": "Food Recipe Mobile App UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Food-Recipe-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "banner": "/images/projects/food_recipe_mobile_app/banner.webp",
  "summary": "Mobile recipe discovery UI/UX concept featuring cuisine category feeds, two-column dish grids, and creator-attributed preparation guides.",
  "projectDescription": "Food Recipe Mobile App UIUX Design is a 2021 mobile interface concept crafted to streamline culinary discovery and meal preparation. Built with warm apricot accents, crisp white reading sheets, and vivid food photography, it connects categories, dish grids, and recipes cleanly.",
  "architectureSummary": "Three-tier mobile navigation flow linking Food Category feeds, two-column cuisine grids, and creator-attributed recipe detail sheets.",
  "techStack": [
    "Figma",
    "WebP"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile App UI/UX Concept",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Culinary & Recipe Discovery",
    "architecturePipeline": "Category -> Grid -> Recipe Detail",
    "testingAndAudit": "Visual Heuristic Review",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "platformType": "iOS & Android Mobile App",
    "designRole": "UI/UX & Mobile Product Designer",
    "targetIndustry": "Food & Culinary",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Many mobile cooking applications clutter screens with dense text, pop-ups, and multi-level menus that slow down everyday meal decisions. This 2021 concept explores a calmer, photography-first interface where home cooks move effortlessly from browsing global cuisines to reading concise preparation instructions.",
  "uiUxUserResearch": {
    "keyFindings": [
      {
        "method": "Visual Hierarchy Audit",
        "description": "Evaluated typical mobile recipe discovery patterns across category browsing, dish comparison, and active cooking views without formal field surveys.",
        "keyFinding": "Photo-dominant cards paired with short white-overlay titles speed up initial cuisine scanning compared to text-heavy lists.",
        "badge": "Visual Scanning"
      },
      {
        "method": "Navigation Friction Review",
        "description": "Reviewed mobile thumb-reach ergonomics and persistent action placement across multi-screen culinary flows.",
        "keyFinding": "Keeping a persistent top search pill and a fixed three-tab bottom bar minimizes disorientation between browsing and recipe reading.",
        "badge": "Wayfinding Clarity"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Everyday Home Cook",
      "role": "Primary Target Audience",
      "demographics": "Mobile-first culinary browsers seeking quick weeknight meal ideas",
      "quote": "I want to pick a cuisine quickly, see appetizing dish photos, and read clear preparation steps without fighting cluttered menus.",
      "painPoints": [
        "Overly dense recipe layouts that obscure ingredients and steps behind pop-ups",
        "Deeply nested category filters that slow down spontaneous meal inspiration"
      ],
      "goals": [
        "Browse familiar cuisines like American, Chinese, and Japanese in one tap",
        "Follow favorite recipe creators and read concise, distraction-free instructions"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture flattens culinary discovery into three primary depths anchored by a persistent search header and a three-tab bottom bar. Users transition seamlessly from top-level Food Categories to a tagged two-column dish grid and into a full-bleed recipe detail sheet.",
    "nodes": [
      {
        "section": "Home / Food Category",
        "screens": [
          "Persistent Search & Overflow Header",
          "Cuisine Category Stack (American, Chinese, Japanese)"
        ]
      },
      {
        "section": "Category Dish Grid",
        "screens": [
          "Tagged Cuisine Banner (American Food)",
          "Two-Column Dish Grid (Double Patty Burger, Apple Pie, Clam Howder, Bagel & Lox, Texas Barbecue, Hominy Grits)"
        ]
      },
      {
        "section": "Recipe Detail & Creator View",
        "screens": [
          "Hero Meal Photography & Search Overlay",
          "Creator Attribution, Star Rating & Follow CTA",
          "Preparation Instruction Sheet"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The core user flow guides a home cook from launching the Food Category feed to selecting a meal preparation guide in three taps. Persistent header search controls and a fixed bottom navigation bar keep exploration, category browsing, and profile access anchored at every step.",
    "steps": [
      {
        "step": "01",
        "title": "Select Cuisine Category",
        "description": "User scans full-width rounded photography cards on the Food Category screen or uses the top search pill to narrow meal ideas.",
        "screenOrAction": "Food Category Screen / Tap American Card"
      },
      {
        "step": "02",
        "title": "Compare Dishes in Grid",
        "description": "App displays the warm tangerine American Food banner above a balanced two-column photo grid with bottom-aligned dish titles.",
        "screenOrAction": "American Food Grid / Tap Double Patty Burger"
      },
      {
        "step": "03",
        "title": "Review Creator & Instructions",
        "description": "App opens a full-bleed burger hero photo over a clean white sheet showing John Que Recipe, star ratings, Follow button, and step-by-step copy.",
        "screenOrAction": "Double Patty Burger Detail / Read & Follow"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Core Recipe Discovery & Preparation Flow",
      "imageUrl": "/images/projects/food_recipe_mobile_app/image01.webp"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Warm Apricot Chrome",
        "hex": "#FFBF85",
        "role": "Primary",
        "usage": "Bottom navigation bar container and iOS status bar accent strip"
      },
      {
        "name": "Tangerine Category Tag",
        "hex": "#FEAB6C",
        "role": "Accent",
        "usage": "Left-anchored section banner pill highlighting active cuisine headers"
      },
      {
        "name": "Active Tab Taupe",
        "hex": "#886D52",
        "role": "Secondary",
        "usage": "Selected bottom navigation icon container indicating current route"
      },
      {
        "name": "Pure Reading Canvas",
        "hex": "#FFFFFF",
        "role": "Surface",
        "usage": "Primary screen background and recipe detail instruction sheet"
      },
      {
        "name": "Search Pill Gray",
        "hex": "#D9D9D9",
        "role": "Neutral",
        "usage": "Persistent rounded search input background across all three screens"
      },
      {
        "name": "Follow Action Cobalt",
        "hex": "#2B4590",
        "role": "Interactive",
        "usage": "Outlined Follow pill button border and label on creator attribution row"
      },
      {
        "name": "Primary Ink",
        "hex": "#000000",
        "role": "Text",
        "usage": "Section headings, recipe titles, author names, and body copy"
      }
    ],
    "typography": [
      {
        "name": "Screen Section Heading",
        "role": "Heading",
        "font": "SF Pro",
        "sizeWeight": "20px / Bold",
        "usage": "Top-level titles such as Food Category, American Food, and Double Patty Burger"
      },
      {
        "name": "Card & Creator Label",
        "role": "Subheading",
        "font": "SF Pro",
        "sizeWeight": "13px / SemiBold",
        "usage": "Photo overlay titles on category/dish cards and creator name John Que Recipe"
      },
      {
        "name": "Recipe Instruction Copy",
        "role": "Body",
        "font": "SF Pro",
        "sizeWeight": "14px / Regular",
        "usage": "Multi-paragraph preparation steps and muted food recipe subtitle"
      }
    ],
    "componentStates": [
      {
        "component": "Bottom Navigation Tab",
        "states": ["Default", "Active"],
        "notes": "Three-icon bar with warm taupe rounded square highlight for the active route"
      },
      {
        "component": "Follow Creator Button",
        "states": ["Default", "Active"],
        "notes": "Compact pill outline in cobalt #2B4590 paired with creator avatar and 5-star row"
      },
      {
        "component": "Recipe Photo Card",
        "states": ["Default", "Pressed"],
        "notes": "Rounded corners with bottom-aligned white title label over dish photography"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "susScore": "Not formally measured (conceptual design archive)",
    "taskSuccessRate": "Not formally measured (no external UT logs)",
    "timeOnTask": "Designed for 3-tap category-to-recipe lookup",
    "iterations": [
      {
        "usabilityIssue": "Risk of losing spatial context when transitioning from full-bleed hero food photos into detail reading mode",
        "iterationSolution": "Retained the top search pill and bottom #FFBF85 navigation bar consistently across all three screens",
        "impact": "Preserved predictable navigation landmarks while keeping the preparation sheet uncluttered"
      },
      {
        "usabilityIssue": "Need to separate recipe attribution from cooking steps so readers can scan instructions quickly",
        "iterationSolution": "Grouped creator avatar, star rating, and Follow pill into a compact top metadata row above the recipe title",
        "impact": "Established clear visual separation between social actions and step-by-step cooking copy"
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "High-Fidelity Mockup Showcase Archive",
    "totalFrames": 3,
    "componentsCount": 12,
    "handoffSpecs": "iOS-proportioned mobile frames featuring a 2-column dish grid, 16px-20px rounded card radii, persistent top search header, and fixed 3-tab bottom bar."
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "2-Column Mobile Card Grid",
    "designTokens": "Warm Apricot Surface Tokens",
    "typography": "Clean Sans-Serif Hierarchy",
    "prototypeFidelity": "High-Fidelity Mobile Mockups"
  }
}
```
