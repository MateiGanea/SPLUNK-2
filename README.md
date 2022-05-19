# SPLUNK-2
# Windows Server Attack
# all users should have to use MFA.
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/user%20k.png?raw=true" alt="userk">
# for user K limit the amount of password reset requests available and lock them out after too many for an appropiate time period.
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/lockout.png?raw=true" alt="lockout">
# User A should have a much longer lockout time period since it appears it is being flooded with bad login requests in the span of one day a longer lockout timer would prevent this.
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/user%20j.png?raw=truee" alt="user j">
# User J appears to be compromised. They should have their account password manually changed by an admin and the account and user should undergo a security audit.


# APACHE WEBSERVER ATTACKS
# My findings indicate that the attacks originate from ukraine. A firewall blocking access from Ukraine entirely would be effective. Additionally the user agent: Mozilla/4.0 (compatible; MSIE 6.0; Windows NT 5.2; SV1; .NET CLR 2.0.50727987787; InfoPath.1) Can be blocked by the firewall as an additional rule and a third rule can be added filtering requests with byte size 65748 because both user agent and byte size are consistent across the attacks.
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/useragent3.png?raw=true" alt="user agent">
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/byte%20size.png?raw=true" alt="byte">
<img src="https://github.com/MateiGanea/SPLUNK-2/blob/main/screenshots/ukraine.png?raw=true" alt="geolocate">

