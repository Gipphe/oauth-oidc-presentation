---
marp: true
---

# Oauth example (with a pool)

---

## Setting

- A pool at a hotel
- You want to swim in the pool

---

## A user

![](./00058-776906947.png)

---

## A user uses a client

![](./00081-805002221_alt.png)

A user cannot do anything on their own directly. With a client, all necessary steps of the OAuth and OIDC protocols are followed.

---

## The client asks the authorization server

![](./00088-963109044_alt.png)

Asks for an access token (a key) to the requested resource server (hotel area) and the requested scopes (activities).

---

## Authorization server checks authorization privileges

![](./00116-2204405606.png)

---

## Authorization server issues an access token (and refresh token)

![](./00133-1873062582.png)

Kept by the client (friend).

---

## Heading over to the resource server

![](./00064-4025594515.png)

Does not necessarily have to be in the same place (hotel).

---

## The resource server

![](./00067-2073054548.png)

A protected area.

---

## Gatekeeper

![](./00065-4149652628.png)

---

## Using the access token to gain access

![](./00143-3133792943.png)

The turnstile allows two to pass 😉

---

## Success!

![](./00151-3903614175.png)
