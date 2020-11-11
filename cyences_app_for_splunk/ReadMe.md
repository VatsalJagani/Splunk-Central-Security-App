# Cyences App for Splunk

### Download from Splunkbase
The Splunkbase link is not available yet.


OVERVIEW
--------
The Cyences App for Splunk is an Splunk App to provide complete security to the environment. It does not contain data collection mechanism. It contains useful security alerts/reports and dashboards.


* Author - CrossRealms International Inc.
* Version - 1.0.0
* Build - 1
* Creates Index - False
* Compatible with:
   * Splunk Enterprise version: 8.0, 7.3, 7.2 and 7.1
   * OS: Platform Independent
   * Browser: Google Chrome, Mozilla Firefox, Safari



TOPOLOGY AND SETTING UP SPLUNK ENVIRONMENT
------------------------------------------
This app can be set up in two ways: 
  1. Standalone Mode: 
     * Install the `Cyences App for Splunk`.
  2. Distributed Mode: 
     * Install the `Cyences App for Splunk` on the search head.
     * App do not require on the Indexer or on the forwarder.


INSTALLATION, DEPENDENCIES, DATA COLLECTION & CONFIGURATION
------------------------------------------------------------
Visit https://cyences.com/cyences-app-for-splunk/ for complete configuration guide.


UNINSTALL APP
-------------
To uninstall app, user can follow below steps:
* SSH to the Splunk instance
* Go to folder apps($SPLUNK_HOME/etc/apps).
* Remove the `cyences_app_for_splunk` folder from apps directory
* Restart Splunk


RELEASE NOTES
-------------
Version 1.0.0
* Created App Dashboards, Alerts and Reports.


LOOKUPS
-------
The lookups directory will have lookups from the customer environment.

1. all_windows_hosts.csv
2. cs_ransomware_file_writes_upperbound.csv
3. ip_range_blocked_list.csv (Current file has been taken from http://iplists.firehol.org/)
4. ip_blocked_list.csv (Current file has been taken from https://honeydb.io/ sample list)
5. cs_malicious_ip_list.csv (List contains the bad IP addresses involve in various activities like DDoS attack or it's an already blocked IP address and connecting through multiple firewalls.)


OPEN SOURCE COMPONENTS AND LICENSES
------------------------------
* NA


CONTRIBUTORS
------------
* Vatsal Jagani
* Usama Houlila
* Preston Carter
* Ahad Ghani


SUPPORT
-------
* Contact - CrossRealms International Inc.
  * US: +1-312-2784445
* License Agreement - https://d38o4gzaohghws.cloudfront.net/static/misc/eula.html
* Copyright - Copyright CrossRealms Internationals, 2020