# Practical Investigation of historical Signal Server Recipes

These are recipes, scripts and configuration files for various versions of
Signal Server, formerly called TextSecure. Signal Server is a centralised
service with a number of cluster nodes, and the implementation architecture has
changed significantly since 2016, when the TextSecure Server was replaced by 
the first SignalServer code.

All recipes for Signal Server versions later than 5.1 have been attempted and compared.

TextSecure Server up to 2.3 Dec 2016  
Main: Luca Conte   https://github.com/lucaconte/BeatTheMeddler
Laurence Ion https://www.linkedin.com/in/laurion/

TextSecure Server up to 2.55 recipe as of Jul 2019 
Main: Denny Aprilio P  probably https://github.com/ngodn
https://community.signalusers.org/t/guide-deploy-signal-server-v2-xx-cds-sgx/8331
This is not usable by any version of Android Signal client published later than 2016

Signal Server Version 1.88, recipe as of 2019
Main:  Mohammed Aqnouch  https://aqnouch.com
https://gist.github.com/aqnouch/9a371af0614f4fe706a951c2b97651e7 

Signal Server Version 1.88, recipe as of 2019
Main: Julian Paolo Dayag https://wisdomsky.github.io
https://gist.github.com/WisdomSky/fd348eb012b8f37f6b9b7dbb69eed6e1

Signal Server Version 3.2.1, recipe as of March 2021
Main:  Mohammed Aqnouch  https://aqnouch.com
https://github.com/aqnouch/Signal-Setup-Guide 

Signal Server Versions 3.2.x --> 5.5.1, recipe as of June 2021
Main: Made Indra Wira Pramana  https://madecanggih.dev/
https://github.com/madeindra/signal-setup-guide 

Signal Server Versions 3.2.x --> 5.5.1, fork of Pramana above
Main: Alberto Margarido
https://github.com/amargarido/Setup-Guide


Mahar Prasetio https://github.com/sinholic

https://github.com/on-premise-signal/signal-setup-guide  Discontined. Apr 2019

https://github.com/secure-sign/securesign-setup-guide 2020 Continuation of the foregoing

https://community.signalusers.org/t/guide-deploy-signal-server-v2-xx-cds-sgx/8331  Inspired the foregoing two

#Non-recipes but relevant to Signal Server

https://www.androidcentral.com/apps-software/how-to-set-up-and-run-a-proxy-signal-server  COmments on installing official *proxy*

git clone https://github.com/signalapp/Signal-TLS-Proxy.git Official Signal proxy - hidden inside docker

https://softwaremill.com/what-ive-learned-from-signal-server-source-code/ Polish Review

https://debabhishek.com/writes/Installing-and-Running-TextSecure-Signal-Server-on-Windows 2017 Old but relevant

https://engineering.mindlinksoft.com/end-to-end-encryption-with-the-signal-protocol/  Discussion

https://gitlab.com/dvandam_thesis
https://gitlab.com/dvandam_thesis/signal-server forked "1.88" version in order to do thesis

https://github.com/dessalines/Messaging-Services-Comparison  Neither on-prem nor private. We try to fix both.

https://github.com/madeindra/signal-setup-guide/tree/master/signal-android  This is for conmpiling the app for a private server

https://medium.com/zengo/mpc-over-signal-977db599de66  as a demo of Secure Multiparty Computing

October 2022 https://github.com/signalapp/Mock-Signal-Server
