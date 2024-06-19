# KLM Flight Academy Maintenance Department
This organization serves to gather all coding projects done for and by the KLM Flight Academy Maintenance Department. Repositories are private but current development consists of the following projects:

### maintenance-statistics
Code to match AcMP maintenance data with FlightLogger flight hours and cycles statistics to generate year-based maintenance statistics such as number of (un)scheduled work per 1000 flight-hours, average turnaround times, average costs, average amount of work-hours and more.

### reliability-monitoring
Code to match AcMP part traceability data with FlightLogger flight hours and cycles to generate part-specific reliability statistics and investigate possible preventive maintenance programs.

### flightlogger-wrapper
Wrapper for the FlightLogger API providing a single function for fetching of a variety of data from FlightLogger.

### CANport-processor
Server-based implementation for handling of received data from CANport modules. Utilizes the Microsoft Graph API to fetch incoming emails with data and handles these accordingly. If deemed required, notifications are sent by email to the Technical Department and over Telegram using the Telegram API.