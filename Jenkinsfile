pipeline {
  agent any

  stages {
    stage("git pull") {
      steps {
        writeFile text: 'hello world', file: 'msg.out'
        /*
         * Some steps may not be fully implemented with symbols or step names to run directly
         * This syntax can be used to call the class directly and run that step.
         * This syntax works fine in Declarative
         */
        step([$class: 'ArtifactArchiver', artifacts: 'msg.out', fingerprint: true])

        // Parentheses are optional when a single parameter is used
        sh('echo $PATH')
        sh 'echo $PATH'
      }
    }
    stage("sonartest") {
      steps {
        writeFile text: 'hello world', file: 'msg.out'
        /*
         * Some steps may not be fully implemented with symbols or step names to run directly
         * This syntax can be used to call the class directly and run that step.
         * This syntax works fine in Declarative
         */
        step([$class: 'ArtifactArchiver', artifacts: 'msg.out', fingerprint: true])

        // Parentheses are optional when a single parameter is used
        sh('echo $PATH')
        sh 'echo $PATH'
      }
    }
    stage("dev deployemnt") {
      steps {
        writeFile text: 'hello world', file: 'msg.out'
        /*
         * Some steps may not be fully implemented with symbols or step names to run directly
         * This syntax can be used to call the class directly and run that step.
         * This syntax works fine in Declarative
         */
        step([$class: 'ArtifactArchiver', artifacts: 'msg.out', fingerprint: true])

        // Parentheses are optional when a single parameter is used
        sh('echo $PATH')
        sh 'echo $PATH'
      }
    }
    stage("dev owasp") {
      steps {
        writeFile text: 'hello world', file: 'msg.out'
        /*
         * Some steps may not be fully implemented with symbols or step names to run directly
         * This syntax can be used to call the class directly and run that step.
         * This syntax works fine in Declarative
         */
        step([$class: 'ArtifactArchiver', artifacts: 'msg.out', fingerprint: true])

        // Parentheses are optional when a single parameter is used
        sh('echo $PATH')
        sh 'echo $PATH'
      }
    }
  }
}
