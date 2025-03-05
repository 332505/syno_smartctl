Some version of Synology DSM would get wrong SMART info while using HBA card, and this script can fix it. (Not for showing the SMART info on DSM7.2.1 or later)

Useage:
1. Rename the smartctl in `/bin` to smartctl-binary.

   `mv /bin/smartctl /bin/smartctl-binary`
2. Copy this smartctl to `/bin`
3. `chmod +x /bin/smartctl`

Principle: https://github.com/RedPill-TTG/redpill-lkm/issues/14#issuecomment-1193940581

