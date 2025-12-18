# Bug-reporting-workflow


# 1. Problem Statement
Bugs were being manually report by QA and tester team, delayed, and sometimes lost. The product management team manually use the reported bug to create a tasks and assigning the task to respective tracks such as backend developer, fronetend developer or design team. Manual movement of task status across the workpsace


# 2. Objective
Automatically route bug report through slack channel or form to clickUp workspace where teams are notified, assigned the track or team responsible for the solution and log activity in real time.


# 3. Tools Used
No-code tools are first-class citizens here.

. Make.com 
. Airtable
. Jotform ( if necessary)
. Gmail / Slack / Webhooks
. ClickUp 


# 4. System Architecture (Critical)

  1. Trigger: Watch slack channel for new report input
  2. Validation: Fetch the necessary details needed from the input (image, bug report title, bug report full description, time submitted)
  3. Decision: Create a bug template and set it as default bug template for every but report created automatically in clickUp workspace
  4. Action:  Apply the template to the created bug report, assign it to necessary track FE, BE, Design Team etc
  5. Logging: Assign different PM as the bug report status changes

# 5. Outcome / Impact

  1. Reduced manual input/ work
  2. Eliminated human error
  3. No loss track of bug reported
  4. Teams awareness fro every bug reported
