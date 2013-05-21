
### Setup

#### Requires
* [Go 1.1](http://golang.org/)
* [goenv](https://bitbucket.org/ymotongpoo/goenv)

#### Prepare

```bash
$ cd $HOME/src
$ git clone git@github.com:PyYoshi/ProGameCollectorWeb.git
$ cd ProGameCollectorWeb
$ source activate
$ go get github.com/robfig/revel
$ go build -o bin/revel github.com/robfig/revel/cmd
```

#### Run

```bash
$ cd $HOME/src/ProGameCollectorWeb
$ source activate
$ revel run webapps/ProGameCollector
```

#### Build

```bash
$ cd $HOME/src/ProGameCollectorWeb
$ source activate
$ revel build webapps/ProGameCollector out/
```