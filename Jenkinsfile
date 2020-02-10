@Library('shlib1')_
pipeline{
  agent any
  stages{
      stage('Nexus')
            {
                steps
                 { 
                 /* Ncreate_repo(JSON) 
                   log_function("NEXUS","Repo created successfully")
                    Ncreate_user(JSON)
                   log_function("NEXUS","User create successfully")
                    Nchange_pwd(JSON)
                   log_function("NEXUS","Password changed successfully")
                    Ndown_artifact(JSON)
                   log_function("NEXUS","Artifact downloaded successfully")
                     Npart_repo(JSON)
                   log_function("NEXUS","Particulor repo details collected")
                     Nlist_repos(JSON)
                   log_function("NEXUS","All repo details collected")
                     Nuserid_info(JSON)
                   log_function("NEXUS","User id details collected")
                     Nrepo_status(JSON)
                   log_function("NEXUS","Status of repo collected")
                     NPrivilage(JSON)
                   log_function("NEXUS","security privileges retrived")*/
                    Ndelete_repo(JSON)
                 log_function("NEXUS","Repo deleted successfully")
    }
    post
    {
    failure
    {
      log_function("NEXUS","CONNECTOR AND COLLECTOR FUNCTIONS NOT EXECUTED SUCCESSFULLY")
    }
    
                 }
            }
            
            }  
            
       }
