# Megan Small | Frontend case study
## M Studio instant quote tool
Live demo: https://mlinx.studio/tools

### The problem
Service businesses need to turn job details into a useful estimate without asking visitors to complete a long form or create an account.

### My contribution
Built and iterated on M Studio’s website and browser tools using AI-assisted development. Applied firsthand service-business experience to the inputs, estimate breakdown and customer inquiry path.

### The interface
The quote tool groups industry, service, property size, frequency and add-ons alongside a price range and itemized explanation. A recurring discount is identified separately. Copy and download controls let visitors retain an estimate; an inquiry link gives them a next step.

### Verified interaction walkthrough
1. Cleaning / Standard / four bedrooms / three bathrooms / biweekly: $189–$222.
2. Increase bedrooms to five: $204–$239; the size line changes from $138 to $156.
3. Add inside-oven cleaning: $229–$268; a $30 add-on appears in the breakdown.

These are sample inputs and demo estimates, not customer records or charges. The walkthrough was checked in the live browser on October 6, 2026. Screenshots show the settled UI after each change. No inquiry, email or payment was submitted.

### Design decisions to discuss
- Use a range to communicate an estimate rather than presenting an exact final charge.
- Explain the price with service, size and add-on line items.
- Keep the result visible near the controls so users can see the effect of changing an input.
- Provide a path from exploration to an inquiry without requiring signup to try the tool.

### Stack
Next.js, TypeScript, Tailwind CSS, Vercel. These describe the project stack; AI-assisted implementation should be discussed honestly in interviews.

### Verification boundaries and next checks
This review verified two input changes and their visible results. It did not audit the pricing formula, run component tests, validate every industry or test keyboard and screen-reader behavior. Next checks: keyboard focus and controls, mobile layout at several widths, boundary values, add-on toggling, and automated assertions for representative input/result pairs.

### Interview practice
Explain how an input change reaches the displayed estimate, where pricing rules live, and how you would test a regression. Use the actual source when preparing; this case study does not establish the internal component or state-management implementation.
