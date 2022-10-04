---
layout: home

---
<div class="wrapper" markdown="0"><div class="footer-col-wrapper">
<div class="footer-col two-col-1">
    <ul class="contact-list">
        <li><b><a href="https://faculty.cs.gwu.edu/timwood">Prof. Tim Wood</a></b></li>
        <li><a href="mailto:timwood@gwu.edu">timwood@gwu.edu</a></li>
        <li>Office Hours: Posted on Discord/Google</li>
        <li>Class: Tuesday/Thursday 12:45-2PM in Gelman B04</li>
    </ul>
</div>
<div class="footer-col two-col-2">
    <ul class="contact-list">
        <li>TA: Yuan Gao</li>
        <li>UTAs/LA: Alex Coleman, Aisha Mohammed, Austin Theriault </li>
    </ul>
    </div>
</div></div>


> This course covers the fundamental concepts of operating systems, focusing on resource management and abstraction. This includes OS structure, processes and thread management, communication with peripherals (I/O), synchronization, deadlocks, memory management, Virtual Machines, cloud infrastructures, and abstractions for cloud computation. The workload for this class is heavy and programming intensive. And fun!


## Announcements ##
- All content for this course can be found in the class's shared google drive.


Your Immediate TODO
-------------------

1.  Accept the invitation to the class' google drive. Find the
    `class-information` document which starts with a number of links
    that you can use to proceed through this list.
2.  Complete the "getting to know you" survey *now*. We cannot grade
    your work without this information.
3.  Find the Discord invite to our server, and join.
4.  Find a link to the first homework (`HW0`) via github classroom.
5.  Please read about installing the class' infrastructure: Ubuntu 20
    LTS (see the [class
    resources](https://github.com/gwu-cs-os/resources) for guidance) and
    `#tech-support` on discord if you have any issues.


## Schedule  ##

<div style="font-size:90%">

| Lecture | Notes | Video/topic (Thanks [Gabe](https://www2.seas.gwu.edu/~gparmer/)!)  |
| --- | --- | --- |
| 8/30 |  | Intro to OS. Setup class accounts |
| 9/1 |  | [Execution stack, system calls, exceptions](https://www.youtube.com/watch?v=GoPTe_eIQwI&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/6 |  | [Input/output and device interactions](https://www.youtube.com/watch?v=a3EpamJ1sNY&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/8 |  | [System structure: isolation & comms](https://www.youtube.com/watch?v=fgrV-mu6JQw&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/13 |  | [Processes (Up to minute 47)](https://www.youtube.com/watch?v=iDJ4RuaJEOQ&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/15 |  | [xv6 switch (after minute 47)](https://www.youtube.com/watch?v=iDJ4RuaJEOQ&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/20 |  | [Process API](https://www.youtube.com/watch?v=-U7gmPsJ3Lo&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/22 |  | [Inter-Process Communication (IPC)](https://www.youtube.com/watch?v=BtQ2jSzGPEU&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/27 |  | [Threading](https://www.youtube.com/watch?v=6zVpznaYclY&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 9/29 |  | [Synchronization: Critical Sections](https://www.youtube.com/watch?v=_ARTXwgjFHo&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 10/4 |  | [Synchronization: Atomic Instructions](https://www.youtube.com/watch?v=_iR8n1tgf2A&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 10/6 |  | [Synchronization Abstractions](https://www.youtube.com/watch?v=rPmm5BPN83Y&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 10/11 |  | [Synchronization Examples](https://www.youtube.com/watch?v=A3lTPUT7lPg&list=PLVW70f0xtTUxHXRtZhGEJAiBDFx-ofc_G) |
| 10/13 |  | [Deadlock](https://www.youtube.com/watch?v=gRQH3zWQBuU) |
| 10/18 | Midterm |  |
| 10/20 |  | [Scheduling Goals and Algorithms](https://www.youtube.com/watch?v=wWhQ3jNPYq8) (first 61 minutes) |
| 10/25 | No class. | Fall break  |
| 10/27 |  | [Multi-core Scheduling](https://youtu.be/wWhQ3jNPYq8?t=3660) and [Linux CFS](https://www.youtube.com/watch?v=KRjBX_lBFYM) (first 23 minutes) |
| 11/1 |  | [Real-time scheduling](https://youtu.be/KRjBX_lBFYM?t=1394) |
| 11/3 |  | [User-level memory management](https://www.youtube.com/watch?v=5zvu7vyypt0) |
| 11/8 |  | [Slab & Buddy allocators](https://www.youtube.com/watch?v=DRAHRJEAEso) |
| 11/10 |  | [Memory Protection](https://www.youtube.com/watch?v=mffHC2FsaIU) |
| 11/15 |  | [Page-Tables](https://www.youtube.com/watch?v=9FC64Lsz6aM) |
| 11/17 |  | [FS API](https://www.youtube.com/watch?v=SQBpk-EicLE) |
| 11/22 |  | [FS Indexing](https://www.youtube.com/watch?v=qWKs1o1ozyU) |
| 11/24 | No class.  | Thanksgiving break. |
| 11/29 |  | Catch up time |
| 12/1 |  | [FS Implementation](https://www.youtube.com/watch?v=_3ISGcSlK4Q) |
| 12/6 |  | [FS Crash Consistency](https://www.youtube.com/watch?v=s_Q3CXhYiIk) |
| 12/8 |  | [Security](https://www.youtube.com/watch?v=IAnggHc0_aA) |

</div> 

## Assignemnts
Full info on all assignments is available to students in the class drive. **These dates may be incorrect -- see the class information file for the latest information!**
 - HW 0: Academic Integrity - due Sunday September 4, 2022
 - HW 1: C Data Structures - due Monday September 19, 2022
   - Resubmit by Friday September 30, 2022
 - HW 2: xv6 Process Status - due Monday October 10, 2022 
   - Note: You may work individually or with one other student. After you set a team using the  - form you may not change!
   - Submit by Friday 11:59PM to get +5pt bonus
 - HW 3: xv6 Threading - due 10/30
   - Submit 72 hours early to get +5pt bonus
 - HW 4: xv6 Locks - due 11/11
   - Submit 72 hours early to get +5pt bonus
 - HW 5: xv6 Memory Management - due 12/4
   - Note: This is an individual assignment!
   - Submit 72 hours early to get +5pt bonus
 - Project: xv6 Containers - due finals week
   - Create 3 person teams - 11/6
   - Progress Check In - 12/1
   - Code Deadline - 12/14
   - Demos - 12/15-12/16
