# Install homebrew

* Open command line and run.
~~~
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
~~~

* Enter your password.

* Press enter.

* Run these two commands in your terminal to add Homebrew to your PATH:
~~~
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/$USER/.bash_profile
~~~
~~~
eval "$(/opt/homebrew/bin/brew shellenv)"
~~~