# PR #2 — Acceptance Test Guide

Use **synthetic data only**. This is an illustrative screening POC, not a validated risk assessment.

## Design and navigation
- [ ] Dashboard displays a professional dark-blue hero and assessment workspace.
- [ ] Setup, Screening, Risk domains, and Results remain navigable on desktop and mobile.
- [ ] Browser refresh retains the active assessment.

## Internal mode
- [ ] Enter organization, use case, AI tool, assessor, and description.
- [ ] Answer screening questions and verify domain descriptions, why-it-matters context, and examples.
- [ ] Add notes to a risk domain; navigate away and back and verify persistence.

## Consultant mode
- [ ] Change assessment mode to Consultant-led.
- [ ] Verify the same core risk questions appear, with additional consultant evidence prompts.
- [ ] Verify report identifies the mode as Consultant-led client assessment.

## Results and reporting
- [ ] Mark AEIC-01, 02, 04, 10, and 11 Yes; mark other items Unknown or No.
- [ ] Verify totals reconcile to 20 domains and chart colors match response categories.
- [ ] Verify report labels Organization name, Assessment type, AI use case, Tool, Assessor, and Date.
- [ ] Verify each finding explains what, why, suggested control, and why the control helps.
- [ ] Verify High/Moderate classification includes plain-language explanation and next steps.
- [ ] Mark AEIC-05 Yes and confirm Critical escalation regardless of index.
- [ ] Print / Save PDF and verify report is legible with headings and chart.

## Known POC limitations
- Classification is an illustrative screening index, not validated risk likelihood × impact.
- Domain answers indicate applicability, not proven failure or severity.
- The visualizations display response distribution, not domain-level severity.
- Browser storage holds only one assessment and is not secure storage for client information.
- No user authentication, independent evidence verification, multiuser approval, or certification.
- No real architectural imagery is embedded; design uses a restrained built-environment-inspired visual style.
