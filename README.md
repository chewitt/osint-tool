# osint-tool

osint-tool is a low-tech tool written in bash for managing the download of OSINT threat intelligence feeds for SOC tools. The main features are:

- Downloading feeds with IP indicators
- Combining feeds, deduplicating and sorting indicators
- Applying static allow/block overrides
- Manipulating feeds for use with Fidelis solutions
- Publising (via nginx/apache)

Feed automation is handled via cron on the host system.

NB: It is an intentionally simple tool that focusses on getting the job done more than bash ettiquette. Contributions that improve how it works are welcomed!
