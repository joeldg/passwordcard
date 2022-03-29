# PasswordCard experiments
Taking https://www.passwordcard.org/en to new places — 3/21/22 - joeldg

The idea here is to take PasswordCard and apply easier lookup symbols and make nice some updates.

The original PasswordCard is great but in most cases people are going to use familiar symbols like the umbrella, star, musical notes and the dollar sign. Picking familiar icon headers is a security problem and the ascii headers don't lend themselves to memonic memorization. Also, the code to generate the card seed in the original is required to be a hexadecimal number, I have changed it to use a phrase or password and still be deterministic so the card can be re-generated.

Instead of "yellow interrobang" or "green square" we can swap out to "purple gorilla" or, with a possible addition of left side icons, you could change it to "green island butterfly" or "Blue compass shark" Colors are also less important in this instance and so you can print on black and white printers and be color-blind friendly.

The main idea is to make these fun and easy to use ... and with this Jupyter book, you can go plug in your own icon/digbat font--probably just avoid using web icon fonts that include logos unless your card method is solid.

This is obviously opensource and you can do whatever with this.

Clone the notebook and enjoy :)
