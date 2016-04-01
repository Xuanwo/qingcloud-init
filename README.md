# qingcloud-init
The script to setup qingcloud environment.

<script type="text/javascript" src="https://asciinema.org/a/c4di0phs0mpi4eudxxo5ede20.js" id="asciicast-c4di0phs0mpi4eudxxo5ede20" async></script>

## Setup

### Pip

```
pip install qingcloud-init
```

## Usage

```
Usage:
    qinginit init
    qinginit config id <access_key_id>
    qinginit config key <secret_access_key>
    qinginit config zone <zone_id>
    qinginit create

Options:
    -v, --version  show verison
    -h, --help show help document
```

### init

```
qinginit init
```

This command will create `config.yml` in current directory, you can modify this file to set your own environment.

### config

```
qinginit config id abcdefg
qinginit config key abcdefghijklmn
qinginit config zone pek2
```

Your can set these value by `config` command.

### create

```
qinginit create
```

Create your own environment from `config.yml` file.