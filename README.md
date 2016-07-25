# XRMS

## About
This is fork of [XRMS v1.99.2](https://sourceforge.net/projects/xrms/) which fixes a couple of bugs when adding companies and contacts with incomplete data. Since the orginal xrms project is no longer being actively developed, it was forked to add these fixes. 

## Bugs fixed in this fork
 - When adding a new contact with out a company if all fields are not filled out the contact will not be added.
 - When adding a new company with a first contact if all fields are not filled out the company but not the contact will be added.

## Context
These bugs seem to only appear when xrms is used on FreeBSD version 10.2 w/mysql56-server.
