# Ansible-automation
# ###### ## Ansible

### ## # ### #### installation:

To get Ansible for CentOS 7, first ensure that the CentOS 7 EPEL repository is installed:

`sudo yum install epel-release`
Once the repository is installed, install Ansible with yum:

`sudo yum install ansible`

check version using 
`ansible --version`

### Ansible Inventory

1. create a ansible-test-project folder inside home directory and specify your host details
2. add your servers inint.

#### Inventory parameters
- **ansible_host**: Specifies the hostname or IP address of the host.

`server1 ansible_host=192.168.1.100`
`server2 ansible_host=example.com`

- ** ansible_use**r: Sets the remote username used to connect to the host.

`server1 ansible_host=192.168.1.100 ansible_user=ubuntu`
`server2 ansible_host=example.com ansible_user=admin`
