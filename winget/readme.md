# export
winget export -o packages.json

# install
winget import -i packages.json
//--accept-source-agreements --accept-package-agreements

# upgrade

winget upgrade --all --silent --accept-source-agreements --accept-package-agreements

