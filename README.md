1.Tell me about What is crm life-cycle?
ANS : In customer relationship management (CRM), customer lifecycle is a term used to describe the progression of steps 
	  a customer goes through when considering, purchasing, using and maintaining loyalty to a product or service.
	
	
2.What is lead conversion process and how its helpful in CRM?.
ANS : Lead conversion in Salesforce is a process in which a lead record is converted into Accounts, Contacts & Opportunities. 
	  This happens when a lead is identified as a qualified Sales prospect.


3.What is SDLC? which methodology you are using?
ANS : SDLC is a process followed for a software project, within a software organization. It consists of a detailed plan describing how to develop, maintain, replace and alter or enhance specific software. The life cycle defines a methodology for improving the quality of software and the overall development process.
	  The steps are Preliminary Analysis, System Analysis, System Design, Programming, Testing, Implementation, and Maintenance.


4.What is profile and explain profile components in salesforce?
ANS : A profile controls Object permissions, Field permissions, User permissions, Tab settings, App settings, Apex class access,
	  Visualforce page access,Custom Settings,Custom Metadata Types, Page layouts, Record Types, Login hours & Login IP ranges. You can define profiles by user's job function.


5. Permission sets and explain its uses?
ANS : A permission set is a collection of settings and permissions that give users access to various tools and functions. 
	  The settings and permissions in permission sets are also found in profiles, but permission sets extend users' functional 
	  access without changing their profiles.


6.Difference between salesforce profile and permission sets
ANS : You can assign permission set as many users you want. The difference between Profile and Permission Sets is Profiles 
	  are used to restrict from something where Permission Set allows user to get extra permissions.


7.What is workflow rules and briefly explain it? Difference between evaluation criteria created, and every time it’s edited and created & and any time it’s edited to subsequently meet the criteria?
ANS : Workflows in Salesforce are a fantastic way to automate certain business processes. You can create a rule, and based on 
	  certain criteria that you set, Salesforce can do a number of things, like send an email, create a task, or update a field.
	1.Criteria: Criteria are conditions you are supposed to put in order to test a record. For example, if you’re from a technical background, what the if statement does in an if/then condition is what criteria mean in a workflow.
    2.Actions: Actions occur after a record meets the criteria. Again, what the then statement does in the if/then condition is what an action means in the workflow.
	  Types of actions present in a workflow in Salesforce:
		2.1.Immediate actions: Actions that get executed immediately when a record is created or edited
		2.2.Time-dependent actions: Actions that get executed after a certain duration of time, such as 10 days, before a record’s close date. After this time period, the workflow rules in salesforce will re-evaluate the record just to make sure that the rule criteria are met. If the record meets the criteria, the aligned actions will be executed.
	3.Salesforce will evaluate the rule when a record is:
	 3.1. created = It will check only if the rule applies when the record is created, which means it will ignore updates to existing records.
	 3.2. created, and every time it’s edited = if the rule criteria is met, the rule will run, no matter what.
											The rule will run when the record is edited to show some condition of data 
											on a record, but the rule will also run every single time that record is edited for any other reason.
	 3.3. created, and every time it’s edited 
		to subsequently meet criteria = rule will run if a new record is created that meets the criteria, 
										or if an existing record is changed from not meeting the criteria to meeting the criteria.


8.Approval process in salesforce and give me one use case?
ANS : An approval process is an automated process an organization can use to approve records in Salesforce. In an approval process, you specify: The steps necessary for a record to be approved and who approves it at each step.
	  To submit a record into the approval process, the user has to manually click on the Submit For Approval button.
	  The disadvantage of this manual process is that a user can forget to click on the Submit For Approval button. It will not auto-send records into the approval process, and therefore, it may cause an issue sometimes.


9.What is report type?
ANS : In Salesforce, reports are created by first selecting a report type. A report type is a template which defines the objects and fields that will be available to use in the report you create.


