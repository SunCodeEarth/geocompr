FROM rockerdev/binder:3.6.3
LABEL maintainer='Robin Lovelace, Jakub Nowosad, Jannes Muenchow'
USER root
COPY . ${HOME}
RUN chown -R ${NB_USER} ${HOME}
USER ${NB_USER}



