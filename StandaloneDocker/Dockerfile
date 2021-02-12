# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM selenium/base:chrome-dev-20210212
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium Standalone Docker Configuration
#========================

EXPOSE 4444

COPY start-selenium-grid-standalone-docker.sh \
    config.toml \
    /opt/bin/

COPY selenium-grid-standalone-docker.conf /etc/supervisor/conf.d/

