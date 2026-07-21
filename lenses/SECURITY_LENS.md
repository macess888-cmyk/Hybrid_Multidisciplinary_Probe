# Security Lens

## Purpose

Inspect how the system behaves under manipulation, compromise, malformed input, misuse, or adversarial pressure.

## Questions

- What is the threat model?
- Which assets are protected?
- Which trust assumptions exist?
- What happens under malformed input?
- What happens under replay?
- What happens under substitution?
- What happens under compromised identity or keys?
- Are controls fail-safe?
- Are unrelated controls preserved?
- Does the same verifier distinguish vulnerable and fixed behavior?

## Pressure Tests

- cryptographic integrity != substantive correctness
- authentication != authorization
- confidentiality != availability
- secure interface != accurate output
- modeled attack resistance != universal security
- fixed candidate pass != remediation proof without baseline