10.Which reports support dashboards
ANS : 1.Tabular(supported in dashboard only if rows are limited (maximum 10)) – This is the simplest type of reports and is suited to just showing lines of data and nothing else. If you just want to show data with no preference to seeing totals, calulations or groups of data then this is the report for you just to keep it simple. It is also best to use this report type if you are planning to use it to export data. 
	  2.Summary(supported) – As soon as you click “Group by this field”, you will turn the report into a summary report. Summary reports are probably the most commonly used and are great for showing groups of data e.g. If you want to see your recent accounts opportunities they will be grouped by account and you can see each opportunity under the account. From then you can do calculations, you can see the total amount of sales under an account, you can see the maximum, minimum and also average amount. You can also sub group fields by dragging them under the initial group. 
	  3.Matrix(supported) – Matrix reports are very similar to Summary but they allow you to group by rows as well as columns to see different totals. Matrix reports aren’t commonly used unless you have to display lots of complex data. 
	  4.Joined Reports(supported) – Joined reports allow you to create two separate reports so that you can compare data. Again not most commonly used.


11.What are sharing settings in salesforce?
ANS : Salesforce provides organization-level sharing settings to set the baseline access for the records, so that you can set the sharing separately for every object. If you want to restrict your users' access to data of an object, set the object's Default Internal Access or Default External Access setting as private.


12. Difference between summary and matrix report in salesforce?
ANS : In short if you need to do the sum or calculate the average on even one parameter then summary report is the answer. Matrix Reports:- These reports are used when the requirement is to summarize both the Axis i.e. when requirement is to group both Rows as well as Columns.


13. Process builder& need of process builder?
ANS : Process Builder in Salesforce is basically an automated tool that allows you to control the order of actions or evaluate the criteria for a record. It has number of actions associated with it: Creating records: This will allow you to create a new record and add different field values for it. We can also acheive operations by process builder instead of writing code.


14.What are escalation rules and briefly explain
ANS : An escalation rule automatically reroutes a case and can notify a user if the case remains open after a certain period of time has passed. With an escalation rule, you can: Choose to escalate a case to a queue or to another user.


15.What is soap web service and briefly expalin how you know about that(It depends if you put in resume)
ANS : Web Services are an abstraction layer allowing systems to communicate independently of their source code language.
	 1.SOAP stands for Simple Object Access protocol. SOAP messages are in XML format and sent over HTTP. Defining an Apex method as a SOAP web service is very easy. The method needs to be placed in a global class and must use the keyword ‘webservice’.
	 2.REST stands for Representational State Transfer; REST is an architectural style not a protocol. REST API uses simple HTTP methods using XML or JSON format. You can define your apex classes as REST Resource by defining the class with @RestResource annotation. The URL mapping to access the REST service is defined at the class level too.


16. How you can rate yourself in salesforce?
ANS : If I can answer all of the above questions without any hesitation then 8 out 10.


17. What type of settings you can give in permission sets
ANS : The permission set is also very similar to profile. Whatever you can manage at profiles (Like Object permissions, Field Permissions, User permissions, Tab settings, App settings, Apex class permission, visualforce permission) the same you can manage here also.


18.What are the technologies available in cloud computing other than salesforce
ANS :	Virtualization
		Service-Oriented Architecture (SOA)
		Grid Computing
		Utility Computing
*Not sure about this question no.18

19.Why is salesforce more popular?
ANS : One of the reasons that Salesforce is so popular is that it is packed with features like no other CRM software; features such as contact management, workflow creation, task management, opportunity tracking, collaboration tools, customer engagement tools, analytics and an intuitive, mobile-ready dashboard.


20. Difference Between Lookup & Master Detail Relationship in salesforce?
ANS : Value is always required in master details and there is no such a condition for lookup. If master record is deleted then its child record is also gets deleted whereas no such a criteria for lookup relationship.
	  Master/detail children inherit their permissions from their parent.
	  You can convert a master-detail relationship to a lookup relationship as long as no roll-up summary fields exist on the master object. You can convert a lookup relationship to a master-detail relationship, but only if the lookup field in all records contains a value.


21.What is web to Lead functionality in salesforce?
ANS : The process of using a website form to capture visitor information and store that information as a new lead in Salesforce. Salesforce lets you can easily create web-to-lead forms that capture information about visitors to your website.


