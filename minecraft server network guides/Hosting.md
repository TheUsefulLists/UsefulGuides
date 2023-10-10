# Hosting

Any suggestions/complaints?

Join our [discord](https://discord.gg/8nzHYhVUQS) or use the issues.

[![Bisect Hosting Image](https://raw.githubusercontent.com/theusefullists/assets/main/images/promo.png)](https://bisecthosting.com/UsefulLists)
We have partnered with BisectHosting this is a exciting step for us. All money earned from this will go to the staff of UsefulLists, Not including myself (Kevsky)

[![Home](https://raw.githubusercontent.com/TheUsefulLists/assets/main/Images/Buttons/Small/Home.png)](/README.md)

## Table of Contents
- [Hosting](#hosting)
  - [Table of Contents](#table-of-contents)
  - [Hosting Providers](#hosting-providers)
    - [Types of hosting plans](#types-of-hosting-plans)
    - [Hosting Providers List](#hosting-providers-list)
      - [BisectHosting](#bisecthosting)
  - [Self Hosting](#self-hosting)
    - [Choosing Hardware](#choosing-hardware)
      - [How much ram do you need?](#how-much-ram-do-you-need)
      - [What CPU do you need?](#what-cpu-do-you-need)
      - [How much storage do you need?](#how-much-storage-do-you-need)

## Hosting Providers

What is a hosting provider? A hosting provider is a company that offers hosting services. They usually offer a wide range of plans across a wide range of prices. Depending on the plan you choose, you may have to share resources with other users.

What are the pros of using a hosting provider?
- You don't have to worry about hardware
- You don't have to worry about electricity
- You don't have to worry about internet
- You don't have to worry about security (you do if you use a dedicated server)
- You don't have to worry about maintenance
- You get support from the hosting provider

What are the cons of using a hosting provider?
- You have to pay for hosting
- You have limited control over your server (less limited if using a dedicated server)
- You have to rely on the hosting provider to keep your server online

### Types of hosting plans

There are 3 main types of hosting plans, shared hosting, dedicated hosting, and Virtual Private Server.

Shared hosting is when you share resources with other users. This is usually the cheapest option, but you have limited control over your server.

Dedicated hosting is when you have a server all to yourself. This is usually the most expensive option, but you have full control over your server and the software running on it. With dedicated hosting, you can also host other things on the same machine.

Virtual Private Server (VPS) hosting is a type of hosting that is in between shared hosting and dedicated hosting. With VPS hosting, you have a virtual machine all to yourself, but you share the hardware with other users. This is usually cheaper than dedicated hosting, but more expensive than shared hosting and is like dedicated hosting in that you have full control over your server and the software running on it. With VPS hosting, you can also host other things on the same machine.

### Hosting Providers List


#### BisectHosting

[BisectHosting](https://bisecthosting.com/UsefulLists) is a hosting provider that offers Minecraft server hosting. They offer a wide range of plans, and have a good reputation.

[![Bisect Hosting Image](https://raw.githubusercontent.com/TheUsefulLists/assets/main/Images/Promo.png)](https://bisecthosting.com/UsefulLists)
We have partnered with BisectHosting this is a exciting step for us. All money earned from this will go to the staff of UsefulLists, Not including myself (Kevsky)

## Self Hosting

What is self hosting? Self hosting is hosting your server yourself. This means you will need to have a computer that is *always on, and that has a good internet connection. You'll have to manage everything your self.

*doesn't need to be always on, especially when you are working on the server and its not open to the public. When it is open to the public it should be always on, otherwise players will see it as downtime and if your server is seen as unreliable players will likely go play on another server.

What are the basic requirements for self hosting?
- A computer that is always on
- A good stable internet connection
  - A connection that fluctuates a lot will cause lag
- A good router
- A good firewall
- A good reliable power source

What are the pros of self hosting?
- You have full control over your server
- You don't have to pay for hosting
  - Besides what you already pay for internet and electricity
- You can host other things on the same machine

What are the cons of self hosting?
- Increased electricity bill
- You have to provide your own hardware
- You are responsible for setting everything up and fixing it when it breaks

If you decide to self host you'll need to decide on a few things:
- What hardware you will use
  - It could be a computer your already have, or a new one
- What software you will use
  - Operating system
  - Management Panel
    - This is how you and others will manage the server

### Choosing Hardware

When choosing hardware, you'll need to consider a few things:
- How much ram you need
- What CPU you need
- How much storage you need

#### How much ram do you need?

The amount of ram you need depends on a few things:
- How many servers you want to run
- How many mods or plugins you'll run on each server
- How many players you want to support on each server
- How much ram each mod or plugin uses

You'll also need to leave some spare for other things, like the operating system, the management panel, and any other software it needs to run.

Some recommendations:
- 2GB for the operating system
- 2GB for the management panel
- 6GB for other software (like databases)
- 1-2GB for each proxy server
- 4GB for each hub server
- 6-16+GB for each game server
  - Most game servers will need 10-12GB, but some will need more
  - The amount of ram they will need is highly dependent on the plugins and mods you use, and how many players will be active on the server at once
  - Modded servers generally needs more ram than plugin based servers
  - As an example, a modded server based on All The Mods 8 takes a minimum of 16GB of ram to run, but can take up to 20+GB of ram to run smoothly

#### What CPU do you need?

For running game servers you'll want few fast cores, instead of many slow cores. As most of the game server will run on 1-2 threads. Plugins and mods can use more threads, but most of the work is done on 1-2 threads.

A Ryzen 7000, 5000, or even an older 3000 series CPU are a good choice, as they has fast cores, and all are full cores. Full cores are what Intel refers to as performance cores on their 13000 series and newer CPUs. Game server will struggle on efficiency cores as they don't preform nearly as well as full cores.

For your management panel, databases, and other software they don't need fast cores and can take advantage of many cores. So if you want to run them on a separate box, you can use a CPU with many cores, like an AMD Threadripper. By running them on a separate box, it'll free up more resources on your game server box for your game servers while allowing them to handle a larger load.

The CPU you need depends on a few things:
- How many servers you want to run
- What type of servers you'll be running
  - Plugin based servers generally need less CPU power than modded servers, At least 2 threads per server is recommended
  - Modded servers generally need more CPU power than plugin based servers, At least 4 threads per server is recommended. When modded server are started they can use a lot of CPU power, but once they are started they don't use as much CPU power. As an example, a modded server based on All The Mods 8 peaks at over 10 thread when starting.
- What other software you'll be running
  - Databases, management panels, and other software will need CPU power. Ideally you should have at least 4 threads for other software.


#### How much storage do you need?

The amount of storage you need depends on a few things:
- Storage for databases
- Storage for backups
- Storage for server files
- Storage for other software
  - Operating system
  - Management panel
  - Other software

Databases and other software will need some storage but not a lot, 100GB should be enough for most cases with room to spare. If your not running this on a separate box from your personal computer, you'll need quite a bit more storage for your operating system and other software.

Backups can need quite a lot of storage, depending on how many backups you keep, how big your server files are, and how often you take backups. You should have at least 1TB of storage for backups, but more is better.

Server files can need a lot of storage, depending on how many servers you want to run, and how big the server files are. You should have at least a few hundred GB of storage for server files, but more is better.

Fast vs slow storage:
- Fast storage is good for databases, management panel, and server files where they will be accessed often.
- Slow storage is good for backups where they won't be accessed often.
- Other software can use either fast or slow storage, depending on the software and what is dose.

You can put everything on fast storage, but it will cost considerably more than using a mix of fast and slow storage.

For fast storage you'll want to use NVMe SSDs, as they are the fastest type of storage available. For slow storage you'll want to use HDDs, as they are the cheapest type of storage available.

You should get at least 2 of each disk and set them up in a RAID 1 array. This will give you redundancy, so if one drive fails you won't lose any data. It will also give you a performance boost, as data can be read from both drives at the same time. RAID 1 is also known as mirroring, as the data is mirrored on both drives such that if one drive fails the other drive has a full copy of the data.
