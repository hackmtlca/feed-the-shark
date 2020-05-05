# Feed The Shark

This problem is part of the `Intro to Hacking Workshop`. View the [Bug Bounty Guide](https://github.com/hackmtlca/bug-bounty-guide) for more information about the score system.

## Context

This is a basic [Wireshark](https://www.wireshark.org/) analysis problem. We provide you a website that a user logged into. This traffic can be found in `user.pcapng`. Your goal is to find `three hidden flags` on the website. The `user.pcapng` file will give you all the information you need for two of the keys. The last one requires abit of forensics.

## Running the App

All you need is `Docker`. Run the following command in the root of this repository:

```
docker-compose up
```

A frontend instance will be created at `http://localhost/`.

## Closing the App

The app can be closed using CTRL+C. The app can be completely closed with the following command in the root of this repository:

```
docker-compose down
```