pipeline{
agent any
tools {
  maven 'maven4'
}
build('build'){
steps{
sh 'mvn clean package'
}
}
}
