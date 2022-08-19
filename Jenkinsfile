pipeline{
agent any
  environment{
   name = "anil" 
   CLOUDSCAN_ENV=""
  }
  
 
stages{
stage("Intro"){
steps{
  sh"""
  echo ${name}
  echo ${CLOUDSCAN_ENV}
  """
}
}


}

}
