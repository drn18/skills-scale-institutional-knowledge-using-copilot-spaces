# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

## Progress Monitoring

### GitHub-Native Tools
- **GitHub Projects**: Visual board to track issues and PRs across workflow states
  - Use views (table, board, roadmap) to monitor different aspects
  - Track issue status, assignees, and milestones in real-time
  - Filter by labels, sprint, or team member
- **Pull Requests Tab**: Monitor all open PRs and review status
  - Check PR age and review bottlenecks
  - View CI/CD status at a glance
  - Track approval and merge readiness
- **GitHub Actions**: Monitor CI/CD pipeline health
  - Review workflow runs for build and test status
  - Identify failing jobs and patterns
  - Track deployment progress to staging/production
- **Insights Tab**: Analyze repository activity and trends
  - Review commit frequency and contributor activity
  - Monitor code frequency and additions/deletions
  - Track issue and PR resolution times

### Copilot Coding Agent Monitoring
When using GitHub Copilot's coding agent for automated work:
- **Mission Control**: Track agent task status and progress
  - View active and completed agent sessions
  - Monitor task execution time (typically 5-15 minutes)
  - Access detailed logs and session history
- **Check from Copilot Space**: Query open PRs and agent status directly
  - Use prompt: "check open pull requests"
  - Review agent-created PRs and their progress
  - Verify agent completion and review readiness

### Progress Tracking Best Practices
- **Daily**: Check GitHub Projects board for blockers and PR status
- **Weekly**: Review velocity, burndown, and sprint progress
- **Per Sprint**: Analyze completed vs. planned work and adjust estimates
- **Continuous**: Monitor CI/CD pipelines for test failures and deployment status

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup
- Level 2: PM escalates to Product Lead and dependent teams
- Level 3: Sponsor-level escalation for business-impacting issues

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
