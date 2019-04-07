node {
    
    
   def mvnHome='F:\\DevOps\\Tools\\apache-maven-3.6.0-bin\\apache-maven-3.6.0\\bin\\'
   
   stage ('version'){

        bat(/"${mvnHome}"mvn -v/)

   }
   
   
   
}