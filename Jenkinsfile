node {

 
    stage('Deploy Dacpac to SQL Server') {
     
        echo "Deploy Dacpac to SQL Server"
     
      
        bat "\"C:\\Program Files (x86)\\Microsoft Visual Studio\\2022\\Community\\Common7\\IDE\\Extensions\\Microsoft\\SQLDB\\DAC\\qlpackage.exe\" /Action:Publish /SourceFile:\"C:\\Users\\SQA\\AppData\\Local\\Jenkins\\.jenkins\\workspace\\SONDA\\SONDA_DB_Build\\CICDSondaBD\\bin\\Debug\\CICDInterfacesBD.dacpac\" /TargetServerName:(local) /TargetDatabaseName:SWIFT_EXPRESS_R"
    }
}
