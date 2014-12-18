Development repository for my local macports.


# Using this macports repo
To use my macports repo you must create a local macports repo as follows:

1. Clone this repo:
    `git clone https://github.com/frqnck/macports.git`
4. run `(echo "file://$PWD [nosync]" && cat
      /opt/local/etc/macports/sources.conf) > sources.conf && sudo mv
      sources.conf /opt/local/etc/macports/sources.conf`.  This weird line is to
      assure that my repo has priority over official repos, this way I can
      override some packages.
5. run `port sync`. Add`-v` if you wanna check.
