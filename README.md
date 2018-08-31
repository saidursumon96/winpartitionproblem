# winpartitionproblem
Problem : We couldn't create a new partition or locate an existing one. For more information, see the Setup log files.

1. Press shift + F10 to open cmd
2. write "diskpart" and hit enter
3. then type "lisk disk" for hdd disk status
4. type "select disk x" ("x" is your hdd disk number)
5. type the following command and press enter :
  * clean (clean your hdd)
  * create partition primary size=98000 (you can set your own partition size)
  * format fs=ntfs (format as ntfs file system)
  * assign (assign drive letter)
  * active (active your primary partition)
  * list volume (check volume list)
  * exit (exit from diskpart)
  * cd d: (change directory to your bootable usb or cd ex: d:)
  * xcopy d: c:/e/h/k (copy setup files from bootable usb or cd to your c drive)
  * after copied all files close windows setup and restart your pc
  * then your problem is solve.
