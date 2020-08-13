📅 What's new on v19.12.16 :-
👉 All casenote link to casenote after double click on it.
👉 System not allow to create same doctor within same casenote, one doctor one casenote.
👉 Scan to file button move out from other button.
👉 add alert for Co-Payment and non-cover (For Mdm Ying)
👉 change "Baby treatment" to Nationality when click lookup Nationality button.
👉 Fix Foreign Patient Percentage error for BMC Miri.
NOTE: Lab Result invalidated still not blocking yet.


📅 HIS ChangeLog for v19.11.25
👉 Fix Price Code won't retrieve on casenote.
👉 Fix some major bug.

📅 HIS ChangeLog for v19.11.25
👉 Delete Xray report which want to cancel.
👉 Support A08 Patient Demographic Change

📅 2019.11.11~24 HIS ChangeLog 
👉 Fix memory error when print Ledger summary
👉 Add default template for Procedure Note

What's I'm test so far with v19.11.11 ?
- Physiotherapy Summary Report now can follow date range select by user.
- Edit Template and Save as template button relocate to new location.


📅 HIS ChangeLog for v19.11.4
👍 Speed improvement for loading Statement/Report
👉 Fixed Patient Label Position if greater than 3
👉 Add permission allow to print/view for Procudure Note
👉 Fix Discount missing on Statement (need feedback from other centre)

📅 31/10 HIS Change Log 
👉 Remove encryption pop up message box.

📅 07/14~27/10 HIS Change Log 
👉 Fixed IC Card Reader issues (v19.10.16 32bit or above)
👉 Fixed POS Receipts (v19.10.16 32bit or above)
🐛 Bring Statement Preview Page to front


📅 HIS Weekly Update Status for 7/10~13/10
🐛 Fixed infant one day age can't retrieve refer range correctly (for Borneo Medical Centre lab report)


📅 HIS Weekly Update Status for 30/10~06/10
👉 Add exclude discontinue item on negative quantity form.
👉 Add function for call selling price when set patient type to Lab for Tina. (v19.10.3)


📅 HIS Weekly Update Status for 23/09~29/09
👉 Add Stock Summary by Department
👉 Add [is Doctor Account] option in Supplier Master Files
👉 Add Skip Docotor Account option in Supplier Aging Form for skip doctor account in one click.


📅 HIS Weekly Update Status for 02/09~22/09
👉 Add category and dianogsis on physio report.
👉 Add consent letter
👉 Stock card balance and on hand improvement by Department No.


📅 HIS Bi-Weekly Update Status for 19/08~01/09
👉 fix casenote not show issue
👉 Add back old version for Medication List
	  

📅 HIS Bi-Weekly Update Status for 05/08~18/08
👉 Add Pharmacy Wait list Tran date
👉 Add Admission Form Print 2 page with one click
👉 Add Casenote Procedure report 


📅 HIS Weekly Update Status for 29/07~/08
👉 Fix All patient in Pharmacy Wait List option
👉 Add Administration Form as Tony request


📅 HIS Bi-Weekly Update Status for 15/07~28/07
👉  Add In-Patient and Out-Patient on Pharmacy Wait List.
👉👉  Now you can set which department belong to In-Patient or Out-Patient by department number.
👉  Exclude Package item on Doctor Commision Report
👉  Seperate Dept No. and Store No on in-patient medication list
👉👉  fix Statement Department Description issues.
👉  Add reference number on official receipt only for SarawakPay payment


📅 HIS Weekly Update Status for 08/07~14/07
👉 Remove auto lock
👉 Unlink dept and StoreNo in Purchase Invoice


📅 HIS Weekly Update Status for 01/07~07/07
👉 Fix change debtor account issues.
👉 Fix change customer account issues.


📅 HIS Weekly Update Status for 24/06~30/06
👉 Fix Patient Label can't print on other paper size.
👉 This week don't have any released, fix some bug on database.
 

📅 HIS Weekly Update Status for 17/06~23/06
👉 Fix Counter sales time on receipts issues
👉 Set X-Ray report print with Crystal rumtime as default.


📅 HIS Weekly Update Status for 02/06~16/06
👉 Add Ward Code & Ward Class on Bed No Configuration
👉 Add TSC Scan To Files.


📅 HIS Weekly Update Status for 27/05~01/06
👉 Medicine Label 
👉 Block Lab report on casenote if not validated 


📅 HIS Weekly Update Status for 13/05~19/05
👉 Patient Registration for SMRP 2.0
       - Speciality Code updated
	   - Add Sample for JsonFile (no complete yet)
	   
	   
📅 HIS Weekly Update Status for 06/05~11/05
👉 Patient Registration for SMRP 2.0
       - Add day Care otpion
	   - Auto select for speciality when choose sub-speciality

📅 HIS Weekly Update Status for 06/05~11/05
👉 Patient Registration for SMRP 2.0
       - Add day Care otpion
	   - Auto select for speciality when choose sub-speciality 
	   
📅 HIS Weekly Update Status for 29/04~05/05
👉 Add Discharge Summary & Death Registration
👉 Add configuration for discipline, speciality and sub-speciality for Out-patient / Day Care

📅 HIS Weekly Update Status for 22~26/04
👉 Add Obstetric Form (v19.4.25)
👉 Add SMRP 2.0 Configuration
      - Discipline and Speciality
      - Facility Code and Baby Treatment
      - Labour Attendant List

📅 HIS Weekly Update Status for 15~20/04
👉 Mapping and implement SMRP 2.0
🐛 Still under investigation for system print receipt suddenly.

📅 HIS Weekly Update Status for 08/04~13/04
👉 Add Bread And Food Price Tag for RMC.
👉 Fixed POS Sales Issues for BMC.

🌄 Good Morning, everyone....
📝HIS summary for Jan-March 2019.

*WHAT DONE SO FAR?*
Need place the link on casenote as Tony request.
👉 Upload scanned report, need to be sorted by Registration Number (user experience improvement)
👉 Restrict user view on remarks on Main Stock Files.
👉 Consignment Item.
👉 Fix delivery order error when change supplier name (report by Mr Teng from Bintulu).
👉 Lock casenote automatically after post bill (Medical Certificate and Refer Letter not yet).
👉 Foreign Worker Report (99% done).
👉 Price tag for meal (just like price tag for bed) (requested by RMC dietician)
👉 Refer Letter and Medical Certificate need auto lock after post bill as same as casenote (security improvement).
👉 Warning message popup if bill have zero amount. (solution for refund issues)
👉 Auto enable always discount when post bill (no include xray department and doctor fees) for certain debtor account like in/out patient cash account.
👉 Standardize 1 price & apply discount for patient pay by cash (insurance co format compliance)
👉 We need show ONE price to Insurance Company and always give discount to Patient who pay by cash. (discount percentage set on Customer Master File)

*WHAT NOT DONE ?*
ℹ Need add page number on every page, remove empty part at bottom of page 2 onward (For itemised bill with receipt).
ℹ SMRP 2.0 (deadline May 2019, please implement export file to JSON format)
ℹ Pharmacy label & patient label (still under progress, email sample and softcopy to Mr Yeo already)


  
  
  
