---
title: How to create an OpenACR Reports
layout: page
sidenav: true
permalink: /create/
---

# **{{page.title}}**

## What is an ACR?

An Accessibility Conformance Report (ACR) is a document that provides information about a digital tool's accessibility. Most ACRs are based on the Section 508 Technical Standards. The most well known ACR is a Voluntary Product Accessibility Template (VPAT™). The VPAT format was built and maintained by the Information Technology Industry Council (ITI).

This is the website for OpenACR, a machine-readable ACR that was developed by the GSA.

## Who is this for?

We have written this assuming you are a:

- vendor's salesperson who has been asked to submit an OpenACR document?
- vendor's accessibility subject matter expert (SME) who maintains your company's ACRs (including VPATs)?
- accessibility SME on contract to a vendor
- accessibility SME working for an organization looking to buy inclusive products and services?
- maintainer of an open source project who needs an OpenACR?

## How to complete an OpenACR report

The ACR is a representation of how a digital product or service conforms to a standard or guideline. OpenACR will initially focus on the Section 508 Technical Standards. Before beginning an ACR a product owner/developer must first audit their tool's accessibility. It is usually preferred to have an external Subject Matter Expert (SME) involved. More teams have accessibility expertise inside the organization.

This part of the guide walks you through how to complete an ACR using OpenACR. It assumes that you are working with an accessibility review.

### Step 1: Go to the OpenACR Editor

The [OpenACR Editor](https://gsa.github.io/openacr-editor/) is a free format with a free editor that guides authors to complete a well structured ACR. Filling out the form in the editor will allow you to produce a validated OpenACR document, as well as an HTML version.

### Step 2: Complete the OpenACR About page

The OpenACR process begins with an overview page that includes basic information about the process.

On the About page you will need to provide information like:

- Company name
- Name of your product (and version number, if applicable)
- Report date (month and year)
- Description of the product
- Contact information
- Additional notes (if any)
- Evaluation methods:

  - how your product was tested (manual, automated, both),
  - testing tools used
  - testing with people with disabilities, etc.

### Step 3: Understanding levels of conformance & comments for OpenACR tables

For categories which encompass the tool, you must select one of the following levels of conformance:

- Supports: The functionality of the product has at least one method that meets the criterion without known defects or meets with equivalent facilitation.
- Partially Supports: Some functionality of the product does not meet the criterion.
- Does Not Support: The majority of product functionality does not meet the criterion.
- Not Applicable: The criterion is not relevant to the product.

**Note:** The "Not Evaluated" phrase may only be used for the Level AAA table since this is the only success criteria table that is not required.

The third column is reserved for remarks, which are required if the product either partially supports or does not support the guideline. If the product supports a particular guideline, then no remarks are required but are encouraged.

### Step 4: Complete Table 1 (A) and Table 2 (AA) if applicable

If your product fits into one or more of the following categories, then the WCAG 2.0 guidelines apply to your product.

1. Web Content
2. Electronic Documents
3. Software
4. Authoring Tool

If your product does not fall under any of these four categories, you may write "Not Applicable" in the notes section for the Success Criteria tables.

The Success Criteria tables--Level A, Level AA, and Level AAA -- cover the WCAG success criteria. Only Level A and AA are required in an ACR.

If your product does satisfy some (or all) Level AAA success criteria guidelines, it can be worth completing this table. Highlighting where and how you meet AAA conformance can provide extra motivation for organizations to buy your tool.

### Step 5: Determine the applicability of the Revised Section 508 Technical Standards to your product

There are four Revised Section 508 tables, labeled as:

- Chapter 3 (Functional Performance Criteria)
- Chapter 4 (Hardware)
- Chapter 5 (Software)
- Chapter 6 (Support Documentation and Services).

Complete the applicable tables.

If there are functions in your product not addressed by Chapters 4 or 5, then your product needs to conform to the criteria in Chapter 3: Functional Performance Criteria. Does your product contain hardware?

Complete Chapter 4: Hardware. Does your product contain non-web software?

Complete Chapter 5: Software. Does your product contain support documentation and services?

Complete Chapter 6: Support Documentation and Services. If your product cannot be evaluated using the current criteria, complete Chapter 3: Functional Performance Criteria. For each table, there is a section for notes. Use this field to enter comments about overall applicability of the table to your product.

The first column "Criteria" of the Revised Section 508 tables lists the Section 508 Technical Standards. By clicking on the links provided in this column, you may access more information about the standards on the U.S. Access Board website.

### Step 6: Final checklist to make sure your OpenACR is complete

☐ Are you using the correct version? Make sure you are using the the latest version of OpenACR to build your ACR! If you have an older OpenACR file (ending with a .yaml extension) you should be able to load it into the editor to verify that it still validates.

☐ Did you complete the information fields in the About tab of the editor? You will see a warning if elements are not entered on this screen.

☐ If applicable, did you complete the Success Criteria, Level A and Level AA tables? If your product contains web-based content, electronic documents, software, or authoring tools, make sure you complete the Level A and Level AA tables.

☐ If applicable, did you complete the Chapter 3: Functional Performance Criteria table? If your product does not contain any applicable standards from the Level A and AA tables, then complete the Chapter 3: Functional Performance Criteria table.

☐ Did you skip the Level AAA tables? Section 508 does not require that your product be tested against the Level AAA Technical Standards. However, Industry may provide this information to show a higher level of accessibility than required.

☐ If applicable, did you complete the tables under the Revised Section 508 Report section? If your product contains hardware, software, or support documentation and services, be sure to complete the applicable Revised Section 508 table.

☐ Are you using the correct phrases to describe conformance levels? Check to see if all phrases under conformance level match one of the following: Supports, Partially Supports, Does Not Support, Not Applicable.

☐ Did you complete the remarks column? If the conformance level is either "Partially Supports" or "Does Not Support," then be sure that you explain further in the respective remarks column.


_**Note:** This content was adapted from NASA's 2021 guide, [Demystifying Section 508: An Industry Guide to Understanding Section 508 of the Rehabilitation Act (PDF)](https://sewp.nasa.gov/documents/Section_508_Guide_111821.pdf)._
