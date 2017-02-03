Adds a few extra features to [pytoutv](https://github.com/bvanheu/pytoutv):

- fetch
  - Retry on timeout
  - Fetch episodes in order
  - Only fetch undownloaded episodes
  - Less verbose file naming
  - More flexible bitrate matching

- list
  - Retry on timeout
  - Only show new emissions
  - Show more information (URL, genre, country)

**Installation**

    git clone https://github.com/bvanheu/pytoutv.git
    cd pytoutv
    sudo python3 setup.py install
    cd ..
    git clone https://github.com/bmaupin/pytoutv-plus.git
    cd pytoutv-plus
    sudo python3 setup.py install

**Usage**

    toutv --help
