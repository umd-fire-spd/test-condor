quick test for condor

make sure the test.sh is executable. try it on the command line first to see if it runs (./test.sh)

also create the logs directory before submitting

submit with condor_submit umd_sample_gen.jdl

check with condor_q

kill with condor_rm job-id

if job held (or idle while there are many nodes sitting around doing nothing), just kill, check for errors/missing steps, resubmit
