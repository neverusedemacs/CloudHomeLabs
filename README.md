# CloudHomeLabs

## Intro

Over time, I've heard the same question multiple ways.

- I understand aws and linux but what is the bigger picture?
- How can I get real world cloud experience without an actual project?
- I have my cloud accounts set up, but what's next?
- Learning the cloud can be pretty expensive.

With that I want to collect resources to get you that experience you need while
not spending too much money.

I'm not going to say this is a lab you can do, and it's 100% free. I can let you
know of any costs that might come up.

## Tools

Here's the list of tools we will go over

- AWS
  - This is where all of our work will live. Everything we're doing is cloud-
  agnostic, if someone can help define the work for other clouds I'm open to
  a contribution
- Terraform
  - This will be our final steps in defining our infrastructure
- CI/CD (not yet sure if aws codebuild, GitHub, GitLab or Jenkins)
  - This is where our code will live and automation occurs (note jenkins doesn't
  store code we'd have it pull from elsewhere)
- Python
  - We will create our own API using aws api gateway and lambda, the code will
  be written in python

## What to build

There's plenty of stuff you can build for your own personal use, there's are
some I have built and continuously looking for more

- [Pihole](https://pi-hole.net)
  - You can lock this down to your home network or have your VPN (pritunl)
  use this instead of public dns servers, depends on your privacy levels.
- [Pritunl](https://pritunl.com)
  - I build one of these every time before I travel in an AWS region closest
  to where I will be.
- API <- I'll give you useful tips on what to build and how

This isn't an extensive list and there will be more in the future. I want to go
over SSO if possible, personal branding for your domain/subdomain and much
more.

## What this guide assumes

- You have a cloud (aws) account
- You can configure your IDE (I use pycharm) <- notepad and terminal is
perfectly fine, I prefer syntax highlighting and such (will demonstrate later)
- All tools are available to all platforms, you'd have to download however
you seem fit (I do still provide recommendations)

## F.A.Q

What benefits will I get from following this guide?

You're going to rock your next interview when they see your resume and
terraform and some CI/CD tools are on the list.

What makes this different from other things I find on the internet?

Nothing at all. I want to enlighten you about personal projects you can
accomplish utilizing aws free tier (there can be costs associated, but I
will put a disclaimer before). You can do whatever you want.

## Overview

| Topic             | Link                                  |
|-------------------|---------------------------------------|
| Personal Tools    | [link](./Personal Tools/README.md)    |
| Personal Branding | [link](./Personal Branding/README.md) |
| Server Builds     | [link](./Server Builds/README.md)     |
| Automations       | [link](./Automations/README.md)       |
| Set and forget    | [link](./Set and Forget/README.md)    |
| API               | [link](./API/README.md)               |
