# MacSetUp

Mac changes

Adjust display sizes
Move dock bar to the side
Remove un necessary apps in the side bar
Invert mouse movement
- Adjust tab to use for buttons - use "keyboard navigation" to move control between buttons

Install chrome

System preferences changes
- Keyboard - use F1 and F2 as standard function keys
- Mouse -change direction.
- Change default browser to chrome

Always display tabs as details


Install brew
brew install bash
brew install git
    echo '/usr/local/bin/bash' | sudo tee -a /etc/shells;
    chsh -s /usr/local/bin/bash

    echo '/usr/local/Cellar/bash/5.1.16/bin/bash' | sudo tee -a /etc/shells;
    chsh -s /usr/local/Cellar/bash/5.1.16/bin/bash

    echo $SHELL
    /usr/local/bin/bash
    /usr/local/Cellar/bash/5.1.16/bin/bash

    $ echo $BASH_VERSION
    4.2.37(2)-release

add brew to path
Install Iterm2
Install rectangle
Install visual studio code
Install intellij

Install java
brew install openjdk@8
sudo ln -sfn /usr/local/opt/openjdk@8/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-8.jdk
sudo ln -sfn /usr/local/opt/openjdk@8/libexec/openjdk.jdk /Users/krishnaka/Library/Java/JavaVirtualMachines/openjdk-8.jdk

/usr/libexec/java_home -V
/usr/libexec/java_home -v1.8

Add these to the bash profile
export PATH="/usr/local/opt/openjdk@8/bin:$PATH"
export PATH="/usr/local/bin:$PATH"
export JAVA_HOME=$(/usr/libexec/java_home -v1.8)


% sudo ln -sfn /usr/local/opt/openjdk/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk.jdk


