node('maven'){
    def mvnhome = tool name: 'maven360', type: 'maven'
    stage('first stage'){
        echo "This is my first stage"
    }
    stage('maven project'){
        echo "this is a maven project"
        echo "this is maven"
        sh "$mvnhome/bin/mvn clean package"
    }
}