@Library('shlib1')_
pipeline{
  agent any
  stages{
      stage('Nexus')
            {
                steps
                 { 
                    Ncreate_repo(jsondata)                
                    Ncreate_user(jsondata)
                    Nchange_pwd(jsondata)
                    Ndown_artifact(jsondata)
                     Npart_repo(jsondata)
                     Nlist_repos(jsondata)
                     Nuserid_info(jsondata)
                     Nrepo_status(jsondata)
                     NPrivilage(jsondata)
                    // Ndelete_repo(jsondata)
                    //NlogNexus("Collector & Connector function executed successfully")
                  }
              /*  post
                  {
                      failure
                          {
                               NlogNexus("Collector & Connector function not executed successfully")
                          }
    
                 }*/
            }
            
            }  
            
       }
