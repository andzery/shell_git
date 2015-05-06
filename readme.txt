1.According to the .sh file, save them to the right position.
2.chmod +x delete restoreTrash logTrashDir cleanTrashCan
3.to the cleanTrashCan, use the 'crontab -e' command to set its execution.
 (by add '10 18 * * * /bin/cleanTrashCan')

4. New Functions(not accomplished by the references files)
  (1)we can delete multiple files at the same time,e.g. delete file1 file2
  (2)we can also restore multiple files to the trash by using restoreTrash file1      file2 ...

references:
1.http://blog.razrlele.com/archives/776
2.http://www.ibm.com/developerworks/cn/linux/1410_licy_linuxtrash/#toggle
