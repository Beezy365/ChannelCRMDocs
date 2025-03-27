
COMPANY
		
| Fieldname|Description|Keyfield|
|--------|:-------:|--------|
| company.name | | name |
| company.department | | 		
| company.street | | name + zip + street
| company.zip | | Postnummer	name + zip
| company.city | | By	
| company.zipcity | | Postnummer By	
| company.state | | 
|company.country | | 
company.relationprim		
company.relationsec		
company.vat	CVR Number	Vat
company.phone		Phone
company.fax		
company.mail		
company.financedepartment		
company.financestreet		
company.financezip		
company.financecity		
company.financestate		
company.financecountry		
company.financephone		
company.financefax		
company.financemail		
company.web		
company.kam		
company.financekey	CustomerNumber	financekey
company.otherkey		
company.description		
company.pno		Vat+Pno
companyudef.<name of udef>	Custom Fields. Use name of variable.	

| Command | Param count | Parameters |
|---------|:-----------:|------------|
| REBUILD | 9 | Source DSN, user, password and prefix (remember ODBC: for ODBC databases), target DSN, user, password, prefix, and A for Ansi or U for Unicode |
| UPGRADE70 | 4 | DSN, user, password, and prefix |
| CREATE7 |16 | DSN, User, Password, Prefix, A for Ansi/ U for unicode target, [Contact name, Country id, First name, Last name, User ID, Password, Serialnumber] |
| IMPORTINITIAL | 5 | DSN, user, password, prefix, name of the section in SOTABLES.INI to import tables for |
| FREETEXTINDEX | 4 | DSN, user, password, and prefix |
| KILLDATABASE | 4 | DSN, user, password, and prefix |
| MAINTENANCE | | |
| IMPORT | 5 | DSN, user, password, prefix, name, and path to file |
| EXPORT | 5 | DSN, user, password, prefix, name, and path to file |
| REBUILDSAINT | 4 | DSN, user, password, and prefix |
| NEXTMILESTONE | 4 | DSN, user, password, and prefix |
| SYNCUSERS | 4 | DSN, user, password, and prefix |
| RECALCSEQUENCE | 4 | DSN, user, password, and prefix |
| RUNCHECKS | 5 | DSN User, Password, Prefix, Semicolon-separated list of Check names |
| RUNSQL | 5 | DSN, user, password, prefix, name, and path to SQL query file |
