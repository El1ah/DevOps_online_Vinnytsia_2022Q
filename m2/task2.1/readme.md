# PART 1. HYPERVISORS

## 1. What are the most popular hypervisors for infrastructure virtualization?

- VMware ESXi

- HyperV

- XenServer

- VirtualBox

- RHEV

## 2. Briefly discribe the main differences of the most popular hypervisors

- Hypervisors have 2 types. First type runs directly on the host machine's physical hardware. Second type is installed on top of an existing OS

# PART 2. WORK WITH VIRTUALBOX

## Creating VM(1.4)

![](screenshots/1.png)



## Creating clone(1.6)

![](screenshots/2.png)



## Creating group and test the functions(1.7)

![](screenshots/4.png)

![](screenshots/5.png)



## Testing snapshot function(1.8)

![](screenshots/6.png)



## Exprot and import ova file(1.9)

![](screenshots/7.png)

![](screenshots/8.png)



## Configure USB connect(2.2)

- virtual machine settings

![](screenshots/9_true.png)



- Moutned flash-drive(/dev/sdb)
  
  ![](screenshots/10.png)



## Configure shared folder(2.3)

- shared folder settings
  
  ![](screenshots/11_true.png)
  
  

- mounting folder
  
  ![](screenshots/12.png)



- result
  
  ![](screenshots/13.png)
  
  ![](screenshots/13_1.png)
  
  ![](screenshots/13_2.png)



## Configure network settings(2.4)

- Creating NAT-Network
  
  ![](screenshots/14.png)
  
  

- Configure virtual machine
  
  ![](screenshots/15.png)



- Try to ping vm2 from vm1(successful)
  
  <img src="screenshots/16.png" title="" alt="" width="848">
  
  ![](screenshots/16_1.png)
  
  ![](screenshots/16_2.png)

- Table of possible connections
  
  ![](screenshots/17.png)



## Working with CLI(3.2)

- List of vm, and info about vm1

![](screenshots/18.png)

- Creating VM

![](screenshots/19.png)

- Start VM

![](screenshots/20.png)



# PART 3. WORK WITH VAGRANT

## Run Vagrant(3-4)

- Init vagrant file and start machine

![](screenshots/21.png)

## Connect to vagrant with Putty(5)

![](screenshots/22.png)

also can use `vagrant ssh` command



## Record the date(6)

![](screenshots/23.png)



## Delete virtual machine(7)

![](screenshots/24.png)



## Making own vagrant box(8)

- Edit vagrant file code

![](screenshots/25.png)

- Run the machine

![](screenshots/26.png)

- Connect to machine

![](screenshots/27.png)

    everythings fine



## Create test enviroment from a few servers(9)

- Make little changes in vagrant file code

![](screenshots/28.png)

- then type `vagrant up` again in terminal

![](screenshots/29.png)

- another server working fine too
