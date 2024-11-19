        stage('Build and pull the docker file  ') {
            steps {
                script {
                    // Installation of docker for CentOS
                    sh 'git pull "sudo git clone https://github.com/akaratsony/DockerOwnImage.git"'
                    sh 'sudo docker build Dockerfile -t my-simple-web-app'
                }
            }
        }
