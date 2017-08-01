
node {
  echo sh(returnStdout: true, script: 'env')
  
  if( env.CHANGE_BRANCH ) {
    echo "available"
  }
  else {
    echo "nope"
  }
}
