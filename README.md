# holidays

This is a project written using [Lucky](https://luckyframework.org). Enjoy!

### Setting up the project

#### Installing crystall

`curl -L https://raw.github.com/pine/crenv/master/install.sh | bash`

`echo 'export PATH="$HOME/.crenv/bin:$PATH"' >> ~/.your_profile`

`echo 'eval "$(crenv init -)"' >> ~/.your_profile`

`exec $SHELL -l`

`crenv install 1.7.1`

`crenv global 1.7.1`

#### Installing Lucky

`git clone https://github.com/luckyframework/lucky_cli`
`cd cd lucky_cli`
`git checkout v1.0.0`
`shards install --without-development`
`shards build --production`
`cp bin/lucky /usr/local/bin`
`lucky -v`

1. [Install required dependencies](https://luckyframework.org/guides/getting-started/installing#install-required-dependencies)
1. Update database settings in `config/database.cr`
1. Run `script/setup`
1. Run `lucky dev` to start the app

### Learning Lucky

Lucky uses the [Crystal](https://crystal-lang.org) programming language. You can learn about Lucky from the [Lucky Guides](https://luckyframework.org/guides/getting-started/why-lucky).
