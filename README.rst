BIG-IP 6.0 Application Service Catalog - Automation Demo 
=========================================================

This repository hosts files to demo JSON files to create/modify/delete an application from the BIG-IQ 
application service catalog. This demo is based on Postman and all required variables are in the Postman format.


Installation
------------

1. Install Postman_ and import the `F5 Workflow Functions postman libraries`_: 
2. Install the F5 Workflow Functions by running the install command inside it's collection.
3. Import the BIG-IQ `environment variables`_ into Postman.
4. Import the BIG-IQ catalog_ into Postman.


Notice
------------

These examples are based on a custom service catalog entry and are intended for use as a example and starting point. 
If you try and run these against your BIG-IQ it will not work.  

Example_Usage
------------

1. Get an authentication token - run the Get Auth Token collection
2. Create an application - run the Create App collection
3. Check the results (you should see status: FINISHED in the JSON response) - run the Get Status collection
4. Add a pool member - run the Add Pool Member collection
5. Check the results (you should see status: FINISHED in the JSON response) - run the Get Status collection
6. Delete a pool member - run the Delete Pool Member collection
7. Check the results (you should see status: FINISHED in the JSON response) - run the Get Status collection
8. Delete the application - run the Delete App Collection
9. Check the results (you should see status: FINISHED in the JSON response) - run the Get Status collection


.. _Postman: https://www.getpostman.com/
.. _F5 Workflow Functions postman libraries: https://raw.githubusercontent.com/0xHiteshPatel/f5-postman-workflows/master/F5_Postman_Workflows.postman_collection.json
.. _environment variables: https://github.com/codygreen/BIG-IQ-Automation-Application-Service-Catalog/blob/master/Postman%20Workflow/big-iq_app_service_catalog_environment.json
.. _catalog: https://raw.githubusercontent.com/codygreen/BIG-IQ-Automation-Application-Service-Catalog/master/Postman%20Workflow/big-iq_app_service_catalog.postman_collection.json
