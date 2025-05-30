This is a grade export plugin which will create an Excel spreadsheet containing all the checkmarks from a single checklist.
You can customise the included fields by editing the included file 'columns.php'.

It will not work without the checklist module - which can be downloaded here:
http://moodle.org/plugins/view.php?plugin=mod_checklist

==Changes==

* 2025-04-19 - 4.0.0.0 - M5.0 compatibility fixes, drop support for M3.11 and below
* 2024-10-19 - 3.4.2.2 - Minor M4.5 compatibility fixes
* 2024-04-05 - 3.4.2.1 - Minor M4.4 compatibility fixes
* 2023-10-02 - 3.4.2.0 - update GitHub actions ready for 4.3 release
* 2023-04-14 - 3.4.1.0 - Minor M4.2 compatibility fixes
* 2022-11-19 - Minor M4.1 compatibility fixes
* 2022-06-28 - Add missing tertiary navigation in M4.0 (to access other grade export plugins)
* 2022-01-22 - Minor M4.0 compatibility fixes
* 2021-04-10 - minor internal documenation update + switch from Travis to Github actions
* 2020-10-17 - speed improvement when calculating user start date on the course
* 2019-12-16 - minor improvement to error message when no checklists to export
* 2018-05-28 - fix typo causing major problems with defining roles
* 2018-04-02 - declare plugin stores no user data (for GDPR), this version only compatible with M3.4+
* 2017-11-09 - Minor behat test fix to work with Moodle 3.4
* 2017-05-12 - Update behat test to work with Moodle 3.3
* 2016-11-21 - Minor M3.2 compatibility fix (only behat affected)
* 2015-09-07 - Fix M2.7+ compatibility (gradeexport/checklist:publish + calculation of 'start date'); fix PostgreSQL compatibility (Thanks to Nick Phillips, Kathrin Osswald)
* 2013-03-20 - Fix assign-by-reference error
* 2012-09-19 - Split the 3 plugins (mod / block / grade report) into separate repos for better maintenance
* 2012-07-07 - Tested against Moodle 2.3
* 2012-02-02 - Added optional percentages for each student / heading / item - based on code from Gordon Bateson ( gordonbateson@gmail.com )
* 2012-02-02 - Added choice of not exporting 'optional' items
* 2012-01-27 - French translation from Luiggi Sansonetti
* 2012-01-02 - Minor tweaks to improve Moodle 2.2+ compatibility (optional_param_array / context_module::instance )
