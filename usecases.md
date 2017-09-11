**Use Case Name:** Model Complex Workflows      
**Description:** Using parallel and sequential execution, GoCD can easily configure dependencies for fast feedback and on-demand deployment. It has fan-in/fan-out dependency management that helps avoid incorrect building.

**Use Case Name:** How Workflow Works  
**Description:** goCD tracks changes from a commit, good to use if something goes wrong

**Use Case Name:** Versioning  
**Description:** Any version can be deployed at any time.

**Use Case Name:**  Build Things Once  
**Description:**  When taking software from initial code change to production in an automated fashion, it's important to deploy the exact same thing you've tested. Once a binary has been built, upload that back to your CD server or artifact repository for later use.

**Use Case Name:** Run Tests in Parallel  
**Description:** Split tests up into manageable size chunks and run them in parallel to avoid only running part of the tests.

**Use Case Name:** Design Parallel Workflows  
**Description:**  GoCD uses fan in/fan out dependency management to make sure the project doesn't get deployed until both of the upstream pipelines have gone green (similar to the Model Complex Workflows use case)

**Use Case Name:** Manage Environments in a Pipeline   
**Description:**  It's easier to break an application with a configuration change than with a bug introduced in the source code, therefore, managing all environments using an automated system and then verifying is efficient and helpful. 
