Virginia Academic Planner

Version: 13.05

Author: Matt Walters

Overview:

This page is intended to meet the virginia requirements for student academic plans.
http://www.doe.virginia.gov/instruction/graduation/academic_career_plan.shtml

Click the Add link in each program of study cell to begin adding courses. Multiple courses can be added
at once. Click "add courses" to add them to the cell. Click a course in the program of study to remove it.

Pages (A)dded or (C)hanged:

A: /admin/students/academicPlan.html
A: /admin/students/academicPlanCourses.json
A: /admin/studetns/academicPlanCoursesSearch.json

Number of fields added:
students: 17 (VA), 18 (Not VA)

Installation:
Use the CPM import function to import the zip file, or upload the pages manually. Add a link to
academicPlan.html to /admin/students/more2.html

I would recommend accessing the page directly, using the url:
admin/students/home.html&ac=suv;lsp=/admin/students/academicPlan.html
until testing is done.

Known Issues:

The diploma seals are not yet active.

Cannot duplicate a course in the student selected test or online course area. This is planned.
Duplication will not be allowed outside of these cells.

Browser Compatibility:
Should work in: IE9, recent versions of firefox and chrome.

Disclaimer:
This page comes with no warranty expressed or implied. It is supplied AS IS. It is recommended that
you thoroughly test this on a non-production server.

This page is currently IN TESTING and should not be used for production purposes.

Change log:
---------------- 13.05 ----------------
Resolved an issue with IE9 displaying "undefined" instead of the course number and name
	when removing a course from the program of study.
Reworked the modal dialog display a bit.
Added the ability to remove courses from the modal dialog by clicking on them.
Added check for feature Array.prototype.indexOf. If not present, it redirects the user to quicklookup.
Diploma Seals now working.
Hid program of study field.

---------------- 13.04 ----------------
Initial Release
