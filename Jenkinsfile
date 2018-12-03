pipeline {
  agent any
  stages {
    stage('') {
      steps {
        sh '''javac HelloWorld/Main.java
java -cp . HelloWorld.Main
jar cfme Main.jar Manifest.txt HelloWorld.Main HelloWorld/Main.class
java -jar Main.jar'''
      }
    }
  }
}