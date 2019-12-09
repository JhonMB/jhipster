node{
    stage('SCM Checkout'){
        tool name: 'maven-3', type: 'maven'
        
        git 'https://github.com/JhonMB/jhipster'
    }
    stage('Compile-Package'){
        sh 'mvn package'
    }
}
