pipeline
{
agent any
stages
{
stage("git")
{
step git "https://github.com/gnana249/taskwindows.git"
}
}
stage('run')
{
step
{ 
sh "java -cp  Demo.java"
sh "python3 main.py"
}
}
}

