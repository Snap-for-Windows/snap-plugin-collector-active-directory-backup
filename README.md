# snap-plugin-collector-active-directory

What needs to be done:
1. Install AD and (1. Figure out what data we can get from AD with powershell - we may be using Get-Counter perfmon-type commands to get AD data) use powershell commands and actually get data from AD. 
1b. Add another user for testing
2. Get the AD with Go file
3. Copy perfmon files and modify to fit with AD
4. Run unit tests on code
5. Try to run with Snap itself with task and get data 
5b. Throw in concurrency if not done already
6. Make sure README is done and code is commented
7. Update glide file 
7. Make a pull request to intelsdi org and have Taylor and Joel code review 