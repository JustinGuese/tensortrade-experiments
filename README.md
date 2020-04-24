
My fix / implementation of tensortrade examples
-----
install the following 

pip install git+https://github.com/tensortrade-org/tensortrade stochastic ta

# how to start it in the cloud

1. choose an aws ec2 instance
2. in the bootstrap area copy the "cloudbootstrap.sh" script
3. ssh into the instance with port forwarding ssh -L 8888:localhost:8888
4. in the home folder there should be the tensortrade-experiments folde, cd into it
5. run the cloudinit.sh script (you might need to "chmod +x cloudinit.sh" first, then just type ./cloudinit.sh
6. in your console the jupyter notebook address should be marked. copy paste it into your local browser
7. jupyter notebook should appear.
- the environment might not activate via script. in that case just copy paste the commands of the cloudinit.sh into your console

