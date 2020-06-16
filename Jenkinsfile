node('UBUNTU'){
    stage('GIT'){
        git 'https://github.com/spring-petclinic/spring-framework-petclinic.git'
    }
    stage('package'){
        sh 'mvn package'
    }
}