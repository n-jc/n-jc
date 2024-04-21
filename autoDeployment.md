
#### Links for automated deployment best practice: 

- https://dora.dev/devops-capabilities/technical/deployment-automation/
- https://docs.aws.amazon.com/wellarchitected/latest/devops-guidance/advanced-deployment-strategies.html
- https://assets-global.website-files.com/6222ca42ea87e1bd1aa1d10c/62fd2d0f11820a703b563a1c_8%20Deployment%20Pattern%20Structures%20to%20Transform%20your%20CI_CDcopy.pdf
- https://dzone.com/refcardz/deployment-automation-patterns
- https://resources.github.com/learn/pathways/automation/intermediate/advanced-automated-deployment-in-github-actions/

#### Levels 

##### Level 0

Deployments :

- are manual
- require synchronisation of many teams changes
- are monolithic with many functional changes deployed together
- do not use artefact management
- do not employ configuration as code to parameterise each environment
- have no rollback strategy
- **release** new functionality immediately to all users


##### Level 1

Deployments :

- include basic automation such as the use of deployment scripts
- require sychronisation of only a few teams changes
- have a basic ability to deploy components (cf. modules) of a change independently
- use artefact management in deplyment for some environments
- have some level of per environment paramertisation via configuration
- have a manually executed rollback strategy
- can support basic incremental release startegies

#### Level 2

Deployments:

- Use CI/CD pipelines to facilitate deployment automation
- 




- do not use artefacts deployed accross multiple environments
