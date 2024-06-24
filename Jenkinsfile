#!groovy
@Library('rspace-shared') _ 
// builds Zenodo-adapter project
genericJavaLibBuild("emails":"dev@researchspace.com",
 "branch":"${BRANCH_NAME}",
  "jdk":"OPEN-JDK-11",
  "maven":"maven3.8.1",
  "jvmArgs":"-Djava-vendor=openjdk -Djava-version=11")
