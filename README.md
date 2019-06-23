# README

## References

[How to define Gradle's home in IDEA?](https://stackoverflow.com/questions/18495474/how-to-define-gradles-home-in-idea)

## Memo

### Preparing environments

```
$ sudo apt install gradle git
$ mkdir -p ~/Sources
$ cd ~/Sources
$ git clone https://github.com/dobachi/gradle_home.git
```

### Execute the task

```
$ cd gradle_home
$ gradle getHomeDir
```
The result is like the following.

```
Starting a Gradle Daemon (subsequent builds will be faster)

> Task :getHomeDir 
/usr/share/gradle
```
