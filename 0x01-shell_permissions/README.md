Shell Basics
Description of all commands

0) - #!/bin/bash
   - su betty
This switches the current user to betty

1) - #!/bin/bash
   - whoami
This scripts prints the username of the current user

2) - #!/bin/bash
   - groups
This prints the group belonged to by the current user

3) - #!/bin/bash
   - sudo chown betty hello
This assigns the owner of the file as betty

4) - #!/bin/bash
   - touch hello
This script creates a new file known as 'hello' which is empty

5) - #!/bin/bash
   - chmod u+x hello
This scripts assigns execution rights to the current 'owner'

6) - #!/bin/bash
   - chmod u+x,g+x,o+r hello
This script assigns execution rights to the owner, group and other users of the file hello


7) - #!/bin/bash
   - chmod ugo+x hello
This assigns execution permissions to the owner, group and other users of the file hello


8) - #!/bin/bash
   - chmod 007 hello
This assigns full permission to only the other users of the file hello


9) - #!/bin/bash
   - chmod 753 hello
This assigns full permissions to the owner, read and execute to groups and write and execute to other users all for the file hello


10) - #!/bin/bash
    - chmod --reference=olleh hello
This script copies the permissions set for hello to be also applicable to the file olleh


11) - #!/bin/bash
    - chmod -R ugo+X
This script assigns execution permission to all subdirectories of the current directories for the owner,groups and other users.


12) - #!/bin/bash
    - mkdir -m 751 my_dir
This script creates a directory with full permissions for owner, read&write for groups and read for other users


13) - #!/bin/bash
    - chgrp school hello
This script creates group owner for file hello to school



14) - #!/bin/bash
    - chown -hR vincent:staff .
This script at once changes owner and group to vincent and staff for all files and directory in the current working directory


15) - #!/bin/bash
    - chown -h vincent:staff _hello
This script at once changes owner and group to vincent and staff for the single file _hello


16) - #!/bin/bash
    - chown --from=guillaume betty hello
This script assigns the ownership of the file hello to betty only if the hello file is owned by guillaume


17) - #!/bin/bash
    - telnet towel.blinkenlights.nl

This script is plays the starwars 4th episode in the terminal



