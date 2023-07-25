FROM nextcloud:stable

RUN apt-get update \
    && apt-get install -y software-properties-common \
    && echo "1111" \
    && cat /etc/apt/sources.list.d/debian.sources \
    && apt-add-repository -y non-free \
    && apt-add-repository -y non-free-firmware \
    && echo "2222" \
    && cat /etc/apt/sources.list.d/debian.sources \
    && apt-get update \
    && apt-get install -y ffmpeg intel-media-va-driver-non-free vainfo i965-va-driver \
    && apt autoclean -y \
    && apt autoremove -y \
    && rm -rf /var/lib/apt/lists


    
    
    
    
    
    
    
    
    
    
    
    
    
    
