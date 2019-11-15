# pologit

pologit is a git version control with with data visualization such as contributing and more. 

## How to use

### To view all commits
``` shell
$ pologit -log
```

### See git contribution in the last 6 months
``` shell
$ pologit <optional> -add <repository> -email <your@email.com>
```

### Git push
``` shell
$ pologit push
```

# Build from source

``` shell
$ git clone https://github.com/polowis/pologit.git
```

``` shell
$ go install
```
