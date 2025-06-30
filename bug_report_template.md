# Bug Report Template
*Fairytale Finder QA Testing*

---

## Bug Information

**Bug ID**: [BUG-FF-XXX]  
**Date Reported**: [MM/DD/YYYY]  
**Reported By**: [Tester Name]  
**Assigned To**: [Developer/Team]  
**Status**: [Open/In Progress/Fixed/Closed/Reopened]

---

## Bug Classification

**Severity**: 
- [ ] **Critical** - App crashes, data loss, security breach
- [ ] **High** - Major feature broken, blocks core functionality  
- [ ] **Medium** - Feature works but with issues, workaround available
- [ ] **Low** - Minor cosmetic issues, spelling errors

**Priority**:
- [ ] **P1** - Fix immediately (blocks release)
- [ ] **P2** - Fix before release
- [ ] **P3** - Fix in next version
- [ ] **P4** - Fix when time permits

**Bug Type**:
- [ ] Functional
- [ ] UI/UX
- [ ] Performance
- [ ] Security
- [ ] Compatibility
- [ ] Data/Content

---

## Environment Details

**Device**: [iPhone 13, Samsung Galaxy S21, etc.]  
**Operating System**: [iOS 16.1, Android 12, Windows 11]  
**Browser** (if web): [Chrome 108, Safari 16, etc.]  
**App Version**: [1.0.0]  
**Network**: [WiFi/4G/5G]  

---

## Bug Description

### Summary
**One-line description of the issue:**  
[Clear, concise summary that explains what's wrong]

### Detailed Description
**What exactly is happening?**  
[Comprehensive explanation of the problem, including context and impact]

### Steps to Reproduce
**How can someone else see this bug?**
1. [Start from a specific state/screen]
2. [Perform specific action]
3. [Continue with exact steps]
4. [Include any specific inputs/selections]
5. [Note when the problem occurs]

### Expected Behavior
**What should happen instead?**  
[Describe the correct/intended functionality]

### Actual Behavior  
**What is actually happening?**  
[Describe the incorrect behavior observed]

---

## Supporting Evidence

### Screenshots/Videos
- [ ] Screenshot attached showing the issue
- [ ] Video recording of bug reproduction
- [ ] Before/after comparison images
- [ ] Error messages captured

**File Names**: [List any attached files]

### Console Logs/Error Messages
```
[Paste any error messages, console output, or technical details here]
```

### Additional Context
[Any other relevant information: user actions leading up to bug, frequency of occurrence, related issues, etc.]

---

## Impact Assessment

**User Impact**: [How does this affect the user experience?]  
**Business Impact**: [Does this affect core app functionality or user retention?]  
**Frequency**: [How often does this occur? Always/Sometimes/Rare]  
**Workaround Available**: [Yes/No - if yes, describe the workaround]

---

## Testing Notes

**Test Case Reference**: [Link to related test case if applicable]  
**Related Bugs**: [Reference any similar or related bug reports]  
**Regression**: [Is this a new bug or regression from previous version?]

---

## Example Bug Reports

### BUG-FF-001: AI Companion Stops Responding
**Summary**: AI companion becomes unresponsive after 10+ messages in conversation

**Environment**: iPhone 13, iOS 16.1, App v1.0.0, WiFi

**Steps to Reproduce**:
1. Start new conversation with AI companion
2. Send 10-15 messages in quick succession
3. Notice responses become slower
4. After message 12-15, AI stops responding entirely
5. No error message appears

**Expected**: AI should continue responding throughout conversation  
**Actual**: AI becomes completely unresponsive, conversation appears frozen

**Severity**: High (blocks core functionality)  
**Priority**: P1 (fix immediately)

---

### BUG-FF-002: Virtual Home Items Disappear
**Summary**: Decoration items vanish from virtual home after app restart

**Environment**: Samsung Galaxy S21, Android 12, App v1.0.0, 4G

**Steps to Reproduce**:
1. Decorate virtual home with 5+ items
2. Save home configuration 
3. Exit app completely
4. Restart app and navigate to virtual home
5. Notice some decoration items are missing

**Expected**: All placed items should remain in their positions  
**Actual**: 2-3 random items disappear, leaving empty spaces

**Severity**: Medium (feature works but data not persistent)  
**Priority**: P2 (fix before release)

---

*Use this template to ensure all bugs are reported with sufficient detail for developers to understand and fix the issues quickly.*