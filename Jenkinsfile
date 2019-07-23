@Library('utils') import org.foo.Utilities
log.info 'Starting'
log.warning 'Nothing to do!'
def utils = new Utilities(this)
node {
  checkout scm
  utils.mvn 'clean package'
}
