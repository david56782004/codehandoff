# Service scope

## Standard report

The customer authorizes a specific repository and commit. CodeHandoff performs
a read-only static scan and delivers:

1. Delivery-readiness score and grade.
2. High-priority findings with file and line references.
3. Documentation, dependency, CI, test-organization, complexity, risky-call,
   and secret-pattern checks.
4. A prioritized repair list with approximate effort.
5. A short HTML, Markdown, or JSON explanation.

## Exclusions

- No execution of untrusted project code.
- No guarantee of zero vulnerabilities or acceptance.
- No security audit, penetration test, legal opinion, or complete coverage
  measurement.
- No access to production systems, customer records, secrets, or payment data.

## Delivery process

1. Customer confirms the repository or a sanitized copy, commit, scope, and
   intended use.
2. Both parties confirm the final price, delivery date, and refund terms in
   writing.
3. Customer pays through the owner-provided method after confirmation.
4. Customer supplies only material they are authorized to share.
5. CodeHandoff performs the static scan and validates that all report artifacts
   open correctly.
6. Customer receives the report and can ask for the included clarification.

## Stop conditions

CodeHandoff will stop when:

- The supplied material appears to contain third-party secrets or personal
  data that is not authorized.
- The request requires executing unknown code in an unsafe environment.
- The customer asks for a guaranteed audit result or misrepresentation.
- The final scope is too broad for the agreed price or delivery window.
- Payment, tax, platform rules, or data rights are unresolved.

