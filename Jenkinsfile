node {
    stage('build and run') {
        git branch: 'main', url: 'https://github.com/IlyassHaidouch/jenkins-helloworld.git'
        sh label: '', script: '''
        javac Main.java 
        java Main
        '''
    }
}
