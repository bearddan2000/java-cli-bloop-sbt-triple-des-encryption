# java-cli-bloop-sbt-triple-des-encryption

## Description
A demo for 3-DES encryption of a password.
3-DES is a 128 byte encryption.

Compiled and ran from build server `bloop`.

# Build note
Dependencies must be compatable with jdk8 or less.

## Tech stack
- bloop
- java
- bloop-sbt

## Docker stack
- openjdk:8-jdk-alpine

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Code concept](https://stackoverflow.com/questions/20227/how-do-i-use-3des-encryption-decryption-in-java)
