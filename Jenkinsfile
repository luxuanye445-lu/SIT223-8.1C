// Jenkinsfile
pipeline {
  agent any
  options { timestamps() }
  triggers { pollSCM('* * * * *') } 
  stages {
    stage('Stage 1: Build') {
      steps { echo 'Task: Compile and package; Example tools: npm / Maven / Gradle' }
    }
    stage('Stage 2: Unit & Integration Tests') {
      steps { echo 'Task: Run unit and integration tests; Example tools: Jest / JUnit / Mocha / Postman(newman)' }
    }
    stage('Stage 3: Code Analysis') {
      steps { echo 'Task: Static code analysis; Example tools: ESLint / SonarQube(SonarCloud) / PMD' }
    }
    stage('Stage 4: Security Scan') {
      steps { echo 'Task: Security vulnerability scanning; Example tools: npm audit / Snyk / OWASP Dependency-Check' }
    }
    stage('Stage 5: Deploy to Staging') {
      steps { echo 'Task: Deploy to staging environment (e.g., AWS EC2); Example tools: Docker / Ansible / Helm' }
    }
    stage('Stage 6: Integration Tests on Staging') {
      steps { echo 'Task: Run integration/smoke tests on staging; Example tools: newman / Cypress' }
    }
    stage('Stage 7: Deploy to Production') {
      steps { echo 'Task: Deploy to production environment; Example tools: Ansible / Helm / ArgoCD (GitOps)' }
    }
    stage('Stage 8: Deploy to Production') {
      steps { echo 'Task: Deploy to production environment; Example tools: Ansible / Helm / ArgoCD (GitOps)' }
    }
  }
}
