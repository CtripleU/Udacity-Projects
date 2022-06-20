# Deployment of Udagram (A high availability web app) using CloudFormation

### Starter template is located here [`Template`](https://github.com/udacity/nd9991-c2-Infrastructure-as-Code-v1/blob/master/project_starter/final-project-starter.yml)

### To spin up the resources,

`git clone https://github.com/CtripleU/Udagram`

`$ cd Udagram`

`$ chmod +x create.sh && chmod +x update.sh` to make the scripts executable


`$ ./create.sh udagraminfra network.yml network-params.json`

`$ ./update.sh udagramserver server.yml server-params.json`


aws cloudformation delete-stack Your-Stack-Name-Here

or run
./destroy.sh Your-Stack-Name-Here

### DNS

http://udagr-udagr-1kzlca4h96u5s-1650533499.us-east-1.elb.amazonaws.com/
