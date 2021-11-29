---
name: V&V Request
about: Checklist for V&V
title: 'V&V Request'
labels: 
assignees: '@abbylindsay'

---
***Please title the issue with the detailed study/project name (not just company/hospital name)***

Note: not applicable items will be struck through

**Initial request:**

**Please explain why a V&V is needed**:

**Will design documentation require revisions?**

**Due date? Justify:**

**Additional Comments?**



***V&V Checklist:***

@biosensics/engineering : 
- [ ] Team lead determine if full or partial V&V is needed
- [ ] Request Server ECO number from [Quality](mailto:quality@biosensics.com)
- [ ] Server ECO Section I submitted to [Quality](mailto:quality@biosensics.com)
      (`G:\Shared drives\QSR\BS-02 Quality System Procedures (SOPs)\BS-02-0021_Software Changes, Releases and Documentation`)
- [ ] Server ECO Section I approved
- [ ] Update Server `CHANGELOG.md` "Unreleased" section
- [ ] Create server release issue in server repository using the Release Issue template 
- [ ] Deploy server release candidate to Aptible test server
- [ ] Confirm any updated Aptible test server configuration values
- [ ] APK connects to server (indicate if Test, Production, UAT or QA)
- [ ] Confirm internal Zoom meeting room
- [ ] Set GitHub secrets per server configuration values and Zoom (if applicable)
- [ ] Update Application `CHANGELOG.md` "Unreleased" section
- [ ] Create application release issue in application repository using the Release Issue template
- [ ] Link this issue to the correct release version
- [ ] Request App ECO number from [Quality](mailto:quality@biosensics.com)
- [ ] App ECO Section I submitted to [Quality](mailto:quality@biosensics.com)
      (`G:\Shared drives\QSR\BS-02 Quality System Procedures (SOPs)\BS-02-0021_Software Changes, Releases and Documentation`)
- [ ] App ECO Section I approved
- [ ] CLI tools set up
- [ ] Send Application RC build to operations team for V&V

@biosensics/operations & @biosensics/quality :
- [ ] V&V Document Released
- [ ] Complete DCO and submit to [Quality](mailto:quality@biosensics.com)
- [ ] Hexnode portal/policy set up
- [ ] Mobile device operating system is correct
- [ ] Mobile device model is correct (version, iOS/Android, etc.)
- [ ] Sensor firmware is correct
- [ ] Device enrolled in Hexnode
- [ ] Equipment set up for V&V execution
- [ ] Parse account created in correct server

*Ensure all above items have been completed before continuing*

@biosensics/test-and-manufacturing :
- [ ] V&V executed
- [ ] Completed V&V submitted to [Quality](mailto:quality@biosensics.com)

@biosensics/engineering :
- [ ] App ECO Section II submitted to [Quality](mailto:quality@biosensics.com)
- [ ] App ECO Section II approved
- [ ] Server ECO Section II submitted to [Quality](mailto:quality@biosensics.com)
- [ ] Server ECO Section II approved
- [ ] Ensure correct Zoom meeting room is set
- [ ] Create server release
- [ ] Deploy server release to Aptible production server
- [ ] Confirm any updated Aptible production server configuration values
- [ ] Merge `release` branch into `master` on server repository
- [ ] Merge `release` branch into `master` on Application repository
- [ ] Send release APK to operations and quality for production use


@biosensics/quality :
- [ ] App ECO closed & filed to QSR
- [ ] Server ECO closed & filed to QSR
- [ ] Insert file path(s) to documentation (ECO, V&V etc):
- [ ] New version released
