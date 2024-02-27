

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
             bat "javac Demo.java"
             bat "java Demo.java"
             bat "python3 main.py"
             
             }
        }
       
      }//stages
      }//pipelin
