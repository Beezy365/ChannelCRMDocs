**ChannelCRM template variables**

Updated : 27-07-2024

**Remember to put 0 infront and behind the name of the variable**

| **COMPANY**               |                             |                                                          |
|---------------------------|-----------------------------|----------------------------------------------------------|
| **Variable**              | **Value**                   | **Description**                                          |
| Companyname               | 0companyname0               | Name field on Company                                    |
| Companycity               | 0companycity0               |                                                          |
| companycountry            | 0companycountry0            |                                                          |
| companydepartment         | 0companydepartment0         |                                                          |
| Companystate              | 0companystate0              |                                                          |
| Companystreet             | 0companystreet0             |                                                          |
| Companyzip                | 0companyzip0                |                                                          |
| companyfinancekey         | 0companyfinancekey0         |                                                          |
| Companymail               | 0companymail0               |                                                          |
| Companyphone              | 0companyphone0              |                                                          |
| Companyvat                | 0companyvat0                |                                                          |
| Companyweb                | 0companyweb0                |                                                          |
| companyotherkey           | 0companyotherkey0           |                                                          |
| companyfinancekey         | 0companyfinancekey0         |                                                          |
| companyfinancedepartment  | 0companyfinancedepartment0  |                                                          |
| companyfinancestate       | 0companyfinancestate0       |                                                          |
| companyfinancestreet      | 0companyfinancestreet0      |                                                          |
| companyfinancezip         | 0companyfinancezip0         |                                                          |
| companyfinancefax         | 0companyfinancefax0         |                                                          |
| companyfinancemail        | 0companyfinancemail0        |                                                          |
| companyfinancephone       | 0companyfinancephone0       |                                                          |
| companyudef+\<fieldname\> | 0companyudef+\<fieldname\>0 | Fieldname should be lowercase letter, without any spaces |

| **CONTACT**                 |                            |                 |
|-----------------------------|----------------------------|-----------------|
| **Variable**                | **Value**                  | **Description** |
| contactfirstnames           | 0contactfirstnames0        |                 |
| contactlastnames            | 0contactlastnames0         |                 |
| contactfullname             | 0contactfullname0          |                 |
| contactfriendlyname         | 0contactfriendlyname0      |                 |
| Contacttitle                | 0contacttitle0             |                 |
| contactsalutation           | 0contactsalutation0        |                 |
| contactphonedirect          | 0contactphonedirect0       |                 |
| contactphonemobile          | 0contactphonemobile0       |                 |
| contactphonehome            | 0contactphonehome0         |                 |
| contactemailaddress1        | 0contactemail10            |                 |
| contactemailaddress2        | 0contactemail20            |                 |
| contactemailaddresspersonal | 0contactemailpersonal0     |                 |
| Contactean                  | 0contactean0               |                 |
| contactudef+\<fieldname\>   | 0contactudef+\<fieldname\> |                 |

**  
**

