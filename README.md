# Proxy

A Webhook Proxy That Is Compliant With Discord From Roblox Programmed In Python


# What is a proxy?

Think of the following scenario:

You and someone you don’t like have to work on a project together. Since you don’t want to speak to one another, you ask a friend of yours and them to ask them if they did their part. The person you don’t like (let’s say his name is Foo) tells your friend that he has done all his work. Your friend tells you Foo’s response, and now you can submit the project.

A proxy is like your friend in that scenario, but in the form of a server on the internet. When a server bans you from accessing a certain API endpoint or URL, you can use a proxy to act as you but using the proxy’s identity.

*it’s basically a webserver that takes in the data that you passed to it and directly kicks it to the receiving server. Proxies don’t have to just exist for Discord*

# Why Do We Need It For Discord Webhooks Through Roblox?

Discord recently banned all requests from Roblox servers as webhooks were being abused, which is why webhooks systems broke. Discord saw the request came from a Roblox server and rejected it.

If you use a proxy, you will pass along what you want the request to do to the proxy, but when the proxy sends the request to Discord, the request looks like it came from that proxy server, not the banned Roblox one.
