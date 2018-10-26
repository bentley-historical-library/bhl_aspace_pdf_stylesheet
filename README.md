# BHL ASpace PDF Stylesheet
This repository contains a slightly modified XSLT, based on the original by Winona Salesky, to generate PDF exports from ArchivesSpace.

The modifications in this version of the stylesheet do the following:
* Replaces the ArchivesSpace logo with a BHL logo
* Comments out the inclusion of revision descriptions
* Comments out the parsing of ref elements [BHL's legacy description does not have internal reference targets, breaking the stylesheet]

## How to Enable
Replace the default `archivesspace/stylesheets/as-ead-pdf.xsl` with this repository's `stylesheets/as-ead-pdf.xsl` and copy `stylesheets/bhl-fa-smlogo.gif` to the `archivesspace/stylesheets/` directory.