| **OPPORTUNITY**                                    |                                |                 |
|----------------------------------------------------|--------------------------------|-----------------|
| **Variable**                                       | **Value**                      | **Description** |
| opportunitynumber                                  | 0opportunitynumber0            |                 |
| opportunitycurrency                                | 0opportunitycurrency0          |                 |
| opportunityudef+\<fieldname\>                      | 0pportunityudef+\<fieldname\>0 |                 |
| opportunityudef+\<fieldname\>.employee.email1      |                                |                 |
| opportunityudef+\<fieldname\>.employee.phonedirect |                                |                 |
| opportunityudef+\<fieldname\>.employee.phonemobile |                                |                 |

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>QUOTE</strong></th>
<th></th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Variable</strong></td>
<td><strong>Value</strong></td>
<td><strong>Description</strong></td>
</tr>
<tr class="even">
<td>quotename</td>
<td>0quotename0</td>
<td></td>
</tr>
<tr class="odd">
<td>quotebodytext1</td>
<td>0quotebodytext10</td>
<td></td>
</tr>
<tr class="even">
<td>quotebodytext2</td>
<td>0quotebodytext20</td>
<td></td>
</tr>
<tr class="odd">
<td>quotenumber</td>
<td>0quotenumber0</td>
<td></td>
</tr>
<tr class="even">
<td>quotevalidfrom</td>
<td>0quotevalidfrom0</td>
<td></td>
</tr>
<tr class="odd">
<td>quotevalidto</td>
<td>0quotevalidto0</td>
<td></td>
</tr>
<tr class="even">
<td><p>quotepricesum</p>
<p>quotepricesumR</p></td>
<td>0quotepricesum0<br />
0quotepricesumR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="odd">
<td>quotepricenetsum quotepricenetsumR</td>
<td><p>0quotepricenetsum0</p>
<p>0quotepricenetsumR0</p></td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="even">
<td>quotetaxsum<br />
quotetaxsumR</td>
<td>0quotetaxsum0<br />
0quotetaxsumR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="odd">
<td>quotediscountsum<br />
quotediscountsumR</td>
<td>0quotediscountsum0<br />
0quotediscountsumR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><strong>QUOTELINES</strong></th>
<th></th>
<th></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><strong>Variable</strong></td>
<td><strong>Value</strong></td>
<td><strong>Description</strong></td>
</tr>
<tr class="even">
<td>quotelineidentifier</td>
<td>0quotelineidentifier0</td>
<td></td>
</tr>
<tr class="odd">
<td>quotelinedescription</td>
<td>0quotelinedescription0</td>
<td></td>
</tr>
<tr class="even">
<td>quotelinelongdescription</td>
<td>0quotelinelongdescription0</td>
<td></td>
</tr>
<tr class="odd">
<td>quotelinecurrency</td>
<td>0quotelinecurrency0</td>
<td></td>
</tr>
<tr class="even">
<td>quotelinerank</td>
<td>0quotelinerank0</td>
<td>Position in quote</td>
</tr>
<tr class="odd">
<td>quotelineprice<br />
quotelinepriceR</td>
<td>0quotelineprice0<br />
0quotelinepriceR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="even">
<td>quotelinequantity<br />
quotelinequantityR</td>
<td>0quotelinequantity0<br />
0quotelinequantityR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="odd">
<td>quotelinediscount<br />
quotelinediscountR</td>
<td>0quotelinediscount0<br />
0quotelinediscountR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="even">
<td>quotelinediscountaspercent<br />
quotelinediscountaspercentR</td>
<td>0quotelinediscountaspercent0<br />
0quotelinediscountaspercentR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="odd">
<td>quotelinepricenet<br />
quotelinepricenetR</td>
<td>0quotelinepricenet0<br />
0quotelinepricenetR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="even">
<td>quotelinetax<br />
quotelinetaxR</td>
<td>0quotelinetax0<br />
0quotelinetaxR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="odd">
<td>quotelineunitprice<br />
quotelineunitpriceR</td>
<td>0quotelineunitprice0<br />
0quotelineunitpriceR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
<tr class="even">
<td>quotelineunitpriceorigin<br />
quotelineunitpriceoriginR</td>
<td>0quotelineunitpriceorigin0<br />
0quotelineunitpriceoriginR0</td>
<td><p>2 decimal</p>
<p>Rounded value</p></td>
</tr>
</tbody>
</table>

| **PRODUCT**               |                             |                            |
|---------------------------|-----------------------------|----------------------------|
| **Variable**              | **Value**                   | **Description**            |
| productdescription        | 0productdescription0        |                            |
| productlongdescription    | 0productlongdescription0    |                            |
| productunit               | 0productunit0               |                            |
| productgroup              | 0productgroup0              |                            |
| productimage              | 0productimage0              | Product Image if available |
| productudef+\<fieldname\> | 0productudef+\<fieldname\>0 |                            |

