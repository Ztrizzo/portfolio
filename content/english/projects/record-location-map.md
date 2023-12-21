---
title: "Record Location Map"
date: 2023-12-17T18:26:42-06:00
draft: true

projectimages: 
  - name: "Record Page"
    image: /images/rlm-record-page.png

  - name: "Drawing"
    image: /images/rlm-drawings.png
---

Created a Packaged component for Salesforce that can be used to display a record's location as well as related records locations. Users can click to save a new location and, if enabled, users can draw their own shapes to be saved to the record. Able to be configured and customized in any Salesforce org without writing any code.


##### Install it into a Salesforce org
[Link](https://login.salesforce.com/packaging/installPackage.apexp?p0=04tDn000000ifxNIAQ)

```
sf package install --package 04tDn000000ifxNIAQ --target-org "Your Org Here"
```