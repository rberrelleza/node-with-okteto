# Develop a Node-based application on an environment provisioned by Okteto

This is an example of how you can deploy a preconfigured environment in Okteto, and then use VSCode to develop remotely a Node-based app 

## Requisites
1. VSCode is installed locally
1. The "Remote - Kubernetes" extension installed in your VSCode instance
1. An Okteto account ([Sign-up for 30 day](https://www.okteto.com/try-free/), self-hosted free trial) 


## To develop 
1. Clone this repository (you only need to do this once)
2. Open it in VSCode
3. Run the "okteto: up" action 
4. Follow the prompt to open a VSCode Remote SSH session. 

The VSCode instance that appears at the end of the process is connected to your remote development environment in Okteto. You can use this to clone your repository, make code changes, and execute your tests. 

When you are finished, run the `okteto: down` action to shutdown your remote development environment.