#####################################################
Lab 4 – Stream Profile
#####################################################

#. Open Chrome Browser
#. Enter https://bigip1 into the address bar and hit Enter
#. Login with username: admin password: admin
#. Click Local Traffic -> iRules  -> iRules List
#. Click Create button
#. Enter Name of Stream_iRule
#. Enter Your Code
#. Click Finished
#. Click Local Traffic -> Virtual Servers -> Virtual Server List
#. Click on https_irules_vip
#. In the Configuration section ensure it says Advanced in the drop down
#. Go to the Stream Profile section and select stream
#. Scroll to the bottom and click the Update button
#. Click on the Resources tab
#. Click Manage button for the iRules section


   .. figure:: ./images/iRulesManage.png
      :width: 800

   |

#. What should you do here?
#. Click the Finished button
#. Open the Firefox browser
#. Enter https://dvwa.f5lab.com  and ensure you get there and it is HTTPS and that the word “Damn” is replaced with “Darn”
