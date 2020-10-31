job('DSL_Project_Auto'){
  description('Test Automation using DSL Type')
  
  scm{
    git ('https://github.com/Srividya-Ravichandran26/LeafTapsAutomation', 'master')
  }
  
  triggers{
    scm('* * * * *')
  }
  
  steps{
   maven('package') 
  }
  
  publishers{
    mailer ('srividyaravichandran26@gmail.com', true, true)
  }
}
