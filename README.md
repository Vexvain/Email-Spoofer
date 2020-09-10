# Setup

    apt-get install sendmail libcurl4-openssl-dev
    
    service sendmail start

    gcc -o email_spoof email_spoof.c -lcurl

    ./email_spoof [RECIPIENT EMAIL]

**#Example**

`./email_spoof example@gmail.com`
