
node {
  //echo sh(returnStdout: true, script: 'env')
  String scmRef = scm.branches[0]
  String scmUrl = scm.browser.url
  
  println(">>>>> BRANCH ${scmRef}")
  println(">>>>> URL ${scmUrl}")
  println(">>>>> BRANCH ${CHANGE_BRANCH}")
  
  /*
  def scmRC = scm.getUserRemoteConfigs()
  
  for (def s in scmRC) {
    println(s.getUrl())
  }
  */
}
