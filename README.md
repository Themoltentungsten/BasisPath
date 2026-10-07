# BasisPath — Interactive Basis Path Testing Lab

Static Netlify-ready academic project. No framework, build step, API, or backend required.

## What works
- 3 realistic case studies: ATM Withdrawal, Login + Retry, Student Result
- Calculates McCabe Cyclomatic Complexity from graph edges/nodes: `V(G) = E - N + 2`
- Interactive SVG control-flow graph
- Click/select independent paths and highlight their route
- Minimum basis-path test set generated from each case study
- Test runner animates the execution trace and marks the test passed
- Export a plain-text analysis report
- Dark mode and responsive layout

## Netlify
Upload/push the contents of this folder to GitHub and import the repository in Netlify. Leave Build command empty and publish directory as `/` (root).
