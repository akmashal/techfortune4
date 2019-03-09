node{
    stage('Git Pull'){
        git 'https://github.com/akmashal/techfortune4.git'
    }
    stage('compile'){
       echo 'mvn compile'
    }

    stage('Test'){
       echo 'mvn test'
    }
    stage('packaging'){
       echo "packaging stage"
    }
}

