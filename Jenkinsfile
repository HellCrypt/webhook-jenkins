pipeline {
  agent any
  stages {
    stage('Source') { steps { echo "Código descargado" } }
    stage('Build')  { steps { echo "Compilando..." } }
    stage('Test')   { steps { echo "Pruebas OK" } }
    stage('Deploy') { steps { echo "Desplegado" } }
  }
}
