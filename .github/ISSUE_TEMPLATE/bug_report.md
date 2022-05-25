---
name: Bug report
about: Create a report to help us improve
title: "[BUG]"
labels: bug, needs-triage
assignees: ''

---

### Does your log mention database corruption?

If your application log reports panics because of database corruption it is
most likely a fault with your system's storage or memory. Affected log
entries will contain lines starting with `panic: leveldb`. 

### Include required information

Please be sure to include at least:

 - which version of this app and what operating system you are using
 - browser and version, if applicable
 - what happened,
 - what you expected to happen instead, and
 - any steps to reproduce the problem.
