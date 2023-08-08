# gitlab
Some gitlab cheatsheets


# GitLab Runner
Docs: https://docs.gitlab.com/runner/commands/

```
gitlab-runner --help

COMMANDS:
   exec                  execute a build locally
   list                  List all configured runners
   run                   run multi runner service
   register              register a new runner
   reset-token           reset a runner's token
   install               install service
   uninstall             uninstall service
   start                 start service
   stop                  stop service
   restart               restart service

**   status                get status of a service**
sudo gitlab-runner status
Runtime platform                                    arch=amd64 os=linux pid=....... revision=...... version=16.0.2
gitlab-runner: Service is running


   run-single            start single runner
   unregister            unregister specific runner

**   verify                verify all registered runners**
sudo gitlab-runner verify
Runtime platform                                    arch=amd64 os=linux pid=....... revision=...... version=16.0.2
Running in system-mode.
Verifying runner... is alive                        runner=.......


   artifacts-downloader  download and extract build artifacts (internal)
   artifacts-uploader    create and upload build artifacts (internal)
   cache-archiver        create and upload cache artifacts (internal)
   cache-extractor       download and extract cache artifacts (internal)
   cache-init            changed permissions for cache paths (internal)
   health-check          check health for a specific address
   read-logs             reads job logs from a file, used by kubernetes executor (internal)
   help, h               Shows a list of commands or help for one command
```


# Gitlab Runner Executors
Docs: https://docs.gitlab.com/runner/executors/
```
SSH
Shell
Parallels
VirtualBox
Docker
Docker Autoscaler (experiment)
Docker Machine (auto-scaling)
Kubernetes
Instance (experiment)
Custom
```
![image](https://github.com/bgelov/gitlab/assets/5302940/982583ac-6f9d-4354-9834-f39aea9b4d4c)

![image](https://github.com/bgelov/gitlab/assets/5302940/b23cc971-dddc-48fa-91e7-0ff12cc233a2)




