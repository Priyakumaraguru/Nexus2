@Library('shlib1')_
pipeline{
  agent any
  stages{
      stage('Nexus')
            {
                steps
                 { 
                  /*  Ncreate_repo(JSON)                
                    Ncreate_user(JSON)
                    Nchange_pwd(JSON)
                    Ndown_artifact(JSON)
                     Npart_repo(JSON)
                     Nlist_repos(JSON)
                     Nuserid_info(JSON)
                     Nrepo_status(JSON)
                     NPrivilage(JSON)
                    Ndelete_repo(jsondata)*/
                 NlogNexus("Repo is created")
    }
    post
    {
    failure
    {
      NlogNexus("Repo not created")
    }
    
                 }
            }
            
            }  
            
       }
