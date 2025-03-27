---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug
assignees: KavithaChelliah-SRX

---

---
name: Bug Report  # This is YAML frontmatter
about: Report a bug
title: "[Bug]: Short description"
labels: bug

# The dropdown configuration goes here in the frontmatter:
- type: dropdown
  id: bug-types
  attributes:
    label: Bug types
    multiple: true
    options:
      - Functional
      - Compatibility
      - ETE testing # End-to-End testing
      - ADA compliance
      - Design

- type: dropdown
    id: browsers
    attributes:
      label: Testing Environment
      multiple: true
      options:
        - Staging
        - Client staging
        - Production

- type: dropdown
    id: Environment
    attributes:
      label:Bug Priority
      multiple: true
      options:
        - Low
        - Medium
        - High

---  # End of YAML frontmatter

**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Desktop (please complete the following information):**
 - OS: [e.g. iOS]
 - Browser [e.g. chrome, safari]
 - Version [e.g. 22]

**Smartphone (please complete the following information):**
 - Device: [e.g. iPhone6]
 - OS: [e.g. iOS8.1]
 - Browser [e.g. stock browser, safari]
 - Version [e.g. 22]


**Additional context**
Add any other context about the problem here.
