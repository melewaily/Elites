# Elites
<html>
Kubernetes provisioning
Follow this documentation to provision a two node (1 master + 1 worker) Kubernetes cluster on Ubuntu 20.04 LTS with cri-o as the container runtime.
Adapt this documentation accordingly if you need more worker nodes.
Vagrant Environment
<table>
<tr>
  <th>Role</th>
  <th>IP</th>
  <th>OS</th>
  <th>RAM</th>
  <th>CPU</th>
</tr>
<tr>
<td>Master</td>
<td>104.248.50.14</td>
<td>Ubuntu 20.04</td>
<td>2G</td>
<td>2</td>
</tr>
</table>
•	Password for the root account on all these virtual machines is Admin@2022.MN <br>
•	Perform all the commands as root user unless otherwise specified <br>

Pre-requisites: <br>
Used Digital ocean account (Droplet) configured as below: <br>
OS: Ubunto v8 <br>
Location : San Francesco Data Center <br>
User : root user <br>
Nginx: <br> 
Installed nginx server <br>
PHP: <br>
installed PHPv8.1 <br>
Database: <br> 
Installed postgres database <br>
Configured  Drupal <br>
Docker: <br> 
installed docker componenets <br>
Created docker image for Drupal <br>
Created container for drupal <br>
Kubernates: <br>
Install Kubernetes components <br>
Created pod then cluster for drupal <br>
</html>
