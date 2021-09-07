# RHDM Event Listener

**This project is deprectated. Use project [RHPAM Event Listener](https://github.com/juliaaano/rhpam-event-listener) instead.**

---

Suitable for KIE Server deployments.

## Maven
```
mvn clean install
```

## Maven deploy
```
mvn deploy --activate-profiles deploy
```
Without distribution management:
```
mvn deploy -DaltDeploymentRepository='nexus::default::http://user:password@maven-repo-host/repo-path/'
```
