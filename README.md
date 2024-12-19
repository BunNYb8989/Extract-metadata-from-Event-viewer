# Extract-metadata-from-Event-viewer
    Custom power script
PowerShell Script Overview
1.Extract Event Data: Use the Get-WinEvent cmdlet to retrieve relevant events from the Windows Event Log.
2.Filter Required Information: Focus on specific attributes such as usernames, IP addresses, and timestamps.
3.Format Data for API: Prepare the extracted data in a format suitable for sending to the third-party API.
4.Send Data to API: Use Invoke-RestMethod or Invoke-WebRequest to forward the data.
