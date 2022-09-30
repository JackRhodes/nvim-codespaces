FROM archlinux
RUN export LV_BRANCH="rolling"; bash <(curl -s https://raw.githubusercontent.com/lunarvim/lunarvim/rolling/utils/installer/install.sh)
RUN pacman -S go kubectl