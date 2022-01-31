---
title: Frequently Asked Questions (FAQ)
layout: page
sidenav: true
permalink: /faq/
---

# Frequently Asked Questions (FAQ)

## How do I know if my product is compliant with Section 508?

Industry is expected to test its products against the applicable Section 508 Technical Standards and report which standards the product supports, partially supports, or does not support so that the U.S. Federal government may consider purchasing the product. This information is provided by Industry in an Accessibility Conformance Report (ACR). If the product supports all of the applicable Section 508 Technical Standards, the product is considered compliant with Section 508.

## How do I know which version of the OpenACR to use?

An OpenACR document should be generated with each release of a digital product or service. If there is an update to the ACR to the same release of your product or service, then the filename should reflect it is a new version of the OpenACR (example-2.3.1.yaml vs example-2.3.1--v2.yaml).

The OpenACR standard will continue to evolve over time, but will support loading older OpenACR data files for 2 years. The OpenACR data files contain the version information for the OpenACR that is used. Vendors are encouraged to always use the latest version of OpenACR standard.

## I have not completed an ACR before. Why am I being required to complete one now? Isn't OpenACR voluntary?

The U.S. Federal government must buy Information and Communication Technology (ICT) that is accessible per Section 508 of the Rehabilitation Act. The government asks Industry to submit an Accessibility Conformance Report so that the accessibility of a product may be evaluated. Without the ACR, the government may not proceed with the purchase unless there is a special use case exception that the government -- never Industry – may claim in which the ACR will not be required. You are being asked to complete the ACR so that your product may be considered for purchase.

If a procurement requires an ACR, it is not voluntary.

## My company created an ACR for a product years ago. May I use that same ACR today?

Every time your product is changed or updated (e.g. version change, bug fix, etc.), an updated ACR is required that addresses any changes in the product's accessibility. Also, if you created an ACR using the Original Section 508 Standards from 2001, you must update your report using the Revised Section 508 Standards published in 2017.

If before you used a VPAT, and a procurement opportunity requires an OpenACR, you will need to create a new ACR.

## Can I submit an OpenACR if a procurement opportunity asks for a VPAT?

OpenACR will work to align with the VPAT format. If you have a procurement opportunity asks for a VPAT you can send the HTML file that is output from the [OpenACR Editor](https://gsa.github.io/openacr-editor/). You will want to keep the YAML file so that you can modify your ACR in the future and use it to submit for RFPs that require an OpenACR.

## Should I complete an ACR if my product is not fully accessible? How can having a completed ACR for my product benefit my company?

Yes. Very few products are fully compliant. Completing an ACR is a win-win situation for Industry and the government. When Industry creates an ACR, it opens the door for the Federal government to purchase your product. Your ACR shows customers that your company takes accessibility seriously. Even if the ACR shows that not all the applicable Section 508 Technical Standards have been met, it allows your product to be evaluated against comparable products for accessibility. If you have an ACR and a competitor's product doesn't, you will always be the most conformant with the Section 508 standards. Completing an ACR raises your awareness of your product's accessibility and allows you to take steps to make your product more accessible and reach a broader customer base.

## My product is not web-based. Do the WCAG 2.0 (Web Content Accessibility Guidelines) apply to my product?

In the Revised Section 508 Technical Standards, electronic content and software are required to conform to WCAG 2.0 Level A and Level AA Success Criteria and Conformance Requirements. While the WCAG applies to web products, they also apply to all electronic content and software.

## My product has support documentation, hardware, and a mobile application. Do I need to complete three separate ACRs?

No, you may complete one ACR that addresses all the relevant standards and criteria that match the functionality of your product. Or, you may provide separate ACRs, if that works better for your workflow.

## My product is an add-on for an existing product from a separate company. Am I responsible for completing the ACR for both products, or will the other company create the ACR?

You are responsible for completing an ACR for the product you developed. If you are extending another poduct you can add a link for where to find the ACR for that product. If it is not available, you can add information in the notes section about the product you are extending.

## My product does not conform to all the relevant Section 508 Technical Standards. Will this prevent the Federal government from purchasing my product?

No. Your product will be still be considered for purchase even if all of the Section 508 Technical Standards are not met. Your product will be compared to other comparable commercially available products. The product that is most accessible and meets customer requirements may be purchased.

## What do I enter under the columns "Conformance Level" and "Remarks and Explanations"?

In the Conformance Level column, you enter terms to describe to what extent your product meets a specific standard. Conformance Level terms are:

- Supports
- Partially Supports
- Does Not Support
- Not Applicable

If your product Partially Supports or Does Not Support the standard, you should provide a comment in the Remarks and Explanations column that indicates how the standard is not met/fully met.

## My product has both software and support documentation. Which sections of the OpenACR do I need to complete?

If your product contains software, there are two sets of Section 508 Technical Standards within the report that you must complete:

- WCAG 2.0, Table 1: Success Criteria Level A and Table 2: Success Criteria Level AA.
- Revised Section 508, Chapter 5: Software.
- For electronic support documentation, complete the Revised Section 508, Chapter 6: Support Documentation and Services section.

## I have an existing ACR (ie. a VPAT) but not an OpenACR document, can I just submit our existing ACR?

This would be specific to the department and the specfics of the RFP or contract. The RFP or contract should clearly state if an OpenACR is required or if a different ACR format (such as a VPAT) will be accepted. Note: OpenACR is still in a pilot phase, so most opportunities will not require it just yet.

## If I have an existing ACR (ie. a VPAT), how can I re-use the information in it to produce an OpenACR?

Yes. Most people will be looking to convert a VPAT to the new OpenACR format, as the VPAT is currently the dominant ACR format. For most the easiest way to move from a VPAT to an OpenACR document will be to copy/paste the text from the older document into the [OpenACR Editor](https://gsa.github.io/openacr-editor/).

If you have many VPAT you want to convert, we will be producing a blog post or possibly an online tool to help extract content into a draft OpenACR document. Currently [Tabula](https://tabula.technology/) promising, but much will depend on how well structured the original document is.

You will still need to manually review this to ensure that the unstructured content from the PDF is properly migrated over to the highly structured OpenACR format. Using the online editor should allow you to verify this.

## How much time should it take to cmplete an OpenACR if I already have an existing ACR (ie. a VPAT)

This will depend on the completeness and complexity of your VPAT, however many vendors can copy and paste the content into the [OpenACR Editor](https://gsa.github.io/openacr-editor/) to produce a valid OpenACR file.

## Do we need to use the OpenACR Editor tool?

No. Your OpenACR file is valid, if it conforms with the [JSON Schema published on GitHub](https://github.com/GSA/openacr). We encourage organizations to optimize their accessibility workflow to align with this document format.

## Can I submit my OpenACR as a Word or PDF document?

No. OpenACR's generally refer to the text file that is in a standard YAML format and ends with a .yaml extension. Even the HTML file is only there as an accessible way to present the information. Starting with a valid OpenACR YAML file, anyone can produce a HTML document. From this users can create Word or PDF versions. This workflow cannot be reversed. Submissions of OpenACR files must be as validated YAML files.

_**Note:** This content was adapted from NASA's 2021 guide, [Demistifying Section 508: An Industry Guide to Understanding Section 508 of the Rehabilitation Act (PDF)](https://sewp.nasa.gov/documents/Section_508_Guide_111821.pdf)._
