# XCorp Webserver Sentinel Policies

## Purpose

This repository contains sentinel policies designed to govern web server infrastructure.  The policies are designed to work in concert with the XCorp Terraform modules.  The modules govern cost, security, and operational concerns.  

## Structure 

The repository is split into folders for each cloud platform and a folder for generic policies.  Each folder is meant to be a base for a Sentinel policy set for the corresponding platform.  Each folder should be individually mounted as a Terraform Cloud policy set.  Documentation for the policies is contained in the platform specific folder.
