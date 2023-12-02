![Public Sector Accelerators logo](/docs/Logo_GPSAccelerators_v01.png)

# Grantmaking SF-424 Forms

**Use these OmniScripts to capture all the data for the SF-424 when an applicant applies for your grant.**

Accelerator Listing: [Grantmaking SF-424 Forms](https://pubsec-accelerators.my.site.com/accelerators/accelerator/a0wDo000000UCF3IAO/grantmaking-sf424-forms)


## Description

Energize your implementation by introducing a user-friendly wizard-driven process that simplifies the completion of the intricate SF-424 form. Beyond incorporating the Public Sector Solutions Grantmaking data model, we've also included supplementary data elements to ensure compliance with the necessary requirements throughout the SF-424 process.

The Standard Forms 424 (SF-424) form families represent the government-wide standard data sets and forms for grant application packages, which were developed in partnership with federal grantmaking agencies and the applicant community.  Leveraging OmniStudio capabilities, this accelerator provides supporting OmniScripts to facilitate an applicant completing the SF-424, based on the [form](https://apply07.grants.gov/apply/forms/sample/SF424_4_0-V4.0.pdf) and [instructions](https://apply07.grants.gov/apply/forms/instructions/SF424D-V1.1-Instructions.pdf) provided by Grants.gov.

![Sample OmniScript SF-424](/docs/SF-424Sample.png)

## Included Assets

This Accelerator includes the following assets in the PSA-Grantmaking-SF424-Forms.json located in the /datapacks/ folder:
<ol>
  <li><strong>OmniScripts</strong> (x5)</li>
  <ul>
    <li>SF424ParentOS - Main OmniScript for the SF-424 that calls the following OmniScripts:</li>
    <ul>
     <li>SF424ApplicantInformation</li>
     <li>SF424EstimatedFunding</li>
     <li>SF424ProgramAndProjectInformation</li>
     <li>SF424Questions</li>
    </ul>
  </ul>
       <li><strong>DataRaptors</strong> (x2)</li>
  <ul>
    <li>grDRGetUserAccountInfo - pulls the running User's Account information</li>
    <li>grDRGetFundingOpInfo - pulls in the Funding Opportunity information for the Individual Application</li>
  </ul>
  <li><strong>Documentation</strong>, including:
    <ul>
      <li>This readme file</li>
    </ul>
  </li>
</ol>


## Before You Install

Follow the instructions to Install the Accelerator for PSA-Grantmaking-FIBF-DataModel

Note: This package will install successfully without PSA-Grantmaking-FIBF-DataModel, but the DataRaptors depend on the Data Model provided within that accelerator.

**License Requirements**

License Public Sector Solutions - requires Public Sector Foundations Advanced for internal users; requires Customer Community license for external users.  

If you would like to test this Accelerator, you may sign up for a [Public Sector Solutions Base Trial Org](https://www.salesforce.com/form/industries/government/public-sector-base-trial/).

**Accelerator or Technology-Specific Assumptions** 

You have installed and configured OmniStudio and provided permission to PSS objects.

**General Assumptions** 

You are using this Accelerator in a sandbox or test environment. It is recommended that you not install any Accelerator directly into production environments.
You are using this Accelerator in conjunction with the Salesforce Lightning Experience (LEX) - not the Classic UI.


## Installation

<ul>
  <li>Open the OmniStudio App</li>
  <li>Navigate to OmniScripts and Click Import </li>
  <li>Click Browse and locate the datapack PSA-Grantmaking-SF424-Forms.json</li>
  <li>Click Next</li>
  <li>Click Next</li>
  <li>Click Activate Later</li>
</ul>

![Installation](/docs/ImportPSAGrantmakingSF424Forms.gif)


## FAQs

**_Q: Why doesn't the data get saved to the Individual Application?_**

A: In the initial release (v1.0) of the accelerator, we made the deliberate decision not to persist data back to the Individual Application object or any other object. This aspect is under evaluation for potential inclusion in a future release.

## Additional Resources


## Revision History

<strong>1.0 Initial release (30 Dec 2023)</strong> - Provides the base SF-424 forms 

## Acknowledgements

<ul>
  <li>Christine Talbot, PHD</li>
  <li>Keegan Virtue</li>
  <li>Laura Bell</li>
  <li>Nicole Peters</li>
  <li>Jen McClure</li>
</ul>


## Terms of Use

Thank you for using Global Public Sector (GPS) Accelerators.  Accelerators are provided by Salesforce.com, Inc., located at 1 Market Street, San Francisco, CA 94105, United States.

By using this site and these accelerators, you are agreeing to these terms. Please read them carefully.

Accelerators are not supported by Salesforce, they are supplied as-is, and are meant to be a starting point for your organization. Salesforce is not liable for the use of accelerators.

For more about the Accelerator program, visit: [https://pubsec-accelerators.my.site.com/accelerators/](https://pubsec-accelerators.my.site.com/accelerators/)
