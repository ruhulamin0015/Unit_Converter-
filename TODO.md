# Task: Universal Unit Converter Implementation

## Plan
- [x] Analysis & Data Modeling
  - [x] Define unit categories and their conversion factors in `src/constants/units.ts`
  - [x] Implement conversion logic utility in `src/lib/conversion.ts`
- [x] Core UI Components
  - [x] Create `CategorySelector` component (Integrated in Home.tsx)
  - [x] Create `ConversionPanel` component (Integrated in Home.tsx)
  - [x] Create `ResultDisplay` component (Integrated in Home.tsx)
- [x] Pages & Integration
  - [x] Implement the main `Home` page in `src/pages/Home.tsx`
  - [x] Update `src/routes.tsx` to include the Home page and remove SamplePage
  - [x] Update `src/App.tsx` if necessary
- [x] Refinement & Polish
  - [x] Add real-time calculation and state management
  - [x] Implement "Copy to Clipboard" with feedback
  - [x] Add "Swap Units" functionality
  - [x] Add warnings for physically unusual values (e.g., negative length)
  - [x] Ensure responsiveness and dark mode compatibility
  - [x] Run `npm run lint` and fix any issues

## Notes
- Base unit pivot approach for most units.
- Temperature needs special formula-based handling.
- Maximum 8 significant digits with scientific notation fallback.
