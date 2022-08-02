FROM returntocorp/semgrep

COPY java.yml /java.yml

ENTRYPOINT ["semgrep", "ci", "--config=/java.yml"]