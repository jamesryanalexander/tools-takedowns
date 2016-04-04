# tools-takedowns
LCATools submodule for DMCA and other copyright takedowns (logging/reporting/deleting)

### Files
* legalTakedown.php - Form to fill out for DMCA take downs sent to the Wikimedia Foundation.  
* legalTakedownProcessor.php - File to process input from legalTakedown.php
** Takes data/logs/sends to Chilling Effects on demand
** Processes and format templates to post on wiki and allows them to be posted via MW OAuth if available
* CEOnlyTakedown.php - Form to fill out for DMCA takedowns which will send to ChillingEffects and update internal log entries without creating templates to post on wiki.
** Used to update old takedowns that were unable to be sent to Chilling Effects at the time but already processed on wiki.
* CEonlyTakedownProcessor.php - File to process input from CEOnlyTakedown.php including updating log entries and sending to Chilling Effects.
