# pintos-threads
Extend pintos timer functionality to not use busy wait.

I used the docker image thierrysans/pintos for testing and used
pintos --qemu -- -q run [test-name]
for all the alarm tests and passed them.  My make grade may or 
may not work. I tried to ask a TA in OH but he said he didn't
know if they use qemu or bochs and bochs has caused a lot of 
errors earlier so I went with qemu but the make grade script
seems to rely on bochs. 
