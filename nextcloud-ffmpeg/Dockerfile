FROM nextcloud:stable

RUN apt-get update \
    && apt-get install -y software-properties-common \
    # && apt-add-repository -y non-free \
    # && apt-add-repository -y non-free-firmware \
    && curl -o /etc/apt/sources.list https://gist.githubusercontent.com/danfate/212207738a32338ba5d4fab18fc3b565/raw/8568bcf004a95322b079dd536f541e9fd0f8fb53/sources.list \
    && apt-get update \
    && apt-get install -y ffmpeg intel-media-va-driver-non-free vainfo i965-va-driver \
    && apt autoclean -y \
    && apt autoremove -y \
    && rm -rf /var/lib/apt/lists


    
    
    
    
    
    
    
    
    
    
    
    
    
    
