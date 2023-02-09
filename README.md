# DiskMaid
a small program to clean up your disk, im not responsible on how you decide to use it, this program was made for educative purposes.

what is it?
- it's just a small tool to overwrite the free space on the hard drive, so it's unreadable and difficult to recover
- it writes a file which size is the free space you have and then deletes it over writing the old spaces that were 
- marked as free, which basically deletes files completely.

how to compile it?
- g++ -o DiskMaid Maid.cpp

dependencies
- objdump
- boost
