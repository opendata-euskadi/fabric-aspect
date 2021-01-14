ECLIPSE IMPORT
==========================

if any of [r01fxxxAspectClasses] project does NOT compile once imported at [eclipse]:  

1. Expand the [src/main/aspect] folder
2. Right-click on the [aspect] folder and select [build path > use as source folder]
3. Right-click on the project and select [configure > convert to AspectJ project]


It's a good practice to SEPARATE the aspects code from the Java code  
... this is why there are a few projects_ 
	- r01fbXXXAspectsClasses : [AspectJ project] 	  
	- r01fbXXXClasses		 : [Java project] contains the aspects implementations  
	- r01fbAspectUtilClasses : [Java Projects] contains util classes  

