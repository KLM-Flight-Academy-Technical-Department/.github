# KLM Flight Academy Maintenance Department
This organization serves to gather all coding projects done for and by the KLM Flight Academy Maintenance Department. Repositories are private but current development consists of the following projects:

### maintenance-statistics
Code to match AcMP maintenance data with FlightLogger flight hours and cycles statistics to generate year-based maintenance statistics such as number of (un)scheduled work per 1000 flight-hours, average turnaround times, average costs, average amount of work-hours and more.

### reliability-monitoring
Code to match AcMP part traceability data with FlightLogger flight hours and cycles to generate part-specific reliability statistics and investigate possible preventive maintenance programs.

### flightlogger-wrapper
Wrapper for the FlightLogger API providing a single function for fetching of a variety of data from FlightLogger.

### jopie
Jopie is a system developed specifically for use by the KLM Flight Academy maintenance department. Jopie is a continuously running script handling incoming ECU data, FlightLogger data and much more. The purpose of Jopie is to develop a helper for the Technical Department, assisting in whatever data-gathering and reporting is necessary and relieving the office employees as much as possible.

### warranty-helper
The warranty helper is a script that processes AcMP traceability and work-order data to generate a simple to use Excel for aid in identifying possible warranty claims.