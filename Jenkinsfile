pipeline{
agent any
  environment{
   name = "anil" 
  }
  
  parameters{
  string(name:"Environment",description:"select env")
  }
stages{
stage("Intro"){
steps{

  echo "Welcome ${params.Environment}"
}
}


}

}
