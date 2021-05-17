Goals
- Build simple docker container on buildkite
- Push spring boot docker image into docker hub


Blocked
- How to add ssh to buildkite docker process for git clone


Done
- `apk update`, `apk add openjdk11`, `export JAVA_HOME=/usr/bin/java` to install java11
- Export app.jar as artifact `buildkite-agent artifact upload build/libs/demo-0.0.1-SNAPSHOT.jar`
