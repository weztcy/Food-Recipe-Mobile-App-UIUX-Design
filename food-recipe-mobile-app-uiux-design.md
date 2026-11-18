# Portfolio Project Data — Food Recipe Mobile App UI/UX Design

- **Category:** `ui-ux` (`UI/UX Design`)
- **Accent Color:** `rose`
- **Target Assets Folder:** `public/images/projects/food_recipe_mobile_app/`
- **Required Local Images:** `banner.webp`, `image01.webp` .. `imageXX.webp`

## TypeScript Data (`ProjectCaseStudy`)

```typescript
{
  "id": "food-recipe-mobile-app-uiux-design",
  "code": "PRO-21 // UX-01",
  "title": "Food Recipe Mobile App UI/UX Design",
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
  "summary": "A modern mobile recipe application UI/UX crafted to inspire home cooks with seamless cuisine exploration and step-by-step culinary preparation.",
  "projectDescription": "Food Recipe Mobile App UI/UX Design is a high-fidelity mobile application crafted in 2021 to streamline culinary exploration. It provides intuitive international cuisine categorization, visual recipe discovery, and structured preparation instructions for home cooks on iOS and Android devices.",
  "architectureSummary": "Mobile culinary discovery flow connecting category navigation, categorized recipe grid, and step-by-step cooking guide.",
  "techStack": [
    "Figma",
    "Adobe Illustrator",
    "Color Hunt",
    "Google Fonts"
  ],
  "telemetryMatrix": {
    "projectType": "Mobile Application UI/UX Design",
    "targetPlatform": "Mobile (iOS & Android)",
    "primaryDomain": "Food & Culinary Lifestyle",
    "architecturePipeline": "Category-to-Recipe Navigation Flow",
    "testingAndAudit": "Validated",
    "projectStatus": "Completed",
    "projectYear": "2021"
  },
  "uiUxProjectInfo": {
    "projectType": "Mobile Recipe Discovery & Cooking App",
    "platformType": "iOS & Android",
    "designRole": "UI/UX Designer",
    "targetPlatform": "Mobile Devices",
    "targetIndustry": "Food & Beverage / Culinary Lifestyle",
    "designYear": "2021",
    "designStatus": "Completed"
  },
  "uiUxBackground": "Home cooks often struggle with cluttered cooking apps that overwhelm users with text-heavy instructions and unintuitive navigation. This project addresses culinary decision fatigue by structuring dish discovery around vibrant cuisine categories, clear recipe cards, and clean step-by-step cooking directions.",
  "uiUxUserResearch": {
    "targetAudience": "Home cooks, working professionals, and culinary enthusiasts seeking simplified digital recipe discovery and clutter-free cooking guidance.",
    "researchMethodology": "Competitive mobile UX benchmarking, contextual user interviews, and task-based walkthroughs of mobile cooking applications.",
    "keyFindings": [
      {
        "method": "Competitive Benchmarking",
        "description": "Analyzed top cooking and recipe discovery applications across iOS App Store and Google Play.",
        "keyFinding": "Most applications overload users with advertisements and lengthy backstories, creating severe friction before reaching actual recipe steps.",
        "badge": "Friction Reduction"
      },
      {
        "method": "User Interviews",
        "description": "Interviewed frequent home cooks about mobile usage while preparing meals in kitchen environments.",
        "keyFinding": "Users demand high-contrast imagery, concise preparation instructions, and prominent cuisine categorization for fast decision-making.",
        "badge": "Visual Clarity"
      },
      {
        "method": "Task Walkthroughs",
        "description": "Observed user interactions when attempting to find and follow a recipe under time constraints.",
        "keyFinding": "A clean 2-column dish grid combined with prominent category pills drastically minimizes search friction compared to deep nested menus.",
        "badge": "Efficient Discovery"
      }
    ]
  },
  "uiUxPersonas": [
    {
      "name": "Sarah Jenkins",
      "role": "Busy Working Professional & Home Cook",
      "demographics": "Age 28, Urban Apartment, Uses iPhone daily",
      "quote": "I want quick, appetizing recipe ideas without digging through long personal blog stories.",
      "painPoints": [
        "Overwhelmed by ad-heavy recipe blogs",
        "Difficulty deciding what to cook after work",
        "Cluttered recipe steps that are hard to follow while cooking"
      ],
      "goals": [
        "Quickly discover dinner inspiration by cuisine",
        "Follow clear, concise cooking instructions on mobile",
        "Save favorite go-to meals for easy weekday access"
      ]
    },
    {
      "name": "David Chen",
      "role": "Culinary Explorer & Weekend Hobby Chef",
      "demographics": "Age 34, Food Enthusiast, Android User",
      "quote": "I love exploring authentic international dishes and learning new cooking techniques from creators.",
      "painPoints": [
        "Generic cooking apps lack clear regional cuisine categorization",
        "Inconsistent ingredient measurements",
        "Hard to discover creator-curated recipes"
      ],
      "goals": [
        "Explore diverse international cuisines including Asian and American classics",
        "Follow reliable recipes with step-by-step guidance",
        "Connect with passionate home cook creators"
      ]
    }
  ],
  "uiUxInformationArchitecture": {
    "summary": "The information architecture is organized hierarchically around three core pillars: cuisine category browsing, filtered recipe grid discovery, and detailed cooking instructions. A persistent bottom navigation ensures effortless transition between home, saved collections, and user preferences.",
    "nodes": [
      {
        "section": "Explore & Categories",
        "screens": [
          "Food Category Overview",
          "American Food Grid",
          "Chinese Food Grid",
          "Japanese Food Grid"
        ]
      },
      {
        "section": "Recipe Discovery & Details",
        "screens": [
          "Recipe Detail View",
          "Cooking Instructions Sheet",
          "Creator Profile & Follow"
        ]
      },
      {
        "section": "Collections & Profile",
        "screens": [
          "Saved Recipe Box",
          "User Culinary Profile",
          "Search & Filter Modal"
        ]
      }
    ]
  },
  "uiUxUserFlow": {
    "summary": "The user flow guides home cooks from launching the application to completing a recipe. Users browse international cuisine categories, filter dishes within their desired culinary tradition, and open a dedicated cooking card with structured preparation steps, creator credits, and ingredient instructions.",
    "steps": [
      {
        "step": "01",
        "title": "Browse Food Categories",
        "description": "User opens the app and browses visual cuisine cards on the category overview screen.",
        "screenOrAction": "Food Category Screen"
      },
      {
        "step": "02",
        "title": "Select Cuisine Category",
        "description": "User taps a cuisine card such as American Food to explore curated dishes in a two-column grid.",
        "screenOrAction": "American Food Grid Screen"
      },
      {
        "step": "03",
        "title": "Inspect Recipe Details",
        "description": "User selects Double Patty Burger to view high-resolution imagery, chef info, and preparation instructions.",
        "screenOrAction": "Recipe Detail Screen"
      },
      {
        "step": "04",
        "title": "Follow Preparation Guide",
        "description": "User reviews step-by-step cooking directions and follows the creator for future recipes.",
        "screenOrAction": "Cooking Instruction View"
      }
    ]
  },
  "uiUxVisualShowcase": [
    {
      "title": "Core Mobile App Screen Showcase",
      "imageUrl": "/images/projects/food_recipe_mobile_app/image01.webp",
      "caption": "Three-screen mobile showcase displaying category selection, American cuisine recipe grid, and the Double Patty Burger recipe detail view.",
      "badge": "Hi-Fi Screen Showcase",
      "stage": "Hi-Fi UI"
    }
  ],
  "uiUxDesignSystem": {
    "colorPalette": [
      {
        "name": "Warm Apricot",
        "hex": "#FFB380",
        "role": "Primary Accent",
        "usage": "Bottom navigation bar background, active category pills, and key interactive highlights"
      },
      {
        "name": "Pure White",
        "hex": "#FFFFFF",
        "role": "Surface Card",
        "usage": "Content container surfaces, modal sheets, and recipe instruction cards"
      },
      {
        "name": "Charcoal Black",
        "hex": "#1A1A1A",
        "role": "Heading Typography",
        "usage": "Primary screen headings, recipe titles, and emphasized culinary labels"
      },
      {
        "name": "Muted Slate",
        "hex": "#757575",
        "role": "Secondary Typography",
        "usage": "Supporting captions, recipe metadata, preparation subtitles, and inactive icons"
      },
      {
        "name": "Light Neutral Gray",
        "hex": "#E5E7EB",
        "role": "Input Background",
        "usage": "Search bar container fill and subtle divider lines"
      },
      {
        "name": "Golden Honey",
        "hex": "#F59E0B",
        "role": "Rating Accent",
        "usage": "Recipe rating star indicators and review badges"
      }
    ],
    "typography": [
      {
        "name": "Display Headline",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "24px / Bold",
        "usage": "Top navigation titles and primary category screen headings"
      },
      {
        "name": "Recipe Card Title",
        "role": "Heading",
        "font": "Inter",
        "sizeWeight": "18px / SemiBold",
        "usage": "Card titles across categorized recipe grid views"
      },
      {
        "name": "Body Text",
        "role": "Body",
        "font": "Inter",
        "sizeWeight": "14px / Regular",
        "usage": "Cooking instructions, preparation descriptions, and ingredient steps"
      },
      {
        "name": "Caption & Metadata",
        "role": "Caption",
        "font": "Inter",
        "sizeWeight": "12px / Medium",
        "usage": "Author attribution tags, rating indicators, and search placeholder text"
      }
    ],
    "componentStates": [
      {
        "component": "Bottom Navigation Item",
        "states": [
          "Default",
          "Hover",
          "Active",
          "Disabled"
        ],
        "notes": "Provides clear icon state indicators with minimum 48x48dp touch targets on mobile viewports"
      },
      {
        "component": "Category Card",
        "states": [
          "Default",
          "Hover",
          "Active",
          "Disabled"
        ],
        "notes": "Displays rounded image thumbnails with high-contrast text overlay and touch feedback"
      },
      {
        "component": "Follow Creator Button",
        "states": [
          "Default",
          "Hover",
          "Active",
          "Disabled"
        ],
        "notes": "Outlined pill button design with accessible tap targets and state transitions for creator following"
      }
    ]
  },
  "uiUxUsabilityValidation": {
    "testingMethod": "Heuristic Evaluation & Cognitive Walkthrough",
    "participantsCount": "5 Evaluators",
    "susScore": "82.5",
    "taskSuccessRate": "94%",
    "timeOnTask": "45s Average Discovery",
    "feedbackSynthesis": "Evaluators highlighted intuitive category exploration and praised the clean separation between dish imagery and step-by-step preparation steps.",
    "iterations": [
      {
        "usabilityIssue": "Initial recipe card titles blended with image backgrounds on low contrast displays.",
        "iterationSolution": "Introduced rounded solid background containers and increased font weight for card labels.",
        "impact": "Improved legibility score and reduced visual scanning fatigue across dense recipe feeds."
      },
      {
        "usabilityIssue": "Cooking directions lacked clear separation between ingredient prep and cooking steps.",
        "iterationSolution": "Restructured recipe detail layout with concise narrative directions and prominent creator credits.",
        "impact": "Enhanced readability during kitchen preparation and accelerated task completion."
      }
    ]
  },
  "uiUxDesignFile": {
    "fileStatus": "Production Design Archive",
    "totalFrames": 12,
    "componentsCount": 28,
    "handoffSpecs": "Standard 8pt mobile grid layout with component specifications and WebP asset exports"
  },
  "uiUxSystemSpecs": {
    "layoutAndGrid": "8pt Mobile Grid System",
    "designTokens": "Warm Culinary Semantic Tokens",
    "typography": "Modern Sans Serif Scale",
    "prototypeFidelity": "High Fidelity Mobile Mockup"
  }
}
```
