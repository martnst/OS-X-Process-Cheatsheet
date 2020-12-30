# OS X Process-Cheatsheet

An overview of process running on Mac OS X. 

|Process Name| Description | Ref |
|------------|-------------|-----|
| backboardd | BackBoard is responsible for forwarding the following hardware events to processes in iOS Simulator | [click](https://www.reddit.com/r/jailbreak/comments/3cp0rm/question_what_is_backboardd_and_why_is_it/) |
| bird | The `bird` process is indeed the back end process behind iCloud drive. | [click](https://discussions.apple.com/thread/6606275?tstart=0)|
| mdworker | Spotlight indexer process | [click](http://osxdaily.com/2009/09/14/mdworker-what-is-mdworker/) |
| spindump | `spindump` is used by various system components to create reports when an unresponsive application is force quit. | [click](https://developer.apple.com/legacy/library/documentation/Darwin/Reference/ManPages/man8/spindump.8.html)
| sysmond | System Monitor Daemon - monitors all system activity in background and automated by `launchd` (launcher daemon) | [click](https://discussions.apple.com/thread/250180809) |