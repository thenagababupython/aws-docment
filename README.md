# aws-docment

ssd - solid state drive
hdd - hard disk drive

volumes :
=================
1.mount the volume 
2.unmount the volume
3.attach volume 
4.detach the volume

volume name --- xvdd volume
format for directory --- sudo mkfs.ext4 /dev/xvdb

	mkdir demo
	sudo cd demo/
	ls -ls
	sudo touch test.txt
	sudo vim test.txt   -- welcome  to volumes
	sudo mount /dev/xvdb demo/
	lsblk
	sudo unmount demo
	lsblk
	
	
	
	
	
	
