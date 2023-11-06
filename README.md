# Setting up a VPC and VSwitch in Alibaba Cloud

Create a Virtual Private Cloud (VPC) and Virtual Switch (VSwitch) in Alibaba Cloud is a fundamental step for building your network infrastructure. In this lab, you will go through the process of creating a VPC and VSwitch in Alibaba Cloud using the Alibaba Cloud Management Console.

A Virtual Private Cloud (VPC) is a virtual network dedicated to your Alibaba Cloud resources.


## Tasks:

**Task 1: Create a VPC**

Create a VPC name it (Lab-VPC) in Riyadh Region, make sure the IPv4 CIDR Block you choose can have only (16) subnet and each subnet can have (512) IP

**Step 2: Create a VSwitch**

A Virtual Switch (VSwitch) is a subnet within your VPC. You can create multiple VSwitches within a VPC to segment your network.

1. Create a subnet in Zone A and name it (app-xyz-a)
2. Create a subnet in Zone B and name it (app-xyz-b)

**Step 3: Verify Your VSwitchs connection**

After creating the 2 ECS Instance  try to ping the other instance 

1. Create an ECS in VSwitch app-xyz-a and name it (app-xyz-a1)
2. Create an ECS in VSwitch app-xyz-b and name it (app-xyz-b1)

## Submission:

- After finishing the tasks take screen shot of newly create VPC basic information and vswitchs details the ping command response.
- Then upload the pictures to the forked repo and then create a pull request.
