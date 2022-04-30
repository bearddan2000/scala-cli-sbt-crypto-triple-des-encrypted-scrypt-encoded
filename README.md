# scala-cli-sbt-crypto-triple-des-encrypted-scrypt-encoded

## Description
Encrypt and decrypt password with 3DES
encoded scrypt.

When storing a password it is best practice
to use a one-way hash such as bcrypt, scrypt,
or argon2.

## Tech stack
- scala
- sbt
  - 3DES
  - scrypt

## Docker stack
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop (optional)
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
