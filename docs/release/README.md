# Eclipse Payara Tools - Fork
This is a fork of the 'fork of the Eclipse GlassFish Tools', tailored and improved to fix issues with the Eclipse console and the server launch configuration.

## Eclipse Update Site
http://andi-huber.github.io/eclipse-payara-plugin/release/


## Build using Eclipse

1. checkout this repository in Eclipse
2. import all projects (3 are under /features and 3 are under /plugins) 
3. within Eclipse open /releng/site.xml
4. under 'org.eclipse.payara.tools' remove the 2 placeholder features 
5. hit the 'Add Feature ...' button and re-add the 'org.eclipse.payara.tools' feature from the list
6. hit the 'Build' button, this should create new files and directories under /releng/
7. the new content under /releng/ serves as the 'Eclipse Update Site' content for the 'Eclipse Payara Tools' (usually to be copied over to some web-server for Eclipse to use as update site)

Eclipse is a trademark of Eclipse Foundation.  
GlassFish is a trademark of Eclipse Foundation.  
Payara is a trademark of Payara Foundation.

