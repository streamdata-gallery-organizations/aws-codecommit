---
swagger: "2.0"
x-collection-name: AWS CodeCommit
x-complete: 0
info:
  title: AWS CodeCommit API Delete Repository
  version: 1.0.0
  description: Deletes a repository.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=BatchGetRepositories:
    get:
      summary: Batch Get Repositories
      description: Returns information about one or more repositories.
      operationId: batchGetRepositories
      x-api-path-slug: actionbatchgetrepositories-get
      parameters:
      - in: query
        name: repositoryNames
        description: The names of the repositories to get information about
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
  /?Action=CreateBranch:
    get:
      summary: Create Branch
      description: Creates a new branch in a repository and points the branch to a
        commit.
      operationId: createBranch
      x-api-path-slug: actioncreatebranch-get
      parameters:
      - in: query
        name: branchName
        description: The name of the new branch to create
        type: string
      - in: query
        name: commitId
        description: The ID of the commit to point the new branch to
        type: string
      - in: query
        name: repositoryName
        description: The name of the repository in which you want to create the new
          branch
        type: string
      responses:
        200:
          description: OK
      tags:
      - Branch
  /?Action=CreateRepository:
    get:
      summary: Create Repository
      description: Creates a new, empty repository.
      operationId: createRepository
      x-api-path-slug: actioncreaterepository-get
      parameters:
      - in: query
        name: repositoryDescription
        description: A comment or description about the new repository
        type: string
      - in: query
        name: repositoryName
        description: The name of the new repository to be created
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
  /?Action=DeleteRepository:
    get:
      summary: Delete Repository
      description: Deletes a repository.
      operationId: deleteRepository
      x-api-path-slug: actiondeleterepository-get
      parameters:
      - in: query
        name: repositoryName
        description: The name of the repository to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Repositories
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---