# Known Issues

## Age

All responses are self-reported meaning the survey respondent (4th grade through 12th grade students in the US) is the one recording the response.  This can lead to strange responses.

We know that some ages were reported with negative values, zero and also values such as 666 or 99999.

A more difficult and subtle issue is one where the respondent is NEAR the modal age for that grade in school, so for example a typical 6th grade student in the United States is 11 or 12 years old.  BUT a 6th grade student could be older or younger as a result of decisions related to their school performance or other issues.

The original decision back in 2015 involved "flagging" unusual responses by creating a separate variable.  This separate variable takes values such as (you are not required to follow this rule, but some type of identification of usual responses must be present in your submission)

0 = no problem/not altered
1 = an obvious problem (e.g., negative age)
2 = not an obvious problem

