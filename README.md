# template repository to create typescript service clients

- create a new repository using this as a template
- clone the respository
- replace the string "{{PLACEHOLDER}}" with the name of your service (without the -service suffix), e.g. for the messaging-service, replace this {{PLACEHOLDER}} with "messaging"
  - running `grep -rl "{{PLACEHOLDER}}" . | xargs sed -i "" -e 's/{{PLACEHOLDER}}/messaging/g'`should do this on the command line
- rename the .github_template folder to .github `mv .github_template .github`
