---
name: AWS CodeCommit
x-slug: aws-codecommit
description: AWS CodeCommit is a fully-managed source control service that makes it
  easy for companies to host secure and highly scalable private Git repositories.
  CodeCommit eliminates the need to operate your own source control system or worry
  about scaling its infrastructure. You can use CodeCommit to securely store anything
  from source code to binaries, and it works seamlessly with your existing Git tools.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
x-kinRank: "10"
x-alexaRank: ""
tags: AWS CodeCommit
created: "2018-05-20"
modified: "2018-05-20"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/apis.md
specificationVersion: "0.14"
apis:
- name: AWS CodeCommit API Batch Get Repositories
  x-api-slug: aws-codecommit-api
  description: Returns information about one or more repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=BatchGetRepositories
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionbatchgetrepositories-get-openapi.md
- name: AWS CodeCommit API Create Branch
  x-api-slug: aws-codecommit-api
  description: Creates a new branch in a repository and points the branch to a commit.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=CreateBranch
  tags: Branch
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actioncreatebranch-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actioncreatebranch-get-openapi.md
- name: AWS CodeCommit API Create Repository
  x-api-slug: aws-codecommit-api
  description: Creates a new, empty repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=CreateRepository
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actioncreaterepository-get-openapi.md
- name: AWS CodeCommit API Delete Repository
  x-api-slug: aws-codecommit-api
  description: Deletes a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=DeleteRepository
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiondeleterepository-get-openapi.md
- name: AWS CodeCommit API Get Branch
  x-api-slug: aws-codecommit-api
  description: Returns information about a repository branch, including its name and
    the last commit ID.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=GetBranch
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiongetbranch-get-openapi.md
- name: AWS CodeCommit API Get Commit
  x-api-slug: aws-codecommit-api
  description: Returns information about a commit, including commit message and committer
    information.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=GetCommit
  tags: Commits
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiongetcommit-get-openapi.md
- name: AWS CodeCommit API Get Repository
  x-api-slug: aws-codecommit-api
  description: Returns information about a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=GetRepository
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiongetrepository-get-openapi.md
- name: AWS CodeCommit API Get Repository Triggers
  x-api-slug: aws-codecommit-api
  description: Gets information about triggers configured for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=GetRepositoryTriggers
  tags: Repository Triggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiongetrepositorytriggers-get-openapi.md
- name: AWS CodeCommit API List Branches
  x-api-slug: aws-codecommit-api
  description: Gets information about one or more branches in a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=ListBranches
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionlistbranches-get-openapi.md
- name: AWS CodeCommit API List Repositories
  x-api-slug: aws-codecommit-api
  description: Gets information about one or more repositories.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=ListRepositories
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionlistrepositories-get-openapi.md
- name: AWS CodeCommit API Put Repository Triggers
  x-api-slug: aws-codecommit-api
  description: Replaces all triggers for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=PutRepositoryTriggers
  tags: Repository Triggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionputrepositorytriggers-get-openapi.md
- name: AWS CodeCommit API Test Repository Triggers
  x-api-slug: aws-codecommit-api
  description: Tests the functionality of repository triggers by sending information
    to the trigger target.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=TestRepositoryTriggers
  tags: Repository Triggers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actiontestrepositorytriggers-get-openapi.md
- name: AWS CodeCommit API Update Default Branch
  x-api-slug: aws-codecommit-api
  description: Sets or changes the default branch name for the specified repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=UpdateDefaultBranch
  tags: Branches
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionupdatedefaultbranch-get-openapi.md
- name: AWS CodeCommit API Update Repository Description
  x-api-slug: aws-codecommit-api
  description: Sets or changes the comment or description for a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=UpdateRepositoryDescription
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionupdaterepositorydescription-get-openapi.md
- name: AWS CodeCommit API Update Repository Name
  x-api-slug: aws-codecommit-api
  description: Renames a repository.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: ://///?Action=UpdateRepositoryName
  tags: Repositories
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/actionupdaterepositoryname-get-openapi.md
- name: AWS CodeCommit API
  x-api-slug: aws-codecommit-api
  description: AWS CodeCommit is a fully-managed source control service that makes
    it easy for companies to host secure and highly scalable private Git repositories.
    CodeCommit eliminates the need to operate your own source control system or worry
    about scaling its infrastructure. You can use CodeCommit to securely store anything
    from source code to binaries, and it works seamlessly with your existing Git tools.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Developer-Tools_AWSCodeCommit.png
  humanURL: https://aws.amazon.com/codecommit/
  baseURL: :///
  tags: AWS CodeCommit
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-codecommit/master/_listings/aws-codecommit/openapi.md
x-common:
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/cli/latest/reference/codecommit/index.html
- type: x-documentation
  url: http://docs.aws.amazon.com/codecommit/latest/APIReference/
- type: x-faq
  url: https://aws.amazon.com/codecommit/faqs/
- type: x-getting-started
  url: ttps://aws.amazon.com/codecommit/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/codecommit/pricing/
- type: x-website
  url: https://aws.amazon.com/codecommit/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---