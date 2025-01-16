# User behavior analysis 

**Required plugins** : Natural Language to KQL to Microsoft Defender XDR, Microsoft Defender XDR, Microsoft Entra, Microsoft Purview

**Required Input**: < userUPN> < Duration >

**Description**: Investigate a user behavior by analyzing authentication methods, logins, associated devices, audit logs, etc.

1.

 ```
Tell me more about <userUPN>.
 ```

2.

 ```
What devices are associated with the above user?
 ```

3.

 ```
Show me the last login for the above user during the last <duration>.
 ```

4.

```
What authentication methods are set up for the above user?
```
5. 

```
Did the above user have any failed sign-ins during the last <duration>? If yes, list the location and IP address of each failed sign-attempt.
```

6. 
```
Show audit logs for the above user in the last <duration>
```

7. 
```
From Purview, list the activities performed by above user in the last <duration>
