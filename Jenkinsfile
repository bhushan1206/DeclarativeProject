pipeline
{ 
 agent any
 {
 stages
  {
   stage("Building")
   { 
    steps{
          bat "mvn clean"
         }
   }
     stage("Testing")
   { 
    steps{
          bat "mvn test"
         }
   }
     stage("packaging")
   { 
    steps{
          bat "mvn package"
         }
   }
  }
}
