node {
    stage('scm'){
    git 'https://github.com/kolaverid/cicd-pipeline-train-schedule-kubernetes.git'
    }
    
    stage('build'){
        sh 'mvn package'
    }
}