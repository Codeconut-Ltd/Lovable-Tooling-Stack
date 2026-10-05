# Limitations & Disclaimer

TOC

- [Stack & Tooling](#stack--tooling)
- [Code Analyzers](#code-analyzers)
- [Configuration & Rules](#configuration--rules)
- [Disclaimer](#disclaimer)

---

## Stack & Tooling

Some stacks might be best run in local environments only.

While the static code analyzers mostly don't cost anything by default, they might incur higher costs if used via AI; due to the amount of code processed and output that could be generated.

---

## Code Analyzers

Not all code analyzers are 'beginner-friendly' for non-coders and best used with formatters/ fixers, that solve things automatically. Whenever a simple solution is not available, one can either instruct AI to follow the tooling rules, or relax rules to allow more flexibility.

---

## Configuration & Rules

Applications often work fine with less strict rules (e.g. TypeScript type definitions). Some rules are intended for large-scale code bases – If the project is a prototype or not there yet, it might be decided to relax now and harden later.

Adjust it to a level, that is comfortable and allows progress, while keeping the application maintainable. Note that rules affect maintainability at the simplest, and stability or security at more profound levels.

---

## Disclaimer

It is advised to be familiar with software engineering and web security principles. The code is provided as-is, without future warranty of claims provided. All software it relies on is maintained by 3rd parties and might change over time.

### Functionality

'Reduce drift and potential bugs': The stack provided is designed to improve application quality – However, due to the nature of increasing the potential for corrections and suggestions to change code, it can introduce either delays in creating features, or even introduce other bugs, if an AI implements suggestions incorrectly.

As each project, stack and AI model behaves differently, it is best explored over time, what rules and configurations work best for the project. Ultimately, they shall keep the application healthy and let craft results faster; not become a burden themselves.

No legacy stacks and versions are supported. Code is up-to-date at the time of release. The user is responsible to keep the stack up-to-date and secure over time.

### Security

> Never sacrifice security for speed or ease!

Code run on a local machine, either resulting of AI/ LLM decisions or executing tooling stacks, always is considered a security risk to the machine.

Always use a safe, isolated environment – e.g. a Docker container/ VM or remote cloud host, with a vendor that specializes in these stacks and keeping them secure.

### Responsibility

**Codeconut Ltd.** assumes no responsibility for security, maintainability or application stability issues that arise from using the provided tooling stack. Unless a specific contractual agreement for maintenance service provision exists, the user is responsible to keep software up to date, stay technically informed, and ensure that their project meets all necessary requirements and regulations.

If users are uncertain about the implications of using the provided tooling stack, they should seek professional advice or refrain from using it.
