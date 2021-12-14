# Personal Branding

## Todo

- [ ] Finish listing potential ways to personally brand yourself
- [ ] Finish cost breakdown of hosting services

## Overview

This repository is about Cloud Home Labs, what does any of
this have to do with personal branding?
You can absolutely brand yourself. It starts by purchasing your domain that
will show off you. Think of it like this, there's nothing wrong with having
a gmail email address, but how would it look to have on your resume
firstname@lastname.com (or .me, .tech, .io, or anything else)

## Domain Picking

There is some cost associated with this. You can purchase most domains in
amazon. You also DON'T have to purchase it in amazon, nor transfer it to
amazon, but outside of this guide you will have to manage dns your own way.

[Amazon TLD Support](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/registrar-tld-list.html)

What benefits do you get having your domain in aws? It makes your
automations easier when we get to that point.

## Create your email

Amazon has a service to create an email
([Amazon Workmail](https://aws.amazon.com/workmail/)). I like this service
for multiple reasons, you can set access rules, inbound and outbound rules
and much more. It's $4 a month with first month free. Is this the cheapest
service? Absolutely not, but I'll leave you to do the research on which
email provider you want to use

## Hosting your site, options, etc

Amazon has a plethora of ways to host a site. You have
[Amazon Amplify](https://aws.amazon.com/amplify/),
[Amazon S3](https://aws.amazon.com/s3/),
[Amazon EC2](https://aws.amazon.com/ec2/),
[Amazon Lightsail](https://aws.amazon.com/lightsail/),
[Amazon ElasticBeanStalk](https://aws.amazon.com/elasticbeanstalk/), and
much more. No way is right or wrong, but here's the cost breakdown.

### EC2

This will probably take you the most effort to configure and the cheapest
option.

Monthly if you run it on a t2.micro (reminder this is personal projects like
your website, dns servers, vpn server, etc) it will be free99.

### S3

You can configure a static website on s3. Security best practices advise
against leaving an s3 bucket open to the internet, but to each his own.

You can get away with doing this for free if you have low hits to your site.
S3 is pay per 1,000 requests, BUT within the free tier limits you pay after
20k requests.

### Amplify

This is a pretty cool option that handles a lot of stuff for you. You can
define your build environment and it will create a pipeline for you. This
isn't within the always free for aws tier. You can find more information
[here](https://aws.amazon.com/amplify/pricing/).

### Lightsail

I personally haven't used it but looks like a viable option. There is a cost
associated with using this however. More details [here](https://aws.amazon.com/lightsail/pricing/)

### Elastic Beanstalk

The pricing for this is similar to amplify. There's no cost to using this
service, you just pay for the resources. So you *could* possibly get free
usage out of this. More details [here](https://aws.amazon.com/elasticbeanstalk/pricing/)
