pipeline{
    parameters { string(name: 'Maven_version', defaultValue: '3.9.4', description: 'pass version') }
    agent any
    stages{
        stage('download maven'){
            steps{
                echo 'Working on parameterize job'
                sh 'cd /var/lib/jenkins'
                sh 'sudo wget https://dlcdn.apache.org/maven/maven-3/$Maven_version/binaries/apache-maven-$Maven_version-bin.tar.gz'
                echo 'Parameterize job completed'
            }
        }
    }

}