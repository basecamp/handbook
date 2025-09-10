# 🤖 Handbook Automation System

This repository now includes intelligent automation to streamline employee onboarding using GitHub Issues and CI/CD workflows.

## 🚀 How It Works

### 1. Create a Master Onboarding Issue
- Go to **Issues** → **New Issue** → **📋 New Employee Onboarding**
- Fill out the employee details:
  - Name, Role, Level, Start Date
  - Manager and Buddy assignments
  - Any special notes

### 2. Automatic Sub-Issue Creation
When you create the master issue, GitHub Actions will automatically:
- Parse the employee details
- Extract role requirements from `titles-for-{role}.md` files
- Generate 6-8 sub-issues covering:
  - 🖥️ IT Setup & Account Provisioning
  - 📚 Week 1 Integration Tasks
  - 🎯 Role-Specific Skills Development  
  - 📊 Performance Review Milestones (3/6/12 months)

### 3. Intelligent Task Generation
Tasks are customized based on:
- **Role**: Designer, Programmer, Ops, QA, Support
- **Level**: L1 (Junior) through L5 (Principal)
- **Handbook Content**: References specific sections and requirements

## 🛠️ Automation Workflows

### Knowledge Extraction (`extract-knowledge.yml`)
- **Triggers**: Push to `*.md` files, manual dispatch
- **Purpose**: Parses handbook content into structured data
- **Output**: Knowledge base artifact for other workflows

### Employee Onboarding (`onboard-employee.yml`) 
- **Triggers**: Issues labeled `onboarding-master`
- **Purpose**: Creates comprehensive onboarding sub-issues
- **Features**: Role-specific tasks, timeline milestones, proper assignments

## 📋 Generated Issue Types

| Issue Type | Purpose | Timeline | Assigned To |
|------------|---------|----------|-------------|
| 🖥️ IT Setup | Equipment & accounts | 1 week before start | Ops team |
| 📚 Week 1 Integration | Manager meetings, introductions | First week | Manager + Buddy |
| 🎯 Skills Development | Role-specific learning plan | Ongoing | Manager |
| 📊 Performance Reviews | Formal review preparation | 3, 6, 12 months | Manager |

## 🎯 Benefits

- **Consistency**: Every employee gets the same comprehensive onboarding
- **Accountability**: Clear task assignments and timelines
- **Visibility**: Managers and HR can track progress across all new hires
- **Scalability**: Handbook changes automatically update onboarding templates
- **Audit Trail**: Complete history of onboarding activities in GitHub Issues

## 📈 Usage Examples

### New Junior Programmer
```
Master Issue: "📋 Onboard: Alice Johnson - Programmer - 2025-02-01"
Generated Tasks:
- 🖥️ IT Setup for Alice Johnson
- 📚 Week 1 Onboarding - Alice Johnson  
- 🎯 Programmer Skills Development - Alice Johnson (4-year L1→L3 plan)
- 📊 3-Month Review - Alice Johnson
- 📊 6-Month Review - Alice Johnson
- 📊 12-Month Review - Alice Johnson
```

### Senior Designer  
```
Master Issue: "📋 Onboard: Bob Smith - Designer - L3 - 2025-02-15"
Generated Tasks:
- 🖥️ IT Setup for Bob Smith
- 📚 Week 1 Onboarding - Bob Smith
- 🎯 Designer Skills Development - Bob Smith (Senior-level expectations)
- 📊 3-Month Review - Bob Smith  
- 📊 6-Month Review - Bob Smith
- 📊 12-Month Review - Bob Smith
```

## 🔧 Customization

The automation system is built to be flexible:

- **Add new roles**: Create `titles-for-{role}.md` and the system will auto-detect
- **Modify task templates**: Edit the workflow in `onboard-employee.yml`
- **Adjust timelines**: Update milestone schedules in the automation logic
- **Custom requirements**: Add role-specific logic in the task generation

## 📚 Technical Details

- **Language**: Node.js with GitHub's Octokit API
- **Permissions**: Requires `issues: write` for task creation
- **Data Source**: Extracts from handbook markdown files
- **Issue Linking**: Master issues link to all generated sub-issues

---

*This automation transforms the static handbook into a living onboarding system that scales with your team while maintaining the personal touch 37signals values.*