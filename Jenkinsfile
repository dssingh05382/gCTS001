@Library('piper-lib-os') _
node() {
  stage('gctsCreateRepository') {
    gctsCreateRepository script: this
  }
  
  stage('gctsCloneRepository') {
    gctsCloneRepository script: this
  }
}
