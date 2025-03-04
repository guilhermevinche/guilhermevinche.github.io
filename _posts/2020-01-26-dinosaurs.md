---
layout: post
title: "What is IAM?"
date: 2025-03-04 09:00:13 -0300
background: '/img/posts/06.jpg'
---

As defined by Gartner, *"Identity and access management (IAM) is the discipline of enabling the right individuals to access the right resources at the right times for the right reasons."*

## Key concepts about IAM

**Authentication:** is the method used to determine whether someone is who they claim to be. The main example is the combination of username and password. However, nowadays, using only this method is considered increasingly insecure, as passwords can be stolen through credential stuffing attacks and are easy to guess. The main way to strengthen authentication is through the use of MFA (Multi-Factor Authentication, or MFA).

**Authorization:** is the delegation of permissions to a specific individual or type of user, ensuring that that individual or group has only the permissions that are truly necessary.

## Main features

### SSO

Single Sign-On is the functionality that allows users to authenticate once and gain access to multiple applications. A famous example is Google: when logging into a Google account, the user is automatically authenticated for Gmail, YouTube and other company applications.

![Single Sign On](/img/posts/sso.png "Single Sign On")

### Federated Identity

Federated Identity is the mechanism of delegating authentication to a third-party application, allowing users to use their primary credentials to log into another application. This way, the application does not necessarily need to store their credentials to perform authentication.

This type of authentication is also known as social login because we can use our Google, Facebook or Apple accounts to log into a wide variety of applications.

![Federation](/img/posts/federation.png "Federation")


### MFA

As mentioned earlier, the user and password authentication method is no longer considered secure. This is where "Multi-Factor Authentication (MFA)" comes in to strengthen authentication. This means that even if credentials are compromised, there will still be another barrier against the attacker.

As the name suggests, MFA is a combination of different types of authentication factors. The three main ones are:

* **Knowledge factors:** Things that only the user knows, such as passwords or PIN numbers.

* **Possession factors:** Things that only the user has, such as ATM cards or hardware key devices.

* **Inherence factors:** Things that only the user has, such as a fingerprint or a face.

### Adaptive Authentication

Adaptive authentication is a form of multi-factor authentication that enhances security when the possibility of a security breach is higher. Additional authentication steps can be added to the authentication process depending on the user's risk profile and behavior.

For example, high-risk transactions, such as a user attempting to transfer a large amount of money, will require the adaptive authentication mechanism to request an extra authentication step, such as sending a one-time security code to the user's mobile phone, to increase security.

## Conclusion

Structuring and delivering an authentication solution may seem simple, but its possibilities, responsibilities and consequences are multiple. This makes any initiative a major challenge for everyone. We have known and enjoyed these challenges for many years. That is why we work with such enthusiasm, versatility and responsibility.

The IAM subject is extensive and quickly unfolds into things like CIAM, EIAM, IDaaS, among others. If you want to know more or deepen the conversation, contact us.

## References:

[https://is.docs.wso2.com/en/latest/references/concepts/single-sign-on/](https://is.docs.wso2.com/en/latest/references/concepts/single-sign-on/)
[https://is.docs.wso2.com/en/latest/references/concepts/authentication/multi-factor-authentication/#what-is-multi-factor-authentication](https://is.docs.wso2.com/en/latest/references/concepts/authentication/multi-factor-authentication/#what-is-multi-factor-authentication)
[https://auth0.com/blog/what-is-iam/](https://auth0.com/blog/what-is-iam/)
[https://is.docs.wso2.com/en/latest/references/concepts/authentication/adaptive-authentication/#what-is-adaptive-authentication](https://is.docs.wso2.com/en/latest/references/concepts/authentication/adaptive-authentication/#what-is-adaptive-authentication)
[https://is.docs.wso2.com/en/6.0.0/assets/img/samples/saml-sso-scenario-diagram.png](https://is.docs.wso2.com/en/6.0.0/assets/img/samples/saml-sso-scenario-diagram.png)
[https://miro.medium.com/max/1400/1*mB4Viy_LmzdS2iObFqh6FA.png](https://miro.medium.com/max/1400/1*mB4Viy_LmzdS2iObFqh6FA.png)
[https://is.docs.wso2.com/en/6.0.0/assets/img/concepts/adaptive-authentication.png](https://is.docs.wso2.com/en/6.0.0/assets/img/concepts/adaptive-authentication.png)