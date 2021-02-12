# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
# NOTE: DO *NOT* EDIT THIS FILE.  IT IS GENERATED.
# PLEASE UPDATE Dockerfile.txt INSTEAD OF THIS FILE
# !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
FROM selenium/base:chrome-dev-20210212
LABEL authors=SeleniumHQ

USER 1200

#========================
# Selenium SessionQueuer Configuration
#========================

EXPOSE 5559

COPY start-selenium-grid-session-queuer.sh \
    /opt/bin/

COPY selenium-grid-session-queuer.conf /etc/supervisor/conf.d/
