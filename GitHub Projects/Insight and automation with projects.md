# Insights and Automation with GitHub Projects 📊🤖

## Insights with Projects

### What are Insights?
- Visual charts that help you track and understand your Project data.
- Charts are available to anyone who can view the Project.

### Types of Charts
- **Current charts:** Show real-time data like issues assigned or upcoming work.
- **Historical charts:** (For GitHub Team and Enterprise) Show progress and trends over time, like burn up charts.

### How to Create and Customize Charts
1. Open your Project.
2. Click the line graph (Insights) icon (top right).
3. Select **New chart**.
4. Filter data by keywords or fields.
5. Save the chart.
6. Select your chart to configure:
   - Choose chart type (bar, line, etc.).
   - Select X-axis and group items if needed.

---

## Automation with Projects

### Ways to Automate
- Built-in workflows
- GraphQL API
- GitHub Actions workflows

### Built-in Workflows (Easy Setup)
- Automatically add new issues and pull requests with a "Todo" status.
- To enable:
  1. Open Project > three-dot menu > **Workflows**.
  2. Select **Item added to project**.
  3. Edit workflow:
     - Include issues and pull requests.
     - Set Status to "Todo".
  4. Save and activate workflow.

### GitHub Actions for Custom Automation
- Create workflows triggered by events (e.g., when an issue is created).
- Perform tasks like adding labels, commenting, moving issues to boards automatically.

### GraphQL API Automation
- Use GitHub's GraphQL API to build custom project automation.
- More advanced setup for developers.

---

With insights and automation, you can work smarter, track progress better, and keep your team aligned! 🚀

_Next: Module assessment_
