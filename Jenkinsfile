node {

 
    stage('Deploy Dacpac to SQL Server') {
     
        echo "Deploy Dacpac to SQL Server"
     
      
bat "\"sqlpackage.exe\" /SourceFile:\"C:\\Users\\SQA\\AppData\\Local\\Jenkins\\.jenkins\\workspace\\SONDA\\SONDA_DB_Build\\CICDSondaBD\\bin\\Debug\\CICDSondaBD.dacpac\" /Action:Publish /TargetServerName:\"localhost\" /TargetDatabaseName:\"SWIFT_EXPRESS_R\" /TargetUser:\"sa\" /TargetPassword:\"Sq12021\" /Variables CICDInterfacesBD=\"SWIFT_INTERFACES_R\" CICDSondaBD=\"SWIFT_EXPRESS_R\" "
     
     
     
     
    }
}
