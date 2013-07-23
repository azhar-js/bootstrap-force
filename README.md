Bootstrap-force is a simple modification to the Twitter bootstrap CSS/Javscript framework through which it can be used in Visual force pages in Salesforce.com.

This enables you to use all the stylings of Bootstrap without any CSS conflicts with standard Lists/Tables of Apex in visual force pages without even disturbing the styles of header and sidebar on VF pages. 

Start with declaring a div with class name "bootstrap-force" nest all the bootstrap markup within. 


## Get started :

* Download the repo and compress it as .zip and uploaded it into the static resources of your Org.
* The bootstrap's Javascript files are individually separated for modals, alerts, tabs, buttons and so on. Include which ever you want based on needs rather including all. In example I've included button, tab, modal and alert. Similarly you can include more.

## Dependencies :
Jquery 1.6+ 

## How to use ?

Simply create a div with class name "bootstrap-force" and write all the bootstrap markup within this Div.

`<apex:includeScript value="{!JSENCODE(URLFOR($Resource.JQuery,'1.8.3/jquery-1.8.3.min.js'))}" />`
<br>
`<apex:includeScript value="{!JSENCODE(URLFOR($Resource.bootstrap,'bootstrap/js/bootstrap-button.js'))}"/>`
<br>`<apex:includeScript value="{!JSENCODE(URLFOR($Resource.bootstrap,'bootstrap/js/bootstrap-tab.js'))}"/>`
<br>`<apex:includeScript value="{!JSENCODE(URLFOR($Resource.bootstrap,'bootstrap/js/bootstrap-modal.js'))}"/>`
<br>`<apex:includeScript value="{!JSENCODE(URLFOR($Resource.bootstrap,'bootstrap/js/bootstrap-alert.js'))}"/>
`<br>
`<apex:stylesheet value="{!JSENCODE(URLFOR($Resource.bootstrap, 'bootstrap/css/bootstrap.css'))}"/>`
<br>  
`<div class = "bootstrap-force">`  
`// All your code here`<br>
`</div>`
## Donts !!
Never use Apex's standard lists controls inside the bootstrap'd div. 
