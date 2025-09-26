# Release Notes
This document outlines all updates applied to the add-on.  Please note that not all updates will show up within the Google Workspace Marketplace listing. 

#### Major Release (ex. version 2.X.0)
A major release means updating the listing on the Google Workspace Marketplace.  Typically this will mean net new features, which often come with new permissions required to use those changes.  Any change to the add-on manifest (what's in the marketplace listing) will be classified as a major update.  

#### Minor Release (ex. version 2.0.X)
A minor release will include bug fixes and minor changes.  Since we're not adding new features or requesting new permissions, there is no need to updating the marketplace listing.  There is no need for customers to do anything for minor releases, the changes are automatically available.

## Minor Release: 2.1.1 - September 26, 2025
This update replaces the static IP address used for Tableau Server environments behind a firewall.  The previous IP address listed turned out to be used only for inbound traffic (http requests _to_ our app), so we added a static outbound IP address (http requests _from_ our app) to our infrastructure.  

## Minor Release: 2.1.0 - July 15, 2025
This update fixed some localization issues for Tableau Pulse.
* Metric titles within the images would not render for non-latin alphabet languages (japanese, korean, etc).
* Pulse insights were always in English, now they are generated in the user's Google Workspace language.  This applies within the right side panel (addon) as well as for link unfurling.
* Some error messages on the initial setup page were too generic, adding more details to help with troubleshooting issues

## Major Release: 2.0.0 - April 4, 2025
This update adds the following new functionality to the add-on:
* Embed images of your views and Pulse metrics within Google Docs & Slides.
* Refresh Tableau images within Google Docs & Slides
* Link Unfurling (Preview Links) in Google Slides


## Major Release: 1.0.0 - June 29, 2023
This is the initial release of the add-on, which supported only link unfurling (Smartchips) in Google Docs.  The original documentation to support that can be found in the [v1 branch](https://github.com/tableau/tableau-google-workspace-integration/tree/v1) of this repo.
