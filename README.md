# Liferay Workflow - Multiple Approvers + Scripting

An example Liferay workflow that demonstrates multiple reviewers as part of an approval path. A fork in the workflow results in parallel scripted tasks which determine whether or not the workflow should progress to a reviewer. There is a final join at the end prior to approval.

## Dependencies

- [Liferay DXP 6.2/7.0+](http://www.liferay.com)

## Instructions

Control Panel > Configuration > Workflow > Add New Workflow > Paste XML source

This workflow was created with Kaleo Designer, Liferay's visual workflow designer. The following is a visual representation of the workflow:
![Alt text](img/workflow_diagram.png?raw=true "Liferay Workflow - Multiple Approvers + Scripting")
