===============
Troubleshooting
===============

The timestamp in the data is wrong
----------------------------------
Kaspersky LEEF format outputs the timestamp in UTC. In the Add-on versions <=0.1.2 the time zone setting was not set explicitly in props, so splunk was assuming system default time. The result was events showing up in the future for systems in GMT- and in the past for systems in GMT+.
