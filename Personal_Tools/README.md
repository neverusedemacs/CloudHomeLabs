# Personal Tools

## Todo

- [ ] formatting
- [ ] list all tools
- [ ] download links

Here's a list of some tools I find useful that might help with this journey
you're about to take. I do use a mac and I believe all these are available
on all platforms.

| Tool      | Description                               | Link                                      |
|-----------|-------------------------------------------|-------------------------------------------|
| Terraform | Infrastructure as code                    | [link](https://www.terraform.io)          |
| Tfenv     | Terraform Version Manager                 | [link](https://github.com/tfutils/tfenv)  |
| Pyenv     | Python Version Manager                    | [link](https://github.com/pyenv/pyenv)    |
| Pycharm   | IDE                                       | [link](https://www.jetbrains.com/pycharm) |
| Awscli    | Interact with AWS from command line       | [link](https://aws.amazon.com/cli/)       |
| jq        | Just download it                          | [link](https://stedolan.github.io/jq/)    |
| ohmyzsh   | Makes your command line experience better | [link](https://ohmyz.sh)                  |
| ipython   | Interactive Python                        | [link](https://pypi.org/project/ipython/) |

## Terraform

This is how we will later define our infrastructure and deploy it to aws.
Just imagine if you're tasked to deploy multiple stacks a week, that's a lot
of clickops. Write up your infrastructure and deploy it with terraform,
makes cleaning up and deleting infrastructure much easier as well.

## Tfenv

Terraform is nothing but a binary that is downloaded and executed on your
machine. No installation necessary just download and run. You're going to
get to a point in your career when you have to upgrade your terraform
version of your infrastructure (yes we have to do that). Tfenv makes it
easier to have multiple versions of terraform on your machine. Now by all
means you can manage this yourself. Or you can do like below.

```bash
tfenv install 1.0.7
tfenv install 1.0.8
tfenv use 1.0.7
```

## Pyenv

Same exact thing as tfenv. This allows you to better manage multiple
versions of python. Why would you want multiple versions of python on your
computer? Support. AWS supports up to version 3.9, your website is written
in python 3.10 because you like all the newer features, why go through the
hassle of trying to figure out how to download all these python versions,
have the package manager do it for you.

## Pycharm

You can use any integrated development environment you want. Vscode is a
viable option. I do most my dev in python so pycharm was an easy choice.
There's plugins that are available that make doing work in terraform easier
as well which includes auto complete and syntax highlighting. There's even a
checkov plugin to scan your terraform code. Major benefit, who wants to
remember all those git commands, not I said the duck. I'll have pycharm
handle all that.

## AWSCLI

This is another way for you to interact with your amazon environment. Not
every time you want to open a web browser and go to the ec2 console to see
if an instance is running. Just do the below

```bash
aws ec2 describe-instances
```

I'll give you some of my shortcuts later which make it more tolerable.

P.S. I highly recommend the aws auto complete which allows you to tab
complete aws commands. Who wants to remember every single command? Not I!

## jq

We will cover this later

## iPython

Do you like tab auto complete and hints as you type in your commands and you
don't have an ide ready? iPython will take care of that for you.
