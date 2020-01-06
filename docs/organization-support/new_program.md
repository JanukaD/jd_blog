---
layout: default
title: New Program
parent: Organization Support
has_children: true
nav_order: 2
---
<style>
.center-image
{
    margin: 0 auto;
    display: block;
    border: 1px solid #a075d1;
}
</style>

# Add new Program
 
To add a new program, an organization need to provide details regarding following sections.

## Policy

The policy section enables organizations to publish information about their program in order to communicate 
the specifics about their program to hackers. It will act as your document of 
requirements for any security testers registered in the Bug Zero Platform. It should clearly mention if 
someone finds security vulnerability, how they should report, things you expect in the report.

To add new policy or edit your existing policy:
- Go to the Policy section in **Program Settings** > **Programs** > **policy**.

![policy]({{ site.url }}/assets/images/policy.PNG){: .center-image }

><i>Note: If you are unable to come up with a policy please contact Bug Zero Team [(support@bugzero.io)](mailto: support@bugzero.io). We are more than happy to help you to come up with a proper policy for your program (organization).</i> 

## Scope

Scope is a collection of assets you want hackers to hack on. When assets are listed, hackers are required to select the applicable asset for each report. Any special requirements will now be explicitly attached to the particular asset in question.

### To Create and Edit your Scope
To view and edit your existing scope:
1. Go to the Scope section in **Program Settings** > **Programs** > **Scope**.<br><br>![scope_preview]({{ site.url }}/assets/images/scope_pre.PNG){: .center-image }

2. Click on **Add Target**. It will bring you to this page:<br><br>![scope]({{ site.url }}/assets/images/scope.PNG){: .center-image }

3. Fill out the different fields. For each target, you can fill out:

Option | Detail
------ | -------
Type | The domain type. <br>You can choose from these options: Domain, iOS App, Android App, Windows App, Source Code, Hardware/IoT, Other
Identifier | Provide an identifier for hackers to know that they are at the correct target.
Eligible for submission| You can can choose the acceptable submission scope from these options, <br>**In Scope**/ **Out Scope**.
Eligible for Bounty | Select whether this target is eligible for the bounty or not.
Threat Level | Select the threat level from these options. <br> **Critical, High, Medium, Low & None**.
Instructions | Provide an additional instruction.
