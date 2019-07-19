# USTreasuryData  

Treasury debt files
Nancy Hammond
July 18, 2019
nahammond@gmail.com
231.714.7184

Data on net purchases of US Treasury securities on other information

1. Financial Accounts of the United States
The online Financial Accounts of the United States Guide is an interactive guide allowing you to drill down into series data sources and series calculations.  
Table descriptions are available for each table describing key features.  https://www.federalreserve.gov/apps/fof/FOFTables.aspx
See the series calculation and underlying components for L.210 line 1: https://www.federalreserve.gov/apps/fof/SeriesAnalyzer.aspx?s=FL313161105&t=L.210&suf=Q
of the United States 
Quarterly Financial Accounts series are available back to 1951:Q4.

See table description entry for F.210, L.210: https://www.federalreserve.gov/apps/fof/Guide/z1_tables_description.pdf
F.210, L.210: Treasury Securities
U.S. Treasury securities are marketable and nonmarketable securities issued by the Department of the Treasury,
net of premiums and discounts. Because this instrument excludes Treasury securities held as investments of federal
government accounts and those issued by federal agencies under special financing authorities, it represents total
borrowing from the public plus nonmarketable securities issued to the federal government employee retirement
funds. Nonmarketable securities issued to the federal government employee retirement funds are considered part
of intergovernmental holdings in U.S. Treasury Department reports, but are treated as public in the financial
accounts. Data on all U.S. Treasury securities outstanding, including intragovernmental holdings, can be found
in the Monthly Statement of the Public Debt published by the Treasury.
Marketable Treasury securities consist of Treasury bills (maturity of 1 year or less), Treasury notes (maturity
of 2 to 10 years), Treasury bonds (maturity of 10 to 30 years), securities issued by the Federal Financing Bank,
and Treasury inflation-protected securities, or TIPS. Marketable Treasury securities are very liquid and are heavily
traded on the secondary market.
Nonmarketable Treasury securities are issued for special purposes or to particular groups of investors and cannot
be traded in the secondary market. These securities include U.S. Savings Securities, State and Local Government
Series, Domestic Series, Foreign Series, Rural Electrification Administration Series, Government Account Series,
HOPE Bonds (securities issued for the HOPE for Homeowners program beginning in 2008), and nonmarketable
securities issued to the federal government employee retirement funds. U.S. Savings Securities are comprised
of U.S. savings bonds, U.S. individual retirement bonds, U.S. retirement plan bonds, U.S. savings stamps, and
matured U.S. savings securities.
Data on holdings of Treasury securities by most sectors are compiled from available data. Net purchases by
the household and nonprofit organizations sector are calculated residually from total issuance; however, all U.S.
savings securities are assets of the household sector. Outstanding holdings are shown at market value for some
sectors, including the household and nonprofit organizations sector, (prefixed with LM on the tables) while other
sectors are shown at book value (prefixed with FL on the tables). The discrepancy series on the level table shows
the accumulated valuation difference between issuance and holdings. Nonmarketable treasury securities do not
have a market value.

The series structure page on the Financial Accounts Guide has information on FA, FL and unadjusted transactions:
https://www.federalreserve.gov/apps/fof/SeriesStructure.aspx
If not available in the download, the FV other changes in volume series can be computed (see series structure link above)

% FA313161105.Q Federal government; Treasury securities; liability	
% FA313161205.Q Federal government; marketable Treasury securities; liability	
% FA313161110.Q Federal government; Treasury bills; liability	
% FA313161275.Q Federal government; other marketable Treasury securities; liability	
% FA313161283.Q Federal government; long-term marketable Treasury securities issued to the Civil Service Retirement Fund through the Federal Financing Bank; liability
% Currency	Currency	Currency	Currency	Currency
% 1000000	1000000	1000000	1000000	1000000
% USD	USD	USD	USD	USD

The Board only disaggregates to "total marketable securities" and "Treasury bills"
Column 2 of the Z1 files are total marketable securities,
Column 3 of the Z1 files are Treasury bills

The US Treasury provides data on: 
Total Outstanding (bln)	<=1 Year, 1-5 Years, 5-10 Years, 10-20 Years, 20+ Years, andAvg Length (months)
 
2. US Treasury: in their Quarterly Data Release 
The data source of  quarterly net borrowing data is the US Treasury: in their Quarterly Release Reports
The Treasury QDR goes back to 1976 in pdf tables but excel file  has only 2000 to 2019.
The most recent file includes net borrowing data from 2001Q1 to 2019Q4
https://www.treasury.gov/resource-center/data-chart-center/quarterly-refunding/Pages/Latest.aspx
Click on last line Quarterly Release Data: 2019 - 2nd Quarter to download file
Net borrowing data are available in bar charts in pdf files, 1976-2000, one file for each quarter
https://www.treasury.gov/resource-center/data-chart-center/quarterly-refunding/Pages/qrc-index.aspx
But only label the bar charts with total debt
he Treasury QRD goes back to 1976 in pdf tables but excel file has only 2000 to 2019.

