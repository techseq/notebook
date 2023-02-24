$ wc -l test_command.gtf  
$ wc -c test_command.gtf  
$ grep 'chr_' test_command.gtf|grep -w 'YDL248W'  
$ sed 's/chr_/chromosome_/g' test_command.gtf > new.gtf  
$ cut -f 1,3,4,5 new.gtf  
$ awk '{tmp=$2;$2=$3;$3=tmp;print}' test_command.gtf| sort -k 4,5 > result.gtf  
$ chmod -R 774 ~/share  
$ ls -hl
