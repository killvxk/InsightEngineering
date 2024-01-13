# What is Windows Error Reporting

Windows Error Reporting (WER) is a feature of Microsoft Windows that provides crash reporting solutions. It was introduced with Windows XP and has been included in subsequent versions of Windows. When a program crashes or encounters a critical error, WER collects debug information, which includes information about the state of the program at the time of the crash.

Here is an example of a log entry that records **beacon.exe** experiencing a problem, and Windows Error Reporting created a crash report for it:

![image](https://github.com/DebugPrivilege/InsightEngineering/assets/63166600/655978ce-70a9-4085-bb69-2a084fe639db)

The **attached files** contains a list of files that are prepared to be sent to Microsoft for analysis if consent was given. This includes the following:

- A minidump file **`(WER035.tmp.mdmp)`** which is a snapshot of the application's memory at the time of the crash.
- 