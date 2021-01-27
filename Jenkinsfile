@Library('piper-lib-os') _
node() {
  stage('Create Repository') {
    gctsCreateRepository script:this
  }
  
  stage('Clone Repository') {
    gctsCloneRepository script:this
  }
}
