# Ch 03 Challenge

### Artifacts

Data preserved from a workflow. Can be a file or a collection of files

E.g. test results or log files

Can also be used to pass data between workflows

E.g. job 1 creates and uploads an artifact, job 2 waits for job 1 to finish then downloads and uses the artifact


### The Challenge

Create a workflow that makes an artifact.

1. Create a new workflow file in a new repo

2. Push trigger

3. Create an environment variable for the name of the artifact

4. Create a job with 2 steps: actions/checkout and actions/upload-artifact

Here we go *swag emoji*