
#tmux #linux #bash

# Creating session

```bash
$ tmux new -session <SESSION_NAME>
$ tmux new -s <SESSION_NAME>
```
> Put your <SESSION_NAME>

# Attaching

## Attaching session

```bash
$ tmux attach-session -t <SESSION_NAME>
$ tmux a -t <SESSION_NAME>
```
> Put your <SESSION_NAME>

# Listing session

```shell
$ tmux ls
```
> Verify your tmux session list

# Splitting the window


## Splitting into two horizontal
![](https://i.imgur.com/SRtjGxQ.png)
```shell
ctrl-a %
```

## Splitting into two vertical
![](https://i.imgur.com/7PqcYKj.png)
```Shell
ctrl-a "
```

## new window
```shell
ctrl-a c
```
> Creating new window in your current session

## exit window
```shell
ctrl-a x
```
> Exsting new window in your current session