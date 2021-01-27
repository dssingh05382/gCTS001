@Library('piper-lib-os') _
node() {
  stage('gctsCreateRepository') {
    gctsCreateRepository(
        script: this,
        host: 'https://fc-pun01-hana.india.rapidigm.com:8001',
        client: '300',
        abapCredentialsId: 'ABAPUserPasswordCredentialsId',
        repository: 'DEV',
        remoteRepositoryURL: 'https://github.com/skondekar/shubh',
        role: 'SOURCE',
        vSID: 'S4H'
      )
  }
  
  stage('gctsCloneRepository') {
    gctsCloneRepository script: this
  }
}
