FROM rcmachado/changelog:latest
docker run -i --rm -v "$(pwd)":/usr/local/app -w /usr/local/app rcmachado/changelog release 2.0.4

ENTRYPOINT ["ls", "-la", "/usr/local/bin/"]
#ENTRYPOINT ["/usr/local/bin/changelog", "release", "2.0.4", "-o", "CHANGELOG.md"]