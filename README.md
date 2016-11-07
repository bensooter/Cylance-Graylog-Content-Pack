Graylog Content Pack for Cylance PROTECT
=========================

This content pack adds an input and extractors for handling the syslog feed from Cylance PROTECT

**Required Graylog version:** 2.0.0 and later

## Includes

* Input Cylance Syslog (Syslog TCP 6514) 
* GROK Pattern - DATESTAMP2: Allows the DATESTAMP function to capture AM/PM.
* Multiple extractors to handle the various Cylance message formats that can come in.

## Requirements

Cylance PROTECT configured to send syslog TCP data on Graylog on port 6514.
