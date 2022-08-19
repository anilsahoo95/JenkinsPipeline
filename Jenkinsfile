pipeline{
agent any
  environment{
   name = "anil" 
  }
  
 
stages{
stage("Intro"){
steps{
  sh"""
  echo $HOME
  export name= sunil
  echo ${name}
  export CLOUDSCAN_ENV=prod
  echo ${CLOUDSCAN_ENV}
  
  """
}
}


}

}
