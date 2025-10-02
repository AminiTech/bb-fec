# Energy Access Dashboard

## Overview and Logistics

We respect your time. This is a short, 3-hour **design challenge** to understand how you think.

Your written explanations are more important than the code you write. The final step will be a 30-minute live discussion about your submission. Please do not spend more than 3 hours of your precious time on this challenge.

## The Problem

At Amini, we build many data dashboards. The process is slow and inconsistent. We need a platform that helps any engineer build good dashboards quickly.

For example, a team might need to build a dashboard for energy data like this:

```json
[
  {
    "country": "Algeria",
    "iso_a3": "DZA",
    "grid_coverage": 41,
    "renewable_adoption": 50
  },
  {
    "country": "Angola",
    "iso_a3": "AGO",
    "grid_coverage": 99,
    "renewable_adoption": 20
  },
  {
    "country": "Benin",
    "iso_a3": "BEN",
    "grid_coverage": 45,
    "renewable_adoption": 24
  },
  ...
]
```

---

## The Task

Imagine you have 3 hours to start this new platform. A full project would include these tasks:

1. Setup a component library project with Storybook.
2. Build a core reusable component.
3. Build a small dashboard app to show data.
4. Create a GitHub Actions workflow for linting and testing.

## What to Submit

You are not expected to complete all the tasks above in 3 hours. Your main goal is to choose what is most important.

### 1. Code

The code you chose to write. Please include one small, reusable component (like a `<Card>` or `<MetricDisplay>` or `<DataTable>` or `<BarChart>` etc).

- **Special requirement:** Our current system requires styling components with a single `style` prop that takes a raw CSS string (e.g., `style="background-color: white;"`). Follow this pattern for your component.

### 2. README

This is the most important part. Answer these questions simply:

- What did you build, and why was it the most important first step?
- What did you not build, and why?
- What is your opinion of the "special requirement" for styling?
- What are the next 2-3 things you would do in the next sprint?

Add any other info you think you should include in the README.

### 3. Do Not

- Build a backend server.
- Build the full dashboard.

## What We Are Looking For

- Your choices and how you prioritize under pressure.
- Your reasoning for your architectural decisions and trade-offs.
- Your ability to plan for scalability, reuse, and the experience of other engineers.
- The code quality of the small component you write.
- How clearly you explain your ideas.
