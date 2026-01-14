Windows Logon Analysis (event ID 4625, 4624 and 4672)

This project analyses Windows Security logon events using Splunk.

Event ID 4625 shows failed logon attemps. this event is generated when the user fails to log into a Windows system. It can indicate incorrect credentials, unauthorised access attemps, or potential brute force activity. SOC analysts monitor this event to detect suspicius login behaviour and possible account compromised

Event ID 4624 shows successful logon attemps. This event is generated when a user successfully logs on to the Windows system. I t is used to track normal user activity, and correlate with failed login attemps to identify suspecious login patterns. 

Event ID 4672 shows special privileges assigned to a new Logon. This occures when a user is granted privilages after loggin in, monitoring this event is important in the SOC enviroment because it can indicate privilage escalation or high risk account activity 

Statistics and event views were used to identify authentification behaviour and potential security issues.

Tool used: Splunk Cloud
