---
layout: post
title: Snapraid-status-error 2019-09-26 10:33:58
date: 2019-09-26 10:33:58
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
    1652       1       1       -     205     769  21% d1
   22136       1       3       -    1776     161  91% d2
   12706       0       0       -    1825     141  92% d3
    3097      13      19       -    2010     181  91% d4
 --------------------------------------------------------------------------
   39591      15      23     0.0    5818    1254  82%


 10%|                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
  5%|                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
  0%|*_______________*___*_______*___*____*__**___*___*___*___*___*___*___*
   121                    days ago of the last scrub/sync                 2

The oldest block was scrubbed 121 days ago, the median 37, the newest 2.

No sync is in progress.
The full array was scrubbed at least one time.
You have 34842 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 4 errors!

They are from block 790893 to 7465210, specifically at blocks: 790893 3685872 5650960 7465210

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```
