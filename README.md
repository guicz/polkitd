To solve this error while restarting httpd:

** (pkttyagent:17053): WARNING **: 19:06:57.744: Unable to register authentication agent: GDBus.Error:org.freedesktop.PolicyKit1.Error.Failed: Cannot determine user of subject
Error registering authentication agent: GDBus.Error:org.freedesktop.PolicyKit1.Error.Failed: Cannot determine user of subject (polkit-error-quark, 0)
Redirecting to /bin/systemctl restart httpd.service

Found here: https://forum.centos-webpanel.com/index.php?topic=9168.0

Centos 7.8
CWP stack
