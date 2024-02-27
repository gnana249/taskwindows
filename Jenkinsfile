

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
             "java Demo.java"
             "python3 main.py"
             }
        }
       
      }//stages
      }//pipelin
