pipeline{
agent any
  environment{
   name = "anil" 
  }
  
  parameters{
  string(name:"Environment",description:"select env")
  choice(name:"Branch",choices:["master","release","deploy"])
  }
stages{
stage("Intro"){
steps{

  echo "Welcome ${params.Branch}"
}
}


}

}
