pipeline
{
  agent any
    stages {
        stage("stage1") {
          steps {
              script {
                   def data = readFile(file: 'fileA.txt')
                   println(data)
               }            //sh 'cat /workflow/sample/fileA'
          }
        }
    }
}
