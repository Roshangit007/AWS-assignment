# AWS-assignment
Topic:-  Elastic Load Balancer

To create load balancer:- 

step 1 : create two ec2 instances in different A_Z ---open http port for application load balancer
step 2 : create target group --> instances --> grp name--->http protocol 80--->Include instance as pending below ---create
step 3 : create load balancer--->application load balancer-->name--> HTTP protocol-->select All A-Z-->security grp---> existing Target grp---> instance--->add to registerd all instances.

(check load balancers DNS)

for auto scaling 
firstly create Template or create AMI
1) create two target grp  3) launch configurations with this AMI
4) create Auto SCaling grp ----select all target grp -----> all subnet 
