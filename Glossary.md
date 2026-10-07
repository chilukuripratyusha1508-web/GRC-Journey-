# GRC Glossary

My own-words definitions while learning cybersecurity GRC (Governance, Risk, Compliance).

## Asset
Anything valuable that needs protecting. In cybersecurity this is not only laptops, but also data, servers, software and even company reputation.
**Example:** the customer database.

## Threat
Something that can cause damage to an asset.
**Example:** an angry employee who steals data and misuses it.

## Vulnerability
A weakness that a threat can use (exploit).
**Example:** a tester has access to every document in the company, not just testing documents. If he misuses it, nothing stops him. (This breaks the "least privilege" rule: give people only the access their job needs.)

## Risk
The chance that something bad happens, combined with how badly it would hurt.
**Example:** a hacker (threat) guesses a weak password (vulnerability) and steals the database (asset).

## Control
A safeguard that reduces risk.
**Example:** MFA, firewalls, backups.

## Policy
A written rule from management saying what must be done.
**Example:** every asset must be checked monthly and patched.

## Confidentiality
Only authorized people can see the data.
**Example:** a salary file visible only to HR. Encryption and access control are ways to achieve it.

## Integrity
Data stays correct and is not changed by anyone who has no permission to change it.
**Example:** in the movie 3 Idiots, the speech was secretly altered before it was delivered. Hashing is one way to detect such changes.

## Availability
Systems and data are accessible when needed.
**Example:** a banking app that is down during salary day has failed on availability.

## Compliance
<!-- REWRITE IN YOUR OWN WORDS -->
Following required laws, standards and rules.
**Example:** (add your own)

## Framework
<!-- REWRITE IN YOUR OWN WORDS -->
A readymade structure of best practices.
**Example:** NIST, ISO 27001.

## Audit
<!-- REWRITE IN YOUR OWN WORDS -->
An independent check, using evidence, of whether controls exist and work. It can be internal or external.

## Risk Assessment
<!-- REWRITE IN YOUR OWN WORDS -->
Identify assets, threats and vulnerabilities, rate likelihood and impact, rank the risks and recommend what to do.

## Inherent Risk
The risk that exists before any controls are applied.

## Residual Risk
<!-- REWRITE IN YOUR OWN WORDS -->
The risk left over after all controls are applied. It never comes to zero.

## Incident
A security event that actually harms, or seriously threatens, the confidentiality, integrity or availability of a system or data.
**Example:** ransomware locks all company files.
