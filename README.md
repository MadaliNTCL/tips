Eggdrop

Step 1:
**Package require**

TLS 1.7 - https://packages.debian.org/sid/amd64/tcl-tls/download
sudo apt-get install tcl tcllib tcl-dev openssl libssl-dev build-essential libssl-dev libperl-dev pkg-config dict tdom


**Step 2**:
package require tdom
package require tls
package require dict
package require http

========================================================================================================================

**ZNC**

_Step 1_:
https://wiki.znc.in/Installation#Source_Tarball

_Step 2_:
https://wiki.znc.in/Identfile

_Step 3_: 
open port 113

_Step 3_:
service oidentd restart
