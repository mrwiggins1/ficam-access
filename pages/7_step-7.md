---
layout: page_collection
title: Step 7 - Establish the Data Management Life Cycle
permalink: 7_step-7
---
<script>
$(function() {
  $( "#accordion" ).accordion({
    heightStyle: "content",
    collapsible: "true",
    active: "false"
  });
});
</script>

<script src="https://use.fontawesome.com/e20c671b68.js"></script>
-----------------------------------------------------------

The Data Management Life Cycle focuses on identifying, obtaining, and maintaining data elements that enable access control decisions. Maintaining current data is essential to effective access management. Using incorrect or out of date data can lead to unauthorized access that put an agency’s resources in jeopardy. The Data Management Life Cycle defines the phases agencies can follow to maintain current data.

### Checklist 

> <i class="fa fa-check-square-o"></i> &nbsp;**Requirements and data gathering.** Data is required by your access control model and includes attributes and their associated metadata about subjects, resources, and the contextual environment. Once you’ve identified what data is required, you’ll need to determine where it’s located, how to obtain access to it, and establish the authoritative source for required attributes. 

<div style="background-color: #edf1f3;color: black;margin: 10px;padding: 10px">

<h3><span>What is data and what types of data exist?</span></h3>
<p><span>NIST defines data as “a subset of information in an electronic format that allows it to be retrieved or transmitted.” The data components in the Framework provide the information necessary to make access control decisions. There are three main types of data:</span></p>

| <center> Data Type </center> | <center> Description </center> |
|:----------------------------:|--------------------------------|
| **Subject/Identity Data** | Subject/identity data is a product of the Data Management Life Cycle and is used to uniquely identify a subject, which allows an access control model to map the subject to their appropriate access permissions. The Policy Execution part of the Framework then uses this information to grant access accordingly. |
| **Protected Resource Data** | Protected resource data describes details about a resource and is a product of the Data Management Life Cycle used to identify characteristics of a protected resource. This information can include the security clearance level required for access to a resource or specified emergency situations during which access can be restricted with increased requirements. |
| **Environmental/Contextual Data** | Environmental/contextual data is the product of the Data Management Life Cycle and allows for more flexibility in access control decisions and policy. Environmental data can include information such as the time of day or current security threat level and provides the Policy Execution part of the Framework with more data elements to consider when making a decision. If this information is available, it can be incorporated into a decision to automatically restrict access to only those authorized during a period when the security threat level is elevated. |


</div>

> <i class="fa fa-check-square-o"></i> &nbsp;**Define Enterprise Data and Attribute Format Standards.** Leverage guidance provided in the <a href="https://bnbuckler.github.io/ficam-identity/">Streamline Identity Management Playbook to define standard data formats for identity and entitlement attributes.</a>

> <i class="fa fa-check-square-o"></i> &nbsp;**Process and integrate data.** Processing data can include entering data, verifying its authenticity, extracting data into a usable form, or simply importing it from the data source so that it can be appropriately consumed during an access control decision.

> <i class="fa fa-check-square-o"></i> &nbsp;**Analyze data.** This can involve tagging data to make it more useful to a wider array of resources, performing quality assurance practices, or even detecting patterns that can be used in the development of policies that advance access security.

> <i class="fa fa-check-square-o"></i> &nbsp;**Preserve data.** The preservation of data minimizes the amount of duplicative work performed because it eliminates the need to acquire data that’s already stored and/or archived. It also provides additional opportunities to share the stored data with business partners to exercise in their own access control processes, including the real-time retrieval of subject/identity data from authoritative sources.

> <i class="fa fa-check-square-o"></i> &nbsp;**Use data to make decisions.** Data is used during the Policy Execution part of the Framework to determine if the subject is authorized to access the protected resource. The access control model components in the Framework diagram reference the data necessary to render an access control decision in the Policy Execution part.
