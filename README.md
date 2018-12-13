# Postman_LearnAPI
This repo contains postman scripts for learning purposes.

Added demo scripts related to functional testing.

 
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
 
 let jsonData = pm.response.json();
 
 console.log(environment.created_deployment_id);
 
pm.test("Found newly created deployment id in response", function () {
    pm.expect(pm.response.text()).to.include(environment.created_deployment_id);
});

