# LTTS Applied SDLC Project
L&amp;T Technology Services Mini-Project (GENESIS_AUGUST_2021)


## Abstract
* 

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
# BADGES 

|Build    |Static Code Analysis |Dynamic Code Analysis|Code Quality     |Unity   |Git Inspector|
|:--------|:--------|:--------|:----------------|:--------|:-----------|
|[![C/C++ CI](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/c_build.yml/badge.svg)](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/c_build.yml)    |    [![cppcheck-action](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/cppcheck-action.yml/badge.svg)](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/cppcheck-action.yml)   |    [![Dynamic Code Check](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/dynamic.yml/badge.svg)](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/dynamic.yml)    | [![Codacy Badge](https://app.codacy.com/project/badge/Grade/b4f7cde618684bbd8ef9a837ddd7fa1e)](https://www.codacy.com/gh/GEN-AUG/SDLC_01_Falcon/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=GEN-AUG/SDLC_01_Falcon&amp;utm_campaign=Badge_Grade) |[![Unit testing](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/unit-test.yml/badge.svg)](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/unit-test.yml)|[![Contribution Check - Git Inspector](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/contribution.yml/badge.svg)](https://github.com/GEN-AUG/SDLC_01_Falcon/actions/workflows/contribution.yml)|
---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


### To build and execute:
```
make all
make run
```
### To execute in dev mode:
The colors are given in a string to setRubixCubeAtOnce function
```
make dev
```

### Input format:
For normal mode input the colors as asked.

For dev mode, edit the string of setRubixCubeAtOnce function as follows:

* The axis is shown below
* Each piece is considered as a node.
* There are total of 26 nodes.
* Input starts from Front Top Left corner(0,0,0).
* Input ends at the Back Bottom Right corner(2,2,2).
* i.e (0,0,0), (0,0,1) ...  (0,2,2), (1,0,0) ...  (1,2,2), (2,0, 0)...(2,2,2)  
* For Front and Back layer nodes( i = 0 and i = 2 ), at each node enter the facing colour, then the up/bottom colour( depending on position of node ), and finally the left/right colour.
* For middle layer ( i = 1 ), enter the up/bottom colour, then the left/right colour.



### Documentation

```
make doc
```

### Test

```
make test
```

### Coverage

```
make coverage
```

### Dynamic analysis

```
make dynamic
```

### Static analysis

```
make static
```

### Uninstall
```
make clean
```


## Folder Structure
|Folder|Description|
|:-----|:----------|
|1_Requirements|Documents detailing requirements and research|
|2_Architecture|Folders regarding design details|
|3_Implementation|Complete code and documentation|
|4_TestPlanAndOutput|Documents with test plan and procedure|
|5_Report|Project Report|
|6_ImagesAndVideos|Project output and videos|
|7_Others| Daily stand up report |


## Challenges Faced

- Time constraints was hard to manage. But later completed the project in time with effective planning and time management.


## Learning Materials 





