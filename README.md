The purpose of this tool is to give you an easy front end GUI to review your user's call forwarding settings. Information such as Call Via Work settings, who's a delegate of who, who's got simultaneous ring set, etc. can be difficult to retrieve without a utility such as sefautil, which itself can be difficult. This tool allows you to review this information for all users in a pool in a GUI format that's easily searchable, sortable, and filterable (Out-Gridview). It also allows you to save the information to a CSV file. The information is gaterhed by parsing data pulled using Export-CSUserData. No SQL calls are made and no data is written back into Skype.

Because this tool uses Export-CSUserData, please be patient during the loading process. If you have difficulty using this utility, first ensure you can run Export-CSUserData successfully. If there is any corrupted user information in a pool, this can cause issues and that corruption will need to be resolved first.

If you would like to see the information in a different format, say an PowerShell command such as Get-CSUserForwardingInfo that can run for a single user or pool for speed, let me know as well. If there's interest I can write it.  Interestingly, if you are in a Skype for Business/Lync 2013 mixed environment, Call Via Work settings may still be populated in Lync pools.

Please let me know if you have any comments, questions, or find any bugs to fix.  Thank you!

![Image](https://github.com/ccaragol/skype-for-business-call-forwarding-information-tool/blob/master/SkypeForwardingInfo.png)
