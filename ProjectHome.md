Future replacement for iCDR program sold as an add-on for iSWITCH and iSERVER voice platform.

Project is started on Slackware 12.

TCPflow selectively collects CDR's generated from iSWITCH,
AWK parses them and prepares script.sql,
shell command inserts CDRs into MySQL database,
PHP5 provides interface for reviewing CDR's.