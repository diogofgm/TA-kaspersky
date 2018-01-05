# Splunk TA for Kaspersky

*Install*
- Install both the TA in the search heads and indexers (or fowarders)
- Setup a TCP input pointed to index an (e.g. kaspersky) with the sourcetype kaspersky
- Configure Kaspersky Security Center to send logs to you splunk instance via syslog using the LEEF (Q1 Radar) option (other formats will be available in the future)

*Roadmap*
- Include extractions in case of CEF format being used
- Add missing event types for sourcetype renaming

*Feedback*
feedback+kaspersky_ta@devbusters.com
