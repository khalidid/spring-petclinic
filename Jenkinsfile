@Library('utils') import org.foo.Utilities
def utils = new Utilities(this)
node {
  checkout scm
  utils.mvn 'clean package'
}
