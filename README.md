# Chain Education Prototype

This is the prototype of my startup [Chain Education](https://www.chaineducation.net), a blockchain based EdTech system.

## What is Chain Education?

You can watch a video of the idea behind Chain Education [here](https://www.chaineducation.net/chaineducation.html).

## How Does This Prototype Works?

The prototype uses the __first 3 nodes__ of a personal blockchain network as a representation of the users in a __ERC20__ token network.

These nodes are listed as follow:
* __Students__ at index __0__.
* __Teachers__ at index __1__.
* __Companies__ at index __2__.

## Getting Started

First, clone the repository.

```bash
git clone https://github.com/PeaKend/ChainEducationPrototype
```

To use the prototype, you will also need a private blockchain network running on your computer.

Download and install [Ganache](https://truffleframework.com/ganache), which is an easy to use personal blockchain network with a GUI.

### Configuring Ganache

Go to __settings__.

![FIRST IMAGE](/repoimages/1.png)

Check that the __hostname__ is _127.0.0.1_ and the __port number__ is _7545_, then go to __accounts & keys__.

![SECOND IMAGE](/repoimages/2.png)

Change __total accounts to generate__ to __3__ and click __save and restart__.

![THIRD IMAGE](/repoimages/3.png)

Now that Ganache is __configured__, you need to __keep it running__ while you use Chain Education.

## Using Chain Education

Just open __account.html__, you'll automatically log in as a __student__ and see the index _0_ public key and the amount of ether it has.

Once inside you can choose to __study__ or __work__, winning or losing money depending on what you do.

If you choose to __study__, then you're going to spend ether and the __teachers__ (index _1_) are going to win that money.

In case you choose to __work__, you will win money, and the __companies__ (index _2_) are going to spend money on that work. 

Take a look from time to time to _Ganache_ while you use the prototype, to see that these transactions are actually made.

You can also watch a video of me using Chain Education [here](https://www.chaineducation.net/workingprototype.html).

## Authors

* __Facundo Atrio__: Idea, implementation and prototype.

## License

This project is licensed under the MIT License - see the [LICENSE](/LICENSE) file for details.

## Acknowledgments

* __HTML5 UP__: Web page template.

