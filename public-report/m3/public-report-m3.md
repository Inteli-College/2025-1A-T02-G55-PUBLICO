# Public Report - Module 3

## Executive Summary

Throughout the module, the project evolved from a minimal viable product (MVP) into a feature-rich and visually cohesive application supported by a stable, cloud-ready architecture. Over five sprints, development focused on consolidating critical user flows, strengthening technical foundations, implementing testing strategies, refining the visual identity, and structuring the complete AWS deployment environment.

The result is a consistent and scalable system across frontend, backend, and database layers, with comprehensive authentication, social and discovery features, a coherent design language, and established quality assurance practices. As the project approaches completion, efforts are directed toward final UX refinements and deployment readiness.

## Objectives and Scope of the Module

The module aimed to transform the MVP into a mature, deployable product integrating social discovery, user-generated content, and rating functionalities within a cohesive experience. The scope included:

- Building and stabilizing the backend architecture (NestJS, Postgres, Firebase Auth).
- Developing the frontend application (React Native / Expo) with modular components.
- Designing and refining core user journeys such as sign-up, reviews, lists, favorites, explore, and profile.
- Implementing automated tests to ensure reliability and maintainability.
- Establishing the cloud infrastructure using AWS services to achieve production readiness.

## Sprint-by-Sprint Highlights

### Sprint 1 — MVP Consolidation and Core Architecture

This sprint focused on consolidating the MVP and completing end-to-end integration across frontend, backend, and authentication.  
Key outcomes included:

- Full Firebase authentication with secure NestJS guards and token-based validation.
- Implementation of sign-up, login, review, list, and profile flows.
- Backend improvements ensuring consistent data models, transactional integrity, and standardized error handling.
- Frontend integrations with review creation, search, and profile visualization.
- Preparation for containerization and continuous integration.

This phase established the technical foundation for subsequent iterations.

### Sprint 2 — Social Features and UX Cohesion

The second sprint expanded functionality with emphasis on social interaction and discovery experiences.  
Main achievements included:

- Development of the follow/unfollow domain with idempotent logic and secure relationship handling.
- Integration of explore, ranking, and saved places pages for user and place discovery.
- Completion of the profile page with identity information, relationships, and related content.
- Backend optimization for query performance, pagination, and consistent response structures.
- Introduction of a new color palette and visual consistency across screens.

This sprint transitioned the application from a functional MVP to a socially integrated and visually coherent product.

### Sprint 3 — Redesign and Visual Identity

The third sprint concentrated on improving discoverability and brand coherence through interface redesign.  
Highlights included:

- Redesign of the home experience with a two-column card layout and restructured header.
- Overhaul of the search flow with category-based exploration and improved usability.
- Introduction of a review creation interface with clearer icons and contextual layout.
- Establishment of the project’s visual identity through logo selection, typography alignment, and spacing rules.

These changes strengthened usability, visual coherence, and brand recognition across all screens.

### Sprint 4 — Testing and Quality Assurance

This sprint focused on implementing and consolidating testing strategies.  
Two categories of tests were introduced:

1. Backend unit tests: achieving full coverage across all controllers and services, validating business logic, and ensuring error consistency.
2. Usability tests: conducted with participants from varied backgrounds to evaluate onboarding, search, favorites, lists, and review flows.

Results indicated stable backend behavior and overall positive user interaction, with minor adjustments identified for category clarity, confirmation feedback, and review flow intuitiveness.

### Sprint 5 — Redesign Completion and Cloud Infrastructure

The latest sprint combined visual refinement with infrastructure implementation.  
Key results included:

- Completion of the establishment details page redesign, adding food, service, and ambience rating categories.
- Synchronization of Figma files with recent UI updates.
- Configuration of the full AWS environment, including:
  - AWS Amplify for frontend hosting and CI/CD.
  - AWS Lambda and API Gateway for backend execution.
  - Amazon RDS for managed database services.
  - Amazon VPC for network isolation and security.

This phase positioned the project for scalable, secure deployment while aligning the interface with the latest design standards.

## Product Evolution

Across all sprints, the application advanced in three primary areas:

- Technical architecture evolved from monolithic development to modular, service-oriented design.
- User experience improved through progressive redesign, structured layouts, and consistent styling.
- Quality assurance practices ensured stability, predictability, and readiness for release.

The project now presents a stable and complete system aligned with usability, scalability, and maintainability requirements.

## Cloud and Deployment Readiness

The deployment architecture is fully structured within AWS, using a serverless approach for efficiency and cost reduction.

- Amplify automates frontend builds and global content delivery.
- Lambda and API Gateway manage backend requests with dynamic scalability.
- RDS provides reliable data storage and automated maintenance.
- VPC secures communication between components.

This configuration supports both development flexibility and future production scalability.

## Testing and Quality Outcomes

Testing efforts confirmed the platform’s technical and experiential stability.

- Full backend coverage across core entities.
- Validation of key user flows through usability sessions.
- Identification of minor refinements related to clarity and visual feedback.

Testing established a strong foundation for future iterations, reducing risk and improving product reliability.

## Figma and Design System Alignment

The design system in Figma was updated to reflect the current implementation.

- Component layouts, typography, and color palette are aligned with the deployed version.
- Documentation ensures visual consistency across all future updates.
- The unified design source improves collaboration and accelerates validation.

This synchronization reinforces the visual and functional coherence of the application.

## Risks and Mitigations

| Risk                              | Potential Impact            | Mitigation Strategy                                      |
| --------------------------------- | --------------------------- | -------------------------------------------------------- |
| Delay in AWS configuration        | Slower deployment readiness | Use Amplify and serverless defaults for rapid setup      |
| UX inconsistency across devices   | Reduced usability           | Conduct final cross-device testing prior to release      |
| Limited user feedback before beta | Incomplete validation       | Schedule an early closed beta with selected participants |

## Conclusion

The progress achieved throughout the five sprints demonstrates a steady and structured evolution toward a complete, deployable product. The application now combines technical robustness, a consistent visual identity, and a user experience refined through testing and design alignment. With the cloud infrastructure configured, full test coverage established, and all major features integrated, the project is entering its final stage of polish and optimization. The current state reflects a mature and production-ready system capable of delivering a stable, scalable, and engaging experience once deployed.
