# packages-artifactory

This is to compile the open source artifactories/package repos across various streams like npm, pip, helm charts, docker registry

## Pypiserver

- To use this server with pip, run the following command:

```sh
pip install --index-url http://localhost:8082/simple/ PACKAGE [PACKAGE2...]
```

- To use this server with easy_install, run the following command:

```sh
easy_install --index-url http://localhost:8082/simple/ PACKAGE [PACKAGE2...]
```




## References:

- https://github.com/pypiserver/pypiserver/blob/master/docker-compose.yml
- https://github.com/verdaccio/verdaccio
- https://docs.docker.com/registry/deploying/
- https://docs.docker.com/registry/deploying/#considerations-for-air-gapped-registries
- https://github.com/helm/chartmuseum

