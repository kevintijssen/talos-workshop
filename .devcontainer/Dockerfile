FROM mcr.microsoft.com/devcontainers/base:debian

COPY --from=ghcr.io/siderolabs/talosctl:v1.7.4 /talosctl /usr/local/bin/talosctl
RUN wget https://github.com/charmbracelet/gum/releases/download/v0.14.1/gum_0.14.1_amd64.deb &&\
    sudo dpkg -i gum_0.14.1_amd64.deb &&\
    #rm gum_0.14.1_amd64.deb