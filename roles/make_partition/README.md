Make Partition
=========

Allows the user to create a new partition and have it mounted featuring:
- prompts the user what disk they want to partition.
- prompts the user for disk label type if not present.
- prompts the user for what size the partition needs to be
- prompts the user what filesystem needs to be used if no other partitions are present.

If there are already partitions present on the disk the filesystem of the last partition will be used.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: make_partition

License
-------

BSD