3. Another source for long data series is FRED https://fred.stlouisfed.org/

Source
The source for both quarterly net borrowing data in the US Treasury Quarterly Release Reports and the FRB  Z1 series for Table 210
Monthly Statement of the Treasury (MTS) and Monthly State of the Public Debt (MSPD). (Note: However, I have not been able to confirm they
are the same numbers.) 
Unadjusted transactions (quarterly net borrowing) are the change in the level outstanding.  F.210 shows seasonally adjusted annualized transactions.
Financial Accounts data for Treasuries outstanding are from the .   See individual series descriptions for more detail.
The Financial Accounts definition of public debt differs slightly from that of the Treasury, mainly because nonmarketable securities issued to 
federal government employee retirement funds are considered part of intergovernmental holdings in U.S.  Treasury Department reports, but are 
treated as public debt in the Financial Accounts. A short FEDS Note paper describes these differences in detail: 
https://www.federalreserve.gov/econresdata/notes/feds-notes/2015/federal-debt-in-the-financial-accounts-of-the-united-states-20151008.html

 
The Financial Accounts does not use the QRD, thus I am not familiar with any conceptual differences.  Please refer to the FEDS note link below for differences between Financial Accounts and Treasury Dept. measures of public debt.
Matt Hoops matthew.c.hoops@frb.gov
Financial Analyst
Federal Reserve Board
Flow of Funds Section
 

NH: I am not able to verify if US Treasury: in their Quarterly Release Reports (QDR) quarterly net borrowing data is the the same as quarterly differences or yoy quarterly differences of FRB Z1 series Table 210
I computed both yoy quarterly differences and first quarterly differences of securities in the L210 table.
These numbers for net borrowing for bills and total marketable securities from L210 (if this is the way to do it)
are not the same as those in the QRD. Looks like BOG Z1 series provides numbers only for 'bills', 'other', and 'total marketable securities'.

NH: It would be great if there are US Treasury QDR bond net borrowing data back to 1976, numbers finer than just total.
Must exist because the bar chart shades out bills, 2-5 yr notes,. bonds etc, but only labels the bar for each quarter 
with total debt.  
Trying to find out where this is:
"Unadjusted transactions (quarterly net borrowing) are the change in the level outstanding. 
The discrepancy series on the level table shows the accumulated valuation difference between issuance and holdings."
I didn't find a "discrepancy series " in the L210 download.

The comparisons of these methods to the QDR values for net borrowing of total marketable securities and Treasuty
bills are below. 

L210 Net borrowing Quarterly yoy difference	
Date 	Total   Total       Bills    Other      Long term for ret. runds
Non+marketable  Marketable			
2018Q1	2991256	1756351	1685636	70716	0
2018Q2	534755	38583	-424219	461006	1796
2018Q3	-452862	380307	-14316	394623	0
2018Q4	783596	133799	-247104	380903	0
2019Q1 	-2122599	-472765	-668990	196224	0
L210 Net borrowing Quarterly first differences	
Date 	Total   Total       Bills    Other      Long term for ret. funds
Non+marketable  Marketable			
2018Q1	3167075	1860179	1338375	521805	0
2018Q2	-1636626	-943350	-1648158	709279	-4472
2018Q3	-7432	-83944	369824	-458240	4472
2018Q4	-739421	-699086	-307145	-391941	0
2019Q1	260880	1253615	916489	337126	0
US Treasury QDR				
Date Bills	Total marketable			
2018Q1	154	270.2			
2018Q2	333	458.5			
2018Q3	-131	24.1			
2018Q4	82	287.2			
2019Q4	100.1	335.1			
Transactions F210				
2018Q1	2827261	2055883	1514846	541038	0
2018Q2	1190635	1112533	-133312	1250317	-4472
2018Q3	1183203	1028589	236512	792077	0
2018Q4	443782	329503	-70633	400136	0
2019Q1	704662	1583118	845856	737262	0
Levels  L210				
2018Q1	2827261	2055883	1514846	541038	0
2018Q2	1190635	1112533	-133312	1250317	-4472
2018Q3	1183203	1028589	236512	792077	0
2018Q4	443782	329503	-70633	400136	0
2019Q1	704662	1583118	845856	737262	0
