pipeline{
    agent any
    stages{
        stage('version'){
            steps{
                bat '"C:\\Users\\ADMIN\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" --version'
            }
        }
        stage('STAGE2'){
            steps{
                bat '"C:\\Users\\ADMIN\\AppData\\Local\\Programs\\Python\\Python312\\python.exe" pro.py %X_VALUE% %Y_VALUE%'
            }
        }
    }
}
