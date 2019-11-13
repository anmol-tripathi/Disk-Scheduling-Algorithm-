# Disk Scheduling Algorithms in Python
Implemented various Disk Scheduling Algorithms in Python
<br>
<br><b> Following Disk Scheduling Algorithms are demonstrated:<br></b>
    1. FCFS<br>
    2. SSTF<br>
    3. SCAN<br>
    4. CSCAN<br>
    5. LOOK<br>
    6. CLOOK<br>
<br>
The process needs either CPU time or Input/Output Time. And for I/O it requires access to disk. The technique that operating system uses to determine the request which is to be satisfied next is called disk scheduling.<br>
<br>
<img src="image.png">
<font size = 1>
<br>Image Source:<br>
https://notesformsc.org/computer-science/operating-systems/operating-systems-disk-scheduling-algorithms/<br> </font>

<br>
 
Seek Time<br>
Seek time is the time taken in locating the disk arm to a specified track where the read/write request will be satisfied.
<br><br>
Rotational Latency<br>
It is the time taken by the desired sector to rotate itself to the position from where it can access the R/W heads.
<br><br>
Transfer Time<br>
It is the time taken to transfer the data.
<br><br>
Disk Access Time<br>
Disk access time is given as,
<br><br>
Disk Access Time = Rotational Latency + Seek Time + Transfer Time
<br><br>
Disk Response Time<br>
It is the average of time spent by each request waiting for the IO operation.
