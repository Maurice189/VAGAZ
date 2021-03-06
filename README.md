# VAGAZ
Gaze-enabled video analysis and annotation

Currently I do a complete reimplementation, which unfortunately further delays the initial release.
There are multiple reasons for this decision:

* The prototype was not well optimized in terms of runtime. This is not so much a concern when the only interest is to reproduce results from our paper. However, this tool is supposed to be used for "real-world" annotation tasks, so I think we should aim for higher standards. In our new version, all data intensive routines will be completely resigned and implemented in C++. 
* Important functionality, like data important and annotation export, have involved lot of manual steps and the general process was not user friendly. I plan to ease this process such that users can focus more on the important parts of the application (like performing annotations).
* Some functionality, like project organization, has been missing in our first prototype. Our plan is to include more of such convienence features.
* The code quality of our prototype implementation is low. The new code basis will be easier to understand, adapt and extend, which is particulary important for developers that want to implement new features.


Thanks for your patience.
