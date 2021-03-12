ARG flutter_tag

FROM cirrusci/flutter:$flutter_tag

RUN flutter config --enable-web 

RUN wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb 

RUN sudo apt-get update \
    && sudo apt-get install -y fonts-liberation libgbm1 xdg-utils 

RUN  sudo dpkg -i google-chrome-stable_current_amd64.deb

