pipeline     // jenkinfile always start with pipeline
{
    agent any   // agent any means - any available execcuto
    stages         // it contains all stage
    {

stage  ("pre build")      // it ttells what to do
{steps { sh "echo hi jenkins"   }   }    // sh- execute the shell script / command
 stage ("build")
 {steps {sh "echo hi build"}}
 stage ("post build")
 {steps {sh "test cases"}}










    }
}
