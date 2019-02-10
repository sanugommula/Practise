pipeline {
    agent any
    parameters {
        string(name: 'HARIKA', defaultValue: 'HARIKA', description: 'HI HOW ARE YOU?')

        text(name: 'HARIKABIO', defaultValue: 'TBIO', description: 'THIS IS MY BIO')

        booleanParam(name: 'TrueFalse', defaultValue: true, description: 'THIS IS BOOLEAN')

        choice(name: 'CHOICE', choices: ['TASK1', 'TASK2', 'TASK3'], description: 'CHOOSE ANY')

        password(name: 'PASSWORD', defaultValue: 'SECRET', description: 'Enter password')

        file(name: "FILE", description: "Choose a file to upload")
    }
    stages {
        stage('Example') {
            steps {
                echo "Hello ${params.HARIKA}"

                echo "Biography: ${params.TASKS}"

                echo "Toggle: ${params.TrueFalse}"

                echo "Choice: ${params.CHOICE}"

                echo "Password: ${params.PASSWORD}"
            }
        }
    }
}
