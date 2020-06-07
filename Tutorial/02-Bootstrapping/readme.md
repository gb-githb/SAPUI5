* ##### What is Bootstrapping ?
  * To Start with SAPUI5 Application , we need to first load SAPUI5 Libraries and Initialise it.
  * Process of loading and initialising the libraries is called as Bootstrapping
* ```id="sap-ui-bootstap"``` 
  * ID for the script
* ```src="https://openui5.hana.ondemand.com/resources/sap-ui-core.js"```
  * Tells Browser from where to load the Javascript Library
* ```data-sap-ui-theme="sap_belize"```
  * Default themer for UI5 Application
* ```data-sap-ui-compatVersion="edge"```
  * make use of the most recent functionality of SAPUI5 we define the compatibility version as edge
* ```data-sap-ui-async="true"```
  * "Bootstraping" process would run asycronously and will be loaded simultaneously in the background for performance reasons
* ```data-sap-ui-onInit="module:sapui5/index"```
  * We would define the module in the declarative way , with this we would avoid direct executable code in the HTML file
  * This would make application secure and modularise
* ```data-sap-ui-resourceroots='{"sapui5.gb.tuto": "./"}'```
  * This would tell the SAP ui5 core library sapui5.gb.tuto namespace is located in the same folder as index.html
