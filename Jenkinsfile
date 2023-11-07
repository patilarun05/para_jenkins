pipeline{

    parameters { string(name: 'Maven_version', defaultValue: '3.9.4', description: '') }
    agent any
    stages{
        stage('Parameterized_job'){
            steps{
                echo 'Working on parameterize job'
                sh 'cd /home'
                sh 'sudo wget https://dlcdn.apache.org/maven/maven-3/$Maven_version/binaries/apache-maven-$Maven_version-bin.tar.gz'
                echo 'Parameterize job completed'
            }
        }
    }

}