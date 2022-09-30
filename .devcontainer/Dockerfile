FROM archlinux
RUN pacman -Syu
RUN pacman -S go
RUN pacman -S kubectl
RUN pacman -S git
RUN pacman -S make
RUN pacman -S python-pip

RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
RUN nvm install node
RUN npm install -g npm
RUN curl https://sh.rustup.rs -sSf | sh
RUN export LV_BRANCH="rolling"; bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/rolling/utils/installer/install.sh)
