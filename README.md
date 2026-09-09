# QA_Intern_Assignment_Aditi_Gosavi
## Candidate Information

**Candidate Name:** Aditi Gosavi  
**Submission Date:** 09 September 2026

## Application Tested

**Application:** OomniEye – Digital Twin Solutions  
**Environment:** Staging  
**Module Tested:** Users

## Submission Links

**GitHub Repository:** https://github.com/AditiGosavi/QA_Intern_Assignment_Aditi_Gosavi

**Final Explanation Video:** https://drive.google.com/drive/folders/1O6pBMogXSZUtmwEsE5C21y2YVhFJqZpj?usp=drive_link



## Tools Used

- Manual Testing
- Microsoft Excel – Test Scenarios, Test Cases and Bug Reports
- Browser Developer Tools
- Browser for application testing
- Screen Recording – Final Explanation Video

## Browser / Environment

**Browser:** Microsoft Edge  
**Environment:** Staging Environment  
**Application:** OomniEye Digital Twin Solutions

## Testing Areas Covered

The testing was primarily focused on the Users module and included:

- User listing
- Search
- Add User
- Filtering
- Sorting
- Pagination
- Column management
- Data export
- Negative testing
- Boundary / edge testing
- UI / usability testing
- Data validation

## Assumptions

- The Users module is expected to allow authorized users to view and manage user records.
- Phone Number should accept valid phone-number data and reject alphabetic input.
- Canceling the Add User operation should discard unsaved data.
- Search and filter operations should display appropriate results or a no-result state when no matching records exist.
- Exported data should correspond to the selected export options.

## Limitations

- Testing was performed on the available staging environment.
- Testing was primarily focused on the Users module.
- Some application requirements and field validation rules were not explicitly defined.
- Advanced security testing was not performed.
- Access/permission behavior was not conclusively verified.
- Automation execution was not completed as part of this practical assignment.

## Execution Summary

- **Total Test Scenarios:** 17
- **Total Test Cases Executed:** 17
- **Passed:** 15
- **Failed:** 2
- **Blocked:** 0
- **Defects Identified:** 3

## Defects Identified

1. **BUG-001:** Cancelled Add User form retains previously entered unsaved data.
2. **BUG-002:** Phone Number field accepts and saves alphabetic characters.
3. **BUG-003:** Three-dot row action menu is visible only when hovering over the user row.

## Conclusion

The Users module was tested across functional, negative, boundary, UI/usability, and data-validation areas. Most of the tested functionality worked as expected. Three defects were identified during testing, including a phone-number validation issue and an Add User form data-retention issue. These defects should be reviewed and resolved before production release.
