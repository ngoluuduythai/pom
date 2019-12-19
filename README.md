# pom

a dumb simple crossplatform CLI pomodoro timer that doesn't eat your ram and melt your cpu

# features

* writes a timelog in your home folder
* plays a start and break sound

# install

```
cargo build --release
```
then add the binary(/target/release/pom.exe) to your PATH

# usage

```
pom <start_time> <break_time>
```
# todo:

* associate a task name with timelog
* convert to async await implementation since threads are hard
* modify settings with config file
* installer to add binary to path

# credits:

https://freesound.org/people/Koyber/sounds/160483/ (CC 0)
https://freesound.org/people/rhodesmas/sounds/320655/ (CC BY 3.0) 