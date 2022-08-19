pipeline{
agent any
  environment{
   CLOUDSCAN_ENV="hello"
  }
  
 
stages{
stage("Intro"){
steps{
  sh"""
  echo "\${env.CLOUDSCAN_ENV}"
  """
 
}
}


}

}
