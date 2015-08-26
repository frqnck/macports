Development repository for my local macports (obsolete -- using Brew nowadays).

# Using this macports repo

To use my macports repo you must create a local macports repo as follows:

1. Clone this repo:
    `git clone https://github.com/frqnck/macports.git frqnck-macports`
4. run `cd frqnck-macports && (echo "file://$PWD [nosync]" && cat
      /opt/local/etc/macports/sources.conf) > sources.conf && sudo mv
      sources.conf /opt/local/etc/macports/sources.conf`.
5. run `port sync`. Add `-v` if you wanna check.
