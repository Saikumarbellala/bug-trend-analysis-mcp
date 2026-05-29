---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| Total Bugs Analyzed | 25 |
| Modules Affected | 5 (API, Login, Dashboard, UI, Database) |
| Bugs Reached Production | 9 (36%) |
| Root Cause Categories | 6 |
| Bugs Resolved | 0 (All open) |

---

## 🔍 Bug Distribution by Component

| Component | Bugs | % |
|-----------|------|---|
| 🔌 API | 6 | 24% |
| 🔐 Login | 5 | 20% |
| 📊 Dashboard | 5 | 20% |
| 🖥️ UI | 5 | 20% |
| 🗄️ Database | 4 | 16% |

---

## 📍 Bug Distribution by Phase Found

| Phase | Bugs | % |
|-------|------|---|
| 🧪 QA | 10 | 40% |
| 🚀 Production | 9 | 36% |
| 🏗️ Staging | 6 | 24% |

> ⚠️ 36% of bugs only reached production — meaning QA missed them!

---

## 🔎 Root Cause Analysis

| Category | Bugs | % |
|----------|------|---|
| 🔴 Coding Defects | 6 | 24% |
| 🟠 Testing Gaps | 5 | 20% |
| 🟡 Requirement Gaps | 4 | 16% |
| 🟢 Design / Architecture | 4 | 16% |
| 🔵 Process / Tooling | 4 | 16% |
| 🟣 Human Factors | 4 | 16% |

---

## 🐛 All 25 Bugs — Full List

| Issue | Summary | Component | Phase | Root Cause |
|-------|---------|-----------|-------|------------|
| KAN-4 | Login page crashes on invalid email format | Login | QA | Coding Defect |
| KAN-5 | Dashboard data not loading for special characters | Dashboard | QA | Coding Defect |
| KAN-6 | API timeout causes blank screen | API | Production | Requirement Gap |
| KAN-7 | Reports page slow due to missing DB indexes | Database | Staging | Design/Architecture |
| KAN-8 | UI buttons misaligned on mobile screens | UI | QA | Testing Gap |
| KAN-9 | Password reset email fails for uppercase emails | Login | Production | Human Factors |
| KAN-10 | CI/CD pipeline missing API integration test gate | API | Staging | Process/Tooling |
| KAN-11 | Dashboard missing internationalization support | Dashboard | Production | Requirement Gap |
| KAN-12 | Duplicate records on double-click submit | Database | QA | Coding Defect |
| KAN-13 | Export to PDF blank pages for large reports | UI | Production | Testing Gap |
| KAN-14 | Session token valid after logout (security) | API | QA | Design/Architecture |
| KAN-15 | Date picker wrong format for non-US users | UI | Staging | Human Factors |
| KAN-16 | Login endpoint has no rate limiting | Login | QA | Testing Gap |
| KAN-17 | Database backup failure not monitored | Database | Production | Process/Tooling |
| KAN-18 | Dashboard chart incorrect totals on date filter | Dashboard | QA | Coding Defect |
| KAN-19 | File upload API has no size limit | API | Staging | Requirement Gap |
| KAN-20 | Notification badge not resetting after read | UI | Production | Coding Defect |
| KAN-21 | Search fails for Unicode/accented characters | Dashboard | QA | Human Factors |
| KAN-22 | Cascading failure due to missing circuit breaker | API | Production | Design/Architecture |
| KAN-23 | Automated UI tests not enforced in merge process | UI | QA | Process/Tooling |
| KAN-24 | Remember me checkbox not persisting session | Login | Staging | Coding Defect |
| KAN-25 | Real-time dashboard stops updating after 30 min | Dashboard | Production | Testing Gap |
| KAN-26 | API exposes internal stack traces to users | API | QA | Human Factors |
| KAN-27 | DB table without partitioning causes scale issues | Database | Staging | Design/Architecture |
| KAN-28 | 2FA deployed without user documentation | Login | Production | Process/Tooling |

---

## ✅ Recommendations

### 🚨 Immediate
- Fix KAN-14 and KAN-16 — active security vulnerabilities
- Implement mandatory peer code reviews before every merge

### 📅 Short-Term
- Enforce CI/CD gates — tests must pass before merge
- Expand QA test plans to cover mobile, security, and edge cases
- Create requirement checklist covering i18n, timeouts, file limits

### 🗺️ Long-Term
- Full architecture review with security and scalability checklist
- Add circuit breaker pattern to microservices
- Set up monitoring and alerting for all background jobs
- Developer onboarding program on security and Unicode handling

---

## 📈 How This Assignment Was Completed
Step 1 → Created free Jira account at bellalasaikumar1998.atlassian.net
Step 2 → Connected Atlassian MCP to Claude AI
Step 3 → Created project KAN (Bug Tracking)
Step 4 → Claude AI created 25 realistic bugs via MCP API
Step 5 → Fetched all bugs using JQL query via MCP
Step 6 → Analyzed trends and categorized root causes
Step 7 → Generated interactive HTML dashboard + report
Step 8 → Published to GitHub
---

## 👨‍💻 Author

**Bellala Saikumar**
GitHub: [github.com/Saikumarbellala](https://github.com/Saikumarbellala)

---

*Generated using Claude AI + Atlassian Rovo MCP Integration | May 2026*
