# Snapshot report for `test/help/help.test.js`

The actual snapshot is saved in `help.test.js.snap`.

Generated by [AVA](https://ava.li).

## should return the correct help info

> Snapshot 1

    `Usage: aragon <command> [options]␊
    ␊
    Commands:␊
      apm <command>                         Publish and manage your aragonPM package␊
                                                                  [aliases: package]␊
      dao <command>                         Manage your Aragon DAO␊
      deploy [contract]                     Deploys contract code of the app to the␊
                                            chain␊
      devchain                              Shortcut for `aragon devchain start`.␊
      extract-functions [contract]          Extract function information from a␊
                                            Solidity file␊
      ipfs <command>                        Manage an IPFS node␊
      start [client-repo] [client-version]  Start the Aragon GUI (graphical user␊
                                            interface)␊
    ␊
    Global options:␊
      -h, --help     Show help                                             [boolean]␊
      -v, --version  Show version number                                   [boolean]␊
      -d, --debug    Show extra output                    [boolean] [default: false]␊
      -s, --silent   Silence all output                   [boolean] [default: false]␊
    ␊
    Options:␊
      --cwd                 The project working directory       [default: (default)]␊
      --use-frame           Use frame as a signing provider and web3 provider␊
                                                          [boolean] [default: false]␊
      --env, --environment  The environment in your arapp.json that you want to use␊
    ␊
    For more information, check out https://hack.aragon.org`
