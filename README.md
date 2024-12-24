# React Router Dom Catch-All Route Issue

This repository demonstrates a common issue encountered when using the catch-all route (`/*`) in React Router Dom v6. The catch-all route unintentionally intercepts all navigation attempts, even when other routes should be matched.

The `App.js` file contains the buggy code.  The `AppSolution.js` file provides a corrected version.  The problem is that the catch all route `/*` should only match if no other routes match.  The solution is to move the catch all route to the end of the Routes.