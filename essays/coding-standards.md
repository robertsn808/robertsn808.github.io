---
layout: essay
type: essay
title: "Lint Me Baby One More Time"
date: 2025-02-10
published: true
labels:
  - ESLint
  - TypeScript
  - Software Engineering
---

<img src="../img/coding-standards/coding-standards.jpg"class="rounded mx-auto d-block" alt="Coding Standards">

## **The Great Debate: Tabs vs. Spaces?**

Many people dismiss coding standards as trivial; things like whether to use tabs or spaces, where to place curly braces, or how to structure import statements. While those details do contribute to readability, reducing coding standards to simple formatting rules is like saying good writing is just about punctuation. Sure, punctuation helps, but clarity, structure, and consistency are what make writing truly effective. The same applies to code.

## **Coding Standards: The One Rule to Rule Them All**

If I could only implement one software engineering practice to improve quality, it would be coding standards. Why? Because they are the foundation of maintainability, readability, and even learning. Well-defined standards enforce best practices, prevent common pitfalls, and establish a shared language within a team. They transform code from a chaotic mess into something predictable, structured, and, most importantly, easier to work with. And let’s be honest—most of coding isn’t writing new code; it’s reading and modifying existing code. When a team follows coding standards, every developer spends less time deciphering what’s going on and more time solving actual problems.

## **ESLint: My Unexpected TypeScript Mentor**

But there’s another overlooked benefit of coding standards: they can teach you a programming language. This is something I’ve experienced firsthand with TypeScript and ESLint. At first, I thought of ESLint as just a tool to nag me about missing semicolons. However, within my first week of using ESLint in VSCode, I realized it was doing something much more valuable—it was forcing me to confront aspects of TypeScript that I didn’t fully understand. 

For example, ESLint threw an error about how I was declaring generics in a function. Instead of blindly fixing it, I questioned why the rule existed. That curiosity led me to read the TypeScript documentation, which deepened my understanding of type inference and proper generic usage. The same thing happened with intersection vs. union types, immutability rules, and function signatures. Each error message became an opportunity to refine my approach and write better, more idiomatic TypeScript.

## **The Pain and the Payoff**

So, was getting rid of all those ESLint errors painful? Absolutely. But was it useful? Without question. It was both frustrating and rewarding—a cycle of being called out for bad habits, fixing them, and coming out the other side a stronger developer. 

Some developers view linting as an annoyance, something to silence with `// eslint-disable-next-line`. But if you actually engage with it, it becomes a mentor. It challenges your assumptions, encourages you to read the fine print of the language, and forces you to be intentional about your coding choices. 

## **Conclusion: Why Standards Matter**

In the end, coding standards aren't just about making code look nice. They're about writing code that is easier to understand, debug, and extend. More than that, they are a tool for continuous learning. So the next time ESLint throws an error, instead of instinctively dismissing it, ask yourself: *Why is this a rule in the first place?* That simple shift in mindset can turn a frustrating experience into a powerful learning opportunity.

