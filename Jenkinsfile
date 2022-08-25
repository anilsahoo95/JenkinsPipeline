pipeline{
agent any
  
  triggers{
   pollSCM 'H H * * *' 
  }
 
stages{
stage("Intro"){
steps{
  git url:'https://github.com/anilsahoo95/learnmaven',branch:'main'
 
}
}


}

}
