---
name: Issue
about: Report an issue with the application
title: "[ISSUE]"
labels: ''
assignees: ''

---

# Issue Documentation Template

## Issue Summary
**Title:** [Brief, descriptive title of the issue]
**Priority:** [Critical/High/Medium/Low]
**Status:** [Open/In Progress/Under Review/Resolved/Closed]
**Assignee:** [Developer name or team]
**Reporter:** [Name of person reporting the issue]
**Date Reported:** [YYYY-MM-DD]
**Last Updated:** [YYYY-MM-DD]

## Problem Description
### What is happening?
[Clear, concise description of the observed behavior or problem]

### What should happen instead?
[Description of the expected behavior or desired outcome]

### Impact Assessment
- **Severity:** [Blocking/Major/Minor/Cosmetic]
- **Affected Users:** [Number/percentage of users affected]
- **Business Impact:** [How this affects business operations or user experience]
- **Workaround Available:** [Yes/No - if yes, describe below]

## Environment Details
### System Information
- **Operating System:** [Windows 10/11, macOS, Linux distribution]
- **Framework Version:** [.NET version, Avalonia version, etc.]
- **IDE/Editor:** [Visual Studio, Rider, VS Code, etc.]
- **Build Configuration:** [Debug/Release]

### Dependencies
- **Key Libraries/Packages:** [List relevant NuGet packages with versions]
- **Database:** [If applicable - type and version]
- **Third-party Services:** [Any external services involved]

## Steps to Reproduce
1. [First step]
2. [Second step]
3. [Third step]
4. [Continue with detailed steps...]

**Expected Result:** [What should happen]
**Actual Result:** [What actually happens]

## Code Samples
### Minimal Reproducible Example
```csharp
// Provide the simplest code that demonstrates the issue
// Include relevant XAML, C#, or other code snippets
```

### Related Code Context

#### View (XAML/UI)
```xml
<!-- Include relevant XAML markup, user controls, styles -->
<!-- Show binding expressions, data templates, etc. -->
```

#### ViewModel
```csharp
// Include relevant view model code
// Show properties, commands, data binding implementations
// Include INotifyPropertyChanged implementations if relevant
```

#### Domain
```csharp
// Include relevant domain models, business logic
// Show entity classes, domain services, business rules
// Include any domain-specific validation or calculations
```

#### Data
```csharp
// Include relevant data access code
// Show repositories, data contexts, API calls
// Include database schemas, entity configurations if relevant
```

## Error Messages and Logs
### Exception Details
```
[Full exception stack trace if available]
```

### Console Output
```
[Relevant console output or debug information]
```

### Log Files
```
[Relevant log entries with timestamps]
```

## Investigation Notes
### Root Cause Analysis
[Findings from investigation - what's causing the issue]

### Areas Investigated
- [x] [Area 1 - findings]
- [x] [Area 2 - findings]
- [ ] [Area 3 - pending investigation]

### Hypotheses Tested
1. **Hypothesis:** [Theory about the cause]
    - **Test:** [How you tested it]
    - **Result:** [Outcome]

## Screenshots/Media
[Include relevant screenshots, GIFs, or videos that help illustrate the problem]
- Screenshot 1: [Description]
- Video: [Description of what the video shows]

## Workaround
### Temporary Solution
[If a workaround exists, provide detailed steps]

### Limitations of Workaround
[Any drawbacks or limitations of the temporary solution]

## Proposed Solution
### Approach
[Detailed description of the proposed fix]

### Implementation Plan
1. [Step 1]
2. [Step 2]
3. [Step 3]

### Risks and Considerations
- [Risk 1 and mitigation strategy]
- [Risk 2 and mitigation strategy]

### Testing Strategy
- [Unit tests needed]
- [Integration tests needed]
- [Manual testing steps]

## References
### Related Issues
- [Link to related GitHub issues, tickets, or documentation]

### Documentation
- [Links to relevant documentation, Stack Overflow posts, or resources]

### Code Reviews/Pull Requests
- [Links to related PRs or code reviews]

## Resolution
### Final Solution
[Description of how the issue was ultimately resolved]

### Code Changes
[Brief summary of code changes made]

### Verification
- [x] [Verification step 1]
- [x] [Verification step 2]
- [x] [Verification step 3]

### Follow-up Actions
- [ ] [Action item 1]
- [ ] [Action item 2]
- [ ] [Update documentation]

## Post-Resolution Notes
### Lessons Learned
[Key takeaways from this issue]

### Prevention Measures
[Steps to prevent similar issues in the future]

---

## Template Usage Guidelines

### For Reporters
- Fill out as much information as possible when creating a new issue
- Be specific and provide concrete examples
- Include all relevant environment details
- Test with minimal reproducible examples when possible

### For Investigators
- Update status and findings regularly
- Document all hypotheses and testing approaches
- Include relevant code snippets and logs
- Communicate impact and timeline clearly

### For Reviewers
- Verify reproduction steps work
- Check that the proposed solution addresses root cause
- Ensure adequate testing coverage
- Review for potential side effects

---
*Last updated: [Date]  
Template version: 1.0*
