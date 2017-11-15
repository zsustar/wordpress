#!/usr/bin/env groovy

node('master') {
    try {
        stage('build') {
            checkout scm

        }

        stage('test') {
            sh "./vendor/bin/phpunit"
        }

        stage('deploy') {
            // ansible-playbook -i ./ansible/hosts ./ansible/deploy.yml
            sh "echo 'WE ARE DEPLOYING'"
        }
    } catch(error) {
        throw error
    } finally {

    }

}
