# Status Aggregator

A Google scrip project which collects data from sheet and send it daily. This small script was originally intended to send daily updated of each developer collectivly to specified recepients via email. 

This works on google sheets and sends email on befalf of you google mail account in which you set trigger.


 * Create one sheet in Google sheets
 * Create two tabs with name **Status** 

![status][status]

* Create tab with label  and **info** 

![info][info]

* Go To `Data > Script Editor..`
* Add content from file *process_data.gs*
* Schedule trigger for required methods (see method doc for details) form small clock icon with label *current project's triggers*

 


[status]: https://raw.githubusercontent.com/Nirmal-zymr/status-aggregator/master/doc/status.png
[info]: https://raw.githubusercontent.com/Nirmal-zymr/status-aggregator/master/doc/info.png

I am not script developer, so dont do "code review" for this :), but this does the job pretty well. 
Patches improvements are invited if anyone want to contribute, send me at nirmal@zymr.com