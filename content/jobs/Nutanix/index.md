---
date: "2025-06-02"
title: "Member of Technical Staff 2"
company: "Nutanix"
location: "San Jose, CA"
range: "June 2025 - Present"
url: "https://www.nutanix.com/"
---

- Redesigned CVM boot disk partition layout to isolate ZooKeeper logs through automation of mount/fstab, LUKS and mdadm RAID setup, while retaining backward-compatibility and reducing crash-loop oncalls down to a third of previous count.
- Introduced API for validating fault tolerance and migration capacity for disk removal flows, then onboarded the disk service to containerized pTest VMs emulating loop devices and udev events, cutting QA time by >1 day per diff
- Developed mechanism to selectively prune kernel errors from node local protos and persist error information as metadata, to prevent hitting 1MB znode limit
