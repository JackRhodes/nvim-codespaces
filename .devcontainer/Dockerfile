FROM archlinux
RUN pacman -Syu --noconfirm
RUN pacman -S go --noconfirm
RUN pacman -S kubectl --noconfirm
RUN pacman -S git --noconfirm
RUN pacman -S make --noconfirm
RUN pacman -S python-pip --noconfirm

RUN curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.1/install.sh | bash
RUN nvm install node
RUN npm install -g npm
RUN curl https://sh.rustup.rs -sSf | sh
RUN export LV_BRANCH="rolling"; bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/rolling/utils/installer/install.sh)
