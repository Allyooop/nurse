# nurse
Website for the nurse recruitment pages


## How to get the NHS Jobs list

You have to use the base URL of http://www.jobs.nhs.uk/extsearch? and build in the query string you need to reply.

Here are the things

client_id= ```this restricts to a specific Trust etc... The agency id in normal NHS Jobs parlance```
resonly=1 ```This removes the NHS Jobs header and footer```
keyword= ```anything you want to search```

etc. etc.

To get only Nurse jobs from NHS Jobs, restricted to STH, you search:

http://www.jobs.nhs.uk/extsearch?client_id=121486&resonly=1&keyword=nurse
