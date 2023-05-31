1. Connect into the environment
2. `grep` your pod
3. `describe` your pod
4. `edit` the secrets
(If it's a new env, you have to go the chart
- Go to the deployment.yaml)
5. `edit` the deployments
6. change to base 64
`echo -n "the key" | base64`