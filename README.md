# MeetingAnalyzer
Meeting Analyzer takes advantage of a new Exchange powershell command that is available in Exchange 2016 and in the Exchange Online service - Get-CalanderDiagnosticObjects
The tool will create a remote powershell connection based on URI, Admin name and password, and then it will prompt for the SMTP address of the user with a problem Meeting Item, and the Subject of that Meeting Item. Once this is entered in - the tool runs the powershell command, retrieves the data, parses and analyzes the data, and produces output showing the version history of the particular meeting. It's great for troubleshooting what happened to a particular meeting on a users Calendar.

Please check the wiki for more info and documentation.
