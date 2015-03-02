# nurse
Website for the nurse recruitment pages


## How to get the NHS Jobs list

You have to use the base URL of http://www.jobs.nhs.uk/extsearch? and build in the query string you need to reply.

Here are the things

* client_id= ```this restricts to a specific Trust etc... The agency id in normal NHS Jobs parlance```
* resonly=1 ```This removes the NHS Jobs header and footer```
* keyword= ```anything you want to search```

etc. etc.

To get only Nurse jobs from NHS Jobs, restricted to STH, you search:

http://www.jobs.nhs.uk/extsearch?client_id=121486&resonly=1&keyword=nurse

## Other available key-value pairs:

* page= ```integer```
* max_result=
* max_salary=
* navigator_fields= ```whole heap of yes or nos by indicating the name... ```

large example:
```
http://www.jobs.nhs.uk/xi/search_vacancy?page=1&max_result=100&keyword=nurse&client_id=121486&max_salary=ANY&navigator_fields=jobtype&navigator_fields=salary_match_type&navigator_fields=pay_band&navigator_fields=staff_group_code&navigator_fields=vac_restricted&navigator_fields=restricted_group&navigator_fields=suitable_for_newly_qualified&navigator_fields=pay_scheme_cd&action=search&resonly=1
```
