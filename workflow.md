# Workflow

## Principle

### **Adopt Integrated-Manager Workflow among Distributed Workflows**

	1. Separate main and private storage

	2. Appoint an Integration-Manager (IM)

	3. Contributors can first clone the official repository and push it to their personal repository after modification

	4. Request 'IM' to pull from new repository

	5. 'IM' remotely adds the contributor's repository and merges it into 	the local (develop) branch

	6. IM then pushes the merged changes to main repository.


![distributed_workflow](/image/distributed_workflow.png)



## Parts


|       **part**           |             **name**                  |
| ------------------------ | ------------------------------------- |
| **Intergration-Manager** |  <i>seonghun-Kim</i>                  |
| **Frontend Developer**   | <i>seunghyeon-Lee, seonmyeong-Song</i>|
| **Backend Developer**    | <i>jaeha-Lee, junho-Lee</i>           |




## Visual Representation

	- Master (Versions for distribution, main storage)

	- Hotfix (Urgent bug fixes)

	- Develop (Developing, where most "branching" happens)

	- Front-end, back-end (Distinguish sectors)

	- Feature (Developer level)

