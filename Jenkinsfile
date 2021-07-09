pipeline{
agent any
tools {
  maven 'maven4'
}
stages{
stage('build') {
   steps {
        echo "dislay"
     sh 'mvn clean package'
     }
}
}
}
