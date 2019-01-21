# Docker_AWS

1. Create an account on https://aws.amazon.com/ec2/ and sign in to console

2. Launch Virtual Machines 

3. Choose Amazon Machine Image(AMI) -> Ubuntu 16.04 LTS

4. Follow default configuration settings; Change storage to 20 gb; Security group limit to 0.0.0.0/0 SSH TCP port 22 for each instance. 

5. Depending on number of Virtual Machines you need, you have to specify during creation of VMs.

6. In the drop-down list of Actions, choose Change Security Groups -> select Security Group Name 'allow-all' and 'default'.

7. Launch the VMs and then from your host's terminal, SSH into it.





