# Brew Bundle Installation

### Configure Jenv

1. Symlink Installed Java Versions
```shell
sudo ln -sfn /opt/homebrew/opt/openjdk@11/libexec/openjdk.jdk /Library/Java/JavaVirtualMachines/openjdk-11.jdk
```

2. Add java version to jenv
```shell
jenv add /Library/Java/JavaVirtualMachines/openjdk-11.jdk/Contents/Home/
```

3. Confirm everything is setup correctly
```shell
jenv doctor
```
