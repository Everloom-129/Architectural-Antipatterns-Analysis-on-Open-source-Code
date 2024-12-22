# MINDMAP

## Map: Reason of all anti-pattern

seven sin

```mermaid
graph TB;
	7SIN --> Haste匆忙 
	7SIN --> Apathy冷漠
	7SIN --> Narrow-mindedness思想狭隘
	7SIN --> Sloth懒惰	
	7SIN --> Avarice贪婪	
	7SIN --> Igorance无知
	7SIN --> Pride自负
```

### Old School Def of ASs

mainly view from Architects' point

```mermaid
graph LR

```



### Smell's formal classification
```mermaid
graph LR
	smell --> ASs
	smell --> design_smells
	smell --> code_smell
		ASs --> Other
	ASs --> Maintenance
	
	
  Maintenance --> interface-based 
  Maintenance -->	change-based 
  Maintenance -->	concern-based 
  Maintenance --> dependency_based
  
  interface-based --> Ambiguous-Interface/Underused_Interface
  interface-based --> Unused_Interface
  interface-based --> Unused_Brick
  interface-based --> Sloppy_delegation
  interface-based --> Brick_Functionality_Overload
  interface-based --> Lego_Symdrome
  
  change-based --> Duplicate_Functionality
  change-based --> Logical_Coupling/Implicit_Cross-module_Dependency
  
  concern-based --> Scattered_parasitic_functionality
  concern-based --> Concern_overload
  
  dependency_based --> Dependency_cycle/Cyclic_Dependency 
  dependency_based --> Link_Overload/Hub-Like_Dependency
  
 
```

### detail:

![](D:\# Courses\暑研\img\ASs_class.png)


​	

```mermaid
graph TB;
	ASs --> Evolution

	ASs --> Other
	Evolution --> Architectural_elements_that_change_too_often_
	Evolution --> Highnumberofelementsimpactedbya_change
	Evolution --> Dependenciesbetweencomponents
	Evolution --> Bi-directionalrelationshipsbetweencomponents
```
