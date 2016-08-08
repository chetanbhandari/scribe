### To get CRM objects using query criteria 
- Get all Accounts:  HTTP GET [scribe-host]/scribe/object/account
- Get all Accounts by id: HTTP GET [scribe-host]/scribe/object/account/Id='001A000000E9ZEuIAN'
- Get all Accounts by name: HTTP GET [scribe-host]/scribe/object/account/name='Dickenson plc'
- Get all Accounts from "Electronics" Industries: HTTP GET [scribe-host]/scribe/object/account/Industry="Electronics"
- Get all Accounts from "Electronics" or "Energy" industry:  HTTP GET	[scribe-host]/scribe/object/account/Industry="Electronics"|Industry="Energy"
- Get all Accounts from "Electronics" industry and from "TX" state: HTTP GET	[scribe-host]/scribe/object/account/Industry='Electronics'&BillingState='TX'
- Get all Accounts from "Electronics" industry and from "TX" state and "Hot" rating: [scribe-host]/scribe/object/account/Industry="Electronics"&BillingState="TX"&Rating="Hot"
- Get all Accounts from "TX" or "KS" states:  HTTP GET [scribe-host]/scribe/object/account/BillingState='TX'|BillingState='KS'
- Get all Accounts with a type:  HTTP GET [scribe-host]/scribe/object/account/type='Customer - Direct'
- Get an account with name like "Genepoint":  HTTP GET [scribe-host]/scribe/object/account/name like '%Genepoint%'