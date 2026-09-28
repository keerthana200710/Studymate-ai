# StudyMate AI — Feature & Bug Checklist

## Application shell
- [x] Responsive dashboard shell with desktop sidebar and mobile bottom navigation
- [x] Light, dark, and system theme options
- [x] Global search across subjects, notes, assignments, exams, and study items
- [x] Notification popover, profile controls, and browser-persisted demo workspace

## Study workflow
- [x] Dashboard overview, study plan, progress metrics, weekly activity, and recommendations
- [x] AI study planner with daily, weekly, and monthly generation controls
- [x] Academic calendar with working month, week, and day views
- [x] Subject and topic management, progress analytics, and comparison charts
- [x] AI mock-test generation and interactive quiz/result flow
- [x] AI chat tutor with subject selection and learning modes
- [x] Assignment manager, exam tracker, focus timer, smart revision, searchable notes, and flashcards
- [x] Profile/preferences and achievement badges

## Server / AI
- [x] Protected server-side GPT-5 mini procedures for tutor responses, study plans, and mock tests
- [x] Sign-in prompts for account-backed AI operations
- [x] Unit tests for AI output, prompt context, access control, and input validation

## Bugs / verification
- [x] Fix blank startup caused by lazy-import initialization order
- [x] Fix timer completion state transitions and calendar period controls
- [x] Replace hard-coded planner dates with current-week dates
- [x] Verify desktop/mobile previews and lazy-loaded tutor screen
- [x] `pnpm check` passes
- [x] `pnpm test` passes — 2 files, 5 tests
- [x] `pnpm build` succeeds
- [x] Save final reviewable project checkpoint `c0911e62`

## Tutor and navigation enhancement
- [x] Add subject-aware quick prompts for step-by-step help, simpler explanations, examples, quizzes, and revision notes
- [x] Strengthen the tutor prompt with an intuition-first explanation structure and a check-for-understanding question
- [x] Add animated thinking feedback, live status text, and smooth auto-scroll in the tutor chat
- [x] Bound the conversation context sent to the protected AI endpoint
- [x] Add route-entry and hover transitions for Planner, Mock Tests, and Flashcards, respecting reduced-motion preferences
- [x] Verify desktop and mobile tutor layouts
- [x] `pnpm check` passes
- [x] `pnpm test` passes — 2 files, 7 tests
- [x] `pnpm build` succeeds
