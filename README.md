# Cloudflare-Firewall-Bypass-Prevention
Cloudflare Firewall Bypass Prevention
This code can be used in your htaccess file to block all traffic from the Internet except Cloudflare IP Blocks.
Be sure the check that all of the IP's are in sync with Cloudflare's IP Blocks.
<pre>
# Cloudflare-Firewall-Bypass-Prevention
# by ClusteredNetworks.com 
# Date Cloudflare IP's Checked and Confirmed - Oct 8, 2021
# BEGIN Cloudflare Firewall Bypass Prevention
#Apache 2.4 Server
<FilesMatch ".*">
    Require ip 173.245.48.0/20
    Require ip 103.21.244.0/22
    Require ip 103.22.200.0/22
    Require ip 103.31.4.0/22
    Require ip 141.101.64.0/18
    Require ip 108.162.192.0/18
    Require ip 190.93.240.0/20
    Require ip 188.114.96.0/20
    Require ip 197.234.240.0/22
    Require ip 198.41.128.0/17
    Require ip 162.158.0.0/15
    Require ip 104.16.0.0/12
    Require ip 104.24.0.0/14
    Require ip 172.64.0.0/13
    Require ip 131.0.72.0/22
    Require ip 2400:cb00::/32
    Require ip 2606:4700::/32
    Require ip 2803:f800::/32
    Require ip 2405:b500::/32
    Require ip 2405:8100::/32
    Require ip 2a06:98c0::/29
    Require ip 2c0f:f248::/32
#    Allow from INSERT YOUR IP HERE
</FilesMatch>
# END Cloudflare Firewall Bypass Prevention
</pre>
