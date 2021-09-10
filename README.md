# Test cmake FetchContent
For the main project I need dependent projects like [Posix Threads for Linux](https://github.com/jwinarske/pthreads4w) that I want to install with **FetchContent** to the main project. But it ignores the given parameter as docuumented. This very simple cmake test program just shows its given parameter to verify the issue with setting FetchContent options.
