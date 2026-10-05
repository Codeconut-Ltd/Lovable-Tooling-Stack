# Limitations & Disclaimer

TOC

- [Stack & Tooling](#stack--tooling)
- [Code Analyzers](#code-analyzers)
- [Configuration & Rules](#configuration--rules)
- [Disclaimer](#disclaimer)

---

## Stack & Tooling

Some stacks might be best run in local environments only.

While static code analyzers mostly do not cost anything by default, they might incur additional costs when used through AI services, due to the amount of code processed and the output that could be generated.

---

## Code Analyzers

Not all code analyzers are 'beginner-friendly' for non-coders and are best used with formatters/fixers that solve things automatically. Whenever a simple solution is not available, one can either instruct an AI to follow the tooling rules or relax the rules to allow more flexibility.

---

## Configuration & Rules

Applications often work fine with less strict rules (e.g. TypeScript compiler settings). Some rules are intended for large-scale codebases – if the project is a prototype or not yet at that stage, it might be decided to relax them now and harden them later.

Adjust them to a level that is comfortable and allows progress while keeping the application maintainable. Note that rules affect maintainability at a basic level, and stability or security at more profound levels.

---

## Disclaimer

It is advised to be familiar with software engineering and web security principles. The code is provided as-is, without any warranty regarding future results. All software it relies on is maintained by third parties and might change over time.

### Functionality

'Reduce drift and potential bugs': The stack provided is designed to improve application quality. However, because corrections and suggestions can change code, it can introduce delays in creating features or even introduce other bugs if an AI implements suggestions incorrectly.

As each project, stack, and AI model behaves differently, it is best to explore over time which rules and configurations work best for the project. Ultimately, they should keep the application healthy and help craft results faster, rather than become a burden themselves.

No legacy stacks or versions are supported. The code is up to date at the time of release. The user is responsible for keeping the stack up to date and secure over time.

### Security

> Never sacrifice security for speed or ease!

Code run on a local machine, whether produced by AI/LLM decisions or executed as part of a tooling stack, is always considered a security risk to the machine.

Always use a safe, isolated environment – e.g. a Docker container, VM, or remote cloud host with a vendor that specializes in these environments and keeps them secure.

### Responsibility

**Codeconut Ltd.** assumes no responsibility for security, maintainability, or application stability issues that arise from using the provided tooling stack. Unless a specific contractual agreement for maintenance services exists, the user is responsible for keeping software up to date, staying technically informed, and ensuring that their project meets all necessary requirements and regulations.

If users are uncertain about the implications of using the provided tooling stack, they should seek professional advice or refrain from using it.
