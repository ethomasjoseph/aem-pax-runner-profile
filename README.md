# AEM Pax Runner Profile

This project lists configurations that could be used to provision various versions of AEM quickly, which will have the basic OSGi specific dependencies, and no dependencies on the Sling, JCR or Adobe AEM libraries itself.

This profiles listed here are intended for used with [Pax Runner](https://ops4j1.jira.com/wiki/display/paxrunner/Pax+Runner). Make your project specific changes to the profile as required.

This project is provided with an intent of starting quickly in OSGifying vanilla jars for AEM, and is in no way any endorsement from Adobe or other entities.

### Features
* Felix Web Console - accessible at [http://localhost:8080/system/console](http://localhost:8080/system/console) (admin:admin)
* Starts with Felix Gogo Shell


### Example Usage:

*AEM 5.6.1*

	pax-run --args=file:aem-5.6.1.args
	
*AEM 6.1.0*

	pax-run --args=file:aem-6.1.0.args
	
## Contributing
If you find this useful, and feel that you have made it better, please consider contributing it back through pull request.