22.What is email to case & web to case in salesforce?
ANS : 1.Email-to-Case : Automatically turn emails from your customers into cases in Salesforce to track and resolve customer cases quickly.
      2.Web To Case : Gather customer support requests directly from your company’s website and automatically generate up to 5,000 new cases a day with Web-to-Case. This can help your organization respond to customers faster, improving your support team’s productivity
	 
	 
23. What is custom metadata types in salesforce ?
ANS : Custom Metadata Type let you use records to configure your app without worrying about migrating those records to other orgs. You can deploy the records of custom metadata types from a sandbox with change sets or packaged in managed packages instead of transferring them manually.
	  With Custom Metadata Types, you can customize, deploy, package, and upgrade application metadata that you design yourself.


24. What is custom setting in salesforce ?
ANS: Custom settings are similar to custom objects. We have to create our own custom setting similar to creating a custom object.).Custom settings are similar to custom objects and enable application developers to create custom sets of data, as well as create and associate custom data for an organization, profile, or specific user. The custom setting data can then be used by formula fields, validation rules, flows, Apex, and the SOAP API.

25. What do you know about sharing rules in salesforce ?
ANS : Use sharing rules to extend sharing access to users in public groups, roles, or territories. Sharing rules give particular users greater access by making automatic exceptions to your org-wide sharing settings

26. Trigger to check duplicate Email ids on contact
ANS : 

