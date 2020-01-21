library(
    identifier: 'my-orgs-pipeline-library@master',
    retriever: modernSCM([
        $class: 'GitSCMSource',
        remote: 'https://github.com/itewk/hello-world-pipeline-library.git',
    ])
)

pipelineJEE8(
  applicationName: 'itewk-hello-world',
  serviceName: 'java-service-1',
  ownerGroupName: 'itewk-hello-world',
  imagePushRegistry: 'https://my-image-push-registry.example.xyz',
  imagePullRegistry: 'https://my-image-pull-registry.example.xyz',
  ansibleVaultJenkinsCredentialName: 'hello-world-java'
)
