Side Projects
===============

List
----
1. Jetson_Monitoring

Jetson_Monitoring
-------------------
This will be a mid-layer between server - client, for broadcasting CPU/GPU usage information, including thermal information.<br>
For now, this project uses cat-ting sysfs via root and broadcast to STDOUT. But I am thinking new way to broadcast HW Information, via init(on-boot) script. By changing permission of each sysfs corresponding to HW Information, we do not need to gain su/root permission on this binary, and it will be more efficient.