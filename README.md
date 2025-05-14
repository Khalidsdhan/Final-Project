applyLegalActionForTaxEvasion __ TaxReportsService 

applyTwoMonthLatePenalty __ TaxReportsService 

applyLegalActionForTaxEvasion __ TaxReportsService 

 approveTaxReportStatus       __ AuditorService 

rejectTaxReportStatus __ AuditorService 


bulkApproveReports        __ TaxReportsService 

 getLatestReportByAuditor       __ TaxReportsService 
 

 changeTaxReportStatus      __ TaxReportsService  
           
            
getUnpaidDueTaxReports __ TaxReportsService 

getProductsByBarcode __ ProductService

getReportsByAuditor        __ TaxReportsService 
        
getReportCountByStatus   __ TaxReportsService 

getUnapprovedTaxReports        __ TaxReportsService 
