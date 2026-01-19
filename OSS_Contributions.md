# 🌟 Open Source Contributions - Mithra J

[![Open Source Love](https://badges.frapsoft.com/os/v2/open-source.svg?v=103)](https://github.com/mithra-j)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)

Welcome to my open source journey! This repository showcases my contributions to various open source projects, demonstrating my skills in collaborative development, Git workflows, and community engagement.

---

## 📊 Contribution Overview

```mermaid
gantt
    title OSS Contribution Timeline
    dateFormat  YYYY-MM-DD
    section 2026
    Coffee Website :done, 2026-01-19, 1d
    OpenRefine :active, 2026-01-17, 2d
    Dinosaur Exploder :2026-01-20, 2d
Project	Type	Status	Tech Stack
Coffee Website	UI/UX Enhancement	✅ Open & Assigned	HTML, CSS, JS
OpenRefine	UI Bug Fix	⏳ Awaiting Review	JavaScript, CSS
Dinosaur Exploder	Feature Implementation	📝 Planned	JavaScript, API
🚀 Recent Contributions
1. Coffee Website
🔧 Fixing Dark/Light Mode Transitions

https://img.shields.io/badge/PR-%252322-blue
https://img.shields.io/badge/Issue-%252314-orange

Before & After:

text
❌ BEFORE: Abrupt color changes causing visual jumps
✅ AFTER: Smooth 300ms transitions for pleasant UX
Changes Made:

css
/* Added smooth transitions */
body, .navbar, .card {
  transition: background-color 0.3s ease, 
              color 0.3s ease,
              border-color 0.3s ease;
}
Impact: Enhanced user experience with subtle, performant animations

2. OpenRefine
🎯 Fixing UI Consistency

https://img.shields.io/badge/PR-%25237610-blue

Problem: Inconsistent button spacing between icon and text-only buttons
Solution: Standardized padding and margin across all button variants

Visual Fix:

text
Buttons with icons    : [🎯 Action] ← Fixed spacing
Buttons without icons : [Action]    ← Now aligned
Tech Details: Isolated CSS fix ensuring no side effects on existing functionality

3. Dinosaur Exploder
📈 Implementing Pagination for GitHub API

https://img.shields.io/badge/Issue-%252399-orange

Current Challenge: API query excludes older repositories with "Good First Issue" labels
Planned Solution: Implement pagination to fetch all relevant issues

Expected Implementation:

javascript
// Planned pagination logic
async function fetchAllGoodFirstIssues() {
  let allIssues = [];
  let page = 1;
  
  while (true) {
    const issues = await fetchGitHubAPI(`page=${page}`);
    if (issues.length === 0) break;
    allIssues.push(...issues);
    page++;
  }
  return allIssues;
}
Goal: Ensure complete data retrieval while maintaining API rate limit compliance

📈 Contribution Stats
Metric	Count
Open PRs	2
Issues Participated	3
Projects Contributed	3
Languages Used	4
🛠️ Technologies Used
https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white
https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white
https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black
https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white
https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white

📝 Contribution Philosophy
✅ Clean Commits - Atomic commits with descriptive messages
✅ Clear PR Descriptions - Context, problem, solution, testing
✅ Respectful Collaboration - Following community guidelines
✅ Performance Conscious - Lightweight, efficient solutions

🔮 What's Next?
Get PRs reviewed and merged

Contribute to more large-scale OSS projects

Work on backend/open source tools

Document my learning journey

📬 Let's Connect!
Found an interesting project I should contribute to? Have feedback on my contributions?

https://img.shields.io/badge/GitHub-Profile-black?style=for-the-badge&logo=github
https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin

Last Updated: January 2026
This portfolio is actively maintained and updated with new contributions
