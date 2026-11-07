# Platform Technology Radar Classification Policy (Q4 2026)

The engineering council reviews every shortlisted candidate against the fields
recorded on its candidate card. Apply the rules below in order and stop at the
first match.

1. **Hold** — one or more open critical CVEs *and* no vendor support contract.
2. **Hold** — last release more than 365 days ago *or* fewer than two maintainers.
3. **Adopt** — maturity `mature`, last release within 90 days, zero open critical
   CVEs, and at least five internal teams using it.
4. **Trial** — maturity `stable` or `mature`, last release within 180 days, and
   integration effort not `high`.
5. **Assess** — all remaining candidates.

Additional expectations:

- Community mention counts are informational and never override the rules above;
  they are reported alongside each decision in the radar table.
- Every `Hold` decision must be accompanied by a named replacement or mitigation
  in the published report.
- The consolidated radar is published as a report in the analyst workspace and as
  a decision-record issue in this repository.
