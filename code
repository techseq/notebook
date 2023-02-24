test@bioinfo_docker:~/share$ wc -l test_command.gtf
test@bioinfo_docker:~/share$ wc -c test_command.gtf
test@bioinfo_docker:~/share$ grep 'chr_' test_command.gtf|grep -w 'YDL248W'
test@bioinfo_docker:~/share$ sed 's/chr_/chromosome_/g' test_command.gtf > new.gtf
test@bioinfo_docker:~/share$ cut -f 1,3,4,5 new.gtf
test@bioinfo_docker:~/share$ awk '{tmp=$2;$2=$3;$3=tmp;print}' test_command.gtf| sort -k 4,5 > result.gtf
test@bioinfo_docker:~/share$ ls -hl
test@bioinfo_docker:~/share$ chmod -R 774 ~/share
test@bioinfo_docker:~/share$ ls -hl
