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

Will design documentation require revisions?

Due date? Justify:

Additional Comments?



***V&V Checklist:***

@biosensics/engineering : 
- [ ] Team lead determine if full or partial V&V is needed
- [ ] Request ECO number from [Quality](mailto:quality@biosensics.com)
- [ ] ECO Section I submitted to [Quality](mailto:quality@biosensics.com)
      (`G:\Shared drives\QSR\BS-02 Quality System Procedures (SOPs)\BS-02-0021_Software Changes, Releases and Documentation`)
- [ ] ECO Section I approved
- [ ] Server has been configured
- [ ] APK connects to server (indicate if Test, Production, UAT or QA)
- [ ] CLI tools set up
- [ ] Parse account created in correct server

@biosensics/operations :
- [ ] Hexnode portal/policy set up
- [ ] Mobile device operating system is correct
- [ ] Mobile device model is correct (version, iOS/Android, etc.)
- [ ] Sensor firmware is correct
- [ ] Device enrolled in Hexnode
- [ ] Equipment set up for V&V execution
- [ ] Parse account created

*Ensure all above items have been completed before continuing*

@biosensics/test-and-manufacturing :
- [ ] V&V executed
- [ ] Completed V&V submitted to [Quality](mailto:quality@biosensics.com)

@biosensics/engineering :
- [ ] Configure production server (if not an initial release)
- [ ] ECO Section II submitted to [Quality](mailto:quality@biosensics.com)
- [ ] ECO Section II approved

@biosensics/quality :
- [ ] ECO closed filed to QSR
- [ ] Insert file path(s) to documentation (ECO, V&V etc):
- [ ] New version released
