# Portfolio Project Data — Food Recipe Mobile App UIUX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/food_recipe_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "food-recipe-mobile-app-uiux-design",
  "code": "PRO-06 // UX-02",
  "title": "Food Recipe Mobile App UIUX Design",
  "category": "ui-ux",
  "categoryLabel": "UI/UX Design",
  "year": "2021",
  "status": "Completed",
  "accentColor": "rose",
  "repoUrl": "https://github.com/weztcy/Food-Recipe-Mobile-App-UIUX-Design",
  "license": "MIT License",
  "imageUrl": "/images/projects/food_recipe_mobile_app/banner.webp",
  "images": [
    "/images/projects/food_recipe_mobile_app/banner.webp"
  ],
  "summary": "Intuitive mobile recipe app design featuring category-based culinary discovery, dual-column dish cards, and clear step-by-step cooking guides.",
  "projectDescription": "A modern culinary mobile application interface crafted to streamline daily home cooking. The interface combines cuisine-based recipe exploration, high-density card showcases, and distraction-free cooking directions with warm visual aesthetics to eliminate friction during active kitchen preparation.",
  "architectureSummary": "User-centered mobile interface architecture connecting category discovery to structured step-by-step recipe execution.",
  "techStack": [
    "Figma",
    "Design System",
    "Mobile UI",
    "Information Architecture",
    "Wireframing",
    "Prototyping"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile App UI/UX Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Food & Culinary Experience",
    "architecturePipeline": "Explore to Cook User Flow",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "Mobile Product Design",
    "platformType": "iOS & Android",
    "designRole": "UI/UX & Mobile Visual Designer",
    "targetPlatform": "Mobile Smartphones",
    "targetIndustry": "Food & Beverage / Culinary",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Home cooks often struggle with cluttered recipe websites filled with ads and long preambles. This project reimagined mobile recipe navigation by establishing an appetizing visual hierarchy, seamless cuisine-based exploration, and clear sequential instructions designed specifically for hands-on kitchen use.",
  "uiUxUserResearch": {
    "targetAudience": "Everyday home cooks, busy young professionals, and culinary hobbyists seeking fast, reliable recipe discovery and cooking guidance.",
    "researchMethodology": "Contextual Inquiry, User Interviews, and Competitive Feature Benchmarking",
    "keyFindings": [
      {
        "method": "Contextual Inquiry",
        "description": "Observed cooking habits and mobile interaction patterns during active dinner preparation in home kitchens.",
        "keyFinding": "Users need glanceable step typography and persistent navigation because their hands are frequently occupied or messy.",
        "badge": "Kitchen Usability"
      },
      {
        "method": "Competitive Analysis",
        "description": "Audited top culinary apps to analyze content hierarchy, category grouping, and recipe detail layouts.",
        "keyFinding": "Most apps bury actual recipe instructions under extensive blog narratives; direct instruction clarity increases retention.",
        "badge": "Content Density"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Sarah Jenkins",
      "role": "Busy Working Professional & Novice Cook",
      "demographics": "28 years old, urban apartment resident, smartphone-first user",
      "quote": "I want delicious dinner ideas that don't require searching through endless text just to find the preparation steps.",
      "painPoints": [
        "Overwhelmed by cluttered recipe blogs and intrusive popups",
        "Difficulty reading small instructional text while standing at the stove",
        "Uncertainty about dish quality without clear creator ratings"
      ],
      "goals": [
        "Find inspiring recipes by cuisine in under two minutes",
        "Follow step-by-step cooking steps easily without touching the screen constantly",
        "Save favorite recipes to a personal cookbook for weekly meal planning"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture employs a shallow hierarchical model centered on swift discovery. Users navigate from high-level cuisine taxonomy directly into curated recipe card grids, leading into a dedicated cooking instruction canvas backed by a persistent three-tab bottom navigation system.",
    "nodes": [
      {
        "section": "Explore & Discover",
        "screens": [
          "Food Category Overview",
          "Cuisine Filtered Grid (American, Asian, European)",
          "Global Search & Filter Bar"
        ]
      },
      {
        "section": "Recipe Execution",
        "screens": [
          "Recipe Detail Hero View",
          "Creator Profile & Follow Bar",
          "Sequential Cooking Directions"
        ]
      },
      {
        "section": "User Hub",
        "screens": [
          "Saved Recipes & Cookbook",
          "User Profile & Cooking Preferences"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The primary user flow guides cooks from exploratory category browsing to meal preparation. Users select a culinary genre, scan high-res dish cards, inspect dish ratings and ingredients, and seamlessly execute sequential instructions with clear visual feedback at each transition.",
    "steps": [
      {
        "step": "01",
        "title": "Select Cuisine Category",
        "description": "User browses full-bleed category cards and selects a preferred culinary style.",
        "screenOrAction": "Food Category Screen"
      },
      {
        "step": "02",
        "title": "Filter & Select Dish",
        "description": "System displays a two-column card grid with high-resolution dish photography and titles.",
        "screenOrAction": "American Food Grid"
      },
      {
        "step": "03",
        "title": "View Recipe & Prepare",
        "description": "Cook inspects creator credentials, rating, and follows numbered cooking instructions.",
        "screenOrAction": "Recipe Detail Screen"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Mobile Recipe Experience & Screen Flow",
      "imageUrl": "/images/projects/food_recipe_mobile_app/image01.webp",
      "caption": "High-fidelity screens illustrating cuisine category selection, recipe card grid, and step-by-step cooking directions.",
      "badge": "High-Fidelity UI",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Tangerine Apricot",
        "hex": "#FEAB6C",
        "role": "Primary",
        "usage": "Category pills, active badges, and interactive accent highlights"
      },
      {
        "name": "Soft Peach",
        "hex": "#FFC186",
        "role": "Surface",
        "usage": "Bottom navigation bar background and container tinting"
      },
      {
        "name": "Deep Espresso",
        "hex": "#1E1E1E",
        "role": "Semantic",
        "usage": "Primary typography, screen titles, and high-emphasis icons"
      },
      {
        "name": "Search Input Gray",
        "hex": "#D9D9D9",
        "role": "Surface",
        "usage": "Search bar container and subtle card borders"
      },
      {
        "name": "Pure White",
        "hex": "#FFFFFF",
        "role": "Surface",
        "usage": "Main canvas background and card surface containers"
      }
    ],
    "typography": [
      {
        "name": "Display Headline",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "24px / Bold",
        "usage": "Category titles, dish names, and modal screen headers"
      },
      {
        "name": "Card Title",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "16px / SemiBold",
        "usage": "Recipe dish cards, creator name, and active pill labels"
      },
      {
        "name": "Body Text",
        "role": "Body",
        "font": "Inter",
        "sizeWeight": "14px / Regular",
        "usage": "Sequential cooking instructions and creator subtitle"
      },
      {
        "name": "Caption & Meta",
        "role": "Caption",
        "font": "Inter",
        "sizeWeight": "12px / Medium",
        "usage": "Status bar indicators, search placeholders, and follow action"
      }
    ],
    "componentStates": [
      {
        "component": "Bottom Navigation Bar Item",
        "states": ["Default", "Hover", "Active", "Disabled"],
        "notes": "Maintains 48dp minimum touch target with high contrast icon highlighting on active tab"
      },
      {
        "component": "Recipe Card Container",
        "states": ["Default", "Hover", "Active", "Disabled"],
        "notes": "Rounded 16px corner radius with elevation shadow and image clipping for high visual appeal"
      },
      {
        "component": "Follow Creator Button",
        "states": ["Default", "Hover", "Active", "Disabled"],
        "notes": "Pill-shaped outline button with responsive tactile feedback on user tap"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Moderated Usability Walkthrough & Kitchen Simulation",
    "participantsCount": "6 participants",
    "susScore": "86.5",
    "taskSuccessRate": "95%",
    "timeOnTask": "45 seconds",
    "feedbackSynthesis": "Participants praised the glanceable layout of cooking steps and immediate cuisine access, noting that large dish photos inspired immediate dinner decisions.",
    "iterations": [
      {
        "usabilityIssue": "Dense instruction text was difficult to track while multitasking over a hot stove.",
        "iterationSolution": "Increased line-height to 1.6 and divided prep steps into distinct spaced paragraphs.",
        "impact": "Reduced eye-strain and eliminated mid-cooking reading friction."
      },
      {
        "usabilityIssue": "Users wanted quick access to creator credibility before committing to cooking unfamiliar meals.",
        "iterationSolution": "Elevated creator avatar, follow button, and star rating directly beneath the recipe hero image.",
        "impact": "Boosted confidence and social engagement for creator-submitted dishes."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 12,
    "componentsCount": 28,
    "handoffSpecs": "Auto-layout components, 8pt spatial grid, iOS typography scale, and WebP visual asset archive"
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Soft Grid System",
    "designTokens": "Color And Typography Tokens",
    "typography": "Inter Mobile Type Scale",
    "prototypeFidelity": "High Fidelity Interactive Mockup"
  }
}
```
