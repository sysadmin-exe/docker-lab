this is a solution to the task given in the test for Cloud Engineer A/B Test Infrastructure from Trivago

this solution uses an NGINX load balancer for the load balancing solution

this uses a docker-compose.yml file to spin up the NGINX load balancer, Java and Go apps

the NGINx load balancer will load balance traffic to the backend app - 70% to the go-app and 30% to the Java-app

