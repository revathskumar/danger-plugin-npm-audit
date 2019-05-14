## danger-plugin-npm-audit

> Danger plugin which will give attention to `npm audit` summary

## Usage

Install:

```sh
npm i -D danger-plugin-npm-audit
```

At a glance:

```js
// dangerfile.js
import { schedule } from "danger";
import npmAudit from "danger-plugin-npm-audit";

// Note: You need to use schedule()
schedule(npmAudit());
```

## Sample message

![sample message](https://raw.githubusercontent.com/revathskumar/danger-plugin-npm-audit/master/images/message.png)

## License

Please see [License](https://github.com/revathskumar/danger-plugin-npm-audit/blob/master/License)
