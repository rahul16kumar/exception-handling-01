**Exception-Handling-01**
<br>
**This repo talks about how to handle exceptions using custom policy. In this policy we are generating error in custom policy as well as in Application.**
<br>
**Error will occur in custom policy in http-policy:source block before http-policy:execute-next block, so nothing from application will be printed**
<br>
**So, overall flow execution will be like. 1. Logger from custom policy, 2. Then, it will move into on error continue block of custom policy and whatever processes have been there will be printed. 3. Nothing from application will be traversed.**