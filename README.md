# nextweb
Nextweb - the Application Engine, documentation and bug reports.

## Welcome to Nextweb

This project is under heavy development and currently pre-release. If you find any problems, please submit a bug report.

## Installation

Current supported Operating System: Ubuntu 24 LTS (all features available)
Other supporting systems: Fedora, Alma, Rocky, Windows (limited features and packages)

```sh
curl -sL get.nextwebjs.com | bash
```

The installer downloads the nextweb binary to the foloder you are currently in.

## Usage

Make a folder where you would like to run Nextweb example:

```sh
mkdir newapp
cd newapp
curl -sL get.nextwebjs.com | bash
./nextweb
```

## Demonstration of Wordpress install

To install Wordpress to demonstrate the system try the following.

```sh
mkdir wptest
cd wptest
curl -sL get.nextwebjs.com | bash
./nextweb
pkg install wordpress
deploy myblog to www.myblog.com using wordpress
```

Follow the printed instructions and `apply` then visit the printed URL.

(c) 2026 NULLIVEX LLC. ALL RIGHTS RESERVED.
