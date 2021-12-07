node {
    stage('Clone') {
        git 'https://github.com/karimsahebettaba/repo_git_trigger.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
