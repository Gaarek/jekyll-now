---
layout: post
title: Snapraid-status-error 2021-01-23 10:34:00
date: 2021-01-23 10:34:00
excerpt_separator: ""
categories: Snapraid-status-error Snapraid
---
```
Self test...
Loading state from /home/public/HDD7/snapraid.content...
Using 394 MiB of memory for the FileSystem.
SnapRAID status report:

   Files Fragmented Excess  Wasted  Used    Free  Use Name
            Files  Fragments  GB      GB      GB
    1652       1       1       -     205     750  21% d1
   22136       1       3       -    1776     162  91% d2
   12717       1       1       -    1825     140  92% d3
    2944      11      22       -    1887     304  86% d4
 --------------------------------------------------------------------------
   39449      14      27     0.0    5695    1358  80%


 10%|                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
    |                                     *   *   *   *   *   *   *   *   *
  5%|                                     *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
    |                                *    *   *   *   *   *   *   *   *   *
  0%|*___________________*___________*____*___*___*___*___*___*___*___*___*
   123                    days ago of the last scrub/sync                 4

The oldest block was scrubbed 123 days ago, the median 32, the newest 4.

No sync is in progress.
The full array was scrubbed at least one time.
You have 34853 files with zero sub-second timestamp.
Run the 'touch' command to set it to a not zero value.
No rehash is in progress or needed.
DANGER! In the array there are 2 errors!

They are from block 4146857 to 5860199, specifically at blocks: 4146857 5860199

To fix them use the command 'snapraid -e fix'.
The errors will disappear from the 'status' at the next 'scrub' command.
```