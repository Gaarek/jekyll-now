---
layout: post
title: Snapraid-status-error 2019-04-28 10:33:54
date: 2019-04-28 10:33:54
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 401 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       0       0       -     205     781  20% d1
   22130       1       3       -    1770     168  91% d2
   12706       0       0       -    1825     141  92% d3
    3098      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39586      14      22     0.0    5811    1272  82%


 10%|              o      *      o      *      o     *      *      *      *
    |              *      *      *      *      *     *      *      *      *
    |       o      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
  5%|       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
    |       *      *      *      *      *      *     *      *      *      *
  0%|*______*__oo_o*__oo_o*__o___*___o__*o_oo__*__oo_*______*______*______*
    75                    days ago of the last scrub/sync                 5

The oldest block was scrubbed 75 days ago, the median 33, the newest 5.

No sync is in progress.
The 3% of the array is not scrubbed.
You have 34836 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 1 errors!

They are from block 6310038 to 6310038, specifically at blocks: 6310038

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
