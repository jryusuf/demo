---
name: User Story (INVEST)
about: Create a vertical slice of functionality
title: 'As a [Role], I want [Action], so that [Benefit]'
labels: 'Story'
assignees: ''
---

### 1. The Story
**As a** [Role]
**I want** [Action]
**So that** [Benefit]

### 2. INVEST Checklist (Must check all)
- [ ] **Independent:** Can we build this without waiting for other tickets?
- [ ] **Negotiable:** Is the "how" open to discussion?
- [ ] **Valuable:** Does the user actually care about this?
- [ ] **Small:** Can this be finished in 2-3 days? (If NO, use SPIDR below)
- [ ] **Testable:** Do we know exactly how to mark this "Done"?

### 3. SPIDR Breakdown (If "Small" is unchecked)
*If this story is too big, how should we split it?*
- [ ] **Spike:** Do we need to research first?
- [ ] **Paths:** Can we do just the "Happy Path" first?
- [ ] **Interface:** Can we do just the API or just the CLI first?
- [ ] **Data:** Can we handle just simple data (valid inputs) first?
- [ ] **Rules:** Can we relax the business rules for now?

### 4. Acceptance Criteria (Gherkin)
- Given [context]
- When [event]
- Then [outcome]
