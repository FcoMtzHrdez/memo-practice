pipeline {
    agent {
      label 'agente1'
    }
    stages {
        stage('Ejecutar comandos de Bash') {
            steps {
                sh '''
                echo $variable
                                    '''
            }
        }
    }
}
