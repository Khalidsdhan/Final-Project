Put - applyLegalActionForTaxEvasion __ TaxReportsService 

Put - applyTwoMonthLatePenalty __ TaxReportsService 

Put - applyLegalActionForTaxEvasion __ TaxReportsService 

Put - approveTaxReportStatus       __ AuditorService 

Put - rejectTaxReportStatus __ AuditorService 

Put -bulkApproveReports        __ TaxReportsService 

Get - getLatestReportByAuditor       __ TaxReportsService        
            
Get -getUnpaidDueTaxReports __ TaxReportsService 

Get -getProductsByBarcode __ ProductService

Get -getReportsByAuditor        __ TaxReportsService 
        
Get -getReportCountByStatus   __ TaxReportsService 

Get -getUnapprovedTaxReports        __ TaxReportsService 
