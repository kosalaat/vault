# Introduction

Vault is a personal password vault based on RSA encryption. The passwords are encrypted and stored on files using RSA2048 encryption with RS privatekey wrapped in a AES256 hash.

# How-to Install

$ git clone to https://github.com/kosalaat/vault.git
$ cd vault
$ ./install

# How-to Use

If you need to add a password for the item MyPassword.

$ vault add MyPassword

To generate a new password for SomeOtherPassword

$ vault new SomeOtherPassword

To list all the items in the Vault

$ vault list

# End
