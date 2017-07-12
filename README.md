# Introduction

Vault is a personal password vault based on RSA encryption. The passwords are encrypted and stored on files using RSA2048 encryption with RS privatekey wrapped in a AES256 hash. This is a bash script, and should work on Mac OS X and Linux.

# How-to Install

`$ git clone to https://github.com/kosalaat/vault.git`
`$ cd vault`
`$ ./install`

NOTE: Installation script will initialize the keys as well.

# How-to Use

If you need to add a password for the item MyPassword.

`$ vault add MyPassword`

To generate a new password for SomeOtherPassword

`$ vault new SomeOtherPassword`

To list all the items in the Vault

`$ vault list`

To recalla password for the item MyPassword, just type:

`$ readpass-MyPassword`

This will prompt for the pass phrase, and the password will be copied to the clip board.

For more options:

`$ vault`

# End
