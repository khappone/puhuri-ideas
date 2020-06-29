# Example worflow diagrams for Puhuri

This directory contains a set of diagrams for the user access management worked on in the Puhuri project

# List of diagrams

## Simple registration - no integration to national system

 * user_registration_fed.txt - User registration with federated AAI
 * user_registration_no_fed.txt - User registration with catch-all AAI
 * project_create.txt - Project creation, membeship management
 * resource_request.txt - Resource request for project

## National portal integration

Option 1) National resource allocator controls identities

 * national_resource_allocation.txt - Main workflows with national resource allocation portal
 * national_data_changes.txt - Managing changing data with national resource allocation portal

Option 2) User controls their own identity
 
 * national_resource_allocation_alt.txt - Main workflows with national resource allocation portal
 * national_data_changes_alt.txt - Managing changing data with national resource allocation portal

## User login diagrams

 * login.txt - Login with an existing account
 * login_no_account.txt - Login without an account
 * login_no_allocation.txt - Login without an allocation
 * login_ssh_keys.txt - Login with SSH keys
 * object_storage_api.txt - Login to the object storage API
 * object_storage_web.txt - Login to the object storage web interface

## Backend (service integration)
 * resource_allocation_sync_new.txt - Sync resource allocations for a project which exist in the backed
 * resource_allocation_sync_existing.txt - Sync resource allocations for a project which doesn't exist yet
 * membership_update.txt - Update of project members
 * project_expiry.txt - Project expiry
 * resource_use_report.txt - Reporting resource use
