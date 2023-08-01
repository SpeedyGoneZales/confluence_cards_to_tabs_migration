# Atlassian Confluence - migrating from Cards to Tabs macro

This script migrates from the currently used used [Deck of Cards / Card macro](https://apps-docs.servicerocket.com/composition/deck-of-cards) (which is deprecated) to the [Tabs Container / Tabs macro](https://docs.adaptavist.com/cfm4cs/latest/content-formatting-macros/tabs)

The Tabs macro brings two primary benefits:
* Lazy loading means content is not generated unless somebody is actually looking at the respective tab. This leads to major performance improvements for Pages using the [Page Properties Report](https://confluence.atlassian.com/doc/page-properties-report-macro-186089616.html) macro (which in turn relies on the Page Properties macro on the affected pages).
* The Tabs Macro supports directly linking to a specific tab out of the box, which makes it easier to share a specific section of a given page.
