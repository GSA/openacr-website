---
title: Accessibility Statement
description: Website accessibility statement and feedback document.
layout: page
sidenav: false
permalink: /accessibility/
---

# **{{page.title}}**

## Our goals

The OpenACR Accessibility website is still an MVP, and we are following accessibility best practices as we develop the site.

We strive to meet the latest W3C Recommendation of the WCAG guidelines (currently [WCAG 2.1 AA](https://www.w3.org/TR/WCAG21/)).

## Design framework

The design framework for this website is built primarily leveraging the [U.S. Web Design System](https://designsystem.digital.gov/) which has undergone extensive accessibility testing. By leveraging open source best practices, we can benefit from much larger teams which have done extensive testing of their patterns.

## Color

The website color palette is based on the GSA's and has been tested to meet color contrast requirements.

## Technology

The pages on this website are primarily written in Markdown which substantially reduces the range of errors available in HTML. These are then compiled using [Jekyll](https://jekyllrb.com/) and presented to the user as structured HTML5\.

We use [axe-core](https://github.com/dequelabs/axe-core) with [Pa11y](https://github.com/pa11y) to evaluate that every page follows basic accessibility best practices.

## Known issues

- [Website accessibility issues can be found on the website](https://github.com/GSA/openacr-website/issues)
- We can control the accessibility of the site, but not the accessibility of GitHub. GitHub is reasonably accessible, but is not currently seeking to be as accessible as this site.

## Feedback

If you run into any accessibility barriers with this website, please contact us:

- Email: [openacr@gsa.gov](mailto:openacr@gsa.gov)
- [Submit an issue](https://github.com/GSA/openacr-website/issues)
- [Submit a pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request)
