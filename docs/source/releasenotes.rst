=============
Release Notes
=============

v0.1.4 - April 2020
-------------------
- App compatibility changed to starting from 7.1.0 due to app.manifest version and Splunk Cloud compatibility
- Improved CIM change datamodel coverage
- Added missing extractions of signature field for several sourcetypes


v0.1.3 - October 2019
---------------------
- Fix issue with the events timezone detection
LEEF format outputs a timestamp in UTC and splunk was detecing it as system default resulting in events in the future for systems in GMT- and in the past for systems in GMT+
  

v0.1.2 - September 2019
-----------------------
- Small fixes
- Improvements on some extractions


v0.1.0 - August 2019
--------------------
- Public release to Splunkbase
