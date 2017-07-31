
node {
  echo sh(returnStdout: true, script: 'env')
  def scmUrl = scm.getUserRemoteConfigs()
  
  for (def s in scmUrl) {
    println(s.getUrl())
  }
}
