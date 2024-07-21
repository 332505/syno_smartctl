Some version of Synology DSM would get wrong SMART info while using HBA card, and this script can fix it. (Not for showing the SMART info on DSM7.2.1 or later)

Useage:
1. Replace the black list in this smartctl for the disks not on your HBA card.
2. Rename the smartctl in `/bin` to smartctl-binary.

   `mv /bin/smartctl /bin/smartctl-binary`
3. Copy this smartctl to `/bin`
4. `chmod +x /bin/smartctl`

Principle: https://github.com/RedPill-TTG/redpill-lkm/issues/14#issuecomment-1193940581

