pipeline{
agent any
  environment{
   CLOUDSCAN_ENV=""
  }
  
 
stages{
stage("Intro"){
steps{
  sh"""
  echo ${env.CLOUDSCAN_ENV}
  """
}
}


}

}
