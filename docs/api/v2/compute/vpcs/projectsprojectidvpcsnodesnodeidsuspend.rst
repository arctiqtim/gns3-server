/v2/compute/projects/{project_id}/vpcs/nodes/{node_id}/suspend
------------------------------------------------------------------------------------------------------------------------------------------

.. contents::

POST /v2/compute/projects/**{project_id}**/vpcs/nodes/**{node_id}**/suspend
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Suspend a VPCS instance (stop it)

Parameters
**********
- **project_id**: Project UUID
- **node_id**: Node UUID

Response status codes
**********************
- **204**: Instance stopped
- **400**: Invalid request
- **404**: Instance doesn't exist

