# 37C3 Application

## Title
Jutta-Proto - Hacking JURA Coffee Makers

## Summary
In this lecture we take a look at how to take over control of your JURA coffee maker.
We loot at the process required for deobfuscating and decrypting the JURA serial, Bluetooth and WiFi protocols.
For all of you activists out there, we'll also take a look at how to get "free" coffee from your friendly electronics store next door.

## Description
Did you ever wish you could brew your own personal coffee from the comfort of your office?
Did you ever wonder how a coffee would taste with Mate instead of water?
Did you ever feel limited by the way JURA restricts you from including your fancy and expensive coffee maker in your home IoT setup?
Than this talk is for you!

In this talk we go over the process required for deobfuscating and decrypting the JURA serial, Bluetooth and WiFi protocols.
We start off with a few basics required for reverse engineering.
Then we take a deep dive into the process of reverse engineered the JURA serial connection with all its up and downs.
Security through obscurity is your best fried!

Once we have understood this, we head over into Bluetooth land.
There we have a look at the communication between the JURA Bluetooth Smart Control dongle and the app.
This includes reverse engineering the JURA Joe Android app and dumping the firmware from the dongle (dex2jar and Ghidra are your friends ;) ).

At the end we take a quick look at the same for the ESP32-based WiFi Connect dongle and how dumping and reverse engineering works here.

As an added benefit, we also look at practical use cases for all of this including a smart-card-based authentication for offices, Home Assistant integration, getting "free" coffee from your friendly electronics store next door, and some more!

## Details for the Submission
Falls ich angenommen werde benötige ich für den Vortrag einen Tisch und einen Stromanschluss, da ein Teil des Vortrages live-hacking einer Kaffeemaschine sein wird, die ich dann mitbringe.
Wir brauen uns unseren eigene Kaffee ;)