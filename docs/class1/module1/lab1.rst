#####################################################
Lab 1 - Create iRule that Parses URI to Route Traffic
#####################################################

#. Open Chrome Browser
#. Enter https://bigip1 into the address bar and hit Enter
#. Login with username: admin password: admin
#. Click Local Traffic -> iRules  -> iRules List
#. Click Create button
#. Enter Name of URI_Routing_iRule
#. Enter your code
#. Click Finished
#. Click Local Traffic -> Virtual Servers -> Virtual Server List
#. Click on http_irules_vip
#. Click on the Resources tab
#. Click Manage button for the iRules section

   .. figure:: ./images/iRulesManage.png
      :width: 1200

   |

#.	Click on URI_Routing_iRule from the Available box and click the << button, thus moving it to the Enabled box.
#.	Click the Finished button
#.	Open a new tab in Chrome
#.	Enter http://dvwa.f5lab.com/ and ensure you get there
#.	Now enter http://peruggia.f5lab.com/ and ensure you get to the app
#. Finally, enter http://wackopicko.f5lab.com/  and ensure you can get to that app
