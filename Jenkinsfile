pipeline
{
  agent any
  stages
  {
    stage('build')
    {
        steps
        {
          sh 'javac DevHelloWorld.java'
        }
    }
     stage('Run')
    {
        steps
        {
          sh 'java DevHelloWorld'
        }
    }
  }
}
