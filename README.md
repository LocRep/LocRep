# LocRep
Opensource Artifact Management Platform for DevOps



# LocRep OpenSource Artifact Management Project for DevOps

**LocRep official website** (http://locrep.com/) 

**LocRep test website** (http://dev.locrep.com/)

**LocRep test Agile and DevOps WebSite** (https://dev.azure.com/LocRep/)

> Before starting to publish, you must link an account in the **Publish** sub-menu.


## SmartyPants

SmartyPants converts ASCII punctuation characters into "smart" typographic punctuation HTML entities. For example:

|                |Scope                         |Status|
|----------------|------------------------------|-----------------------------|
|*			|`maven`            |      Coding	|
|*          |`nuget`            |           	|
|*          |`npm`				|				|




## UML diagrams



```mermaid
sequenceDiagram
Virtual Repo->> Local Repo : contains more than one local repo 
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR

A[Locrep Virtual Repo Node 1] -- maven,npm,etc... --> B((Remote Repositories))
Clients--> F5 
F5 --> A
A --> C(Local Repositories)
B --> D{Proxy Server}
C --> D





```



```
