---
description: Cryptography uses mathematical algorithms to encode and decode data.
---

# Overview

Cryptography uses algorithms to decode and encode data. Cryptographic algorithms are designed to be difficult or nearly impossible to break.\
\
Information secured with cryptography is incredibly hard for unauthorized parties to access.&#x20;

The sender and receiver of the information must have the right cryptographic key in order to encode and decode the data.&#x20;

Two main types of Cryptography:

{% tabs %}
{% tab title="Symmetric key cryptography" %}
A <mark style="color:yellow;">**single key system**</mark>: the same key is used to encode and decode data. \
\
_This key must be kept secret, as anyone who has access to it can decode the data._&#x20;
{% endtab %}

{% tab title="Asymmetric key cryptography" %}
Also known as public-key cryptography, asymmetric cryptography uses two different keys: a public key and a private key. \
\
_The <mark style="color:purple;">**public key**</mark> can be shared with anyone, as it is used to encode the data._ \
\
_The <mark style="color:red;">**private key**</mark> is kept secret and is used to decode the data._&#x20;
{% endtab %}
{% endtabs %}

{% hint style="info" %}
A key can be a number, a word, or a phrase.
{% endhint %}
