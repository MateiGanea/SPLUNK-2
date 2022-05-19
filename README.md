# SPLUNK-2
# Windows Server Attack
# all users should have to use MFA


# APACHE WEBSERVER ATTACKS
# My findings indicate that the attacks originate from ukraine. A firewall blocking access from Ukraine entirely would be effective. Additionally the user agent: Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; SV1; .NET CLR 2.0.50727987787; InfoPath.1) Can be blocked by the firewall as an additional rule and a third rule can be added filtering requests with byte size 65748 because both user agent and byte size are consistent across the attacks.
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/useragent3.png?raw=true" alt="user agent">
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/byte%20size.png?raw=true" alt="user agent2">
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/ukraine.png?raw=true" alt="user agent2">

