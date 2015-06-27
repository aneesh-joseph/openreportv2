# Open Report V2 #
### This is a branch of Open Reports (http://sourceforge.net/projects/oreports/) will be updating it with few more feature. ###


## Below are the features that have been made available in this release ##

  * Dashboard with Alerts Conditional Scheduling
  * Global Scheduler Admin
  * Drill Down Chart Reports
  * Reporting Statistics
  * Upgraded Jasper Reports, BIRT, Quartz (1.8) and Hibernate (3.6) to the latest versions.
  * Password encryption when storing in the DB tables.
  * Encrypted password for UserID:password(admin:admin) is admin:=?UTF-8?B?YWRtaW4=?=
  * Integrated JMESA instead of DisplayTag for displaying HTML reports.

## To Do ##

  * Remove JFreeReports as this project is dead and replaced by Pentaho. Need to see if Pentaho can/should be integrated.
  * Add AJAX using YUI
  * Add FTP report sharing function
  * Try to get the Dashboard Portlets functionality using an open source Portlet framework.
  * Downloadable link sent in the email for scheduled reports (in case the size of the  report is more and the email system doesn’t allow more than 10mb of attachment)