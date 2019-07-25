
# Fixing AWS Cloudformation Templates

Exercise to fix AWS cloud formation YAML file.

## Files Given
1. [Template 1](https://codefellows.github.io/code-401-aws-guide/curriculum/17-deployment-troubleshoot/lab/aws-1.yml)
2. [Template 2](https://codefellows.github.io/code-401-aws-guide/curriculum/17-deployment-troubleshoot/lab/aws-2.yml)

## Template 1

#### Errors

<hr>

![Alt text](./assets/1-err1.png)
- "cool-react-bucket" was not formatted properly. The dashes were not allowed.
<hr>

![Alt text](./assets/1-err3.png)
![Alt text](./assets/1-err4.png)
- One of the parameters on the yaml file, specifically "GithubOAuthToken" was not indented properly causing the above errors. 

<hr>

## Template 2

#### Errors

![Alt text](./assets/2-err1.png)
- one of the commands was given a private permission parameter instead of 'public'

<hr>


