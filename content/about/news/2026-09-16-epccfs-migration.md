---
layout: 'news'
title: Cirrus Migration to EPCCFS storage
date: 2026-09-14T09:00:00
---

The current `/work` storage is coming to its end of life so on Wed 16 Sep 2026 weare moving to new storage mounted on Cirrus login and compute nodes as `/epccfs`.

There will be a full maintenance session (starting at 09:00 BST on Wed 16 Sep 2026) with no jobs running on compute nodes for this switch. During this maintenance session, the following high level steps will be followed:

- All jobs Pending in the queue will be deleted
- This step is necessary as jobs in the Pending queue before the switch will expect to be able to write to `/work`. As this will not be possible after the switch, any pending jobs would fail.
- Current `/work` storage will be changed to read-only mode
- `/epccfs` storage will be made available in read/write-mode
- Final testing of `/epccfs`
- Service returned to users

The current `/work` storage will remain available in read-only mode until at least 21 Nov 2026 for users to copy over any data they wish to access/keep on the new `/epccfs` storage.

Full details in the [Cirrus Documentation](https://docs.cirrus.ac.uk/epccfs-migration-2026/)