#!groovy
import com.capgemini.nkaas.jenkins.pipeline.library.common.Constants
@Library('git-devops-libraries@tooling')_
EI_CommonTemplate{
   CiapDeployer = "ver-2.1"
   GitRepo = "eaf_ei_task"
   ImageName = "up_microei_masterdata"
   NameSpace = "gadm-eicustomerconnector"
   //HostnameOverride = "ei-core-common.gadm-dev.cs.usnc.eafcore.com"
   HelmBranch = "develop"
   HelmName = "ei-masterdata"
   HelmCharName = "microei-masterdata"
   ComponentName = "masterdata"
   IngressName = "microei-masterdata"

  repoType = Constants.REPO_TYPE_MAVEN
  kanikoContainerEnabled = true
  mavenContainerEnabled = true
  nodeContainerEnabled = false
}
