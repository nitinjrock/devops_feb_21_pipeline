pipeline
{
agent any
stages                                                                          

 {
   stage ('scm check - download the code') 
     { steps  { echo "code is downling"}   }                                    
   stage ('build the code')
      { steps  { echo "code is building"  }  } 
  stage ('Test the code')
      { steps { echo "code is test" } }
  stage ("deploy the code")
  { step { echo "deploy the code"} }

 }

}