trigger AvoidDuplicate on contact (before insert,before update)
{
   set<String> setEmail = new set<String>();
   set<String> setExistingEmail = new set<String>();

   //Add alll email in set to fetch related existing records
   for(Contact con : Trigger.new)
   {
          setEmail.add(con.email);

    }

   // get all records in database.
    for(Contact con : [select email from contact where email in : setEmail)
   {
          setExistingEmail.add(con.email);
    }

   //compare and add error if already exist
   if(Trigger.isInsert||Trigger.isUpdate)
     for(contact a:trigger.new)
     {
         if(setExistingEmails.contains(a.email))
        {
                 a.Email.adderror('This email already exists');
        }
     }
}


27. If OWD is private then who can acccess its records ?
ANS : Private : Only the record owner, and users above that role in the hierarchy, can view, edit, and report on those records.


28. Trigger to restrict insert if city = pune
ANS : 
trigger RetrictAccountforPune on Account (before insert) {
    
	for(Account acc : Trigger.new)
   		{
            if(acc.City__c != Null && acc.City__c == 'Pune'){
                acc.City__c.adderror('Pune city is not allowed.');
            }

    	}
}

29. Custom ListView in LWC
ANS : We can create/build anything in LWC.

30. Winter'21 release notes
ANS : 1.Flow Updates : now can handle deletions, debug flows as a specific user, auto flow layouts
	  2.Dynamic Forms and actions : allow you to create mini-page layouts that can be placed anywhere using the Lightning App Builder.
									allow you to show/hide actions based on the user viewing the page, for a cleaner user experience.
	  3.Optimize Lightning Page Performance-click 'Analyze' from the Lightning App Builder toolbar.
	  4.Auto Add Fields to Custom Report Types-option given in reports and dashboard user interface setting.
	  5.Community name replaced with Digital Experience Builder in setup
	  
	  
31. Where we can use Lightning Components?
ANS : We can use Lightning Components in the following places:
	Drag-and-drop Components in the Lightning App Builder and Community Builder.
	Add Lightning Components to Lightning Pages.
	Add Lightning Components to Lightning Experience Record Pages.
	Launch a Lightning Component as a Quick Action
	Override Standard Actions with Lightning Components
	Create Stand-Alone Apps
	
	
32. How do you build Lightning Components?
ANS : We can build Lightning Components using two programming models: the Lightning Web Components model, and the original Aura Components model.

33. How can you create Lightning Record Pages in Salesforce, and what are the different types
ANS : We can make use of Lightning App Builder for creating Lightning Record Pages, to create the following three types of pages:
		App Page
		Home Page
		Record Page
		
		
34. What options are there for Lightning Record Page assignment?
ANS : “Lightning Pages” can be assigned at three different levels:
		The org default
		App default – this overrides the assignment done at the org level
		App, record type, profile – this overrides the assignment done at org level and at the App level.

35. What are attributes? What are their required parameters?
ANS : Attributes are variables which are used to store values. We specify the Name, Type, Default, Description, Access in the attribute definition. Only Name and Type are required parameters in the attribute definition.

36. What are the types of attributes that we can use to store values?
ANS : We can use different types of attributes, listed below:
		String
		Integer
		Boolean
		Date
		Datetime
		Double
		Decimal
		Long
		Array
		List
		Set
		Map
		
	Standard object attribute – example: <aura:attribute name=”contactObj” type=”Contact”
	Custom object attribute – example A: aura:attribute name=”customObjectList” type=”customObject__c[]”/>OR example B: <aura:attribute name=”customObject” type=”customObject__c”/>
	
37. How can you access a value from an attribute?
ANS : Use “Value Provide” which is denoted with the symbol “v”.

38. How can you call a javascript controller action from a component markup?
ANS : We can use action provider to call a javascript controller action from the component markup

39. Which interface should you use if you want to get the id of the record from the record Detail page?
ANS : You can use the force:hasRecordId interface. Use this as opposed to the {!v.recordId} in controller we can get the id of the current record.

40. Which interface should you use if you want your component to be available for all pages?
ANS : You can use the flexipage:availableForAllPageTypes interface.

41. Which interface should you use if you want to override a standard action?
ANS : You will need to use the Lightning:actionOverride interface.

42. Which interface should you use if you want your component to be available only on the record home page?
ANS : You will need to use the flexipage:availableForRecordHome interface.

43. Which interface should you use if you want your component to be used a tab?
ANS : You will need to use the force:appHostable interface.

44. Which interface should you use if you want your component to be used a quick action?
ANS : You will need to use the force:lightningQuickAction interface.

45. How can you define field level security in Lightning Components?
ANS : You will need to use Lightning:recordForm, Lightning:recordEditForm, Lightning:recordViewForm, force:recordData.

46. What is force:recordData, and what are its advantages?
ANS : force:recordData is a standard controller of a Lightning Component. We can perform an operation such as creating a record, editing a record,deleting a record using force:recordData. If we are using force:recordData, it identifies and eliminates the duplicate request going to the server if they are requesting for the same record data (which in turn improves performance).

47. What are all component bundles we deal with while working with Lightning Component?
ANS : Following are the component bundles we deal with while working with Lightning Component.
	Component: contains markup.
	Controller: handles the client side events.
	Helper: write the common logic inside helper which can be used by different controller methods, avoiding repetition.
	Style: contains the style for the component.
	Documentation: used to record the component’s use.
	Renderer: contains the default rendering behaviour of a component.
	SVG: the icon which gets displayed before the component name in the Lightning App Builder.
	Design: control which attribute we can expose to tools like the Lightning App Builder. It helps with component re-usability.
	
48. What is Lightning:isUrlAddressable interface?
ANS : If we are navigating to a component, then the component where we are navigating to must implement lightning:isUrlAddressable interface to navigate there successfully.


49 : Is Lightning Web Components and Aura Components Work Together ?
ANS : Yes, Lightning web components and aura components work together without any issues. Aura components can contain Lightning web components, but Lightning web components can't contain aura components.


50. What is a @track decorator in js file?
ANS : It will keep track of the property’s value changes. This decorator is used to make a property private and which helps to re-render the component when the property value is changed.


51. What is a @api decorator in js file?
ANS : It is used to expose the public property of a web component. this property can use in it's parent component. 


52. What is a @wire decorator in js file?
ANS : To access Salesforce data (calling an apex method), Lightning web components use a reactive wire service.

53. Does Profile permissions override OWD ?
ANS : Profile gives you the permission too Create/Read/Edit/Delete the OBJECT as a whole. (Account, Contact, Opportunity etc). Then further the OWD restrict the access for Records belonging to that object (records not owned by you).

54. Difference Between Trigger.New and Trigger.old
ANS : 	Trigger.New: Trigger.new returns List of new records which are trying to insert/update into Database. This is available in Before Insert, Before Update, After Insert,  After Update Triggers and undelete Triggers. This list of records can only modified in Before triggers.

		Trigger.Old: Trigger.old returns List of old records which are updated with new values. These List of records already there in Database. Trigger.old available in Before update, after update, Before Delete and After Delete triggers.
		
55. How do you call apex method in lwc component?
ANS : explain the syntax : import VARIABLENAME from '@salesforce/apex/CLASSNAME.METHODNAME';

56. Have you worked on Integration in your current project? if yes then explain it.
ANS : SFDC(REST)>Mule(SOAP)>CBS

57. Which deployment tools you have worked on so far ?
ANS : ANT, Changeset, Jenkins.

58. In how many ways you can display SF records in AURA/LWC?
ANS : Datatable using custom metadata type.

59. What was the most challenging task you faced in your current project?
ANS : Explain according to your experience. In my case it was related to deployment.

60. Batch Apex methods ?
ANS : start(), Execute(), finish().
		ref : http://salesforcevenkat81215.blogspot.com/2017/06/interview-questions-on-batch-apex-in.html
	
61. What are different authentications available in Salesforce ?
62. Can we delete the SF record using Flow ? Yes
63. Trigger to calculate detail records on master object.
64. How authentication takes place while integrating with external systems?
65. Asynchronous Apex-Batch/Future
66. Custom settings and it types ?List and Heirarchy
67. Financial Cloud - Need to explain basic flow if you are/have working/worked in finacial domain project(bank)

	
	
	
	
	
	
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
	Interview Questions from Goldman Sachs
1. Walk me through basic flow of Financial Cloud > https://www.salesforce.com/products/financial-services-cloud/faq/
2. Difference between Business and Person Accounts > http://sfdcsrini.blogspot.com/2014/12/person-account-and-business-account-in.html#:~:text=The%20basic%20difference%20between%20these,on%20which%20they%20are%20based.&text=In%20Person%20account%20record%20type,related%20list%20will%20be%20present.
3. Aura Component Bundle(Events, Attributes, CSS, Aura Method)
4. How you will use workflow rule is some cases like some field is getting updated by trigger and
	then only your workflow should run. > Use Created, Every time its Edited to subsequently meet the criteria
5. What will you do if you dont want to run your workflow rule > Deactivate It
6. What is the difference between Workflow and Trigger
7. Tell me about Asynchronous Apex(Batch, Queuable)
8. I have two batch classes, say A and B and I have added B in finish() method of A. But A batch gets failed,
	Will the Batch B will run ? 
9. Security Model(OWD,Profile,Role,Sharing Rule)
10. How you will create Sharing Rule ? How I will know that my sharing rule is created. > Under OWD in Setup>Sharing Setting. You will get notification saying your sharing rule     is active.
11. What is Difference between Custom Object and Custom Settings ?
12. What will happen after you disburs the loan to a customer and he didn't show up for dues > Explain Vijay Mallya case(you have to pay
	them back else there will be cort matters or you can run away to different country) > p.s.explain this in professional way
13. Deployments > How you will resolve if you get error in deployment saying apex jobs are running? Go to deployment setting and check "Allow deployments of components when corresponding Apex jobs are pending or in progress.Caution: Enabling this option may cause Apex jobs to fail." checkbox from deployment options section
14. What is the minimum Code Coverage required for Apex Class and Apex Trigger in production deployment ? 75% for Apex and 1% for Trigger
15. Will the production and sandbox orgs configurations are different after taking refresh from production ? No, only some data will differ
16. Which Components you can edit directly in production ? VisualforcePage, Aura Component
17. How will you resolve the deployment issue of code coverage, say you have 90% coverage for a class,
	and at the time of production validation it is showing 35% ? Have one sandbox instance from production and try to run the apex test class and resolve the issue.
18. What is Package.xml in package ? Its the Markup of your components from Org.
19. Approval Process > Explain in detail> Entry Criteria, Actions
20. Do you feel okay to work in any other technology than Salesforce if you get a chance ? Yes/No
	
