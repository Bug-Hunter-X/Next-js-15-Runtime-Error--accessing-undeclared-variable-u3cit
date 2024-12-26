# Next.js 15 Runtime Error: accessing undeclared variable

This repository demonstrates a runtime error in Next.js 15 that occurs when accessing an undeclared variable within a page component.

## Description

The `about.js` file attempts to access a variable (`badVariable`) that is not defined.  This results in a runtime error in Next.js 15. This is different from previous versions where this might have been handled differently or given a different error.

## Reproduction

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.
4. Navigate to `/about`.
5. Observe the runtime error.

## Solution

The `aboutSolution.js` shows how to fix the error by declaring the variable or handling potential errors.