---
title: "Error Code"
weight: 8
description: >
  Common error codes for the Poter downloader.
---
# Error Code (EXIT STATUS)

## Packages
This document is referenced from https://aria2.github.io/manual/en/html/aria2c.html#exit-status

Because aria2 can handle multiple downloads at once, it encounters lots of errors in a session. aria2 returns the following exit status based on the last error encountered.


## 0
If all downloads were successful.

## 1
If an unknown error occurred.

## 2
If time out occurred.

## 3
If a resource was not found.

## 4
If aria2 saw the specified number of “resource not found” error. See --max-file-not-foundoption.

## 5
If a download aborted because download speed was too slow. See --lowest-speed-limitoption.

## 6
If network problem occurred.

## 7
If there were unfinished downloads. This error is only reported if all finished downloads were successful and there were unfinished downloads in a queue when aria2 exited by pressing Ctrl-C by an user or sending TERM or INT signal.

## 8
If remote server did not support resume when resume was required to complete download.

## 9
If there was not enough disk space available.

## 10
If piece length was different from one in .aria2 control file. See --allow-piece-length-changeoption.

## 11
If aria2 was downloading same file at that moment.

## 12
If aria2 was downloading same info hash torrent at that moment.

## 13
If file already existed. See --allow-overwrite option.

## 14
If renaming file failed. See --auto-file-renaming option.

## 15
If aria2 could not open existing file.

## 16
If aria2 could not create new file or truncate existing file.

## 17
If file I/O error occurred.

## 18
If aria2 could not create directory.

## 19
If name resolution failed.

## 20
If aria2 could not parse Metalink document.

## 21
If FTP command failed.

## 22
If HTTP response header was bad or unexpected.

## 23
If too many redirects occurred.

## 24
If HTTP authorization failed.

## 25
If aria2 could not parse bencoded file (usually “.torrent” file).

## 26
If “.torrent” file was corrupted or missing information that aria2 needed.

## 27
If Magnet URI was bad.

## 28
If bad/unrecognized option was given or unexpected option argument was given.

## 29
If the remote server was unable to handle the request due to a temporary overloading or maintenance.

## 30
If aria2 could not parse JSON-RPC request.

## 31
Reserved. Not used.

## 32
If checksum validation failed.