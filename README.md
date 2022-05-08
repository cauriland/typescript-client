# Cauri - TypeScript Client

<p align="center">
    <img src="./banner.png" />
</p>

> Lead Maintainer: [Arsel Tindo](https://github.com/tnga) <br/>
> Legacy Maintainer: [Brian Faust](https://github.com/faustbrian)

## Installation

```bash
yarn add @cauriland/client
```

## Usage

```ts
import { Connection } from "@cauriland/client";

const init = async () => {
	const connection: Connection = new Connection("https://dnode.cauri.cm/api");

	console.log(await connection.api("blocks").all())
};

init();
```

See [tests](https://github.com/cauriland/javascript-client/tree/master/__tests__/resources) for more examples.

## Security

If you discover a security vulnerability within this package, please send an e-mail to security@cauri.cm. All security vulnerabilities will be promptly addressed.

## Credits

This project exists thanks to all the people who [contribute](../../contributors).

## License

[MIT](LICENSE) © [Cauri Land](https://cauri.cm)
