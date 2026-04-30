# Camel-Case-Matching

[![Pharo P14](https://img.shields.io/badge/Pharo-P14-2c98f0.svg)](https://github.com/pharo-completion/camel-case-matching)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://github.com/pharo-completion/camel-case-matching/blob/master/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/pharo-completion/camel-case-matching/pulls)
[![Status: Active](https://img.shields.io/badge/status-active-success.svg)](https://github.com/pharo-completion/camel-case-matching)

Camel Case Matching is a pharo extension that introduces optional camel-case matching for global and class completions. It extends prefix matching to work on the internal structure of identifiers, not just their beginning. 

### Example :

<img width="471" height="301" alt="CamelCaseMatching" src="https://github.com/user-attachments/assets/45220566-2e5d-4ce1-a027-ab9dce9ca359" />


---

```smalltalk
Metacello new
  githubUser: 'pharo-completion' project: 'camel-case-matching' commitish: 'main' path: 'src';
  baseline: 'CamelCaseMatching';
  load.
```
