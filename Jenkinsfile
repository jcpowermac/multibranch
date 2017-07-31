
node {
  echo sh(returnStdout: true, script: 'env')
  String scmRef = scm.branches[0]
  String scmUrl = scm.browser.url
  
  println(">>>>> BRANCH ${scmRef}")
  println(">>>>> URL ${scmUrl}")
  
  def scmUrl = scm.getUserRemoteConfigs()
  
  for (def s in scmUrl) {
    println(s.getUrl())
  }
}
