
# show results

// needs to statically serve files from results and also provide api's that query the file system for test results
// to develop the front end we need these apis, so we run this via proxy.

This should allow results to be collected incrementally and from multiple servers.
Rsync or sftp can be used to update the folders, then republish web api can be called as update.
Maybe there should be an incoming directory and possibly a WIP directory for tests that are still running.
Maybe should use sqlite instead of continually rewriting the entire directory.
Can c# portably use sqlite? on m1?

Maybe the test directory should be a command line option.

