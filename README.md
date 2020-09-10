# Setup

    apt-get install sendmail libcurl4-openssl-dev
    
    service sendmail start

    gcc -o email_spoof spoof.c -lcurl

    ./spoof [RECIPIENT EMAIL]

**#Example**

`./spoof example@gmail.com`
