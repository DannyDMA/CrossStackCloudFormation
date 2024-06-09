# CrossStackCloudFormation
This repository contains AWS CloudFormation templates for crossStackCloudFormation (This diagrams shows how templates link with each other.)

MINI PROJECT 
[![Project](./images/Project.png)](images/Project.png)

---

Deploy a sample network configuration stack. For the Stack name use: SampleNetworkCrossStack
### OUTPUT EXPORTING STACK

[![COMPLETE STACK](./images/SampleNetworkCrossStack.png)](images/SampleNetworkCrossStack.png)

---

### VPC RESOURCE MAP
This diagram shows the base VPC with public subnets.

[![VPC Road Map](./images/VPC_RoadMap.png)](images/VPC_RoadMap.png)

---

### Deployed Template (Importer)
Deployed template in us-west-2 region to allocate an Elastic IP Address using resources, Reference all available variables from SampleNetworkCrossStack, Create a Mapping function to dynamically choose regions, Create Parameters for requesting user inputs as much as possible, Output the value of the Private IPV4 Address and DNS name of the EC2 instance

[![Deplyed Template](./images/MyTemplate1.png)](images/MyTemplate1.png)
[![Template CONT](./images/MyTEMPLATE2.png)](images/MyTEMPLATE2.png)
[![Running Stack of Template](./images/ImportStack.png)](images/ImportStack.png)

---

### Running EC2
My EC2 Running with the Security Group from Previous Stack.

[![EC2](./images/Running_Instance.png)](images/Running_Instance.png)

---

### My Website
Website_Preview

[![Website](./images/Website_Preview.png)](images/Website_Preview.png)