This is Bazel 0.19.2 built on Alpine Linux installed on a Raspberry Pi 2B+
It is a painful experience building this binary file. Successfully buit time took 32 hours. 
I struggled from missing dependencies, missing requires libralies etc then finally the real build began.
Unfortunately, it terminated after 25 hours with message unable to find /usr/bin/python.
I only have python3 installed so create a symbolic link to python3 may work and that my solution.
Again, with bad luck it terminates again after around 31 hours later with message permission denied make dir bazel/output
my solution to this is sudo -i as root then start compile.sh instead sudo ./compile.sh 
This time I got working bazel 0.19.2 after 32 hours.
