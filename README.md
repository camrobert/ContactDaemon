# ContactDaemon
A series of suppression and selection methods to assist in subscriber email frequency capping
3 Solutions are identified with various practical applications:

# 1: At Send Frequency Suppression Script
This is a foolproof way to ensure no subscriber ever receives more than the allotted number of emails per day.
It requires some light DE and AMPScript development, however it scales well without performance degradation and allows for ad-hoc workarounds.


# 2: Daily Send Frequency Suppression DE Automation
An easy solution that is more practical for businesses with staggered journey sends throughout the day. Less development then Solution 1 and much less processing overhead; however it does have run time limits that can allow subscribers to receive “too many” emails if multiple campaigns are sent at the same time.


# 3: Daily Send Frequency Selection Rule
The simplest way to solve frequency filtering, however, is dependant on a send process that involves selecting new data for every send. Not a viable solutions for highly automated businesses, however it is very quick and easy to implement.
