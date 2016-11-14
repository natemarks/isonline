# isonline
python conenctivity checker logs resukts and updates state


Edit yaml config file in some location to list the tcp socket test that should be run

on start:
log dig output
log ifconfig.co  results
run checks on set interval. state  yaml in tmp location has the last result.  logs  have trail of results
if verbose, log all results, otherwise just log failures
on failures, change polling time to the obsess time for that check

Also create python  api to make it easy to access the results and trigger other events
