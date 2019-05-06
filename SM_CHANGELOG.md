CHANGELOG
=========
2.176.0
-----
* jenkins core
* bumping all plugins to latest
* pinning kubernetes plugin to v1.14.3


2.167.0
-----
* jenkins core
* install-plugins.sh - build stability/retry logic from upstream
* ansicolor:0.6.2
* blueocean:1.13.1
* credentials-binding:1.18
* git:3.9.3
* github:1.29.4
* github-branch-source:2.4.2
* google-oauth-plugin:0.7
* junit:1.27
* kubernetes:1.14.8
* metrics:4.0.2.3
* monitoring:1.76.0
* timestamper:1.9
* workflow-cps:2.63

2.159.0
-----
* jenkins core
* ansicolor:0.6.0 -> ansicolor:0.6.1
* kubernetes:1.13.5 -> kubernetes:1.14.3
* pipeline-aws:1.35 -> pipeline-aws:1.36
* workflow-cps:2.61 -> workflow-cps:2.62
* blueocean:1.9.0 -> blueocean:1.10.1
* editing Dockerfile gpg --no-tty  in order to build with cloudbuilder

2.156.2
-----
* downgrading kubernetes plugin from v1.14.1 to v1.13.5 (re: DEVOPS-4276)

2.156.1
-----


2.156.0
-----


2.141.0
-----
* jenkins.war upgraded to v2.141
* upgrading plugins
    - prometheus:2.0.0
    - pipeline-aws:1.30

2.140.1
-----
* modified jenkins.sh (entrypoint) to clear out plugins directory
* establishing forked repo baseline, Jenkins.war v2.140 + plugins.txt
    - ansicolor:0.5.2
    - basic-branch-build-strategies:1.0.1
    - blueocean:1.8.2
    - branch-api:2.0.20
    - cobertura:1.12.1
    - credentials-binding:1.16
    - git:3.9.1
    - github:1.29.2
    - github-branch-source:2.3.6
    - ghprb:1.42.0
    - google-login:1.4
    - google-oauth-plugin:0.6
    - google-storage-plugin:1.2
    - jira:3.0.1
    - junit:1.24
    - kubernetes:1.12.4
    - metrics:4.0.2.2
    - pipeline-aws:1.29
    - prometheus:1.2.2
    - timestamper:1.8.10
    - workflow-aggregator:2.5
    - workflow-cps:2.54
