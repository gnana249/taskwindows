

pipeline 
     {
      agent any
      stages
      {
       stage('git')
       {
        steps
            {
              git "https://github.com/gnana249/taskwindows.git"
              }
}
        stage('run')
        {
         steps
            {
             sh "java c java Demo.java"
             sh "python3 main.py"
             }
        }
       
      }//stages
      }//pipelin
