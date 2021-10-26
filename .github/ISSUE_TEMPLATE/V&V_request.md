---
name: V&V Request
about: Checklist for V&V
title: 'V&V Request'
labels: 
assignees: '@abbylindsay'

---
***Please title the issue with the detailed study/project name (not just company/hospital name)***

**Initial request:**

Please explain why a V&V is needed:

Due date? Justify:

Does the V&V or SRS need to be revised?:



***V&V Checklist:***

@biosensics/engineering : 
- [ ] Determine if full or partial V&V is needed
- [ ] Request ECO number from [Quality](mailto:quality@biosensics.com)
- [ ] ECO Section I completed and approved (`G:\Shared drives\QSR\BS-02 Quality System Procedures (SOPs)\BS-02-0021_Software Changes, Releases and Documentation`)
- [ ] Server has been configured
- [ ] APK connects to server (test, or production for initial release)
- [ ] CLI tool set up

@biosensics/operations :
- [ ] Equiptment set up
- [ ] Test account created
- [ ] Attach V&V PDF to this issue

*Ensure all above items have been completed before continuing*
@biosensics/test-and-manufacturing
- [ ] V&V executed
- [ ] Attach filled out V&V to this issue

@biosensics/engineering
- [ ] Configure production server (if not an initial release)
- [ ] ECO Section II completed and approved
- [ ] Attach ECO to this issue
