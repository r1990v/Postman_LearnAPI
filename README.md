# Postman_LearnAPI
This repo contains postman scripts for learning purposes.

Added demo scripts related to functional testing.

//Documentation 
https://learning.getpostman.com/docs/postman/scripts/postman_sandbox/

 let jsonData = pm.response.json();
 
 console.log(environment.created_deployment_id);
 
pm.test("Found newly created deployment id in response", function () {
    pm.expect(pm.response.text()).to.include(environment.created_deployment_id);
});

