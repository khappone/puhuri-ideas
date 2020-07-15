# Example worflow diagrams for Puhuri

This directory contains a set of diagrams for the user access management worked on in the Puhuri project

# List of diagrams

## Simple registration - no integration to national system

 * user_registration_fed - User registration with federated AAI

[user_registration_fed](user_registration_fed.png)

 * user_registration_no_fed - User registration with catch-all AAI
 * project_create - Project creation, membeship management
 * resource_request - Resource request for project

## National portal integration

Option 1) National resource allocator controls identities

 * national_resource_allocation - Main workflows with national resource allocation portal
 * national_data_changes - Managing changing data with national resource allocation portal

Option 2) User controls their own identity
 
 * national_resource_allocation_alt - Main workflows with national resource allocation portal
 * national_data_changes_alt - Managing changing data with national resource allocation portal

## User login diagrams

 * login_first - First login to LUMI
 * login - Login with an existing account
 * login_no_account - Login without an account
 * login_no_allocation - Login without an allocation
 * login_ssh_keys - Login with SSH keys
 * object_storage_api - Login to the object storage API
 * object_storage_web - Login to the object storage web interface

## Backend (service integration)
 * resource_allocation_sync_new - Sync resource allocations for a project which exist in the backed
 * resource_allocation_sync_existing - Sync resource allocations for a project which doesn't exist yet
 * membership_update - Update of project members
 * project_expiry - Project expiry
 * resource_use_report - Reporting resource use
