---
title: Roadmap
layout: page
sidenav: true
permalink: /roadmap/
---

# **{{page.title}}**

## What we have done

Milestones documented, project description written, and initial OpenACR schema and catalog drafts published.

- Create the [highly structured, machine-readable document format](https://github.com/GSA/openacr/tree/main/catalog). YAML was chosen as the markup language. Refine the YAML OpenACR schema to support the requirements of the current Section 508 version of VPAT (ie. the example with [Drupal 9](https://github.com/GSA/openacr/tree/main/catalog)).
- Ensure that YAML documents conform to a defined [structure](https://github.com/GSA/openacr/tree/main/schema) and [catalog](https://github.com/GSA/openacr/tree/main/catalog). Build in validation code for the OpenACR schema so that key elements are evaluated.
- [Build testing into the development](https://github.com/GSA/openacr/tree/main/tests) so that errors are caught early in the process. Continuous integration should be used to validate the code and process.
- Define outreach goals and targets. This is a GSA project, but if successful it will have implications far outside of the GSA. The team will need to raise awareness about OpenACR.
- The OpenACR document will be written in YAML, but this isn't an easily readable format. The YAML file must be [converted to both Markdown and a themed HTML output](https://github.com/GSA/openacr/tree/main/openacr).
- Outreach and engagement will need to be done with stakeholders. Input will be needed for all roles of the procurement process.
- Display a web directory listing of available OpenACRs. Users should be able to view a [list of OpenACR files](https://federalist-02947dd8-86df-467a-b2af-4c5b94c5b1f0.app.cloud.gov/site/gsa/openacr-website/openacr/) as long as they are in a YAML format. These will need to be displayed in HTML in a format similar to the current VPAT.
- OpenACR Editor - Editors need to be able to create, load, update and save OpenACR documents in a YAML format.

## What we plan to do

Build process to submit vendor ACRs. Vendors need to be able to submit new ACRs to the GSA.

- Proccess to get updates from vendors version control repositories (git). Updates need to be pulled from the source from key government ICT suppliers.
- penACR Comparison Tool - it should be simple to compare OpenACRs to understand relative accessibility.
- Procurement focused documentation. Procurement teams in government need to understand how OpenACR changes their workflow.
- Vendor/Author focused documentation. Authors of OpenACRs need to understand how they should write and maintain the ACRS.
- Agency Accessibility Procurement Workflow. The flow of an ACR through the GSA should be clearly understood.
- Support government-wide documentation refresh. Current documentation is with VPAT but would need to be updated.
- Training will need to be required for government and possibly vendors.
- Integrate with DART (Procurement Accessibility Requirements Tool). Procurement officers should be able to easily re-create requirements to evaluate.
- Integrate with The W3C's EARL & WCAG-EM reporting. Creating ACRs should be consistent and easy to implement.
