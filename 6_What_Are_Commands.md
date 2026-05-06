![[Splunk_Command.png]]
- **First**: Search Terms.
- **Pipe |**: To tell Splunk to pass the current results on to the next component.
# Best Practices
- Search Terms, Commands, Functions... **ARE NOT CASE SENSITIVE**
- Specific values **ARE CASE SENSITIVE**
- **DO** "failed password" **NOT** "password"
- **DO** "access denied" **NOT** "NOT access granted"
- **DO** user IN (admin, administrator) **NOT** user=admin OR user=administrator
- **DO** sourcetype=access_combined failed **NOT** sourcetype=\*
