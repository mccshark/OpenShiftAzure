# Workshop Demos

## Set 1
* Show web console
* Show how to login in CLI
* Create 4 new projects for dev, qa, prod, test teams
* Add user to project (Resources…Membership)
	* Note: don't have a UI in K8s
* Show how to deploy applications
* From Docker File
* Source to image
	* JBOSS - https://github.com/RedHatWorkshops/kitchensink
	* Ruby - https://github.com/RedHatWorkshops/ruby-hello-world
* Tasks
	* Show builds
	* Show deployments
	* Show routing

## Set 2
* Deploy NodeJS application
	* https://github.com/webbdog28/nodejs-welcome.git
	* Show advanced deployment options in interface
* Show instances deployed
	* OpenShift supports sticky sessions by default; show in multiple browser windows
	* Use curl to show round robin works
* Use curl loop to hit application and then scale out pods
	* while true; do sleep 1; curl http://node-welcome-my-php.ocpdapps.cardinalsolutions.com/; done
	* Kill a pod
* Health of applications
	* Show how to use /healthz endpoint
	* Show readiness probes
	* Use healthz endpoint for both probes
* Show autoscaling of pods
	* Configure autoscale by CPU%

## Set 3
* Show Azure Portal
	* Demo deployment using Marketplace image
* Show ARM templates and Ansible deployment
	* https://github.com/openshift/openshift-ansible-contrib/tree/master/reference-architecture/azure-ansible
