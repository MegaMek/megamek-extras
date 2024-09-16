## Description

Please provide a summary of the changes, including related issues (e.g., Fixes #), the type of change (Bug Fix, New Feature, Refactoring), and the scope of the changes. Make sure to explain the impact of the change and any relevant context.

## Type of Change

Please select the type of change this PR introduces:
- [ ] **Bug Fix**: A code change that fixes an issue.
  - Fixes # (issue) <!-- Provide the issue number this PR fixes to automatically close it when merged -->
- [ ] **New Feature**: A code change that adds functionality.
  - Addresses RFE # (issue) <!-- Provide the issue number this PR fixes to automatically close it when merged -->
- [ ] **Refactoring**: A code change that improves the structure, quality, or performance of the code without altering functionality.

## Checklist

### General Requirements
- [ ] **No use of the Trademarked terms "MechWarrior", "BattleMech", "'Mech", or "AeroTech". in the code or comments**
   - Use "MekWarrior", "BattleMek", "'Mek", and "AeroTek" instead.
- [ ] **Are you using descriptive variable, class, and function names? Human Readable code**
  - [ ] Ensure names like `mechBA` are replaced with descriptive alternatives such as `mechanizedBattleArmor`.
- [ ] **Ensure you have documented your code using JavaDoc.**
- [ ] **Follow coding standards** including formatting, naming conventions, and avoiding deprecated or disallowed terms.

### For Bug Fixes
- [ ] The bug has been identified, and I have provided details about its cause.
- [ ] The fix resolves the issue without introducing new bugs or breaking existing functionality.
- [ ] I have added tests that verify the fix, including tests with both valid and invalid inputs.
- [ ] I have reviewed related code to ensure the fix does not impact other areas of the codebase.
- [ ] **Have you added or verified tests** for related sections of the codebase, even if they weren’t directly changed in this PR?

### For New Features
- [ ] I have written comprehensive **tests** for the new feature, including tests with good and bad values.
- [ ] I have ensured that this new feature does not break existing functionality.
- [ ] I have updated relevant **documentation** to reflect the new feature, including user guides or developer docs.
- [ ] **Have you added or verified tests** for related sections of the codebase, even if they weren’t directly changed in this PR?

### For Refactoring
- [ ] I have ensured that **no functionality** has changed during refactoring.
- [ ] I have written **tests** to ensure refactored code works as expected.
- [ ] I have improved code readability, performance, or maintainability with the refactor.
- [ ] **Have you added or verified tests** for related sections of the codebase, even if they weren’t directly changed in this PR?

### Forward Compatibility
- [ ] **If changing existing behavior** saved to preferences or files, provide a **forward-facing conversion path** until the next Milestone release.
- [ ] **Have you ensured to document and prepare the removal of the conversion** after the next Milestone?

## Additional Notes

Please include any additional comments or notes for the reviewer here.
