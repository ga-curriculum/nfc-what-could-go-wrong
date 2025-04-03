<h1>
  <span class="headline">NFC - What Could Go Wrong?</span>
  <span class="subhead">Concepts</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to describe the basics of NFC technology and how it enables wireless data transmission.

## What is Near Field Communication (NFC) technology?

Have you ever used Apple Pay, Google Wallet, or a tap-to-pay credit or debit card? If so, you are already an NFC pro!

Think of NFC as a tiny invisible bubble around your phone or payment card that can share information when it touches another bubble. Cool, right?

The NFC standard is a maintained by the [NFC Forum](https://nfc-forum.org/) - a non-profit with over 100 member companies. The NFC Forum also certifies devices that are compliant with the standard.

### How does it work?

NFC creates a tiny wireless field (up to 4cm or 1.6 inches) and uses electromagnetic fields to transmit data.

When two fields are close enough, they interact automatically. This requires very little power - so little that one device (the *Initiator* or *active* device) can even wirelessly power another (the *Target* or *passive* device).

This is how many NFC devices interact. When you use a tap-to-pay credit card at an NFC-enabled payment terminal, the terminal is the *active Initiator*, and the tap-to-pay card is the *passive Target*. The card doesn't require its own power because it is provided with power by any terminal at which it is used.

### Where is NFC used?

![NFC has many uses like in credit cards, as identity, in gaming, public transport, and connecting devices.](./assets/nfc-uses.png)

We've already discussed how NFC is used for contactless payments, but it also has a wide variety of other applications, including:

- **Access control**: Similar to embedding NFC in a credit card for quick and easy payments, it can also be embedded in employee badges, hotel keycards, and other tap-and-go authentication tools like [NFC YubiKeys](https://www.yubico.com/product/yubikey-5c-nfc/).
- **Gaming**: Nintendo uses NFC in physical amiibo figures or cards to communicate with their systems and provide in-game rewards.
- **Transportation**: Public transit passes can utilize NFC to quickly scan many people onto buses, trains, subways, and planes.
- **Connecting devices**: NFC can be used to connect devices without going into menus or scanning QR codes. NFC can quickly configure a Bluetooth or other wireless connection between two devices. Once that connection is established, it can be sustained after the phones move apart, and more data can be sent than if the connection only utilized NFC.

  The iPhone's Tap to Cash and NameDrop features are examples of this. They establish an initial connection using NFC, but only for a long enough time to create a temporary wireless network that is used to send data.

That's just the start! All of the above have a common quality - they're repetitive activities where speed is essential. Often, reducing the physical effort required to act can significantly impact how long it takes to complete. That's the value of NFC!

### The tech behind the tap

NFC technology operates at 13.56 MHz and has transfer speeds up to 424 kbps.

It works in three modes:

1. **Card Emulation**: Used to pay with your phone or contactless card.
2. **Reader/Writer**: For scanning tags such as amiibo or transit cards. You can even make custom NFC tags yourself using a writable NFC tag and a device capable of writing NFC tags.
3. **Peer-to-Peer**: To share between devices. In this mode, each device is able to switch between the *Initiator*/*Target* role. This may happen if the original *Target* device needs to transmit larger amounts of data.
