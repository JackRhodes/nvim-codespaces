FROM archlinux
RUN pacman -S go kubectl git make python-pip

RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
RUN nvm install node
RUN npm install -g npm
RUN curl https://sh.rustup.rs -sSf | sh
RUN export LV_BRANCH="rolling"; bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/rolling/utils/installer/install.sh)
