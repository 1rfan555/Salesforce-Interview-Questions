# Salesforce-Interview-Questions
Salesforce Interview Questions

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


5. permission sets and explain its uses?
ANS : A permission set is a collection of settings and permissions that give users access to various tools and functions. 
	  The settings and permissions in permission sets are also found in profiles, but permission sets extend users' functional 
	  access without changing their profiles.


6.difference between salesforce profile and permission sets
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


8.approval process in salesforce and give me one use case?
ANS : An approval process is an automated process an organization can use to approve records in Salesforce. In an approval process, you specify: The steps necessary for a record to be approved and who approves it at each step.
	  To submit a record into the approval process, the user has to manually click on the Submit For Approval button.
	  The disadvantage of this manual process is that a user can forget to click on the Submit For Approval button. It will not auto-send records into the approval process, and therefore, it may cause an issue sometimes.


9.What is report type?
ANS : In Salesforce, reports are created by first selecting a report type. A report type is a template which defines the objects and fields that will be available to use in the report you create.


10.Which reports support dashboards
ANS : 1.Tabular(supported in dashboard only if rows are limited (maximum 10)) – This is the simplest of reports and is suited to just showing lines of data and nothing else. If you just want to show data with no preference to seeing totals, calulations or groups of data then this is the report for you just to keep it simple. It is also best to use this report type if you are planning to use it to export data. 
	  2.Summary(supported) – As soon as you click “Group by this field”, you will turn the report into a summary report. Summary reports are probably the most commonly used and are great for showing groups of data e.g. If you want to see your recent accounts opportunities they will be grouped by account and you can see each opportunity under the account. From then you can do calculations, you can see the total amount of sales under an account, you can see the maximum, minimum and also average amount. You can also sub group fields by dragging them under the initial group. 
	  3.Matrix(supported) – Matrix reports are very similar to Summary but they allow you to group by rows as well as columns to see different totals. Matrix reports aren’t commonly used unless you have to display lots of complex data. 
	  4.Joined Reports(supported) – Joined reports allow you to create two separate reports so that you can compare data. Again not most commonly used.


11.What are sharing settings in salesforce?
ANS : Salesforce provides organization-level sharing settings to set the baseline access for the records, so that you can set the sharing separately for every object. If you want to restrict your users' access to data of an object, set the object's Default Internal Access or Default External Access setting as private.


12. Difference between summary and matrix report in salesforce?
ANS : In short if you need to do the sum or calculate the average on even one parameter then summary report is the answer. Matrix Reports:- These reports are used when the requirement is to summarize both the Axis i.e. when requirement is to group both Rows as well as Columns.


13. process builder& need of process builder?
ANS : Process Builder Salesforce is basically an automated tool that allows you to control the order of actions or evaluate the criteria for a record. It has eight actions associated with it: Creating records: This will allow you to create a new record and add different field values for it. We can also acheive operations by process builder instead of writing code.


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


21.what is web to Lead functionality in salesforce?
ANS : The process of using a website form to capture visitor information and store that information as a new lead in Salesforce. Salesforce lets you can easily create web-to-lead forms that capture information about visitors to your website.


22.What is email to case & web to case in salesforce?
ANS : 1.Email-to-Case : Automatically turn emails from your customers into cases in Salesforce to track and resolve customer cases quickly.
      2.Web To Case : Gather customer support requests directly from your company’s website and automatically generate up to 5,000 new cases a day with Web-to-Case. This can help your organization respond to customers faster, improving your support team’s productivity
