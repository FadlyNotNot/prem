# `INSTALL SCRIPT`
<pre><code>apt update && apt upgrade -y && update-grub && sleep 2 && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade && apt install -y bzip2 gzip coreutils screen curl unzip && wget https://raw.githubusercontent.com/FadlyNotNot/prem/main/setup.sh && chmod +x setup.sh && ./setup.sh</code></pre>

## Support OS
### Ubuntu 18.04, Ubuntu 20.04, Ubuntu 22.04
### Debian 9, Debian 10, Debian 11
