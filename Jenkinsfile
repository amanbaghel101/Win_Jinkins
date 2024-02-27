pipeline
{
  agent any
  stages
  {
    stage("GIT")
    {
      steps
      {
        git "https://github.com/amanbaghel101/Win_Jinkins.git"
      }
    }
    stage("Run")
    {
      steps
      {
        bat "java Demo.java"
	bat "python main.py"
      }
    }
  }
}
