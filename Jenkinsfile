#!/usr/bin/groovy

node {
  stage('scm'){
    checkout scm
  }
  stage('branch'){
    echo env.BRANCH_NAME
  }
}
