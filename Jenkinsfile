node ('UBUNTU'){
    stage ('GIT'){
        git 'https://github.com/shamsheer-7/shamsheer.git'
    }
    stage ('PACKAGE'){
      sh 'mvn package'
    }
}