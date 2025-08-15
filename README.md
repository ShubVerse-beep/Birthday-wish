# Happy Birthday Card

A Customizable Web-based birthday card to wish your friends and family in a unique way.


## How to setup

Here are the methods to set it up for yourself.


### For Local Building

1. Clone the repository

```sh
git clone https://github.com/ShubVerse-beep/Happy-Birthday-Card

```

2. Install dependencies

```sh
npm install

```

3. Add a pic of the receiver, in the `./local` directory. Ensure that the image is of a 1:1 ratio or it might get cropped and squished.

4. Create a `.env` file in the root directory, and add the following lines.

```env
 NAME='Name of the Receiever'
 PIC='name-of-image.extension'

```

5. Execute the following commands in order.

```sh
 npm run init-index-local
 npm run build:parcel

```

6. Upon Successful execution, your built files will be ready in the `./dist` directory. Serve this directory using `live-server` or similar tools to see your card.

For further customization, check out [here](./docs/customizations.md).

---

## References

- [Environment Variables](./docs/variables.md)
- [Attributions](./docs/attributions.md)

---

<div align="center">
Made with 💖 by Shubham Sawant
</div>