| **ACTIVITY**        |                       |                 |
|---------------------|-----------------------|-----------------|
| **Variable**        | **Value**             | **Description** |
| activitysubject     | 0activitysubject0     |                 |
| activitydescription | 0activitydescription0 |                 |
| activitydescription | 0activitydescription0 |                 |
| activitystart       | 0activitystart0       |                 |
| activitystartutc    | 0activitystartutc0    |                 |
| activitystarttime   | 0activitystarttime0   |                 |
| activitystartdate   | 0activitystartdate0   |                 |
| activityfinish      | 0activityfinish0      |                 |
| activityfinishutc   | 0activityfinishutc0   |                 |
| activityfinishtime  | 0activityfinishtime0  |                 |
| activityfinishdate  | 0activityfinishdate0  |                 |
| Activitylocation    | 0activitylocation0    |                 |

| **OWNER (KAM)** |                   |                 |
|-----------------|-------------------|-----------------|
| **Variable**    | **Value**         | **Description** |
| userfirstnames  | 0userfirstnames0  |                 |
| userlastnames   | 0userlastnames0   |                 |
| userfullname    | 0userfullname0    |                 |
| Userjobtitle    | 0userjobtitle0    |                 |
| usermail1       | 0usermail10       |                 |
| usermail2       | 0usermail20       |                 |
| userphonemobile | 0userphonemobile0 |                 |
| userphonedirect | 0userphonedirect0 |                 |
| userunitname    | 0userunitname0    |                 |
| userstreet      | 0userstreet0      |                 |
| userzip         | 0userzip0         |                 |
| usercity        | 0usercity0        |                 |
| userstate       | 0userstate0       |                 |
| uservat         | 0uservat0         |                 |

| **CURRENT USER/EMPLOYEE** |                    |                 |
|---------------------------|--------------------|-----------------|
| **Variable**              | **Value**          | **Description** |
| cuserfirstnames           | 0cuserfirstnames0  |                 |
| cuserlastnames            | 0cuserlastnames0   |                 |
| cuserfullname             | 0cuserfullname0    |                 |
| cuserjobtitle             | 0cuserjobtitle0    |                 |
| cuseremail1               | 0cuseremail10      |                 |
| cuseremail2               | 0cuseremail20      |                 |
| cuserphonemobile          | 0cuserphonemobile0 |                 |
| cuserphonedirect          | 0cuserphonedirect0 |                 |
| Cuserunitname             | 0cuserunitname0    |                 |
| Cuserstreet               | 0cuserstreet0      |                 |
| Cuserzip                  | 0cuserzip0         |                 |
| Cusercity                 | 0cusercity0        |                 |
| Cuserstate                | 0cuserstate0       |                 |
| Cuservat                  | 0cuservat0         |                 |

| **PROJECT**               |                             |                 |
|---------------------------|-----------------------------|-----------------|
| **Variable**              | **Value**                   | **Description** |
| projectcity               | 0projectcity0               |                 |
| projectnumber             | 0projectnumber0             |                 |
| projectcountry            | 0projectcountry0            |                 |
| projectstate              | 0projectstate0              |                 |
| projectstreet             | 0projectstreet0             |                 |
| projectname               | 0projectname0               |                 |
| projectzip                | 0projectzip0                |                 |
| projectudef+\<fieldname\> | 0projectudef+\<fieldname\>0 |                 |

| **COMMANDS**  |                 |                                                                                                                                                                                                                                                                                   |
|---------------|-----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Variable**  | **Value**       | **Description**                                                                                                                                                                                                                                                                   |
| rankfirstline | 0rankfirstline0 | If this code is inserted in the first cell of the table, the table will only show the first line of the quote. This is used to highlight the first line in the quote                                                                                                              |
| alternativX   | 0alternativeX0  | If this code is inserted in the first cell of the table, the table will only show the quotelines maked with alternativ \> 0. If lines are marked with alternative 1 then the code is 0alternative10. The table will be removed if there are no lines marked with the alternative. |
|               |                 |                                                                                                                                                                                                                                                                                   |
