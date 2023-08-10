<img src="https://github.com/chdb-io/chdb/raw/main/docs/_static/snake-chdb.png" width=200>

[![PyPI](https://img.shields.io/pypi/v/chdb.svg)](https://pypi.org/project/chdb/)
[![Downloads](https://static.pepy.tech/badge/chdb)](https://pepy.tech/project/chdb)
[![Discord](https://img.shields.io/discord/1098133460310294528?logo=Discord)](https://discord.gg/Njw5YXSPPc)

# chdb-cli
Python CLI/REPL for [chdb](https://chdb.io)

##### Usage
```bash
wget https://raw.githubusercontent.com/lmangani/chdb-cli/main/chdb-cli.py -O chdb-cli
chmod +x chdb-cli
```

```
./chdb-cli
```

```sql
CTRL-D to Exit.
chDB "23.6.1.1"

:) SELECT 'hello chdb', version() as version;
┏━━━━━━━━━━━━━━┳━━━━━━━━━━┓
┃ 'hello chdb' ┃ version  ┃
┡━━━━━━━━━━━━━━╇━━━━━━━━━━┩
│ hello chdb   │ 23.6.1.1 │
└──────────────┴──────────┘
```
