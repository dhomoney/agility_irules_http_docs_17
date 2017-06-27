#####################################################
Lab 5 – HTTP Payload Manipulation
#####################################################

#. Open Chrome Browser
#. Enter https://bigip1 into the address bar and hit Enter
#. Login with username: admin password: admin
#. Click Local Traffic -> iRules  -> iRules List
#. Click Create button
#. Enter Name of HTTP_Payload_iRule
#. Enter Your Code
#. Click Finished
#. Click Local Traffic -> Virtual Servers -> Virtual Server List
#. Click on https_irules_vip
#. Click on the Resources tab
#. Click Manage button for the iRules section

   .. figure:: ./images/iRulesManage.png
      :width: 800

   |

#. What should you do here? (Hint: Remove Stream_iRule)
#. Click the Finished button
#. Open the Firefox browser
#. Enter https://dvwa.f5lab.com  and ensure you get there and it is HTTPS
