# circleci-windows-install-javaruntime-by-choco

This is an example project for testing the issue which choco randomly fail to download JRE
The cause is that sdlc-esd.oracle.com includes bad host. If builds are routed to use the bad ip, the download speed will be extremely slow.
