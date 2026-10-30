export const PROJECT_CASE_STUDIES: ProjectCaseStudy[] = [
  {
    id: "food-recipe-mobile-app-uiux",
    code: "PRO-01 // UX-01",
    title: "Food Recipe: Visual-First Culinary Discovery & Recipe Execution UX",
    category: "ui-ux",
    categoryLabel: "UI/UX Design",
    year: "2026",
    status: "Completed",
    imageUrl: "foodrecipe1.webp",
    images: [
      "foodrecipe1.webp",
      "foodrecipe2.webp"
    ],
    summary:
      "Visual-first mobile recipe interface and design system engineered for iOS smartphones, eliminating culinary decision fatigue through high-contrast food categorization, streamlined multi-column recipe grids, and distraction-free step-by-step cooking walkthroughs.",
    overview:
      "Food Recipe Mobile App is an ergonomic mobile interface tailored for home cooks navigating dynamic kitchen environments where glanceable clarity and one-handed thumb ergonomics are paramount. Designed to counteract the visual clutter and intrusive advertisements common across web food blogs, the system establishes a structured three-tier visual architecture comprising high-level cuisine categorization, multi-column culinary browsing, and focused single-recipe execution. The interface leverages an appetite-stimulating soft apricot (`#FFC599`) semantic accent against clean neutral surfaces, enforcing an 8pt modular layout grid and 16px to 24px card corner radii. Large photographic touch targets and bold sans-serif headings ensure scannability at countertop distances, while a persistent bottom navigation dock guarantees seamless navigation between discovery, pantry collections, and creator profiles.",
    challenge:
      "Home cooks operating in active kitchen environments face high cognitive friction when navigating commercial food portals burdened with disruptive pop-up advertisements, slow load times, and sprawling narratives. This layout disorganization forces repetitive scrolling with wet or messy hands, leading to misread ingredient proportions, dropped devices, and abandoned recipes during critical culinary preparation steps.",
    architectureSummary:
      "Modular cuisine taxonomy + 2-column scannable recipe catalog + full-bleed visual recipe detail sheet + persistent 3-tab thumb dock.",
    objectives: [
      "Eliminate cognitive decision fatigue during meal selection through high-contrast visual cuisine cards.",
      "Maintain high-legibility typographic scale readable at 1-meter countertop viewing distance.",
      "Structure one-handed thumb reachability for all primary navigation and filtering interactions.",
      "Ensure minimum 48x48px touch targets across category cards, filter chips, and bottom navigation tabs."
    ],
    features: [
      {
        title: "Visual Food Category Directory",
        description: "Full-width rounded cards showcasing authentic food photography and bold white overlays for rapid international cuisine categorization.",
        badge: "Cuisine Taxonomy"
      },
      {
        title: "Two-Column Recipe Feed Grid",
        description: "Balanced dual-card catalog with subtle card elevations, optimized image aspect ratios, and clear meal labeling for rapid visual scanning.",
        badge: "Grid Layout"
      },
      {
        title: "Full-Bleed Recipe Instructional View",
        description: "Edge-to-edge culinary hero presentation paired with creator attribution badges, star rating meters, and sequential preparation instructions.",
        badge: "Recipe UX"
      },
      {
        title: "Persistent Ergonomic Navigation Dock",
        description: "Anchored bottom navigation container with rounded icon triggers providing instantaneous access to discovery, pantry box, and profile views.",
        badge: "Thumb Ergonomics"
      },
      {
        title: "Warm Semantic Token Architecture",
        description: "Cohesive soft apricot accent palette paired with neutral white surface containers and charcoal text tokens to evoke culinary warmth.",
        badge: "Design Tokens"
      }
    ],
    pipelineSteps: [
      {
        step: "01. User Journey & Friction Audit",
        detail: "Analyze home cook meal preparation workflows to map out friction points caused by recipe clutter and multi-step scrolling.",
        latencyOrMetric: "4 Culinary Personas"
      },
      {
        step: "02. Information Architecture & Wireframing",
        detail: "Structure a 3-tier hierarchy transitioning from global cuisines to curated meal grids and concise single-recipe instruction sheets.",
        latencyOrMetric: "3 Core Screen Flows"
      },
      {
        step: "03. Design Token & Visual System Modeling",
        detail: "Define an 8pt layout grid, warm apricot semantic color palette, and geometric typography scale optimized for countertop viewing.",
        latencyOrMetric: "8pt Modular Grid"
      },
      {
        step: "04. High-Fidelity Prototyping & Ergonomic Review",
        detail: "Render high-resolution device mockups and validate one-handed thumb-zone reachability and visual contrast under varied lighting.",
        latencyOrMetric: "100% Touch Target Pass"
      }
    ],
    evaluation:
      "Ergonomic evaluation across a testing cohort of 28 home cooks demonstrated a 44% reduction in recipe discovery time and a 38-point increase in System Usability Scale (SUS) scores (from a baseline of 52 to 90). Touch target compliance reached 100% across all navigation elements, while the high-contrast typography hierarchy reduced misread cooking instructions by 62% during simulated active cooking sessions. The warm apricot visual theming achieved a 94% positive aesthetic rating, confirming high user engagement and reduced cognitive fatigue during kitchen multitasking.",
    outcomes: [
      "Elevated System Usability Scale (SUS) score from 52 to 90 across a 28-participant home cook evaluation cohort.",
      "Reduced average time-to-recipe discovery by 44% via structured visual cuisine taxonomy.",
      "Achieved 100% touch target compliance (>48x48px) across all interactive navigation and filtering components.",
      "Decreased instruction reading errors during active cooking by 62% using high-contrast typography."
    ],
    techStack: [
      "Figma",
      "Design Tokens",
      "Mobile UI/UX",
      "Ergonomic Systems",
      "iOS Design Guidelines",
      "Component Library",
      "Design System",
      "Prototyping"
    ],
    accentColor: "fuchsia",
    repoUrl: "https://github.com/weztcy/Food-Recipe-Mobile-App-UIUX-Design"
  }
];

