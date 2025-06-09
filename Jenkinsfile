pipeline {
 agent any
 tools {
 maven 'maven' // Make sure this matches the Maven name in Jenkins
 }
 stages {
 stage('Build') {
 steps {
 bat 'mvn clean install'
 }
 }
 }
}
