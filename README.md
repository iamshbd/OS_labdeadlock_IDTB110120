# OS_labdeadlock_IDTB110120
Level1
Both virtual drives are successfully mounted as loopback devices. /dev/loop52 represents vault_alpha and /dev/loop56 represents vault_beta. Each has 5.4MB total capacity with 4.7MB available because the ext4 filesystem was formatted correctly and the drives are live and accessible by the OS.ext4 uses some space for its own internal structures like the journal, inode tables, and superblocks which is completely normal.
