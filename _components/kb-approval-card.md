---
title:  "KB Approval Card"
author: "Nia"
---
[KB Approval Card](https://github.com/NowComponents/kb-approval-card) - A KB Approval card component that takes in a sys_id of a KB Approval Record.
![KB Approval Card](./assets/images/kb-approval-card.png)


This is a simple KB Approval card component rendered a now-card component.

For Paris release version - leverages [now-card](https://developer.servicenow.com/dev.do#!/reference/now-experience/paris/now-components/now-card/overview), [now-rich-text](https://developer.servicenow.com/dev.do#!/reference/now-experience/paris/now-components/now-rich-text/overview), and [now-modal](https://developer.servicenow.com/dev.do#!/reference/now-experience/paris/now-components/now-modal/overview) components

The KB article content is displayed in a now-modal pop-up when clicking on the action represented by the eye icon in the top right corner of the card. 
![KB Article Modal Pop-up](./assets/images/kb-approval-card-modal.png)

To test, update the sysid attribute in the [example](https://github.com/NowComponents/kb-approval-card/blob/main/example/element.js) - provide a valid sys_id of an Approval [sysapproval_approver] record in your instance.

when the approval is actioned, the component provides feedback with the status and updates the card.
![KB Approved](./assets/images/kb-approved.png)