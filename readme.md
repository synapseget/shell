pgm_1
find the range of process id using cat /proc/sys/kernel/pid_max and min=1(not included in program)
read  the pid 
compared for the validity
if valid, checked for its running state else print that the given pid is invalid
if running kill dat process using kill $pid
each time the required message is printed using echo


pgm_2
placed some .log ang .txt files in a directory
using find placed .log in a new file
using find added the .txt in the new file 
created the tar.gz file which comprises  all of the text and log files
