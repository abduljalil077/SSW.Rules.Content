---
type: rule
archivedreason: 
title: Schema - Do you create a consistent primary key column on your tables?
guid: 9dc11961-9ede-4e90-8c37-44b9a5ba9bbc
uri: schema---do-you-create-a-consistent-primary-key-column-on-your-tables
created: 2019-11-06T18:21:56.0000000Z
authors:
- id: 1
  title: Adam Cogan
related: []

---

Make sure you created a consistent primary key column named  **Id** on your tables.

<!--endintro-->

Employee.ID, Employee.EmployeeId, Employee.EmployeeID, Employee.Employee\_Code, Employee.Employee


::: bad
Figure: Bad Example

:::


Employee.Id


::: good
Figure: Good Example

:::


### Why?




* We shouldn’t capitalise ID (identifier) as it is an abbreviation not an acronym.
* Using the approach [TableName]Id, e.g. EmployeeId, is redundant as we already know the context of the Id.