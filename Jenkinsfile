pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                // 这里可以添加构建步骤，例如：执行maven构建：sh 'mvn clean install'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                // 这里可以添加测试步骤，例如：执行单元测试：sh 'mvn test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                // 这里可以添加部署步骤，例如：将构建的产物部署到服务器
            }
        }
    }
}
